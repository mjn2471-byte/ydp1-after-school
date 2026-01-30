<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>2026 청소년 방과후 프로그램 안내 포털</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet" />
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pretendard:wght@400;600;700;900&display=swap');
    body{font-family:'Pretendard',sans-serif;background:#f8fafc;color:#1e293b;word-break:keep-all;margin:0;padding:0}
    .gradient-text{background:linear-gradient(135deg,#6366f1 0%,#a855f7 50%,#ec4899 100%);-webkit-background-clip:text;-webkit-text-fill-color:transparent}

    .program-card{transition:all .3s cubic-bezier(.4,0,.2,1);border-top:5px solid #e2e8f0;cursor:pointer;background:#fff;border-radius:1.5rem;padding:2.25rem;display:flex;flex-direction:column;box-shadow:0 4px 6px -1px rgba(0,0,0,.05);height:100%}
    .program-card:hover{transform:translateY(-8px);box-shadow:0 20px 25px -5px rgba(0,0,0,.1)}
    .category-line{width:40px;height:5px;border-radius:10px;margin-bottom:1.25rem}
    .info-item{display:flex;align-items:center;gap:8px;font-size:.85rem;color:#64748b;margin-bottom:4px}

    #viewer-overlay{display:none;position:fixed;top:0;left:0;width:100vw;height:100vh;background:#fff;z-index:9999;flex-direction:column}
    .viewer-header{height:64px;padding:0 24px;display:flex;align-items:center;border-bottom:1px solid #f1f5f9;background:#fff;justify-content:space-between;box-shadow:0 2px 4px rgba(0,0,0,.02);flex-shrink:0}
    #viewer-title{font-weight:900;letter-spacing:-.02em}
    #detail-iframe{width:100%;height:calc(100vh - 64px);border:none;display:block}
    .close-btn{background:#1e293b;color:#fff;padding:10px 20px;border-radius:12px;font-weight:800;font-size:.9rem;transition:all .2s;display:flex;align-items:center;gap:8px}
    .close-btn:hover{background:#334155;transform:scale(1.02)}

    #viewer-loading{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);display:none;flex-direction:column;align-items:center;gap:1rem}
    .spinner{width:40px;height:40px;border:4px solid #f3f3f3;border-top:4px solid #6366f1;border-radius:50%;animation:spin 1s linear infinite}
    @keyframes spin{0%{transform:rotate(0deg)}100%{transform:rotate(360deg)}}
  </style>
</head>
<body class="antialiased">

  <div id="portal-root">
    <nav class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-100">
      <div class="max-w-7xl mx-auto px-6 h-16 flex items-center justify-between">
        <div class="flex items-center gap-2">
          <div class="w-8 h-8 bg-slate-900 rounded-lg flex items-center justify-center text-white text-sm shadow-sm">
            <i class="fa-solid fa-rocket"></i>
          </div>
          <span class="text-lg font-black tracking-tighter uppercase">YDP Youth</span>
        </div>
      </div>
    </nav>

    <header class="pt-20 pb-10 px-6 text-center">
      <div class="max-w-4xl mx-auto">
        <h1 class="text-4xl md:text-5xl font-black mb-4 leading-tight tracking-tight text-slate-900">
          2026 청소년 <span class="gradient-text">방과후 프로그램 안내</span>
        </h1>
      </div>
    </header>

    <main class="max-w-7xl mx-auto px-6 mb-24">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

        <div class="program-card" style="border-top-color:#6366f1" onclick="openDetail('청소년디지털드로잉교실.html','디지털 드로잉')">
          <div class="category-line bg-indigo-500"></div>
          <h3 class="text-2xl font-black mb-4">디지털 드로잉</h3>
          <div class="space-y-1 mb-6">
            <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 목요일 16:00~18:00</div>
            <div class="info-item"><i class="fa-solid fa-location-dot"></i> 3층 프로그램방</div>
          </div>
          <p class="text-slate-500 text-sm leading-relaxed">태블릿을 활용해 나만의 작품을 완성하는 디지털 미술 시간입니다.</p>
        </div>

        <div class="program-card" style="border-top-color:#10b981" onclick="openDetail('청소년메이커스.html','청소년 메이커스')">
          <div class="category-line bg-emerald-500"></div>
          <h3 class="text-2xl font-black mb-4">청소년 메이커스</h3>
          <div class="space-y-1 mb-6">
            <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 월요일 17:00~18:00</div>
            <div class="info-item"><i class="fa-solid fa-location-dot"></i> 3층 주간활동실</div>
          </div>
          <p class="text-slate-500 text-sm leading-relaxed">디폼블럭·보석십자수 등 생활 공예로 창의력을 키워요.</p>
        </div>

        <div class="program-card" style="border-top-color:#0891b2" onclick="openDetail('청소년라이프업.html','청소년 라이프 up')">
          <div class="category-line" style="background:#0891b2"></div>
          <h3 class="text-2xl font-black mb-4">청소년 라이프 up</h3>
          <div class="space-y-1 mb-6">
            <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 화요일 17:30~19:00</div>
            <div class="info-item"><i class="fa-solid fa-location-dot"></i> 2층 프로그램실</div>
          </div>
          <p class="text-slate-500 text-sm leading-relaxed">자기관리·경제·진로 등 일상생활기술을 체계적으로 훈련합니다.</p>
        </div>

        <div class="program-card" style="border-top-color:#ff6b6b" onclick="openDetail('청소년 댄스교실.html','청소년 댄스교실')">
          <div class="category-line" style="background:#ff6b6b"></div>
          <h3 class="text-2xl font-black mb-4">청소년 댄스교실</h3>
          <div class="space-y-1 mb-6">
            <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 금요일 16:00~18:00</div>
            <div class="info-item"><i class="fa-solid fa-location-dot"></i> 지하 특수체육실</div>
          </div>
          <p class="text-slate-500 text-sm leading-relaxed">K-POP 방송댄스와 신체 발달 활동으로 자신감을 키워요.</p>
        </div>

        <div class="program-card" style="border-top-color:#10b981" onclick="openDetail('청소년특수체육.html','청소년 특수체육')">
          <div class="category-line bg-emerald-500"></div>
          <h3 class="text-2xl font-black mb-4">청소년 특수체육</h3>
          <div class="space-y-1 mb-6">
            <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 화요일(상세 페이지 참고)</div>
            <div class="info-item"><i class="fa-solid fa-location-dot"></i> 복지관(상세 페이지 참고)</div>
          </div>
          <p class="text-slate-500 text-sm leading-relaxed">다양한 종목 경험으로 대근육·사회성·자존감을 강화합니다.</p>
        </div>

        <div class="program-card" style="border-top-color:#00d2ff" onclick="openDetail('디지털스포츠온.html','디지털스포츠 온(ON)')">
          <div class="category-line" style="background:linear-gradient(90deg,#00d2ff,#ff007a)"></div>
          <h3 class="text-2xl font-black mb-4">디지털스포츠 온(ON)</h3>
          <div class="space-y-1 mb-6">
            <div class="info-item"><i class="fa-solid fa-calendar"></i> 매주 월요일(상세 페이지 참고)</div>
            <div class="info-item"><i class="fa-solid fa-location-dot"></i> 복지관(상세 페이지 참고)</div>
          </div>
          <p class="text-slate-500 text-sm leading-relaxed">IT 기술과 스포츠를 결합한 미래형 특수체육 프로그램입니다.</p>
        </div>

      </div>
    </main>
  </div>

  <div id="viewer-overlay">
    <div class="viewer-header">
      <div class="flex items-center gap-3">
        <div class="w-9 h-9 bg-slate-900 rounded-lg flex items-center justify-center text-white text-sm">
          <i class="fa-solid fa-file-lines"></i>
        </div>
        <div id="viewer-title" class="text-slate-900">상세페이지</div>
      </div>
      <button class="close-btn" onclick="closeDetail()"><i class="fa-solid fa-arrow-left"></i> 포털로</button>
    </div>

    <div class="relative flex-1">
      <div id="viewer-loading">
        <div class="spinner"></div>
        <div class="text-slate-600 font-bold">불러오는 중…</div>
      </div>
      <iframe id="detail-iframe" title="프로그램 상세" loading="eager"></iframe>
    </div>
  </div>

  <script>
    const DETAIL_PAGES = {
  "\uccad\uc18c\ub144\ub514\uc9c0\ud138\ub4dc\ub85c\uc789\uad50\uc2e4.html": `<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>청소년 디지털드로잉 교실 안내</title>
    <script src="https://cdn.tailwindcss.com"><\/script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            word-break: keep-all;
            scroll-behavior: smooth; /* 부드러운 스크롤 이동 */
        }

        .art-gradient {
            background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 50%, #d946ef 100%);
        }

        .glass {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.3);
        }

        /* 글자 잘림 방지를 위해 padding-bottom 추가 */
        .section-title {
            font-weight: 900;
            letter-spacing: -0.03em;
            background: linear-gradient(to right, #4f46e5, #9333ea);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            padding-bottom: 0.2em; 
            display: inline-block;
        }

        .curriculum-card {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .curriculum-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -6px rgba(0, 0, 0, 0.04);
        }

        .list-dot {
            width: 8px;
            height: 8px;
            background: #8b5cf6;
            border-radius: 50%;
            display: inline-block;
            margin-right: 12px;
            flex-shrink: 0;
            margin-top: 10px;
        }
    </style>
</head>
<body class="antialiased">

    <!-- 상단 히어로 섹션 -->
    <header class="relative pt-40 pb-52 overflow-hidden bg-white">
        <div class="absolute top-0 right-0 -mr-20 -mt-20 w-96 h-96 bg-indigo-100 rounded-full blur-3xl opacity-60"></div>
        <div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-96 h-96 bg-purple-100 rounded-full blur-3xl opacity-60"></div>

        <div class="max-w-4xl mx-auto px-6 relative z-10 text-center">
            <div class="inline-flex items-center bg-indigo-50 border border-indigo-100 px-4 py-1.5 rounded-full text-indigo-600 font-bold text-sm mb-8 shadow-sm">
                <span class="flex h-2 w-2 rounded-full bg-indigo-500 mr-2 animate-ping"></span>
                영등포장애인복지관 아동청소년팀
            </div>
            <h1 class="text-6xl md:text-8xl font-black mb-8 leading-[1.1] tracking-tighter">
                상상이 <span class="text-indigo-600">예술</span>이<br>되는 시간
            </h1>
            <p class="text-2xl text-gray-500 font-medium mb-12 leading-relaxed max-w-2xl mx-auto">
                최신 디지털 도구로 펼치는 우리들만의 드로잉 스튜디오.<br>
                태블릿과 펜슬만 있다면 누구나 아티스트가 될 수 있습니다.
            </p>
            <div class="flex flex-wrap gap-4 justify-center">
                <a href="#curriculum" class="bg-indigo-600 text-white px-10 py-4 rounded-2xl font-bold text-xl shadow-xl shadow-indigo-200 hover:bg-indigo-700 transition">
                    2026 프로그램 안내
                </a>
                <div class="bg-white border border-gray-200 px-10 py-4 rounded-2xl font-bold text-xl text-gray-700 shadow-sm cursor-default">
                    상시 모집 중
                </div>
            </div>
        </div>
    </header>

    <!-- 요약 정보 보드 -->
    <section class="max-w-6xl mx-auto -mt-24 px-6 mb-32 relative z-20">
        <div class="glass rounded-[3rem] p-12 shadow-2xl grid grid-cols-1 md:grid-cols-3 gap-12 text-center md:text-left">
            <div class="flex flex-col items-center md:items-start">
                <div class="w-14 h-14 bg-indigo-100 text-indigo-600 rounded-2xl flex items-center justify-center text-2xl mb-6">
                    <i class="fa-solid fa-location-dot"></i>
                </div>
                <h3 class="text-gray-400 font-bold text-sm uppercase tracking-widest mb-2">Location</h3>
                <p class="text-2xl font-black text-gray-900">도림생활문화센터<br>3층 프로그램방</p>
            </div>
            <div class="flex flex-col items-center md:items-start">
                <div class="w-14 h-14 bg-purple-100 text-purple-600 rounded-2xl flex items-center justify-center text-2xl mb-6">
                    <i class="fa-solid fa-calendar-days"></i>
                </div>
                <h3 class="text-gray-400 font-bold text-sm uppercase tracking-widest mb-2">Schedule</h3>
                <p class="text-2xl font-black text-gray-900">매주 목요일</p>
                <p class="text-lg font-bold text-gray-400 mt-1">오후 4시 ~ 6시 (2~11월)</p>
            </div>
            <div class="flex flex-col items-center md:items-start">
                <div class="w-14 h-14 bg-pink-100 text-pink-600 rounded-2xl flex items-center justify-center text-2xl mb-6">
                    <i class="fa-solid fa-user-tie"></i>
                </div>
                <h3 class="text-gray-400 font-bold text-sm uppercase tracking-widest mb-2">Mentor</h3>
                <p class="text-2xl font-black text-gray-900">임다솔 대표님</p>
                <p class="text-lg font-bold text-gray-400 mt-1">달팽이 네트워크</p>
            </div>
        </div>
    </section>

    <!-- 무엇을 하나요? -->
    <section class="max-w-6xl mx-auto px-6 mb-40">
        <div class="text-center mb-24">
            <h2 class="text-5xl md:text-6xl font-black mb-8 section-title">무엇을 하나요?</h2>
            <p class="text-2xl text-gray-500 font-medium max-w-3xl mx-auto">
                태블릿을 그저 '보는 도구'가 아닌 '만드는 도구'로 활용하는 법을 배웁니다. 기초부터 창작까지 단계별로 함께합니다.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
            <div class="bg-white p-12 rounded-[3.5rem] border border-gray-100 shadow-sm transition-all hover:border-indigo-200 text-center">
                <div class="text-5xl font-black text-indigo-100 mb-8 tracking-tighter italic">01</div>
                <h4 class="text-2xl font-black text-gray-900 mb-6">디지털 도구 마스터</h4>
                <p class="text-lg text-gray-500 leading-relaxed font-medium">태블릿과 애플펜슬, 드로잉 앱의 핵심 기능을 익혀 창작을 위한 기초 체력을 기릅니다.</p>
            </div>
            <div class="bg-white p-12 rounded-[3.5rem] border border-gray-100 shadow-sm transition-all hover:border-purple-200 text-center">
                <div class="text-5xl font-black text-purple-100 mb-8 tracking-tighter italic">02</div>
                <h4 class="text-2xl font-black text-gray-900 mb-6">트레이싱 & 드로잉</h4>
                <p class="text-lg text-gray-500 leading-relaxed font-medium">사진이나 스케치를 따라 그리며 선의 강약과 형태를 잡는 디지털 드로잉 감각을 익힙니다.</p>
            </div>
            <div class="bg-white p-12 rounded-[3.5rem] border border-gray-100 shadow-sm transition-all hover:border-pink-200 text-center">
                <div class="text-5xl font-black text-pink-100 mb-8 tracking-tighter italic">03</div>
                <h4 class="text-2xl font-black text-gray-900 mb-6">창작물 & 애니메이션 완성</h4>
                <p class="text-lg text-gray-500 leading-relaxed font-medium">나만의 캐릭터를 디자인하고 직접 움직이는 애니메이션을 만들어 작품을 완성합니다.</p>
            </div>
        </div>
    </section>

    <!-- 선생님 프로필 -->
    <section class="py-32 bg-indigo-50/30 overflow-hidden relative">
        <div class="max-w-6xl mx-auto px-6 relative z-10 text-center md:text-left">
            <div class="flex flex-col md:flex-row items-center gap-20">
                <div class="flex-1">
                    <span class="text-indigo-600 font-black text-lg tracking-[0.3em] uppercase mb-4 block">Meet the Mentor</span>
                    <h2 class="text-5xl md:text-7xl font-black text-gray-900 italic mb-10 tracking-tighter">임다솔 선생님</h2>
                    <blockquote class="text-2xl md:text-4xl font-light text-gray-500 leading-tight italic mb-12">
                        "그림은 정답이 없습니다. 여러분의 선 하나가 세상과 소통하는 따뜻한 대화가 되도록 돕겠습니다."
                    </blockquote>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-12 pt-12 border-t border-indigo-100 text-left">
                        <div>
                            <h5 class="text-indigo-400 font-black text-sm uppercase mb-6 tracking-widest">Background</h5>
                            <ul class="text-lg text-gray-700 space-y-4">
                                <li class="flex"><span class="list-dot"></span> 한양대 공공정책대학원 석사</li>
                                <li class="flex"><span class="list-dot"></span> 용인대학교 회화학과 학사</li>
                                <li class="flex"><span class="list-dot"></span> 문화예술교육사 전문 자격</li>
                            </ul>
                        </div>
                        <div>
                            <h5 class="text-purple-400 font-black text-sm uppercase mb-6 tracking-widest">Experience</h5>
                            <ul class="text-lg text-gray-700 space-y-4">
                                <li class="flex"><span class="list-dot" style="background: #a855f7;"></span> 달팽이 네트워크 공동대표</li>
                                <li class="flex"><span class="list-dot" style="background: #a855f7;"></span> 신경다양성 창작실 운영</li>
                                <li class="flex"><span class="list-dot" style="background: #a855f7;"></span> 장애 청소년 예술교육 전문가</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 커리큘럼 여정 -->
    <section id="curriculum" class="max-w-6xl mx-auto px-6 py-40">
        <div class="text-center mb-24">
            <h2 class="text-5xl md:text-6xl font-black mb-8 section-title">성장하는 드로잉 여정</h2>
            <p class="text-2xl text-gray-400 font-medium">40주간 펼쳐지는 체계적인 창작 단계</p>
        </div>

        <div class="space-y-8">
            <div class="curriculum-card bg-white p-12 rounded-[3.5rem] border border-gray-100 flex flex-col md:flex-row gap-12 items-center">
                <div class="w-32 h-32 bg-indigo-600 text-white rounded-full flex flex-col items-center justify-center shrink-0 shadow-xl shadow-indigo-100">
                    <span class="text-sm font-bold opacity-80 uppercase">Step 1</span>
                    <span class="text-3xl font-black">기초</span>
                </div>
                <div class="flex-1 text-center md:text-left">
                    <div class="flex flex-col md:flex-row items-center gap-4 mb-4">
                        <span class="text-indigo-500 font-black text-xl">1~15회기</span>
                        <h4 class="text-3xl font-black text-gray-900">도구 익히기 & 기초 드로잉</h4>
                    </div>
                    <p class="text-xl text-gray-500 font-medium leading-relaxed">나만의 시그니처 달팽이 그리기, 드로잉 앱 인터페이스 마스터, 사진 트레이싱 기법 익히기</p>
                </div>
            </div>

            <div class="curriculum-card bg-white p-12 rounded-[3.5rem] border border-gray-100 flex flex-col md:flex-row gap-12 items-center">
                <div class="w-32 h-32 bg-purple-600 text-white rounded-full flex flex-col items-center justify-center shrink-0 shadow-xl shadow-purple-100">
                    <span class="text-sm font-bold opacity-80 uppercase">Step 2</span>
                    <span class="text-3xl font-black">심화</span>
                </div>
                <div class="flex-1 text-center md:text-left">
                    <div class="flex flex-col md:flex-row items-center gap-4 mb-4">
                        <span class="text-purple-500 font-black text-xl">16~30회기</span>
                        <h4 class="text-3xl font-black text-gray-900">표현의 확장</h4>
                    </div>
                    <p class="text-xl text-gray-500 font-medium leading-relaxed">디지털 풍경화 제작, 다양한 브러시 질감 활용, 점묘법 응용, 움직이는 애니메이션 제작</p>
                </div>
            </div>

            <div class="curriculum-card art-gradient p-12 rounded-[3.5rem] flex flex-col md:flex-row gap-12 items-center text-white shadow-2xl">
                <div class="w-32 h-32 bg-white text-indigo-600 rounded-full flex flex-col items-center justify-center shrink-0 shadow-xl">
                    <span class="text-sm font-bold opacity-60 uppercase">Step 3</span>
                    <span class="text-3xl font-black">완성</span>
                </div>
                <div class="flex-1 text-center md:text-left">
                    <div class="flex flex-col md:flex-row items-center gap-4 mb-4">
                        <span class="text-yellow-300 font-black text-xl">31~40회기</span>
                        <h4 class="text-3xl font-black">자유 창작 & 작품집 완성</h4>
                    </div>
                    <p class="text-xl opacity-90 font-medium leading-relaxed">나만의 고유한 스타일을 살린 자유 드로잉 프로젝트, 1년 동안의 성과물을 모은 온라인 전시 준비</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 문의하기 (중앙 정렬 및 문구 수정) -->
    <section class="max-w-6xl mx-auto px-6 mb-40">
        <div class="glass rounded-[4rem] p-20 text-center relative overflow-hidden">
            <div class="absolute top-0 right-0 -mr-20 -mt-20 w-80 h-80 bg-indigo-100 rounded-full blur-3xl opacity-40"></div>
            
            <h2 class="text-5xl font-black text-gray-900 mb-16 italic">프로그램 참여 및 문의</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center relative z-10">
                <div class="bg-white/50 p-10 rounded-[2.5rem] border border-white flex flex-col items-center">
                    <span class="text-indigo-400 font-black text-xs uppercase tracking-widest mb-4 block">주관 부서</span>
                    <p class="text-2xl font-black text-gray-900">영등포장애인복지관<br>아동청소년팀</p>
                </div>
                <div class="bg-indigo-600 px-6 py-10 rounded-[2.5rem] text-white shadow-xl shadow-indigo-100 flex flex-col justify-center items-center">
                    <span class="text-indigo-200 font-black text-xs uppercase tracking-widest mb-4 block">전화 접수</span>
                    <p class="text-2xl font-black tracking-tight whitespace-nowrap">070-5202-0543</p>
                </div>
                <div class="bg-white/50 p-10 rounded-[2.5rem] border border-white flex flex-col items-center">
                    <span class="text-indigo-400 font-black text-xs uppercase tracking-widest mb-4 block">접수 기간</span>
                    <p class="text-2xl font-black text-gray-900">상시모집</p>
                </div>
            </div>
        </div>
    </section>

    <footer class="text-center py-20 border-t border-gray-100 bg-white">
        <p class="text-gray-400 font-bold text-lg">© 2026 영등포장애인복지관. All rights reserved.</p>
    </footer>

</body>
</html>`,
  "\uccad\uc18c\ub144\uba54\uc774\ucee4\uc2a4.html": `<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>청소년 메이커스 - 손끝에서 피어나는 창의력</title>
    <script src="https://cdn.tailwindcss.com"><\/script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"><\/script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;700;900&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #fdfcf9; 
            color: #4a4238;
            scroll-behavior: smooth;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 400px;
        }
        .card {
            background-color: white;
            border-radius: 1.5rem;
            box-shadow: 0 4px 20px -5px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
            border: 1px solid #f1f0e8;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px -10px rgba(0, 0, 0, 0.1);
        }
        .step-active {
            border-bottom: 4px solid #4a7c59;
            color: #4a7c59;
            font-weight: 700;
        }
        .step-inactive {
            border-bottom: 4px solid transparent;
            color: #a0a090;
        }
        input[type=range] {
            -webkit-appearance: none;
            width: 100%;
            background: transparent;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            height: 28px;
            width: 28px;
            border-radius: 50%;
            background: #4a7c59;
            cursor: pointer;
            margin-top: -12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            border: 3px solid white;
        }
        input[type=range]::-webkit-slider-runnable-track {
            width: 100%;
            height: 6px;
            cursor: pointer;
            background: #e5e7eb;
            border-radius: 2px;
        }
    </style>
</head>
<body class="antialiased selection:bg-green-100 selection:text-green-900">

    <!-- Navigation -->
    <nav class="sticky top-0 z-50 bg-white/90 backdrop-blur-sm border-b border-gray-100">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="text-xl font-black text-gray-800 tracking-tight">
                    🛠️ <span class="text-green-700">청소년</span> 메이커스
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#overview" class="text-gray-600 hover:text-green-700 font-medium transition">안내</a>
                    <a href="#journey" class="text-gray-600 hover:text-green-700 font-medium transition">성장 시뮬레이션</a>
                    <a href="#curriculum" class="text-gray-600 hover:text-green-700 font-medium transition">전체 커리큘럼</a>
                    <a href="#apply" class="text-gray-600 hover:text-green-700 font-medium transition">문의</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative bg-gradient-to-br from-green-50 to-stone-100 pt-20 pb-24 px-4 overflow-hidden">
        <div class="max-w-5xl mx-auto text-center relative z-10">
            <div class="inline-block px-4 py-1.5 rounded-full bg-white border border-green-100 text-green-700 font-bold text-sm mb-6 shadow-sm">
                🧶 시립영등포장애인복지관 아동청소년팀
            </div>
            <h1 class="text-5xl md:text-7xl font-black text-gray-900 mb-6 tracking-tight leading-tight">
                상상을 현실로,<br>
                나만의 <span class="text-green-700">작품 세상</span>
            </h1>
            <p class="text-xl text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed">
                2~6월, 매주 월요일 오후 5시!<br>
                손끝으로 배우고 마음으로 느끼는 18번의 창의 여행을 떠나보세요.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#journey" class="bg-green-700 text-white text-lg px-8 py-4 rounded-xl font-bold shadow-lg hover:bg-green-800 transition">활동별 변화 미리보기</a>
                <a href="#curriculum" class="bg-white text-gray-700 hover:bg-gray-50 border border-gray-200 text-lg px-8 py-4 rounded-xl font-bold shadow-sm transition">전체 활동 확인</a>
            </div>
        </div>
        <div class="absolute top-10 left-10 w-32 h-32 bg-yellow-100 rounded-full mix-blend-multiply filter blur-2xl opacity-60 animate-pulse"></div>
        <div class="absolute bottom-10 right-10 w-40 h-40 bg-green-200 rounded-full mix-blend-multiply filter blur-3xl opacity-40 animate-pulse"></div>
    </header>

    <!-- Overview Dashboard -->
    <section id="overview" class="py-20 max-w-6xl mx-auto px-4">
        <div class="mb-12 text-center">
            <h2 class="text-3xl font-bold text-gray-900 mb-4">프로그램 핵심 요약</h2>
            <p class="text-gray-500">오감을 자극하는 창의 공예 활동의 주인공이 되어보세요.</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            <div class="card p-8 border-l-4 border-green-600">
                <div class="text-3xl mb-3">🗓️</div>
                <h3 class="font-bold text-lg text-gray-900 mb-2">일시</h3>
                <p class="text-gray-600 text-sm leading-relaxed">2~6월 매주 월요일<br>오후 5시 ~ 6시</p>
            </div>
            <div class="card p-8 border-l-4 border-amber-500">
                <div class="text-3xl mb-3">🏠</div>
                <h3 class="font-bold text-lg text-gray-900 mb-2">장소</h3>
                <p class="text-gray-600 text-sm leading-relaxed">영등포장애인복지관<br>3층 주간활동실</p>
            </div>
            <div class="card p-8 border-l-4 border-blue-500">
                <div class="text-3xl mb-3">🎨</div>
                <h3 class="font-bold text-lg text-gray-900 mb-2">내용</h3>
                <p class="text-gray-600 text-sm leading-relaxed">디폼블럭, 보석십자수 등<br>다채로운 생활 공예</p>
            </div>
            <div class="card p-8 border-l-4 border-purple-500">
                <div class="text-3xl mb-3">🤝</div>
                <h3 class="font-bold text-lg text-gray-900 mb-2">대상</h3>
                <p class="text-gray-600 text-sm leading-relaxed">창작활동을 좋아하는<br>청소년 누구나</p>
            </div>
        </div>
    </section>

    <!-- Interactive Journey Section -->
    <section id="journey" class="py-24 bg-white border-y border-gray-100">
        <div class="max-w-6xl mx-auto px-4">
            <div class="grid lg:grid-cols-2 gap-16 items-center">
                <div>
                    <div class="inline-block px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs font-bold mb-4">Interactive Simulator</div>
                    <h2 class="text-3xl md:text-4xl font-black text-gray-900 mb-6">
                        18회차 성장 시뮬레이션
                    </h2>
                    <p class="text-gray-600 mb-8 text-lg leading-relaxed">
                        아래 슬라이더를 <strong>좌우로 밀어보세요.</strong><br>
                        각 회차의 구체적인 활동명과 그에 따른 5대 역량의 변화가 차트에 실시간으로 반영됩니다.
                    </p>

                    <div class="bg-stone-50 p-10 rounded-[2rem] border border-stone-100 shadow-inner mb-8">
                        <div class="flex justify-between items-end mb-6">
                            <span class="text-xs font-bold text-stone-400 uppercase tracking-widest">Session</span>
                            <span class="text-3xl font-black text-green-700" id="sessionDisplay">제 1회차</span>
                            <span class="text-xs font-bold text-stone-400 uppercase tracking-widest">Total 18</span>
                        </div>
                        <input type="range" min="1" max="18" value="1" class="w-full mb-8" id="growthSlider">
                        
                        <div id="dynamicDescription" class="bg-white p-6 rounded-2xl border border-stone-100 shadow-sm min-h-[140px] flex flex-col justify-center">
                            <!-- JS updates this -->
                        </div>
                    </div>
                </div>

                <div class="relative">
                    <div class="chart-container bg-white p-8 rounded-[3rem] shadow-[0_30px_60px_rgba(0,0,0,0.06)] border border-stone-50">
                        <canvas id="growthChart"></canvas>
                    </div>
                    <div class="absolute -z-10 top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-3/4 h-3/4 bg-green-50 rounded-full blur-3xl opacity-50"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Detailed Curriculum Explorer -->
    <section id="curriculum" class="py-24 bg-stone-50">
        <div class="max-w-5xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-900 mb-4">전체 커리큘럼 로드맵</h2>
            <p class="text-center text-gray-500 mb-16">체계적으로 구성된 18회의 메이킹 여정입니다.</p>

            <div class="flex flex-wrap border-b border-gray-200 mb-12 justify-center gap-4">
                <button onclick="switchTab(1)" id="tab-1" class="step-active pb-6 px-8 text-sm md:text-base transition-all text-center">
                    <span class="block text-[10px] font-black uppercase tracking-tighter opacity-50 mb-1">Phase 1</span>
                    기초 조형 & 달력
                </button>
                <button onclick="switchTab(2)" id="tab-2" class="step-inactive pb-6 px-8 text-sm md:text-base transition-all text-center">
                    <span class="block text-[10px] font-black uppercase tracking-tighter opacity-50 mb-1">Phase 2</span>
                    감성 데코 공예
                </button>
                <button onclick="switchTab(3)" id="tab-3" class="step-inactive pb-6 px-8 text-sm md:text-base transition-all text-center">
                    <span class="block text-[10px] font-black uppercase tracking-tighter opacity-50 mb-1">Phase 3</span>
                    창의 융합 & 업사이클
                </button>
            </div>

            <div id="tab-content" class="bg-white rounded-[2rem] shadow-sm border border-stone-100 p-10 md:p-14 min-h-[450px]">
                <!-- Dynamic Content -->
            </div>
        </div>
    </section>

    <!-- Information / Contact -->
    <section id="apply" class="py-24 bg-stone-900 text-white text-center px-4">
        <div class="max-w-3xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-black mb-6">나만의 작품이 완성되는 순간!</h2>
            <p class="text-stone-400 mb-12 text-lg">
                창작의 즐거움은 거창한 것이 아닙니다.<br>
                작은 블럭 하나, 보석 한 알이 모여 만들어낼 놀라운 변화를 함께하세요.
            </p>
            <div class="bg-stone-800 rounded-3xl p-10 max-w-xl mx-auto border border-stone-700 shadow-2xl">
                <h3 class="text-xl font-bold mb-8 text-green-400">📝 프로그램 문의 및 안내</h3>
                <ul class="text-left space-y-8">
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-green-900/50 border border-green-700/50 flex items-center justify-center text-sm font-black text-green-400 mr-5">1</div>
                        <div>
                            <strong class="block text-white text-lg mb-1">참여 안내</strong>
                            <span class="text-stone-400 text-lg leading-relaxed">참여자의 장애특성, 연령대 등을 반영하여 활동 내용이 유연하게 변경될 수 있습니다.</span>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-green-900/50 border border-green-700/50 flex items-center justify-center text-sm font-black text-green-400 mr-5">2</div>
                        <div>
                            <strong class="block text-white text-lg mb-1">접수 방법</strong>
                            <span class="text-stone-400 text-lg leading-relaxed">복지관 방문 접수 및 전화 접수</span>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-green-900/50 border border-green-700/50 flex items-center justify-center text-sm font-black text-green-400 mr-5">3</div>
                        <div>
                            <strong class="block text-white text-lg mb-1">문의 (아동청소년팀)</strong>
                            <span class="text-green-300 font-black block mt-1 text-2xl tracking-tighter">070-5202-0540 ~ 3</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <footer class="bg-stone-50 py-16 border-t border-stone-200 text-center text-xs text-stone-500">
        <p class="mb-3 font-bold">시립영등포장애인복지관</p>
        <p>© 2026 영등포장애인복지관. All rights reserved.</p>
    </footer>

    <script>
        const sessionDetails = {
            1: { title: "오리엔테이션 & 슈링클즈 키링", desc: "첫 만남! 열을 가하면 작아지는 마법 종이로 나만의 열쇠고리를 만들며 공예의 기초를 배웁니다.", stats: [3, 3, 4, 3, 3] },
            2: { title: "포토달력 만들기 1", desc: "나의 소중한 사진들을 선별하고 레이아웃을 잡으며 나만의 시간을 기록하는 첫걸음을 뗗니다.", stats: [4, 4, 4, 4, 3] },
            3: { title: "포토달력 만들기 2", desc: "달력의 디테일을 꾸미고 일정을 기입하며 1년간의 계획을 창의적으로 시각화하여 완성합니다.", stats: [5, 4, 4, 5, 3] },
            4: { title: "3D 디폼블럭 1", desc: "작은 블럭을 연결해 입체물을 만드는 기초 원리를 익히며 공간 지각 능력을 키우기 시작합니다.", stats: [5, 5, 6, 5, 4] },
            5: { title: "3D 디폼블럭 2", desc: "더 복잡한 도안에 도전! 반복적인 조립 과정을 통해 소근육을 정교하게 제어하는 훈련을 합니다.", stats: [6, 6, 7, 6, 4] },
            6: { title: "3D 디폼블럭 3", desc: "대형 입체 캐릭터 완성! 성취감을 느끼고 조형물에 대한 자신감을 완벽하게 확보하는 회차입니다.", stats: [7, 6, 8, 7, 5] },
            7: { title: "초코 프레첼 만들기", desc: "직접 꾸미고 맛보는 즐거움! 시각과 미각을 활용해 창의력을 발휘하는 달콤한 요리 공예 시간입니다.", stats: [8, 5, 7, 8, 6] },
            8: { title: "스칸디아모스 액자 만들기", desc: "천연 이끼의 질감을 느끼며 자연 친화적인 인테리어 소품을 제작해 정서적 안정감을 얻습니다.", stats: [8, 7, 7, 8, 6] },
            9: { title: "보석십자수 액자 만들기 1", desc: "수많은 보석을 정해진 위치에 붙이는 작업을 시작하며 집중력을 폭발적으로 끌어올립니다.", stats: [7, 8, 8, 7, 6] },
            10: { title: "보석십자수 액자 만들기 2", desc: "작업의 중반부! 끈기 있게 결과물을 만들어가며 몰입의 즐거움을 깊이 있게 경험합니다.", stats: [7, 9, 8, 8, 6] },
            11: { title: "보석십자수 액자 만들기 3", desc: "반짝이는 대작 완성! 장시간 집중하여 완성한 작품을 통해 최고의 성취감을 맛봅니다.", stats: [7, 10, 8, 10, 6] },
            12: { title: "펀치니들 액자 만들기", desc: "전용 바늘로 실을 찔러 넣어 포근한 질감을 표현하는 새로운 기법으로 창의적 영역을 넓힙니다.", stats: [9, 9, 9, 9, 7] },
            13: { title: "액막이 명태 만들기", desc: "전통의 의미를 현대적으로 재해석한 인형을 만들며 스토리텔링이 있는 공예를 체험합니다.", stats: [9, 8, 9, 9, 7] },
            14: { title: "2D 디폼블럭", desc: "평면 도안을 활용해 세밀한 캐릭터 굿즈를 신속하고 정확하게 완성하는 연습을 합니다.", stats: [8, 8, 10, 9, 7] },
            15: { title: "노오븐 쿠키 만들기", desc: "안전한 재료로 모양을 빚고 꾸미며 창의적 감각과 협동의 즐거움을 동시에 느낍니다.", stats: [9, 7, 9, 9, 9] },
            16: { title: "테라리움 만들기", desc: "작은 병 속에 생태계를 구성하며 미적 감각과 생명 존중의 마음을 함께 기르는 융합 공예입니다.", stats: [10, 8, 9, 9, 8] },
            17: { title: "병뚜껑 그림액자 만들기 1", desc: "버려지는 병뚜껑을 예술 재료로 재탄생시키며 환경 보호의 가치를 실천하는 업사이클링을 시작합니다.", stats: [10, 9, 9, 9, 8] },
            18: { title: "병뚜껑 그림액자 만들기 2", desc: "18회의 여정 마무리! 재활용 예술 작품을 완성하고 성장한 나의 모습을 돌아보는 피날레입니다.", stats: [10, 9, 10, 10, 9] }
        };

        const curriculumGroups = {
            1: {
                title: "Phase 1: 기초 조형 및 사진 공예",
                subtitle: "탐색과 경험",
                items: [
                    { h: "1회차: 슈링클즈 키링", d: "오리엔테이션 및 기초 공예 기법 익히기" },
                    { h: "2-3회차: 포토달력 만들기", d: "나만의 사진으로 구성하는 디자인 달력" },
                    { h: "4-6회차: 3D 디폼블럭", d: "입체 조립을 통한 공간 감각 향상 활동" }
                ]
            },
            2: {
                title: "Phase 2: 감성 데코 및 고몰입 공예",
                subtitle: "표현과 몰입",
                items: [
                    { h: "7회차: 초코 프레첼", d: "미각과 시각의 창의적 융합 요리 공예" },
                    { h: "8회차: 스칸디아모스", d: "천연 이끼를 활용한 친환경 데코 소품" },
                    { h: "9-11회차: 보석십자수", d: "집중력과 인내심을 키우는 반짝이는 예술" },
                    { h: "12회차: 펀치니들", d: "실의 질감을 살린 포근한 자수 액자" }
                ]
            },
            3: {
                title: "Phase 3: 창의 융합 및 생활 공예",
                subtitle: "조화와 완성",
                items: [
                    { h: "13-14회차: 전통&블럭", d: "액막이 명태 인형 및 2D 캐릭터 굿즈 제작" },
                    { h: "15-16회차: 요리&가드닝", d: "노오븐 쿠키 및 나만의 정원 테라리움" },
                    { h: "17-18회차: 업사이클링", d: "병뚜껑을 활용한 환경 보호 그림 액자 완성" }
                ]
            }
        };

        const ctx = document.getElementById('growthChart').getContext('2d');
        const growthChart = new Chart(ctx, {
            type: 'radar',
            data: {
                labels: ['창의력', '집중력', '소근육 발달', '성취감', '협동심'],
                datasets: [{
                    label: '성장 레벨',
                    data: sessionDetails[1].stats,
                    backgroundColor: 'rgba(74, 124, 89, 0.25)',
                    borderColor: 'rgba(74, 124, 89, 1)',
                    pointBackgroundColor: 'rgba(74, 124, 89, 1)',
                    pointBorderColor: '#fff',
                    pointBorderWidth: 2,
                    borderWidth: 3,
                    pointRadius: 5
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    r: {
                        angleLines: { color: '#f1f0e8' },
                        grid: { color: '#f1f0e8' },
                        suggestedMin: 0,
                        suggestedMax: 10,
                        ticks: { display: false, stepSize: 2 },
                        pointLabels: { font: { size: 14, weight: '700' }, color: '#4a4238' }
                    }
                },
                plugins: { legend: { display: false } }
            }
        });

        const slider = document.getElementById('growthSlider');
        const sessionDisplay = document.getElementById('sessionDisplay');
        const descBox = document.getElementById('dynamicDescription');

        slider.addEventListener('input', (e) => {
            const val = parseInt(e.target.value);
            const data = sessionDetails[val];
            sessionDisplay.innerText = \`제 \${val}회차\`;
            growthChart.data.datasets[0].data = data.stats;
            growthChart.update('none');
            descBox.innerHTML = \`
                <div class="animate-fade-fast">
                    <h4 class="font-black text-gray-900 text-lg mb-2 flex items-center gap-2">
                        <span class="w-2 h-2 rounded-full bg-green-500"></span>
                        \${data.title}
                    </h4>
                    <p class="text-gray-500 text-sm leading-relaxed">\${data.desc}</p>
                </div>
            \`;
        });

        slider.dispatchEvent(new Event('input'));

        function switchTab(id) {
            for(let i=1; i<=3; i++) {
                const btn = document.getElementById(\`tab-\${i}\`);
                btn.className = (i === id) ? "step-active pb-6 px-8 text-sm md:text-base transition-all text-center" : "step-inactive pb-6 px-8 text-sm md:text-base transition-all text-center";
            }
            const group = curriculumGroups[id];
            const contentDiv = document.getElementById('tab-content');
            let listHtml = group.items.map(item => \`
                <div class="flex items-start mb-10 last:mb-0 group">
                    <div class="flex-shrink-0 w-12 h-12 rounded-2xl bg-green-50 flex items-center justify-center text-green-700 font-black mr-6 border border-green-100 group-hover:bg-green-700 group-hover:text-white transition-colors">
                        Q
                    </div>
                    <div>
                        <h4 class="font-bold text-gray-800 text-xl mb-2">\${item.h}</h4>
                        <p class="text-gray-400 leading-relaxed font-medium">\${item.d}</p>
                    </div>
                </div>
            \`).join('');
            contentDiv.innerHTML = \`
                <div class="animate-fade-in">
                    <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-12 pb-8 border-b border-stone-100">
                        <div>
                            <h3 class="text-3xl font-black text-gray-900 mb-2">\${group.title}</h3>
                            <p class="text-green-600 font-bold uppercase tracking-widest text-xs">\${group.subtitle} 단계</p>
                        </div>
                    </div>
                    <div class="grid grid-cols-1 gap-4">\${listHtml}</div>
                </div>
            \`;
        }
        switchTab(1);

        const styleSheet = document.createElement("style");
        styleSheet.innerText = \`
            @keyframes fadeIn { from { opacity: 0; transform: translateY(15px); } to { opacity: 1; transform: translateY(0); } }
            @keyframes fadeInFast { from { opacity: 0; } to { opacity: 1; } }
            .animate-fade-in { animation: fadeIn 0.6s cubic-bezier(0.22, 1, 0.36, 1) forwards; }
            .animate-fade-fast { animation: fadeInFast 0.3s ease-out forwards; }
        \`;
        document.head.appendChild(styleSheet);
    <\/script>
</body>
</html>`,
  "\uccad\uc18c\ub144\ub77c\uc774\ud504\uc5c5.html": `<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>청소년 라이프 up - 자립을 향한 당당한 첫걸음</title>
    <script src="https://cdn.tailwindcss.com"><\/script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"><\/script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;700;900&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #f8fafc; 
            color: #334155;
            scroll-behavior: smooth;
            word-break: keep-all; /* 단어 단위 줄바꿈 방지 */
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 380px;
        }
        .card {
            background-color: white;
            border-radius: 1.5rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
        }
        .step-active {
            border-bottom: 4px solid #0891b2;
            color: #0891b2;
            font-weight: 700;
        }
        .step-inactive {
            border-bottom: 4px solid transparent;
            color: #94a3b8;
        }
        input[type=range] {
            -webkit-appearance: none;
            width: 100%;
            background: transparent;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            height: 24px;
            width: 24px;
            border-radius: 50%;
            background: #0891b2;
            cursor: pointer;
            margin-top: -10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            border: 2px solid white;
        }
        input[type=range]::-webkit-slider-runnable-track {
            width: 100%;
            height: 4px;
            cursor: pointer;
            background: #e2e8f0;
            border-radius: 2px;
        }
        /* 모바일 텍스트 및 레이아웃 최적화 */
        @media (max-width: 640px) {
            .hero-title { font-size: 2.75rem !important; line-height: 1.2; }
            .section-title { font-size: 1.75rem !important; }
            .nav-logo { font-size: 1.1rem !important; }
            .tab-btn { font-size: 0.8rem !important; padding: 0.5rem !important; }
        }
    </style>
</head>
<body class="antialiased selection:bg-cyan-100 selection:text-cyan-900">

    <!-- Navigation -->
    <nav class="sticky top-0 z-50 bg-white/90 backdrop-blur-sm border-b border-slate-100">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="nav-logo text-xl font-black text-slate-800 tracking-tight whitespace-nowrap">
                    🚀 <span class="text-cyan-600">청소년</span> 라이프 up
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#overview" class="text-slate-600 hover:text-cyan-600 font-medium transition">개요</a>
                    <a href="#journey" class="text-slate-600 hover:text-cyan-600 font-medium transition">성장 시뮬레이션</a>
                    <a href="#curriculum" class="text-slate-600 hover:text-cyan-600 font-medium transition">로드맵</a>
                    <a href="#apply" class="text-slate-600 hover:text-cyan-600 font-medium transition">접수안내</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative bg-gradient-to-br from-cyan-50 to-blue-50 pt-24 pb-28 px-4 overflow-hidden">
        <div class="max-w-5xl mx-auto text-center relative z-10">
            <div class="inline-block px-4 py-1.5 rounded-full bg-white border border-cyan-100 text-cyan-600 font-bold text-sm mb-8 shadow-sm whitespace-nowrap">
                🏠 영등포장애인복지관 아동청소년팀
            </div>
            <h1 class="hero-title text-5xl md:text-7xl font-black text-slate-900 mb-8 tracking-tight leading-tight break-keep">
                자립을 향한<br class="hidden md:block">
                당당한 <span class="text-cyan-600">첫걸음</span>
            </h1>
            <p class="text-lg md:text-xl text-slate-600 mb-12 max-w-2xl mx-auto leading-relaxed break-keep">
                2~6월 매주 화요일 오후 5시 30분!<br>
                일상의 기술을 스스로 배우고 미래를 설계하는 18회기의 특별한 여정에 초대합니다.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#journey" class="bg-cyan-600 text-white text-lg px-8 py-4 rounded-xl font-bold shadow-lg hover:bg-cyan-700 transition whitespace-nowrap">나의 변화 미리보기</a>
                <a href="#curriculum" class="bg-white text-slate-700 hover:bg-slate-50 border border-slate-200 text-lg px-8 py-4 rounded-xl font-bold shadow-sm transition whitespace-nowrap">전체 로드맵 확인</a>
            </div>
        </div>
        
        <!-- Decoration -->
        <div class="absolute top-20 left-10 w-32 h-32 bg-cyan-200 rounded-full mix-blend-multiply filter blur-3xl opacity-50 animate-pulse"></div>
        <div class="absolute bottom-10 right-10 w-48 h-48 bg-blue-200 rounded-full mix-blend-multiply filter blur-3xl opacity-40 animate-pulse"></div>
    </header>

    <!-- Overview Dashboard -->
    <section id="overview" class="py-20 max-w-6xl mx-auto px-4">
        <div class="mb-12 text-center">
            <h2 class="section-title text-3xl font-bold text-slate-900 mb-4">프로그램 핵심 요약</h2>
            <p class="text-slate-500">2~6월 동안 진행되는 청소년 일상생활 훈련 프로젝트</p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
            <div class="card p-8 border-l-4 border-cyan-600">
                <div class="text-3xl mb-3">🗓️</div>
                <h3 class="font-bold text-lg text-slate-900 mb-2">일시</h3>
                <p class="text-slate-600 text-sm leading-relaxed">2~6월 매주 화요일<br>오후 5:30 ~ 7:00</p>
            </div>
            <div class="card p-8 border-l-4 border-blue-500">
                <div class="text-3xl mb-3">🏢</div>
                <h3 class="font-bold text-lg text-slate-900 mb-2">장소</h3>
                <p class="text-slate-600 text-sm leading-relaxed break-keep">영등포장애인복지관<br>2층 프로그램실</p>
            </div>
            <div class="card p-8 border-l-4 border-emerald-500">
                <div class="text-3xl mb-3">🎯</div>
                <h3 class="font-bold text-lg text-slate-900 mb-2">내용</h3>
                <p class="text-slate-600 text-sm leading-relaxed break-keep">자기관리, 경제활동,<br>진로설계 및 자립체험</p>
            </div>
            <div class="card p-8 border-l-4 border-indigo-500">
                <div class="text-3xl mb-3">🤝</div>
                <h3 class="font-bold text-lg text-slate-900 mb-2">대상</h3>
                <p class="text-slate-600 text-sm leading-relaxed break-keep">일상생활훈련을 희망하는<br>청소년 누구나</p>
            </div>
        </div>
    </section>

    <!-- Interactive Journey Section -->
    <section id="journey" class="py-24 bg-white border-y border-slate-100">
        <div class="max-w-6xl mx-auto px-4">
            <div class="grid lg:grid-cols-2 gap-16 items-center">
                <div>
                    <div class="inline-block px-3 py-1 bg-cyan-100 text-cyan-700 rounded-full text-xs font-bold mb-4">Interactive Simulation</div>
                    <h2 class="section-title text-3xl md:text-4xl font-black text-slate-900 mb-6 break-keep">
                        18회차 후, <br class="md:hidden">달라질 나의 역량은?
                    </h2>
                    <p class="text-lg text-slate-600 mb-8 leading-relaxed break-keep">
                        슬라이더를 움직여 회차별 활동과 자립 역량의 변화를 확인해보세요.
                        체계적인 훈련을 통해 스스로 해내는 기쁨을 시각화했습니다.
                    </p>

                    <div class="bg-slate-50 p-6 md:p-10 rounded-3xl border border-slate-100 shadow-inner mb-8">
                        <div class="flex justify-between items-center mb-6">
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-widest">START</span>
                            <span class="text-2xl md:text-3xl font-black text-cyan-600" id="sessionDisplay">제 1회차</span>
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-widest">END</span>
                        </div>
                        <input type="range" min="1" max="18" value="1" class="w-full mb-8" id="growthSlider">
                        
                        <div id="dynamicDescription" class="bg-white p-6 rounded-2xl border border-slate-100 shadow-sm min-h-[130px] flex flex-col justify-center transition-all duration-300 break-keep">
                            <!-- Injected by JS -->
                        </div>
                    </div>

                    <div class="flex flex-wrap gap-4 text-sm text-slate-500 justify-center lg:justify-start">
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-3 rounded-full bg-cyan-500"></span> 자립성
                        </div>
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-3 rounded-full bg-blue-500"></span> 문제해결
                        </div>
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-3 rounded-full bg-emerald-500"></span> 수행능력
                        </div>
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-3 rounded-full bg-indigo-500"></span> 진로인식
                        </div>
                    </div>
                </div>

                <div class="relative">
                    <div class="chart-container bg-white p-4 md:p-6 rounded-[2.5rem] shadow-[0_20px_50px_rgba(0,0,0,0.08)] border border-slate-50">
                        <canvas id="growthChart"></canvas>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Detailed Curriculum Explorer -->
    <section id="curriculum" class="py-24 bg-slate-50">
        <div class="max-w-5xl mx-auto px-4">
            <h2 class="section-title text-3xl font-bold text-center text-slate-900 mb-4">전체 로드맵</h2>
            <p class="text-center text-slate-500 mb-16">성장 단계별 18회기 전체 일정을 확인하세요.</p>

            <div class="flex flex-wrap border-b border-slate-200 mb-12 justify-center gap-2 md:gap-4">
                <button onclick="switchTab(1)" id="tab-1" class="tab-btn step-active pb-6 px-4 md:px-6 text-sm md:text-base transition-colors text-center break-keep">
                    <span class="block text-xs font-black opacity-50 mb-1">PHASE 1</span>
                    자기관리 & 가사훈련
                </button>
                <button onclick="switchTab(2)" id="tab-2" class="tab-btn step-inactive pb-6 px-4 md:px-6 text-sm md:text-base transition-colors text-center break-keep">
                    <span class="block text-xs font-black opacity-50 mb-1">PHASE 2</span>
                    환경 & 경제활동
                </button>
                <button onclick="switchTab(3)" id="tab-3" class="tab-btn step-inactive pb-6 px-4 md:px-6 text-sm md:text-base transition-colors text-center break-keep">
                    <span class="block text-xs font-black opacity-50 mb-1">PHASE 3</span>
                    자립체험 & 진로설계
                </button>
            </div>

            <div id="tab-content" class="bg-white rounded-3xl shadow-sm border border-slate-100 p-6 md:p-14 min-h-[400px]">
                <!-- Dynamic Content -->
            </div>
        </div>
    </section>

    <!-- Information / Contact -->
    <section id="apply" class="py-24 bg-slate-900 text-white text-center px-4">
        <div class="max-w-3xl mx-auto">
            <h2 class="section-title text-3xl md:text-4xl font-black mb-8 break-keep">내 삶의 주인공으로 우뚝 서는 시간!</h2>
            <p class="text-slate-400 mb-12 text-lg break-keep">
                작은 일상의 변화가 모여 찬란한 자립의 미래를 만듭니다.<br>
                전문적인 지도와 즐거운 경험이 있는 '라이프 up'에 참여하세요.
            </p>
            <div class="bg-slate-800 rounded-3xl p-6 md:p-10 max-w-xl mx-auto border border-slate-700 shadow-2xl">
                <h3 class="text-xl font-bold mb-8 text-cyan-400">📝 프로그램 문의 및 접수</h3>
                <ul class="text-left space-y-8">
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-cyan-900/50 border border-cyan-700/50 flex items-center justify-center text-sm font-black text-cyan-400 mr-5 mt-1">1</div>
                        <div>
                            <strong class="block text-white text-lg mb-1 whitespace-nowrap">참여 안내</strong>
                            <span class="text-slate-400 text-lg leading-relaxed break-keep">참여자의 장애특성, 연령대 등을 반영하여 활동 내용이 유연하게 변경될 수 있습니다.</span>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-cyan-900/50 border border-cyan-700/50 flex items-center justify-center text-sm font-black text-cyan-400 mr-5 mt-1">2</div>
                        <div>
                            <strong class="block text-white text-lg mb-1 whitespace-nowrap">접수 방법</strong>
                            <span class="text-slate-400 text-lg leading-relaxed font-bold break-keep">복지관 방문 접수 및 전화 접수</span>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-cyan-900/50 border border-cyan-700/50 flex items-center justify-center text-sm font-black text-cyan-400 mr-5 mt-1">3</div>
                        <div>
                            <strong class="block text-white text-lg mb-1 whitespace-nowrap">문의처 (아동청소년팀)</strong>
                            <span class="text-cyan-300 font-black block mt-1 text-2xl tracking-tighter whitespace-nowrap">070-5202-0540 ~ 3</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-white py-16 border-t border-slate-200 text-center text-xs text-slate-500">
        <p class="mb-3 font-bold">대한불교조계종사회복지재단 | 영등포장애인복지관</p>
        <p>© 2026 영등포장애인복지관. All rights reserved.</p>
    </footer>

    <script>
        const sessionDetails = {
            1: { title: "오리엔테이션 & 자립이란?", desc: "활동 안내 및 동기부여! 나 스스로 해낸다는 것의 의미와 가치를 함께 이야기합니다.", stats: [2, 2, 2, 1, 3] },
            2: { title: "건강한 식단, 유통기한 확인", desc: "나의 몸을 아끼는 첫걸음! 신선한 식재료를 고르고 안전하게 관리하는 법을 배웁니다.", stats: [3, 3, 3, 2, 3] },
            3: { title: "전자레인지 사용법 & 안전 교육", desc: "가장 기본적인 주방 가전 사용법을 익히고, 화상 및 안전사고를 예방하는 법을 훈련합니다.", stats: [4, 4, 5, 2, 4] },
            4: { title: "요리 활동 (직접 해보기)", desc: "배운 것을 토대로 간단한 요리를 직접 수행하며 성취감을 얻는 실전 주방 훈련입니다.", stats: [5, 5, 7, 3, 5] },
            5: { title: "의류관리 & 계절별 옷차림", desc: "나를 깔끔하게 유지하기! 상황과 날씨에 맞는 옷을 선택하고 관리하는 기술을 배웁니다.", stats: [6, 5, 6, 3, 5] },
            6: { title: "세탁기 활용법 익히기", desc: "혼자서도 빨래할 수 있어요! 세탁기 조작법과 세제 사용법 등 가사 기술을 습득합니다.", stats: [7, 6, 7, 3, 6] },
            7: { title: "청소 및 정리정돈", desc: "내가 머무는 공간 가꾸기! 효율적인 청소법과 정리 정돈의 규칙을 실습합니다.", stats: [8, 7, 8, 3, 6] },
            8: { title: "기후위기 이해하기", desc: "지구를 아끼는 마음! 현재 지구가 겪고 있는 변화와 우리의 역할을 함께 공부합니다.", stats: [7, 7, 7, 5, 7] },
            9: { title: "분리수거 이해하기", desc: "올바른 배출 방법! 재활용품을 구분하고 환경을 지키는 생활 습관을 훈련합니다.", stats: [8, 8, 8, 5, 7] },
            10: { title: "에너지 절약 습관", desc: "아껴 쓰는 즐거움! 전기와 물을 절약하는 사소하지만 중요한 습관들을 익힙니다.", stats: [8, 8, 8, 6, 8] },
            11: { title: "금전 관리 (돈의 개념)", desc: "경제 자립의 기초! 돈의 가치와 화폐 단위, 지출의 기본 개념을 이해합니다.", stats: [8, 9, 8, 7, 8] },
            12: { title: "지출과 저축의 이해", desc: "똑똑하게 쓰고 모으기! 사고 싶은 것과 필요한 것을 구분하고 저축의 필요성을 배웁니다.", stats: [9, 9, 8, 8, 8] },
            13: { title: "모의 구매 활동 (실습)", desc: "장보기 실전! 정해진 예산 내에서 계획적으로 물건을 구매하는 체험 활동을 진행합니다.", stats: [9, 10, 9, 8, 9] },
            14: { title: "자립 체험 (1박 2일)", desc: "부모님 품을 떠나 친구들과 생활하며 그동안 배운 자립 기술을 총동원하는 특별한 캠프!", stats: [10, 10, 10, 9, 10] },
            15: { title: "직업 세계 알아보기", desc: "나는 어떤 일을 할 수 있을까? 다양한 직업군을 탐색하고 나의 흥미를 찾아봅니다.", stats: [9, 8, 9, 10, 9] },
            16: { title: "직업별 실제 업무 탐색", desc: "현장의 소리! 각 직업이 구체적으로 어떤 일을 하는지 심도 있게 알아봅니다.", stats: [9, 9, 9, 10, 9] },
            17: { title: "진로 계획 & 이력서·면접", desc: "꿈 설계하기! 중등부는 진로 계획을, 고등부는 이력서 작성 및 면접 준비를 진행합니다.", stats: [9, 9, 10, 10, 10] },
            18: { title: "내가 배운 것 돌아보기", stats: [10, 10, 10, 10, 10], desc: "피날레! 18회의 여정을 마무리하며 성장한 나의 모습을 확인하고 서로 축하하는 시간입니다." }
        };

        const curriculumGroups = {
            1: {
                title: "자기관리 & 가사훈련",
                subtitle: "가정 내 자립 역량 강화",
                items: [
                    { h: "1-4회차: 건강과 식생활", d: "오리엔테이션, 건강 식단, 주방 안전 및 실전 요리 실습" },
                    { h: "5-7회차: 생활 관리", d: "의류 선택 및 관리, 세탁기 사용법, 정리정돈 기술 습득" }
                ]
            },
            2: {
                title: "환경 & 경제활동",
                subtitle: "지역사회 일원으로서의 준비",
                items: [
                    { h: "8-10회차: 환경 보호", d: "기후위기 교육, 올바른 분리수거 및 에너지 절약 습관 형성" },
                    { h: "11-13회차: 경제 교육", d: "화폐 가치 이해, 합리적 지출과 저축, 실전 모의 구매 활동" }
                ]
            },
            3: {
                title: "자립체험 & 진로설계",
                subtitle: "미래를 향한 당당한 도전",
                items: [
                    { h: "14회차: 자립 체험", d: "독립적인 생활을 직접 경험해보는 1박 2일 자립 체험 캠프" },
                    { h: "15-18회차: 진로 설계", d: "직업 탐색, 진로 계획 수립, 이력서/면접 훈련 및 활동 리뷰" }
                ]
            }
        };

        const ctx = document.getElementById('growthChart').getContext('2d');
        const growthChart = new Chart(ctx, {
            type: 'radar',
            data: {
                labels: ['자립성', '문제해결', '수행능력', '진로인식', '자신감'],
                datasets: [{
                    label: '성장 레벨',
                    data: sessionDetails[1].stats,
                    backgroundColor: 'rgba(8, 145, 178, 0.2)',
                    borderColor: 'rgba(8, 145, 178, 1)',
                    pointBackgroundColor: 'rgba(8, 145, 178, 1)',
                    pointBorderColor: '#fff',
                    pointBorderWidth: 2,
                    borderWidth: 3,
                    pointRadius: 5
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    r: {
                        angleLines: { color: '#e2e8f0' },
                        grid: { color: '#e2e8f0' },
                        suggestedMin: 0,
                        suggestedMax: 10,
                        ticks: { display: false, stepSize: 2 },
                        pointLabels: { font: { size: 12, weight: '700' }, color: '#334155' } 
                    }
                },
                plugins: { legend: { display: false } }
            }
        });

        const slider = document.getElementById('growthSlider');
        const sessionDisplay = document.getElementById('sessionDisplay');
        const descBox = document.getElementById('dynamicDescription');

        slider.addEventListener('input', (e) => {
            const val = parseInt(e.target.value);
            const data = sessionDetails[val];
            sessionDisplay.innerText = \`제 \${val}회차\`;
            growthChart.data.datasets[0].data = data.stats;
            growthChart.update('none');
            descBox.innerHTML = \`
                <div class="animate-fade-fast">
                    <h4 class="font-black text-slate-900 text-lg mb-2 flex items-center gap-2">
                        <span class="w-2 h-2 rounded-full bg-cyan-500"></span>
                        \${data.title}
                    </h4>
                    <p class="text-slate-500 text-sm leading-relaxed">\${data.desc}</p>
                </div>
            \`;
        });

        slider.dispatchEvent(new Event('input'));

        function switchTab(id) {
            for(let i=1; i<=3; i++) {
                const btn = document.getElementById(\`tab-\${i}\`);
                btn.className = (i === id) ? "tab-btn step-active pb-6 px-4 md:px-6 text-sm md:text-base transition-colors text-center break-keep" : "tab-btn step-inactive pb-6 px-4 md:px-6 text-sm md:text-base transition-colors text-center break-keep";
            }
            const group = curriculumGroups[id];
            const contentDiv = document.getElementById('tab-content');
            let listHtml = group.items.map(item => \`
                <div class="flex items-start mb-10 last:mb-0 group">
                    <div class="flex-shrink-0 w-12 h-12 rounded-2xl bg-cyan-50 flex items-center justify-center text-cyan-700 font-black mr-6 border border-cyan-100 group-hover:bg-cyan-700 group-hover:text-white transition-all">
                        🚀
                    </div>
                    <div>
                        <h4 class="font-bold text-slate-800 text-xl mb-2">\${item.h}</h4>
                        <p class="text-slate-400 leading-relaxed font-medium text-lg break-keep">\${item.d}</p>
                    </div>
                </div>
            \`).join('');
            contentDiv.innerHTML = \`
                <div class="animate-fade-in-up">
                    <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-12 pb-8 border-b border-slate-100">
                        <div>
                            <h3 class="text-3xl font-black text-slate-900 mb-2 break-keep">\${group.title}</h3>
                            <p class="text-cyan-600 font-bold uppercase tracking-widest text-xs">\${group.subtitle}</p>
                        </div>
                    </div>
                    <div class="grid grid-cols-1 gap-4">\${listHtml}</div>
                </div>
            \`;
        }
        switchTab(1);

        const styleSheet = document.createElement("style");
        styleSheet.innerText = \`
            @keyframes fadeInUp { from { opacity: 0; transform: translateY(15px); } to { opacity: 1; transform: translateY(0); } }
            @keyframes fadeInFast { from { opacity: 0; } to { opacity: 1; } }
            .animate-fade-in-up { animation: fadeInUp 0.6s cubic-bezier(0.22, 1, 0.36, 1) forwards; }
            .animate-fade-fast { animation: fadeInFast 0.3s ease-out forwards; }
        \`;
        document.head.appendChild(styleSheet);
    <\/script>
</body>
</html>`,
  "\uccad\uc18c\ub144 \ub304\uc2a4\uad50\uc2e4.html": `<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2026 청소년 댄스교실 - 꿈을 향한 스텝</title>
    <script src="https://cdn.tailwindcss.com"><\/script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"><\/script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;700;900&display=swap" rel="stylesheet">
    
    <!-- Chosen Palette: Warm Neutrals & Energetic Coral -->
    <!-- Application Structure Plan: 
         1. Hero Section: Focused on the dream and corrected organization name '영등포장애인복지관'.
         2. Program Overview: Detailed logistics (Feb-Nov, Fri 4-6 PM) at 'Underground Special Gym'.
         3. Growth Journey: Interactive visualization of 40-week progress.
         4. Curriculum Explorer: Month-based thematic breakdowns.
         5. Information/Contact: Specific team contact numbers (070-5202-0540~0543) without registration buttons as requested.
    -->

    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #fdfbf7; 
            color: #4a4a4a;
            scroll-behavior: smooth;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 400px;
        }
        @media (max-width: 640px) {
            .chart-container {
                height: 300px;
            }
        }
        .card {
            background-color: white;
            border-radius: 1rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03);
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-2px);
        }
        .step-active {
            border-bottom: 4px solid #ff6b6b;
            color: #ff6b6b;
            font-weight: 700;
        }
        .step-inactive {
            border-bottom: 4px solid transparent;
            color: #a0aec0;
        }
        .step-inactive:hover {
            color: #718096;
        }
        input[type=range] {
            -webkit-appearance: none;
            width: 100%;
            background: transparent;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            height: 24px;
            width: 24px;
            border-radius: 50%;
            background: #ff6b6b;
            cursor: pointer;
            margin-top: -10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.2);
        }
        input[type=range]::-webkit-slider-runnable-track {
            width: 100%;
            height: 4px;
            cursor: pointer;
            background: #e2e8f0;
            border-radius: 2px;
        }
    </style>
</head>
<body class="antialiased selection:bg-red-100 selection:text-red-900">

    <!-- Navigation -->
    <nav class="sticky top-0 z-50 bg-white/90 backdrop-blur-sm border-b border-gray-100">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="text-xl font-black text-gray-800 tracking-tight">
                    <span class="text-red-500">2026</span> 청소년 댄스교실
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#overview" class="text-gray-600 hover:text-red-500 font-medium transition">개요</a>
                    <a href="#journey" class="text-gray-600 hover:text-red-500 font-medium transition">성장 시뮬레이션</a>
                    <a href="#curriculum" class="text-gray-600 hover:text-red-500 font-medium transition">상세 커리큘럼</a>
                    <a href="#apply" class="text-gray-600 hover:text-red-500 font-medium transition">안내 및 문의</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative bg-gradient-to-br from-red-50 to-orange-50 pt-20 pb-24 px-4 overflow-hidden">
        <div class="max-w-5xl mx-auto text-center relative z-10">
            <div class="inline-block px-4 py-1.5 rounded-full bg-white border border-red-100 text-red-500 font-bold text-sm mb-6 shadow-sm">
                💃 영등포장애인복지관 아동청소년팀
            </div>
            <h1 class="text-5xl md:text-7xl font-black text-gray-900 mb-6 tracking-tight leading-tight">
                꿈을 향한 <span class="text-red-500">스텝</span>,<br>
                주인공은 바로 너!
            </h1>
            <p class="text-xl text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed">
                2026년 2월부터 11월까지, 40주간의 여정!<br>
                <span class="font-bold text-gray-800 text-red-600">영등포장애인복지관 지하 특수체육실</span>에서 펼쳐질 신나는 댄스 타임!
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#journey" class="bg-red-500 text-white text-lg px-8 py-4 rounded-xl font-bold shadow-lg hover:bg-red-600 transition">나의 성장 미리보기</a>
                <a href="#curriculum" class="bg-white text-gray-700 hover:bg-gray-50 border border-gray-200 text-lg px-8 py-4 rounded-xl font-bold shadow-sm transition">커리큘럼 확인</a>
            </div>
        </div>
        
        <!-- Decoration -->
        <div class="absolute top-10 left-10 w-24 h-24 bg-yellow-200 rounded-full mix-blend-multiply filter blur-xl opacity-70 animate-pulse"></div>
        <div class="absolute top-10 right-10 w-24 h-24 bg-red-200 rounded-full mix-blend-multiply filter blur-xl opacity-70 animate-pulse"></div>
    </header>

    <!-- Overview Dashboard -->
    <section id="overview" class="py-20 max-w-6xl mx-auto px-4">
        <div class="mb-12 text-center">
            <h2 class="text-3xl font-bold text-gray-900 mb-4">프로그램 핵심 요약</h2>
            <p class="text-gray-500">2026년 2월부터 11월까지 이어지는 알찬 성장 프로젝트</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            <div class="card p-6 border-l-4 border-red-500">
                <div class="text-2xl mb-2">📅</div>
                <h3 class="font-bold text-lg text-gray-900 mb-1">일시</h3>
                <p class="text-gray-600 text-sm">2026년 2~11월<br>매주 금요일 오후 4~6시</p>
            </div>
            <div class="card p-6 border-l-4 border-orange-400">
                <div class="text-2xl mb-2">📍</div>
                <h3 class="font-bold text-lg text-gray-900 mb-1">장소</h3>
                <p class="text-gray-600 text-sm">영등포장애인복지관<br>지하 특수체육실</p>
            </div>
            <div class="card p-6 border-l-4 border-yellow-400">
                <div class="text-2xl mb-2">👯‍♀️</div>
                <h3 class="font-bold text-lg text-gray-900 mb-1">대상</h3>
                <p class="text-gray-600 text-sm">춤을 사랑하는<br>청소년 누구나</p>
            </div>
            <div class="card p-6 border-l-4 border-pink-400">
                <div class="text-2xl mb-2">🎵</div>
                <h3 class="font-bold text-lg text-gray-900 mb-1">내용</h3>
                <p class="text-gray-600 text-sm">최신 K-POP 방송댄스<br>& 신체 발달 활동</p>
            </div>
        </div>
    </section>

    <!-- Interactive Journey Section -->
    <section id="journey" class="py-20 bg-white border-y border-gray-100">
        <div class="max-w-6xl mx-auto px-4">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <div class="inline-block px-3 py-1 bg-red-100 text-red-600 rounded-full text-xs font-bold mb-4">Interactive</div>
                    <h2 class="text-3xl md:text-4xl font-black text-gray-900 mb-6">
                        40주 후, <br>달라질 나의 모습은?
                    </h2>
                    <p class="text-gray-600 mb-8 text-lg leading-relaxed">
                        아래 슬라이더를 움직여 2월부터 11월까지의 성장 과정을 확인해보세요.
                        매주 금요일, 특수체육실에서 쌓여갈 변화를 시각화했습니다.
                    </p>

                    <div class="bg-gray-50 p-8 rounded-2xl border border-gray-200 shadow-inner mb-8">
                        <div class="flex justify-between mb-4">
                            <span class="text-sm font-bold text-gray-500">2월 (1주차)</span>
                            <span class="text-xl font-black text-red-500" id="weekDisplay">Week 1</span>
                            <span class="text-sm font-bold text-gray-500">11월 (40주차)</span>
                        </div>
                        <input type="range" min="1" max="40" value="1" class="w-full mb-6" id="growthSlider">
                        
                        <div id="dynamicDescription" class="bg-white p-4 rounded-xl border border-gray-100 shadow-sm transition-all duration-300">
                            <h4 class="font-bold text-gray-900 mb-2">🌱 STEP 1: 기초 탐구 (진행중)</h4>
                            <p class="text-gray-600 text-sm">아직은 어색하지만, 내 몸의 움직임을 알아가고 있어요. 기본 스텝부터 차근차근!</p>
                        </div>
                    </div>

                    <div class="flex gap-4 text-sm text-gray-500">
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-3 rounded-full bg-red-200"></span> 신체발달
                        </div>
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-3 rounded-full bg-blue-200"></span> 리듬감
                        </div>
                        <div class="flex items-center gap-2">
                            <span class="w-3 h-3 rounded-full bg-yellow-200"></span> 자신감
                        </div>
                    </div>
                </div>

                <div>
                    <div class="chart-container bg-white p-4 rounded-3xl shadow-[0_20px_50px_rgba(0,0,0,0.1)] border border-gray-100">
                        <canvas id="growthChart"></canvas>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Detailed Curriculum Explorer -->
    <section id="curriculum" class="py-20 bg-gray-50">
        <div class="max-w-5xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-900 mb-4">상세 커리큘럼 탐색</h2>
            <p class="text-center text-gray-500 mb-12">매주 금요일 진행되는 활동의 구체적인 단계를 확인하세요.</p>

            <div class="flex flex-wrap border-b border-gray-200 mb-8 justify-center gap-2 md:gap-8">
                <button onclick="switchTab(1)" id="tab-1" class="step-active pb-4 px-4 text-sm md:text-base transition-colors">STEP 1<br><span class="text-xs font-normal">2~4월 기초 탐구</span></button>
                <button onclick="switchTab(2)" id="tab-2" class="step-inactive pb-4 px-4 text-sm md:text-base transition-colors">STEP 2<br><span class="text-xs font-normal">5~6월 디테일 강화</span></button>
                <button onclick="switchTab(3)" id="tab-3" class="step-inactive pb-4 px-4 text-sm md:text-base transition-colors">STEP 3<br><span class="text-xs font-normal">7~9월 감정 표현</span></button>
                <button onclick="switchTab(4)" id="tab-4" class="step-inactive pb-4 px-4 text-sm md:text-base transition-colors">STEP 4<br><span class="text-xs font-normal">10~11월 완성</span></button>
            </div>

            <div id="tab-content" class="bg-white rounded-2xl shadow-sm border border-gray-100 p-8 md:p-12 min-h-[300px]">
                <!-- Dynamic Content Injected via JS -->
            </div>
        </div>
    </section>

    <!-- Information / Contact (Buttons Removed) -->
    <section id="apply" class="py-20 bg-gray-900 text-white text-center px-4">
        <div class="max-w-3xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-black mb-6">무대의 주인공은 바로 당신입니다!</h2>
            <p class="text-gray-300 mb-10 text-lg">
                매주 금요일 오후 4시, 영등포장애인복지관 지하 특수체육실에서 만나요.<br>
                춤을 통해 더 멋진 나를 만나는 시간에 여러분을 초대합니다.
            </p>
            <div class="bg-gray-800 rounded-xl p-8 max-w-xl mx-auto border border-gray-700">
                <h3 class="text-xl font-bold mb-6 text-red-400">📝 접수 및 문의 안내</h3>
                <ul class="text-left space-y-6">
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-6 h-6 rounded-full bg-red-500 flex items-center justify-center text-xs font-bold mr-4 mt-1">1</div>
                        <div>
                            <strong class="block text-white text-lg">접수 기간</strong>
                            <span class="text-gray-400">상시모집</span>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-6 h-6 rounded-full bg-red-500 flex items-center justify-center text-xs font-bold mr-4 mt-1">2</div>
                        <div>
                            <strong class="block text-white text-lg">활동 장소</strong>
                            <span class="text-gray-400 text-lg">영등포장애인복지관 지하 특수체육실</span>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <div class="flex-shrink-0 w-6 h-6 rounded-full bg-red-500 flex items-center justify-center text-xs font-bold mr-4 mt-1">3</div>
                        <div>
                            <strong class="block text-white text-lg">문의처 (아동청소년팀)</strong>
                            <span class="text-gray-100 font-bold block mt-1 text-xl tracking-wider">070-5202-0540 ~ 0543</span>
                            <span class="text-gray-400 text-sm mt-1 block">궁금한 점은 언제든 전화주세요!</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <footer class="bg-gray-50 py-12 border-t border-gray-200 text-center text-sm text-gray-500">
        <p class="mb-2">© 2026 영등포장애인복지관. All rights reserved.</p>
        <p>본 프로그램은 청소년의 건강한 성장과 즐거운 활동을 지원합니다.</p>
    </footer>

    <script>
        const curriculumData = {
            1: {
                title: "STEP 1: 기초 탐구 및 신체 발달",
                subtitle: "\\"내 몸과 친해지는 시간 (2월~4월)\\"",
                items: [
                    { header: "방송댄스 입문", desc: "기본 안무를 익히며 나의 신체 가동범위를 알아봅니다." },
                    { header: "소근육 & 스텝", desc: "까다로운 손동작과 기본 스텝을 반복 연습하여 탄탄한 기초를 다집니다." },
                    { header: "중간 점검", desc: "그동안 배운 동작의 숙련도를 높여 자신감을 키웁니다." }
                ],
                weeks: "1~10회기 (2월~4월)"
            },
            2: {
                title: "STEP 2: 리듬 정복 및 디테일 강화",
                subtitle: "\\"리듬에 몸을 맡겨봐! (5월~6월)\\"",
                items: [
                    { header: "박자 감각", desc: "노래 박자에 맞춰 정확한 타이밍에 동작을 연결하는 법을 배웁니다." },
                    { header: "동작의 강약", desc: "춤의 '맛'을 살리는 동작의 크기 조절과 강약 조절을 익힙니다." },
                    { header: "포인트 안무", desc: "곡의 핵심이 되는 킬링 포인트 동작을 마스터합니다." }
                ],
                weeks: "11~20회기 (5월~6월)"
            },
            3: {
                title: "STEP 3: 감정 표현 및 몰입",
                subtitle: "\\"춤으로 말하는 우리들의 이야기 (7월~9월)\\"",
                items: [
                    { header: "표정 연기", desc: "가사의 의미를 이해하고 신체와 표정으로 감정을 표현합니다." },
                    { header: "심화 신체 발달", desc: "가동범위 이상을 활용하는 역동적이고 큰 동작에 도전합니다." },
                    { header: "완성도 UP", desc: "전체적인 안무의 흐름을 이해하고 몰입하는 집중 연습 기간입니다." }
                ],
                weeks: "21~30회기 (7월~9월)"
            },
            4: {
                title: "STEP 4: 조화와 완성",
                subtitle: "\\"함께라서 더 빛나는 무대 (10월~11월)\\"",
                items: [
                    { header: "고난이도 스텝", desc: "복합적인 스텝과 빠른 리듬을 완벽하게 소화합니다." },
                    { header: "팀 구성 (Formation)", desc: "혼자가 아닌 '함께' 합을 맞추며 대형을 이동하고 협동심을 기릅니다." },
                    { header: "최종 리뷰", desc: "1년간의 성장을 확인하고 서로 격려하는 감동의 피날레!" }
                ],
                weeks: "31~40회기 (10월~11월)"
            }
        };

        const growthStages = [
            { week: 0,  data: [1, 1, 1, 2, 1], label: "시작 전", desc: "매주 금요일 오후, 새로운 도전이 시작됩니다!" },
            { week: 10, data: [3, 2, 2, 4, 3], label: "4월 말", desc: "기초 동작을 익히니 몸이 훨씬 가벼워졌어요!" },
            { week: 20, data: [5, 5, 3, 6, 4], label: "6월 말", desc: "박자를 가지고 놀기 시작했어요. 디테일이 살아납니다." },
            { week: 30, data: [7, 7, 7, 8, 6], label: "9월 말", desc: "내 감정을 춤으로 표현할 수 있어요. 자신감 뿜뿜!" },
            { week: 40, data: [9, 9, 9, 10, 10], label: "11월 말 (수료)", desc: "친구들과 완벽한 호흡! 우리는 영등포장애인복지관의 주인공입니다." }
        ];

        const ctx = document.getElementById('growthChart').getContext('2d');
        const growthChart = new Chart(ctx, {
            type: 'radar',
            data: {
                labels: ['신체 능력', '리듬감', '표현력', '자신감', '협동심'],
                datasets: [{
                    label: '나의 성장 레벨',
                    data: growthStages[0].data,
                    backgroundColor: 'rgba(255, 107, 107, 0.2)',
                    borderColor: 'rgba(255, 107, 107, 1)',
                    pointBackgroundColor: 'rgba(255, 107, 107, 1)',
                    borderWidth: 2,
                    pointRadius: 4
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    r: {
                        angleLines: { display: true, color: '#e2e8f0' },
                        grid: { color: '#e2e8f0' },
                        suggestedMin: 0,
                        suggestedMax: 10,
                        ticks: { display: false }
                    }
                },
                plugins: {
                    legend: { display: false }
                }
            }
        });

        const slider = document.getElementById('growthSlider');
        const weekDisplay = document.getElementById('weekDisplay');
        const descBox = document.getElementById('dynamicDescription');

        slider.addEventListener('input', (e) => {
            const week = parseInt(e.target.value);
            weekDisplay.innerText = \`Week \${week}\`;
            
            let stageIndex = 0;
            if (week >= 10 && week < 20) stageIndex = 1;
            else if (week >= 20 && week < 30) stageIndex = 2;
            else if (week >= 30 && week < 40) stageIndex = 3;
            else if (week === 40) stageIndex = 4;

            const currentStage = growthStages[stageIndex];
            
            if (JSON.stringify(growthChart.data.datasets[0].data) !== JSON.stringify(currentStage.data)) {
                growthChart.data.datasets[0].data = currentStage.data;
                growthChart.update();
            }

            let stepTitle = "";
            if(week < 11) stepTitle = "🌱 STEP 1: 기초 탐구";
            else if(week < 21) stepTitle = "🎵 STEP 2: 리듬 정복";
            else if(week < 31) stepTitle = "✨ STEP 3: 감정 표현";
            else stepTitle = "🏆 STEP 4: 조화와 완성";

            descBox.innerHTML = \`
                <h4 class="font-bold text-gray-900 mb-2">\${stepTitle} (\${week}주차)</h4>
                <p class="text-gray-600 text-sm">\${currentStage.desc}</p>
            \`;
        });

        function switchTab(stepId) {
            for(let i=1; i<=4; i++) {
                const btn = document.getElementById(\`tab-\${i}\`);
                if(i === stepId) {
                    btn.className = "step-active pb-4 px-4 text-sm md:text-base transition-colors";
                } else {
                    btn.className = "step-inactive pb-4 px-4 text-sm md:text-base transition-colors";
                }
            }

            const data = curriculumData[stepId];
            const contentDiv = document.getElementById('tab-content');
            
            let listHtml = data.items.map(item => \`
                <div class="flex items-start mb-6 last:mb-0">
                    <div class="flex-shrink-0 w-8 h-8 rounded-full bg-red-100 flex items-center justify-center text-red-500 font-bold mr-4 mt-1">
                        •
                    </div>
                    <div>
                        <h4 class="font-bold text-gray-800 text-lg mb-1">\${item.header}</h4>
                        <p class="text-gray-600 leading-relaxed">\${item.desc}</p>
                    </div>
                </div>
            \`).join('');

            contentDiv.innerHTML = \`
                <div class="animate-fade-in-up">
                    <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-8 pb-6 border-b border-gray-100">
                        <div>
                            <span class="text-sm font-bold text-red-500 tracking-wider uppercase mb-1 block">\${data.weeks}</span>
                            <h3 class="text-2xl md:text-3xl font-black text-gray-900">\${data.title}</h3>
                        </div>
                        <div class="mt-4 md:mt-0 italic text-gray-500 font-medium bg-gray-50 px-4 py-2 rounded-lg">
                            \${data.subtitle}
                        </div>
                    </div>
                    <div>
                        \${listHtml}
                    </div>
                </div>
            \`;
        }

        switchTab(1);

        const styleSheet = document.createElement("style");
        styleSheet.innerText = \`
            @keyframes fadeInUp {
                from { opacity: 0; transform: translateY(10px); }
                to { opacity: 1; transform: translateY(0); }
            }
            .animate-fade-in-up {
                animation: fadeInUp 0.4s ease-out forwards;
            }
        \`;
        document.head.appendChild(styleSheet);
    <\/script>
</body>
</html>`,
  "\uccad\uc18c\ub144\ud2b9\uc218\uccb4\uc721.html": `<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>2026 청소년 특수체육 - 활력 에너지</title>
    <script src="https://cdn.tailwindcss.com"><\/script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Urbanist:wght@700;900&family=Noto+Sans+KR:wght@300;400;700;900&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --vital-emerald: #10b981;
            --vital-navy: #0f172a;
            --vital-blue: #3b82f6;
            --slate-light: #f8fafc;
        }

        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: var(--slate-light);
            color: var(--vital-navy);
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
            /* 한국어 단어 단위 줄바꿈 유지 */
            word-break: keep-all; 
            overflow-x: hidden;
        }

        h1, h2, .font-display {
            font-family: 'Urbanist', 'Noto Sans KR', sans-serif;
            letter-spacing: -0.02em;
        }

        .keep-line {
            white-space: nowrap;
        }

        .section-title {
            position: relative;
            display: inline-block;
            margin-bottom: 1.5rem;
            word-break: keep-all;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 40px;
            height: 4px;
            background: linear-gradient(90deg, var(--vital-emerald), var(--vital-blue));
        }

        .nav-link {
            transition: all 0.3s ease;
        }

        .nav-link:hover {
            color: var(--vital-emerald);
        }

        .hover-lift {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .hover-lift:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px -10px rgba(16, 185, 129, 0.2);
        }

        .img-container {
            background-color: #1e293b;
            position: relative;
            overflow: hidden;
            border-radius: 2.5rem;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
            border: 4px solid white;
        }

        .img-content {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }

        .dynamic-h1 {
            font-size: clamp(2.5rem, 8vw, 5rem);
        }
        .dynamic-h2 {
            font-size: clamp(1.8rem, 5vw, 3rem);
        }

        .curriculum-card {
            background: white;
            padding: 2rem;
            border-radius: 2rem;
            border: 1px solid #f1f5f9;
            transition: all 0.3s ease;
            height: 100%;
        }

        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: var(--slate-light); }
        ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 10px; }
    </style>
</head>
<body class="antialiased text-left">

    <!-- Navigation Area -->
    <nav class="fixed top-0 w-full z-50 bg-white/90 backdrop-blur-md border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-4 h-20 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <div class="w-10 h-10 bg-emerald-500 rounded-lg flex items-center justify-center text-white text-xl shadow-lg font-bold text-sm">V</div>
                <span class="text-lg md:text-xl font-black text-slate-900 tracking-tight keep-line">청소년 특수체육 <span class="text-emerald-500">[활력 에너지]</span></span>
            </div>
            <div class="hidden lg:flex items-center gap-6 font-bold text-slate-600 text-sm">
                <a href="#about" class="nav-link">활동 소개</a>
                <a href="#curriculum" class="nav-link">40회기 로드맵</a>
                <a href="#details" class="nav-link">상세 정보</a>
                <a href="#apply" class="bg-emerald-500 text-white px-5 py-2 rounded-full hover:bg-emerald-600 transition shadow-md">상시모집</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative min-h-screen pt-20 flex items-center overflow-hidden bg-slate-950 px-4">
        <div class="absolute inset-0 opacity-40">
            
            <img src="https://images.unsplash.com/photo-1526676037777-05a232554f77?auto=format&fit=crop&q=80&w=1920" class="w-full h-full object-cover" alt="청소년 체육 배경">
        </div>
        <div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/60 to-transparent"></div>
        
        <div class="relative z-10 max-w-7xl mx-auto py-20 text-left">
            <div class="max-w-4xl text-left">
                <span class="inline-block px-4 py-1 rounded-full bg-emerald-500 text-white font-bold text-xs mb-6 uppercase tracking-widest shadow-lg keep-line">
                    Youth Special PE Program 2026
                </span>
                <h1 class="dynamic-h1 font-black text-white mb-8 leading-tight text-left">
                    잠재된 에너지를<br class="hidden md:block"> <span class="text-emerald-400 italic">스포츠</span>로 깨우다
                </h1>
                <p class="text-lg md:text-2xl text-slate-300 mb-12 leading-relaxed font-light text-left">
                    매주 화요일, 영등포장애인복지관 4층 대강당에서 펼쳐지는 활기찬 도전!<br>
                    다양한 종목을 배우며 자존감을 높이는 40주간의 여정입니다.
                </p>
                <div class="flex flex-wrap gap-5 text-left">
                    <a href="#curriculum" class="bg-emerald-500 text-white px-8 py-4 rounded-2xl text-lg font-black hover:bg-emerald-600 transition shadow-xl shadow-emerald-500/30 keep-line">
                        40회기 커리큘럼 확인
                    </a>
                    <div class="flex items-center gap-4 px-6 text-white border-l border-slate-700 text-left">
                        <span class="text-xl md:text-2xl font-bold font-display text-emerald-400 keep-line">곽미송</span>
                        <span class="text-slate-400 font-medium italic text-sm keep-line">지도강사</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Program Goal -->
    <section id="about" class="py-24 bg-white px-4">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center text-left">
                <div>
                    <h2 class="section-title dynamic-h2 font-bold text-slate-900 text-left">우리가 지향하는 변화</h2>
                    <p class="text-lg md:text-xl text-stone-600 mb-10 leading-relaxed font-light text-left">
                        체계적인 특수체육 커리큘럼을 통해 청소년들이 운동의 즐거움을 깨닫고 건강한 일상을 스스로 가꾸어나가도록 지원합니다.
                    </p>
                    <div class="space-y-6 text-left">
                        <div class="flex gap-4 items-center text-left">
                            <span class="w-8 h-8 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center font-bold flex-shrink-0 text-sm">✓</span>
                            <p class="text-stone-700 font-bold text-base md:text-lg">다양한 종목 경험을 통한 대근육 발달</p>
                        </div>
                        <div class="flex gap-4 items-center text-left">
                            <span class="w-8 h-8 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center font-bold flex-shrink-0 text-sm">✓</span>
                            <p class="text-stone-700 font-bold text-base md:text-lg">협동 경기를 통한 사회적 상호작용 강화</p>
                        </div>
                        <div class="flex gap-4 items-center text-left">
                            <span class="w-8 h-8 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center font-bold flex-shrink-0 text-sm">✓</span>
                            <p class="text-stone-700 font-bold text-base md:text-lg">성공 경험을 통한 자존감 및 인내심 고취</p>
                        </div>
                    </div>
                </div>
                
                <div class="flex justify-center lg:justify-end">
                    <div class="img-container w-full max-w-lg h-[350px] md:h-[450px] hover-lift transition duration-500">
                        <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b?auto=format&fit=crop&q=80&w=800" class="img-content" alt="체육 활동 사진">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 40-Week Curriculum Roadmap (DETAILED) -->
    <section id="curriculum" class="py-24 bg-stone-50 px-4 text-left">
        <div class="max-w-7xl mx-auto">
            <div class="mb-16 text-left">
                <h2 class="section-title dynamic-h2 font-bold text-slate-900 text-left">40주간의 성장 로드맵</h2>
                <p class="text-base md:text-lg text-slate-500 mt-4 font-light text-left">한 시즌을 관통하는 체계적인 체육 교육 프로세스입니다.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 text-left">
                <!-- Phase 1 -->
                <div class="curriculum-card border-t-4 border-emerald-500 hover-lift flex flex-col">
                    <span class="text-emerald-600 font-black text-xs uppercase tracking-widest block mb-4">Phase 01: 웜업</span>
                    <h3 class="text-xl font-bold text-slate-800 mb-6 tracking-tight text-left">신체 인식 및 측정</h3>
                    <ul class="space-y-4 text-slate-600 text-sm font-bold flex-grow text-left">
                        <li class="flex gap-2"><span>1~5회:</span> <span>안전 교육 및 초기 체력 측정</span></li>
                        <li class="flex gap-2"><span>•</span> <span>대근육 이완을 위한 스트레칭 습득</span></li>
                        <li class="flex gap-2"><span>•</span> <span>올바른 걷기와 달리기 자세 훈련</span></li>
                        <li class="flex gap-2"><span>•</span> <span>공간 인지 및 신체 협응 연습</span></li>
                    </ul>
                </div>

                <!-- Phase 2 -->
                <div class="curriculum-card border-t-4 border-blue-500 hover-lift flex flex-col">
                    <span class="text-blue-600 font-black text-xs uppercase tracking-widest block mb-4">Phase 02: 런닝</span>
                    <h3 class="text-xl font-bold text-slate-800 mb-6 tracking-tight text-left">구기 및 라켓 기초</h3>
                    <ul class="space-y-4 text-slate-600 text-sm font-bold flex-grow text-left">
                        <li class="flex gap-2"><span>6~17회:</span> <span>축구 및 농구 드리블/슈팅</span></li>
                        <li class="flex gap-2"><span>•</span> <span>눈과 손·발의 협응력 집중 강화</span></li>
                        <li class="flex gap-2"><span>•</span> <span>탁구, 배드민턴 라켓 컨트롤 실습</span></li>
                        <li class="flex gap-2"><span>•</span> <span>줄넘기를 활용한 순발력 증진</span></li>
                    </ul>
                </div>

                <!-- Phase 3 -->
                <div class="curriculum-card border-t-4 border-amber-500 hover-lift flex flex-col">
                    <span class="text-amber-500 font-black text-xs uppercase tracking-widest block mb-4 text-left">Phase 03: 부스트</span>
                    <h3 class="text-xl font-bold text-slate-800 mb-6 tracking-tight text-left">전략 스포츠 심화</h3>
                    <ul class="space-y-4 text-slate-600 text-sm font-bold flex-grow text-left">
                        <li class="flex gap-2"><span>18~31회:</span> <span>볼링, 보치아, 컬링 정밀 실습</span></li>
                        <li class="flex gap-2"><span>•</span> <span>힘의 강약 조절 및 방향성 훈련</span></li>
                        <li class="flex gap-2"><span>•</span> <span>팀별 전략 수립 및 규칙 이해</span></li>
                        <li class="flex gap-2"><span>•</span> <span>표적 경기를 통한 집중력 향상</span></li>
                    </ul>
                </div>

                <!-- Phase 4 -->
                <div class="curriculum-card bg-slate-900 text-white shadow-2xl hover-lift flex flex-col border-t-4 border-emerald-400 text-left">
                    <span class="text-emerald-400 font-black text-xs uppercase tracking-widest block mb-4">Phase 04: 피날레</span>
                    <h3 class="text-xl font-bold text-white mb-6 tracking-tight text-left">종합 체육 축제</h3>
                    <ul class="space-y-4 text-slate-300 text-sm font-bold flex-grow text-left">
                        <li class="flex gap-2"><span>32~40회:</span> <span>플로어볼 및 선호 종목 경기</span></li>
                        <li class="flex gap-2"><span>•</span> <span>팀 대항전을 통한 사회성 강화</span></li>
                        <li class="flex gap-2"><span>•</span> <span>종합 체육 대회를 통한 성취감</span></li>
                        <li class="flex gap-2"><span>•</span> <span>1년 성장 기록 공유 및 수료식</span></li>
                    </ul>
                </div>
            </div>
            <p class="mt-10 text-stone-400 text-xs italic font-medium text-left">* 상기 일정은 참여자 컨디션 및 복지관 상황에 따라 변경될 수 있습니다.</p>
        </div>
    </section>

    <!-- Details Section -->
    <section id="details" class="py-24 bg-white px-4 text-left">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="p-10 rounded-[3rem] bg-slate-950 text-white shadow-xl flex flex-col justify-between text-left">
                    <div>
                        <span class="text-emerald-400 text-xs font-black tracking-widest uppercase mb-4 block text-left">Schedule</span>
                        <h3 class="text-3xl font-bold mb-6 keep-line">진행 일정</h3>
                        <p class="text-lg text-slate-300 mb-2">2026년 2월 ~ 11월 (40회기)</p>
                        <p class="text-2xl font-bold text-emerald-400 keep-line font-display text-left">매주 화요일 16:30 ~ 17:30</p>
                    </div>
                </div>

                <div class="p-10 rounded-[3rem] bg-emerald-500 text-white shadow-xl flex flex-col justify-between transform md:-translate-y-4 text-left">
                    <div>
                        <span class="text-emerald-100 text-xs font-black tracking-widest uppercase mb-4 block text-white text-left">Location</span>
                        <h3 class="text-3xl font-bold mb-6 keep-line text-white">진행 장소</h3>
                        <p class="text-lg text-emerald-50 mb-2 text-white">영등포장애인복지관</p>
                        <p class="text-2xl font-bold text-white keep-line font-display text-white">4층 대강당</p>
                    </div>
                </div>

                <div class="p-10 rounded-[3rem] bg-stone-50 border border-stone-200 flex flex-col justify-between text-left">
                    <div>
                        <span class="text-blue-600 text-xs font-black tracking-widest uppercase mb-4 block">Target</span>
                        <h3 class="text-3xl font-bold mb-6 text-stone-800 keep-line">모집 안내</h3>
                        <div class="space-y-4 text-left">
                            <div class="flex justify-between border-b border-stone-200 pb-2">
                                <span class="text-stone-500 font-bold text-sm">대상</span>
                                <span class="text-base font-black text-stone-900 keep-line">발달장애 청소년</span>
                            </div>
                            <div class="flex justify-between border-b border-stone-200 pb-2">
                                <span class="text-stone-500 font-bold text-sm">정원</span>
                                <span class="text-base font-black text-emerald-600">6명</span>
                            </div>
                            <div class="pt-4 text-left">
                                <p class="text-[10px] font-black text-stone-400 mb-1 uppercase tracking-widest">Status</p>
                                <p class="text-xl font-black text-stone-800 keep-line">현재 상시모집 중</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Apply Section (Updated: '방문 접수') -->
    <section id="apply" class="py-24 bg-slate-950 text-white relative overflow-hidden text-center px-4">
        <div class="max-w-4xl mx-auto relative z-10 text-center">
            <h2 class="dynamic-h2 font-bold mb-10 leading-tight text-center">함께 땀 흘리며<br>더 큰 내일을 꿈꿔요!</h2>
            
            <div class="bg-white/5 backdrop-blur-2xl p-10 md:p-16 rounded-[4rem] border border-white/10 shadow-2xl text-center">
                <div class="mb-12 text-center text-center">
                    <p class="text-emerald-400 font-black text-sm mb-4 uppercase tracking-widest text-center">Contact Information</p>
                    <p class="text-xl md:text-2xl font-bold text-stone-300 mb-2 font-display">영등포장애인복지관 아동청소년팀</p>
                    <h3 class="text-3xl md:text-5xl font-black tracking-tighter text-white">070-5202-0540 ~ 0543</h3>
                    <p class="text-stone-400 mt-8 text-sm font-medium italic underline decoration-emerald-500 underline-offset-8 text-center">프로그램 등록 및 상담은 언제든 환영합니다.</p>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8 pt-10 border-t border-white/10 text-center">
                    <div class="flex flex-col items-center">
                        <div class="text-3xl mb-2 text-center">📞</div>
                        <p class="font-bold text-sm text-center">전화 상담</p>
                    </div>
                    <div class="flex flex-col items-center text-center">
                        <div class="text-3xl mb-2 text-center">🏢</div>
                        <!-- Updated to '방문 접수' -->
                        <p class="font-bold text-sm text-center">방문 접수</p>
                    </div>
                    <div class="flex flex-col items-center text-center">
                        <div class="text-3xl mb-2 font-bold text-center">💪</div>
                        <p class="font-black text-sm text-emerald-400 text-center">프로그램 등록</p>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Decoration -->
        <div class="absolute -top-40 -right-40 w-[500px] h-[500px] bg-emerald-900/20 rounded-full blur-[120px]"></div>
        <div class="absolute -bottom-40 -left-40 w-[500px] h-[500px] bg-blue-900/20 rounded-full blur-[120px]"></div>
    </section>

    <!-- Footer -->
    <footer class="bg-white py-12 border-t border-stone-200 text-center px-4">
        <div class="max-w-7xl mx-auto text-center">
            <div class="flex items-center justify-center gap-2 mb-4 text-center">
                <div class="w-8 h-8 bg-slate-900 rounded-lg flex items-center justify-center text-white text-[10px] font-black shadow-md text-center">V</div>
                <span class="text-lg font-black text-stone-800 tracking-tighter keep-line">영등포장애인복지관</span>
            </div>
            <p class="text-stone-400 font-bold mb-1 uppercase tracking-widest text-[10px] text-center">Child & Youth Special PE: Vital Energy 2026</p>
            <p class="text-stone-300 text-[10px] italic text-center text-center">© 2026 Yeongdeungpo Welfare Center for the Disabled. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>`,
  "\ub514\uc9c0\ud138\uc2a4\ud3ec\uce20\uc628.html": `<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2026 청소년 특수체육 - 디지털스포츠 온</title>
    <script src="https://cdn.tailwindcss.com"><\/script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"><\/script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Urbanist:wght@700;900&family=Noto+Sans+KR:wght@300;400;700;900&display=swap" rel="stylesheet">
    
    <!-- Chosen Palette: Neon Digital Blue & Cyber Fuchsia -->
    <style>
        :root {
            --digital-blue: #00d2ff;
            --cyber-pink: #ff007a;
            --tech-navy: #0a0e17;
            --slate-light: #f8fafc;
        }

        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: var(--slate-light);
            color: var(--tech-navy);
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
        }

        h1, h2, .font-display {
            font-family: 'Urbanist', 'Noto Sans KR', sans-serif;
            letter-spacing: -0.02em;
        }

        .section-title {
            position: relative;
            display: inline-block;
            margin-bottom: 1.5rem;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -8px;
            left: 0;
            width: 40px;
            height: 4px;
            background: linear-gradient(90deg, var(--digital-blue), var(--cyber-pink));
        }

        .nav-link {
            transition: all 0.3s ease;
            position: relative;
        }

        .nav-link:hover {
            color: var(--digital-blue);
        }

        .hover-lift {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .hover-lift:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px -10px rgba(0, 210, 255, 0.2);
        }

        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: var(--slate-light); }
        ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 10px; }

        .glow-text {
            text-shadow: 0 0 10px rgba(0, 210, 255, 0.5);
        }
        
        .img-container {
            background-color: #1a202c;
            position: relative;
            overflow: hidden;
            border-radius: 2.5rem;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
            border: 4px solid white;
        }

        .img-content {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }
    </style>
</head>
<body class="antialiased text-left">

    <!-- Navigation Area -->
    <nav class="fixed top-0 w-full z-50 bg-white/95 backdrop-blur-md border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-slate-900 rounded-lg flex items-center justify-center text-white text-xl shadow-lg border border-cyan-500 font-bold text-sm">
                    ON
                </div>
                <span class="text-xl font-black text-slate-900 tracking-tight">디지털스포츠 <span class="text-cyan-500">온(ON)</span></span>
            </div>
            <div class="hidden md:flex items-center gap-8 font-bold text-slate-600">
                <a href="#about" class="nav-link">프로그램 안내</a>
                <a href="#tech" class="nav-link">스마트 기술</a>
                <a href="#curriculum" class="nav-link">로드맵</a>
                <a href="#details" class="nav-link">상세일정</a>
                <a href="#apply" class="bg-slate-900 text-white px-6 py-2 rounded-full hover:bg-cyan-600 transition shadow-md">상시모집</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative min-h-screen pt-20 flex items-center overflow-hidden bg-slate-950">
        <div class="absolute inset-0 opacity-40">
            <img src="https://images.unsplash.com/photo-1550745165-9bc0b252726f?auto=format&fit=crop&q=80&w=1920" 
                 class="w-full h-full object-cover" alt="디지털 스포츠 배경">
        </div>
        <div class="absolute inset-0 bg-gradient-to-t from-slate-950 via-slate-950/60 to-transparent"></div>
        
        <div class="relative z-10 max-w-7xl mx-auto px-6 py-20">
            <div class="max-w-4xl">
                <span class="inline-block px-4 py-1 rounded-full bg-cyan-500 text-white font-bold text-sm mb-6 shadow-lg shadow-cyan-500/30 uppercase tracking-widest">
                    Digital Youth Special PE
                </span>
                <h1 class="text-6xl md:text-8xl font-black text-white mb-8 leading-tight glow-text">
                    움직임에 <span class="text-cyan-400 italic">기술</span>을<br>더하다
                </h1>
                <p class="text-xl md:text-2xl text-slate-300 mb-12 leading-relaxed font-light">
                    매주 월요일, 영등포장애인복지관 1층 스마트발달트레이닝실에서 펼쳐지는 미래형 특수체육!<br>
                    IT 기술과 스포츠의 만남으로 청소년들에게 새로운 즐거움을 선사합니다.
                </p>
                <div class="flex flex-wrap gap-5">
                    <a href="#curriculum" class="bg-cyan-500 text-white px-10 py-5 rounded-2xl text-xl font-black hover:bg-cyan-600 transition shadow-xl shadow-cyan-500/30">
                        활동 로드맵 확인하기
                    </a>
                    <div class="flex items-center gap-4 px-6 text-white border-l border-slate-700 text-left">
                        <span class="text-2xl font-bold text-pink-500 font-display">허지아</span>
                        <span class="text-slate-400 font-medium italic">지도강사</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Program Highlights (Smart Focus) -->
    <section id="tech" class="py-24 bg-white text-center">
        <div class="max-w-7xl mx-auto px-6">
            <div class="mb-20">
                <h2 class="section-title text-4xl font-black text-slate-900">왜 디지털스포츠인가요?</h2>
                <p class="text-xl text-slate-500 mt-4">최첨단 IT 인프라를 통해 운동의 문턱을 낮추고 성취감을 극대화합니다.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
                <div class="p-10 rounded-[2.5rem] bg-slate-50 border border-slate-100 hover-lift">
                    <div class="text-5xl mb-6">🎮</div>
                    <h3 class="text-2xl font-bold mb-4 text-cyan-600">스마트 플레이</h3>
                    <p class="text-slate-600 leading-relaxed">닌텐도 스위치 등 최신 콘솔을 활용해 가상 세계에서 스포츠를 경험하며 신체 조절 능력을 키웁니다.</p>
                </div>
                <div class="p-10 rounded-[2.5rem] bg-slate-900 text-white hover-lift shadow-2xl shadow-cyan-500/10">
                    <div class="text-5xl mb-6">🧱</div>
                    <h3 class="text-2xl font-bold mb-4 text-cyan-400">벽면형 인터랙티브 게임</h3>
                    <p class="text-slate-300 leading-relaxed">벽면 스크린을 활용한 실감형 운동 콘텐츠를 통해 순발력과 민첩성을 즐겁게 향상시킵니다.</p>
                </div>
                <div class="p-10 rounded-[2.5rem] bg-slate-50 border border-slate-100 hover-lift">
                    <div class="text-5xl mb-6">📊</div>
                    <h3 class="text-2xl font-bold mb-4 text-pink-600">데이터 기반 관리</h3>
                    <p class="text-slate-600 leading-relaxed">체력 평가지와 디지털 기록을 통해 청소년 개개인의 신체 발달 과정을 체계적으로 모니터링합니다.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Program Goals -->
    <section id="about" class="py-24 bg-slate-50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
                <div>
                    <h2 class="section-title text-4xl font-black text-slate-900 text-left">교육 목표</h2>
                    <p class="text-xl text-slate-600 mb-10 leading-relaxed font-light text-left">
                        디지털 기술을 활용한 맞춤형 운동 환경을 제공하여, 청소년들이 특수체육 활동에 즐겁게 참여하고 신체 기능을 자연스럽게 발달시키도록 돕습니다.
                    </p>
                    <div class="space-y-6">
                        <div class="flex gap-4 items-center text-left">
                            <span class="w-8 h-8 rounded-full bg-cyan-100 text-cyan-600 flex items-center justify-center font-bold flex-shrink-0">✓</span>
                            <p class="text-slate-700 font-bold text-lg">스포츠 활동을 통한 신체기능 발달 도모</p>
                        </div>
                        <div class="flex gap-4 items-center text-left">
                            <span class="w-8 h-8 rounded-full bg-cyan-100 text-cyan-600 flex items-center justify-center font-bold flex-shrink-0">✓</span>
                            <p class="text-slate-700 font-bold text-lg">성공적인 운동 경험을 통한 자신감 향상</p>
                        </div>
                        <div class="flex gap-4 items-center text-left">
                            <span class="w-8 h-8 rounded-full bg-cyan-100 text-cyan-600 flex items-center justify-center font-bold flex-shrink-0">✓</span>
                            <p class="text-slate-700 font-bold text-lg">디지털 기기 활용 능력 및 규칙 준수 학습</p>
                        </div>
                    </div>
                </div>
                
                <div class="flex justify-center lg:justify-end">
                    <div class="img-container w-full max-w-lg h-[400px] hover-lift transform transition duration-500">
                        <img src="https://images.unsplash.com/photo-1593508512255-86ab42a8e620?auto=format&fit=crop&q=80&w=800" 
                             class="img-content" alt="닌텐도 스위치 스포츠 장비">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Curriculum Roadmap (FONT SIZE REDUCED) -->
    <section id="curriculum" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex flex-col lg:flex-row gap-20 items-center">
                <div class="lg:w-1/3 text-left">
                    <h2 class="section-title text-3xl font-black mb-8 text-slate-900">40주간의<br>성장 시나리오</h2>
                    <p class="text-lg text-slate-500 mb-10 leading-relaxed">
                        기초 체력 측정부터 다양한 종목의 융합까지, 단계별로 구성된 스마트 특수체육 커리큘럼입니다.
                    </p>
                    <div class="space-y-4 font-bold">
                        <div class="flex items-center gap-4 p-4 bg-slate-50 rounded-2xl border border-slate-100 hover:bg-cyan-50 transition">
                            <span class="w-10 h-10 rounded-xl bg-cyan-500 text-white flex items-center justify-center">1</span>
                            <span class="text-sm">기초 체력 & 농구 기본기</span>
                        </div>
                        <div class="flex items-center gap-4 p-4 bg-slate-50 rounded-2xl border border-slate-100 hover:bg-cyan-50 transition">
                            <span class="w-10 h-10 rounded-xl bg-cyan-500 text-white flex items-center justify-center">2</span>
                            <span class="text-sm">순발력 & 축구 기본기</span>
                        </div>
                        <div class="flex items-center gap-4 p-4 bg-slate-50 rounded-2xl border border-slate-100 hover:bg-cyan-50 transition">
                            <span class="w-10 h-10 rounded-xl bg-cyan-500 text-white flex items-center justify-center">3</span>
                            <span class="text-sm">피구 & 라켓 종목 습득</span>
                        </div>
                        <div class="flex items-center gap-4 p-4 bg-slate-900 text-white rounded-2xl shadow-lg shadow-cyan-500/30">
                            <span class="w-10 h-10 rounded-xl bg-cyan-500 text-white flex items-center justify-center">4</span>
                            <span class="italic font-bold text-sm">플로어볼 & 스마트 페스티벌</span>
                        </div>
                    </div>
                </div>

                <div class="lg:w-2/3 grid grid-cols-1 md:grid-cols-2 gap-8 text-left">
                    <div class="p-8 bg-slate-50 rounded-3xl border border-slate-100 hover-lift">
                        <h3 class="text-xl font-black text-cyan-600 mb-4 tracking-tight">Phase 1: 웜업 (1~10회)</h3>
                        <p class="text-slate-500 text-sm leading-relaxed mb-4 font-medium">체력 평가지를 통한 신체 밸런스 확인 및 농구 기본기를 통한 기초 협응력을 훈련합니다.</p>
                        <div class="text-xs font-bold text-slate-400">#체력평가 #농구드리블 #순환운동</div>
                    </div>
                    <div class="p-8 bg-slate-50 rounded-3xl border border-slate-100 hover-lift">
                        <h3 class="text-xl font-black text-blue-600 mb-4 tracking-tight">Phase 2: 런닝 (11~20회)</h3>
                        <p class="text-slate-500 text-sm leading-relaxed mb-4 font-medium">축구 기본기와 줄넘기를 통해 심폐지구력을 기르고 정기적인 스마트 플레이를 통해 동기를 부여합니다.</p>
                        <div class="text-xs font-bold text-slate-400">#축구패스 #줄넘기 #닌텐도경험</div>
                    </div>
                    <div class="p-8 bg-slate-50 rounded-3xl border border-slate-100 hover-lift">
                        <h3 class="text-xl font-black text-purple-600 mb-4 tracking-tight">Phase 3: 부스트 (21~30회)</h3>
                        <p class="text-slate-500 text-sm leading-relaxed mb-4 font-medium">배드민턴과 피구 등 응용 스포츠를 통해 집중력을 높이고 정교한 신체 조절을 마스터합니다.</p>
                        <div class="text-xs font-bold text-slate-400">#배드민턴 #응용피구 #집중력강화</div>
                    </div>
                    <div class="p-8 bg-slate-900 rounded-3xl text-white shadow-2xl hover-lift">
                        <h3 class="text-xl font-black text-cyan-400 mb-4 tracking-tight">Phase 4: 피날레 (31~40회)</h3>
                        <p class="text-slate-300 text-sm leading-relaxed mb-4 font-medium">플로어볼 팀 게임과 벽면형 게임 축제를 통해 실력을 발휘하고 최종 성취감을 맛봅니다.</p>
                        <div class="text-xs font-bold text-slate-500 uppercase tracking-wider">Showtime & Festival</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Logistics Dashboard -->
    <section id="details" class="py-24 bg-slate-50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                <div class="p-12 rounded-[3.5rem] bg-slate-950 text-white shadow-2xl flex flex-col justify-between">
                    <div>
                        <span class="text-cyan-400 text-sm font-black tracking-widest uppercase mb-6 block">Schedule</span>
                        <h3 class="text-4xl font-black mb-8 text-left">진행 일정</h3>
                        <div class="space-y-4 text-left">
                            <p class="text-xl font-bold text-slate-300">2026년 2월 ~ 11월</p>
                            <div class="p-4 bg-white/5 rounded-2xl border border-white/10">
                                <p class="text-2xl font-black text-cyan-500">매주 월요일</p>
                                <p class="text-3xl font-black">16:00 ~ 17:00</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="p-12 rounded-[3.5rem] bg-cyan-500 text-white shadow-2xl flex flex-col justify-between transform -translate-y-4 md:translate-y-0">
                    <div>
                        <span class="text-cyan-100 text-sm font-black tracking-widest uppercase mb-6 block">Location</span>
                        <h3 class="text-4xl font-black mb-8 text-left">어디서 하나요?</h3>
                        <div class="space-y-4 text-left">
                            <p class="text-xl font-bold">영등포장애인복지관</p>
                            <div class="p-4 bg-black/10 rounded-2xl border border-black/5">
                                <p class="text-3xl font-black tracking-tighter">1층 스마트발달<br>트레이닝실</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="p-12 rounded-[3.5rem] bg-white border border-slate-200 shadow-2xl flex flex-col justify-between">
                    <div>
                        <span class="text-pink-500 text-sm font-black tracking-widest uppercase mb-6 block">Target</span>
                        <h3 class="text-4xl font-black mb-8 text-slate-900 text-left">누가 하나요?</h3>
                        <div class="space-y-6">
                            <div class="flex justify-between items-center text-left">
                                <span class="text-slate-500 font-bold">모집 대상</span>
                                <span class="text-lg font-black">발달장애 청소년</span>
                            </div>
                            <div class="flex justify-between items-center text-left">
                                <span class="text-slate-500 font-bold">정원</span>
                                <span class="text-lg font-black text-pink-600">6명</span>
                            </div>
                            <div class="pt-6 border-t border-slate-100 text-left">
                                <p class="text-xs font-black text-pink-500 mb-2 uppercase tracking-widest">Status</p>
                                <p class="text-2xl font-black text-slate-900">현재 상시모집 중</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Registration / Contact (RENAMED TO '프로그램 등록') -->
    <section id="apply" class="py-24 bg-slate-950 text-white relative overflow-hidden">
        <div class="max-w-4xl mx-auto px-6 text-center relative z-10">
            <h2 class="text-5xl md:text-7xl font-black mb-12 leading-tight glow-text">당신의 활력을<br>기술로 ON 하세요!</h2>
            
            <div class="bg-white/5 backdrop-blur-2xl p-12 md:p-20 rounded-[4rem] border border-white/10 shadow-2xl">
                <div class="mb-14">
                    <p class="text-cyan-400 font-black text-lg mb-4 uppercase tracking-widest">Contact Team</p>
                    <p class="text-2xl font-bold text-slate-300 mb-2">영등포장애인복지관 아동청소년팀</p>
                    <h3 class="text-4xl md:text-6xl font-black tracking-tighter text-white">070-5202-0540 ~ 0543</h3>
                    <p class="text-slate-400 mt-8 text-lg font-medium italic">프로그램에 대한 궁금증은 언제든 전화주세요!</p>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-10 pt-14 border-t border-white/10">
                    <div class="hover:text-cyan-400 transition cursor-default text-center">
                        <div class="text-4xl mb-3 text-center">📞</div>
                        <p class="font-black text-lg text-center">전화 상담</p>
                    </div>
                    <div class="hover:text-cyan-400 transition cursor-default text-center">
                        <div class="text-4xl mb-3 text-center">🏢</div>
                        <p class="font-black text-lg text-center">기관 방문</p>
                    </div>
                    <div class="hover:text-cyan-400 transition cursor-default text-center">
                        <div class="text-4xl mb-3 text-center">🖊️</div>
                        <!-- Updated text from '특수체육 등록' to '프로그램 등록' -->
                        <p class="font-black text-lg text-center">프로그램 등록</p>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Animated Background Lights -->
        <div class="absolute -top-40 -right-40 w-[500px] h-[500px] bg-cyan-600/20 rounded-full blur-[120px] animate-pulse"></div>
        <div class="absolute -bottom-40 -left-40 w-[500px] h-[500px] bg-pink-600/20 rounded-full blur-[120px] animate-pulse" style="animation-delay: 1s;"></div>
    </section>

    <!-- Footer -->
    <footer class="bg-white py-14 border-t border-slate-100 text-center">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <div class="flex items-center justify-center gap-3 mb-6">
                <div class="w-8 h-8 bg-slate-900 rounded-lg flex items-center justify-center text-white text-xs font-black shadow-lg">ON</div>
                <span class="text-xl font-black text-slate-900">영등포장애인복지관</span>
            </div>
            <p class="text-slate-400 font-bold mb-2 uppercase tracking-widest text-sm text-center">Child & Youth Team Special PE</p>
            <p class="text-slate-300 text-xs text-center">© 2026 영등포장애인복지관. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>`
};

    const overlay = document.getElementById('viewer-overlay');
    const portal = document.getElementById('portal-root');
    const frame = document.getElementById('detail-iframe');
    const loading = document.getElementById('viewer-loading');
    const titleEl = document.getElementById('viewer-title');

    let currentBlobUrl = null;

    function openDetail(filename, title) {
      const html = DETAIL_PAGES[filename];
      if (!html) {
        alert('상세페이지 데이터가 없습니다: ' + filename);
        return;
      }

      titleEl.textContent = title;
      portal.style.display = 'none';
      overlay.style.display = 'flex';
      loading.style.display = 'flex';

      if (currentBlobUrl) {
        try { URL.revokeObjectURL(currentBlobUrl); } catch(e) {}
        currentBlobUrl = null;
      }

      const blob = new Blob([html], { type: 'text/html; charset=utf-8' });
      currentBlobUrl = URL.createObjectURL(blob);

      frame.onload = () => { loading.style.display = 'none'; };
      frame.src = currentBlobUrl;

      window.scrollTo(0, 0);
    }

    function closeDetail() {
      if (currentBlobUrl) {
        try { URL.revokeObjectURL(currentBlobUrl); } catch(e) {}
        currentBlobUrl = null;
      }
      frame.src = 'about:blank';
      overlay.style.display = 'none';
      portal.style.display = 'block';
      loading.style.display = 'none';
      window.scrollTo(0, 0);
    }
  </script>
</body>
</html>
