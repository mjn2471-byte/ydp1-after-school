<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>2026 청소년 방과후 프로그램 안내 포털</title>

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- FontAwesome -->
  <link
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
    rel="stylesheet"
  />

  <!-- Pretendard -->
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pretendard:wght@400;600;700;900&display=swap');

    body {
      font-family: 'Pretendard', sans-serif;
      background: #f8fafc;
      color: #1e293b;
      word-break: keep-all;
      margin: 0;
    }

    .gradient-text {
      background: linear-gradient(135deg,#6366f1 0%,#a855f7 50%,#ec4899 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .program-card {
      transition: all .3s cubic-bezier(.4,0,.2,1);
      border-top: 5px solid #e2e8f0;
      cursor: pointer;
      background: #fff;
      border-radius: 1.5rem;
      padding: 2.25rem;
      display: flex;
      flex-direction: column;
      height: 100%;
      box-shadow: 0 4px 6px -1px rgba(0,0,0,.05);
    }

    .program-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 20px 25px -5px rgba(0,0,0,.1);
    }

    .category-line {
      width: 40px;
      height: 5px;
      border-radius: 10px;
      margin-bottom: 1.25rem;
    }

    .info-item {
      display: flex;
      align-items: center;
      gap: 8px;
      font-size: .85rem;
      color: #64748b;
    }

    /* 상세 뷰어 */
    #viewer-overlay {
      display: none;
      position: fixed;
      inset: 0;
      background: #fff;
      z-index: 9999;
      flex-direction: column;
    }

    .viewer-header {
      height: 64px;
      padding: 0 24px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 1px solid #e2e8f0;
    }

    #detail-iframe {
      width: 100%;
      height: calc(100vh - 64px);
      border: none;
    }

    .close-btn {
      background: #1e293b;
      color: #fff;
      padding: 10px 20px;
      border-radius: 12px;
      font-weight: 700;
      display: flex;
      align-items: center;
      gap: 8px;
    }
  </style>
</head>

<body>

<!-- ===== 포털 ===== -->
<div id="portal-root">

  <!-- 상단 -->
  <nav class="sticky top-0 z-50 bg-white/80 backdrop-blur border-b">
    <div class="max-w-7xl mx-auto px-6 h-16 flex items-center gap-2">
      <div class="w-8 h-8 bg-slate-900 rounded-lg flex items-center justify-center text-white">
        <i class="fa-solid fa-rocket"></i>
      </div>
      <span class="text-lg font-black tracking-tight">YDP Youth</span>
    </div>
  </nav>

  <!-- 헤더 -->
  <header class="pt-20 pb-10 text-center">
    <h1 class="text-4xl md:text-5xl font-black">
      2026 청소년 <span class="gradient-text">방과후 프로그램 안내</span>
    </h1>
  </header>

  <!-- 카드 영역 -->
  <main class="max-w-7xl mx-auto px-6 mb-24">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

      <div class="program-card" style="border-top-color:#6366f1"
        onclick="openDetail('청소년디지털드로잉교실.html','디지털 드로잉')">
        <div class="category-line bg-indigo-500"></div>
        <h3 class="text-2xl font-black mb-4">디지털 드로잉</h3>
        <div class="space-y-1 mb-6">
          <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 목요일 16:00~18:00</div>
          <div class="info-item"><i class="fa-solid fa-location-dot"></i> 3층 프로그램방</div>
        </div>
        <p class="text-slate-500 text-sm">
          태블릿을 활용해 나만의 작품을 완성하는 디지털 미술 활동
        </p>
      </div>

      <div class="program-card" style="border-top-color:#10b981"
        onclick="openDetail('청소년메이커스.html','청소년 메이커스')">
        <div class="category-line bg-emerald-500"></div>
        <h3 class="text-2xl font-black mb-4">청소년 메이커스</h3>
        <div class="space-y-1 mb-6">
          <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 월요일 17:00~18:00</div>
          <div class="info-item"><i class="fa-solid fa-location-dot"></i> 3층 주간활동실</div>
        </div>
        <p class="text-slate-500 text-sm">
          디폼블럭·보석십자수 등 생활 공예 활동
        </p>
      </div>

      <div class="program-card" style="border-top-color:#0891b2"
        onclick="openDetail('청소년라이프업.html','청소년 라이프 up')">
        <div class="category-line bg-cyan-600"></div>
        <h3 class="text-2xl font-black mb-4">청소년 라이프 up</h3>
        <div class="space-y-1 mb-6">
          <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 화요일 17:30~19:00</div>
          <div class="info-item"><i class="fa-solid fa-location-dot"></i> 2층 프로그램실</div>
        </div>
        <p class="text-slate-500 text-sm">
          자기관리·경제·진로 중심의 일상생활훈련
        </p>
      </div>

    </div>
  </main>
</div>

<!-- ===== 상세 뷰어 ===== -->
<div id="viewer-overlay">
  <div class="viewer-header">
    <strong id="viewer-title">상세 페이지</strong>
    <button class="close-btn" onclick="closeDetail()">
      <i class="fa-solid fa-arrow-left"></i> 포털로
    </button>
  </div>
  <iframe id="detail-iframe"></iframe>
</div>

<script>
  function openDetail(url, title) {
    document.getElementById('viewer-title').innerText = title;
    document.getElementById('detail-iframe').src = url;
    document.getElementById('viewer-overlay').style.display = 'flex';
  }

  function closeDetail() {
    document.getElementById('detail-iframe').src = '';
    document.getElementById('viewer-overlay').style.display = 'none';
  }
</script>

</body>
</html>
</body>
</html>
