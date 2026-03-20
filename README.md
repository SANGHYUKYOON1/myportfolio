# myportfolio
나의 포트폴리오 페이지


## 과연 수정이 될까요?

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yoon Sang-hyuk | Data & Art Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Pretendard:wght@100;300;400;700;900&display=swap');
        body { font-family: 'Pretendard', sans-serif; background-color: #000; color: #fff; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .text-gradient { background: linear-gradient(135deg, #fff 0%, #3b82f6 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .scroll-hide::-webkit-scrollbar { display: none; }
    </style>
</head>
<body class="overflow-x-hidden selection:bg-blue-500/30">

    <!-- Nav -->
    <nav class="fixed top-0 w-full z-50 border-b border-white/5 bg-black/50 backdrop-blur-xl">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <span class="text-xl font-black italic tracking-tighter">SANGHYUK.Y</span>
            <div class="hidden md:flex gap-8 text-xs font-bold uppercase tracking-widest text-zinc-400">
                <a href="#about" class="hover:text-white transition">About</a>
                <a href="#work" class="hover:text-white transition">Exhibition</a>
                <a href="#ai" class="hover:text-white transition">AI Journey</a>
            </div>
            <a href="https://search.naver.com/search.naver?query=%EC%9C%A4%EC%83%81%ED%98%81" target="_blank" class="bg-blue-600 px-5 py-2 rounded-full text-[10px] font-black uppercase flex items-center gap-2">
                <i data-lucide="external-link" class="w-3 h-3"></i> Naver Official
            </a>
        </div>
    </nav>

    <!-- Hero -->
    <section class="min-h-screen flex items-center justify-center px-6 relative">
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_50%_50%,rgba(59,130,246,0.15),transparent_70%)]"></div>
        <div class="text-center z-10" data-aos="fade-up">
            <div class="mb-6 inline-flex items-center gap-2 px-3 py-1 rounded-full border border-blue-500/30 bg-blue-500/10">
                <span class="w-2 h-2 bg-blue-500 rounded-full animate-pulse"></span>
                <span class="text-[10px] font-bold text-blue-400 uppercase tracking-widest">Microsoft AI Candidate</span>
            </div>
            <h1 class="text-6xl md:text-[8rem] font-black leading-[0.9] tracking-tighter mb-8">
                DATA & <br><span class="text-gradient italic">ARTISTRY</span>
            </h1>
            <p class="text-zinc-500 text-lg md:text-xl max-w-2xl mx-auto leading-relaxed font-light">
                데이터정보학의 논리와 사진작가의 감수성을 결합하여,<br>인공지능 시대를 기록하고 분석하는 융합형 인재 윤상혁입니다.
            </p>
        </div>
    </section>

    <!-- About -->
    <section id="about" class="py-32 px-6">
        <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-20 items-center">
            <div data-aos="fade-right">
                <h2 class="text-blue-500 font-black text-[10px] uppercase tracking-[0.4em] mb-4 underline decoration-2 underline-offset-8 italic">Background</h2>
                <h3 class="text-4xl md:text-5xl font-bold mb-8 leading-tight italic">지성과 감성의 교차점.</h3>
                <p class="text-zinc-400 text-lg leading-relaxed mb-10 font-light">
                    데이터의 흐름을 읽는 <strong>데이터정보학</strong>을 전공했습니다. 동시에 <strong>네이버 인물정보</strong>에 등재된 프로페셔널 사진작가로서 찰나의 순간을 영원으로 기록합니다.
                </p>
                <div class="grid grid-cols-2 gap-4">
                    <div class="glass p-6 rounded-3xl">
                        <i data-lucide="database" class="text-blue-500 mb-4"></i>
                        <h4 class="font-bold text-sm mb-1">Data Science</h4>
                        <p class="text-[10px] text-zinc-500">데이터정보학 전공</p>
                    </div>
                    <div class="glass p-6 rounded-3xl">
                        <i data-lucide="camera" class="text-purple-500 mb-4"></i>
                        <h4 class="font-bold text-sm mb-1">Photography</h4>
                        <p class="text-[10px] text-zinc-500">네이버 인물정보 등재</p>
                    </div>
                </div>
            </div>
            <div class="relative" data-aos="zoom-in">
                <div class="aspect-[4/5] bg-zinc-900 rounded-[3rem] flex items-center justify-center border border-white/5 group">
                    <i data-lucide="aperture" class="w-24 h-24 text-zinc-800 group-hover:text-blue-600 transition-all duration-700"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- Works -->
    <section id="work" class="py-32 px-6 bg-zinc-950/50">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl md:text-6xl font-black italic mb-20 uppercase tracking-tighter">Exhibitions</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="glass p-10 rounded-[3rem] group" data-aos="fade-up">
                    <span class="text-blue-500 text-[10px] font-black uppercase tracking-widest mb-4 block italic">Solo / Group</span>
                    <h4 class="text-3xl font-bold mb-4">빈칸 : 봄의 움직임</h4>
                    <p class="text-zinc-500 text-sm leading-relaxed mb-8">생명의 역동성을 뷰파인더 너머로 포착한 기록입니다.</p>
                    <div class="h-40 bg-zinc-900 rounded-2xl flex items-center justify-center italic text-zinc-800 font-black">SPRING MOVEMENT</div>
                </div>
                <div class="glass p-10 rounded-[3rem] group" data-aos="fade-up" data-aos-delay="200">
                    <span class="text-purple-500 text-[10px] font-black uppercase tracking-widest mb-4 block italic">Owl Gallery Exhibition</span>
                    <h4 class="text-3xl font-bold mb-4">시선의 여정</h4>
                    <p class="text-zinc-500 text-sm leading-relaxed mb-8">일상의 낯선 시선을 탐구한 아울갤러리 전시작입니다.</p>
                    <div class="h-40 bg-zinc-900 rounded-2xl flex items-center justify-center italic text-zinc-800 font-black">JOURNEY OF VISION</div>
                </div>
            </div>
        </div>
    </section>

    <!-- AI Journey -->
    <section id="ai" class="py-40 px-6 relative overflow-hidden">
        <div class="absolute inset-0 bg-blue-600/5"></div>
        <div class="max-w-4xl mx-auto text-center z-10 relative" data-aos="zoom-in">
            <div class="mb-12 inline-block p-8 bg-white rounded-3xl shadow-2xl">
                <svg width="40" height="40" viewBox="0 0 23 23"><path d="M0 0H11V11H0V0Z" fill="#F25022"/><path d="M12 0H23V11H12V0Z" fill="#7FBA00"/><path d="M0 12H11V23H0V12Z" fill="#00A4EF"/><path d="M12 12H23V23H12V12Z" fill="#FFB900"/></svg>
            </div>
            <h2 class="text-4xl md:text-6xl font-black italic mb-8 tracking-tighter">Microsoft AI Journey</h2>
            <p class="text-zinc-400 text-lg md:text-xl leading-relaxed mb-12 font-light italic">
                현재 <strong>Microsoft AI 교육 과정</strong>을 통해 차세대 엔지니어로 성장하고 있습니다. 데이터 분석 역량과 예술적 감수성을 AI 기술에 결합하여 미래의 시각 경험을 혁신합니다.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <span class="px-6 py-2 glass rounded-full text-[10px] font-black uppercase tracking-widest text-blue-400">Generative AI</span>
                <span class="px-6 py-2 glass rounded-full text-[10px] font-black uppercase tracking-widest text-blue-400">Computer Vision</span>
                <span class="px-6 py-2 glass rounded-full text-[10px] font-black uppercase tracking-widest text-blue-400">Data Intelligence</span>
            </div>
        </div>
    </section>

    <footer class="py-20 px-6 border-t border-white/5">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-10">
            <span class="text-2xl font-black italic">SANGHYUK.Y</span>
            <div class="flex gap-8 text-[10px] font-bold uppercase tracking-widest text-zinc-500">
                <a href="#" class="hover:text-white transition">Instagram</a>
                <a href="https://search.naver.com/search.naver?query=%EC%9C%A4%EC%83%81%ED%98%81" target="_blank" class="hover:text-white transition italic underline underline-offset-4">Naver Profile</a>
                <a href="mailto:contact@example.com" class="hover:text-white transition">Email</a>
            </div>
        </div>
    </footer>

    <script>
        lucide.createIcons();
        AOS.init({ duration: 1000, once: true });
    </script>
</body>
</html>
