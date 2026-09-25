<!doctype html><html><head><meta charset=utf8><meta name=viewport content="width=device-width,initial-scale=1"><style>:root{color-scheme:light}body{margin:0;padding:0;font:14px -apple-system,BlinkMacSystemFont,sans-serif;background:#faf9f5;color:#141413}img{max-width:100%}[hidden]:not([hidden=until-found i]){display:none!important}</style></head><body>
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>포항그린방역 | 포항 소독·방역 전문기업</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
<style>
  :root{
    --navy:#0D1420;
    --blue:#2F6FEB;
    --blue-dark:#1E4FB8;
    --red:#E5423F;
    --teal:#0FA88A;
    --ink:#1B2430;
    --ink-soft:#5B6672;
    --line:#E6E9ED;
    --bg:#F7F8F9;
    --gray-band:#F1F2F4;
    --font:'Noto Sans KR','Apple SD Gothic Neo','Malgun Gothic',sans-serif;
  }
  *{box-sizing:border-box;margin:0;padding:0;}
  html{scroll-behavior:smooth;}
  body{font-family:var(--font);color:var(--ink);background:#fff;line-height:1.65;-webkit-font-smoothing:antialiased;}
  a{color:inherit;text-decoration:none;}
  button{font-family:inherit;cursor:pointer;}
  img,svg{display:block;max-width:100%;}
  .wrap{max-width:1180px;margin:0 auto;padding:0 28px;}

  #sampleNotice{background:#F2A93B;color:#3A2A05;font-size:12.5px;font-weight:700;text-align:center;padding:8px 34px;position:relative;}
  #sampleNotice button{position:absolute;right:10px;top:50%;transform:translateY(-50%);background:none;border:none;font-size:16px;color:#3A2A05;padding:4px;}

  /* ---------- 헤더 ---------- */
  header{position:sticky;top:0;z-index:200;background:rgba(9,14,22,0.55);backdrop-filter:blur(6px);}
  header .wrap{display:flex;align-items:center;justify-content:space-between;height:68px;}
  .logo{font-size:20px;font-weight:800;color:#fff;letter-spacing:-0.01em;}
  .logo b{color:var(--blue);}
  nav.mainnav{display:flex;gap:30px;}
  nav.mainnav > .navitem{position:relative;}
  nav.mainnav a.top{color:rgba(255,255,255,0.88);font-size:14.5px;font-weight:600;padding:8px 2px;display:inline-block;}
  nav.mainnav a.top:hover, nav.mainnav a.top.active{color:#fff;}
  .dropdown{
    position:absolute;top:38px;left:50%;transform:translateX(-50%);
    background:#fff;border-radius:8px;box-shadow:0 10px 30px rgba(0,0,0,0.18);
    padding:8px 0;min-width:120px;display:none;
  }
  .navitem:hover .dropdown{display:block;}
  .dropdown a{display:block;padding:9px 18px;font-size:13.5px;color:var(--ink-soft);white-space:nowrap;}
  .dropdown a:hover{color:var(--blue);background:var(--bg);}
  .hdr-cta{
    display:flex;align-items:center;gap:8px;background:var(--blue);color:#fff;
    font-size:13.5px;font-weight:700;padding:10px 18px;border-radius:100px;
  }
  .navtoggle{display:none;background:none;border:none;color:#fff;font-size:22px;}
  @media(max-width:900px){ nav.mainnav{display:none;} .navtoggle{display:block;} }

  /* ---------- 히어로 공통 ---------- */
  .hero{position:relative;overflow:hidden;display:flex;align-items:center;color:#fff;}
  .hero::after{content:"";position:absolute;inset:0;background:rgba(8,12,18,0.5);}
  .hero-slide{position:absolute;inset:0;opacity:0;transition:opacity 1s ease;background-size:cover;background-position:center;}
  .hero-slide.active{opacity:1;}
  .hero .wrap{position:relative;z-index:2;width:100%;}

  /* 홈 히어로 */
  #heroHome{height:560px;}
  .hero-callout{
    max-width:420px;background:#fff;color:var(--ink);border-radius:6px;
    padding:26px 26px 22px;box-shadow:0 20px 50px rgba(0,0,0,0.25);
  }
  .hero-callout .hc-line{font-size:14px;color:var(--ink-soft);margin-bottom:2px;}
  .hero-callout .hc-line b{color:var(--blue);font-weight:800;}
  .hc-brand{display:flex;align-items:center;gap:0;margin:12px 0 16px;font-weight:900;font-size:22px;letter-spacing:-0.01em;}
  .hc-brand .b1{background:var(--navy);color:#fff;padding:6px 10px;border-radius:5px 0 0 5px;}
  .hc-brand .b2{background:var(--blue);color:#fff;padding:6px 12px;border-radius:0 5px 5px 0;}
  .hc-tags{display:flex;flex-direction:column;gap:6px;margin-bottom:12px;}
  .hc-tag{display:inline-block;background:var(--blue);color:#fff;font-size:12.5px;font-weight:700;padding:6px 10px;border-radius:4px;width:fit-content;}
  .hc-list{display:flex;gap:14px;flex-wrap:wrap;margin-bottom:14px;}
  .hc-list span{font-size:13px;font-weight:700;color:var(--ink);display:flex;align-items:center;gap:4px;}
  .hc-list span::before{content:"▶";color:var(--blue);font-size:10px;}
  .hc-note{color:var(--red);font-weight:800;font-size:13px;margin-bottom:4px;}
  .hc-phone{font-size:26px;font-weight:900;color:var(--navy);letter-spacing:-0.02em;}

  .hero-arrows{position:absolute;left:24px;top:50%;transform:translateY(-50%);z-index:3;display:flex;gap:10px;}
  .hero-arrow{width:38px;height:38px;border-radius:50%;border:1px solid rgba(255,255,255,0.5);display:flex;align-items:center;justify-content:center;color:#fff;background:rgba(255,255,255,0.08);font-size:15px;}
  .hero-dots{position:absolute;left:50%;bottom:26px;transform:translateX(-50%);display:flex;gap:8px;z-index:3;}
  .hero-dot{width:8px;height:8px;border-radius:50%;background:rgba(255,255,255,0.45);}
  .hero-dot.active{background:#fff;}
  .scrolldown{position:absolute;right:40px;bottom:26px;z-index:3;font-size:11px;color:rgba(255,255,255,0.75);text-align:center;letter-spacing:0.08em;}
  .scrolldown .line{width:1px;height:26px;background:rgba(255,255,255,0.5);margin:0 auto 6px;}

  /* 서브페이지 히어로 */
  .hero-sub{height:230px;justify-content:center;text-align:center;}
  .hero-sub h1{font-size:30px;font-weight:800;margin-bottom:16px;}
  .hero-phone-pill{display:inline-flex;align-items:center;gap:8px;background:rgba(20,24,30,0.55);border:1px solid rgba(255,255,255,0.25);padding:11px 22px;border-radius:100px;font-size:15px;font-weight:700;}

  /* ---------- 서브탭 / 브레드크럼 ---------- */
  .subtab-row{border-bottom:1px solid var(--line);}
  .subtab-row .wrap{display:flex;gap:36px;}
  .subtab{padding:16px 2px;font-size:14.5px;font-weight:700;color:var(--ink-soft);border-bottom:2px solid transparent;}
  .subtab.active{color:var(--blue);border-color:var(--blue);}
  .crumb-row{background:var(--gray-band);border-bottom:1px solid var(--line);}
  .crumb-row .wrap{display:flex;justify-content:flex-end;padding:11px 28px;font-size:12.5px;color:var(--ink-soft);}
  .crumb-row b{color:var(--ink);}

  /* ---------- CS band (홈 전용) ---------- */
  .cs-band{background:var(--gray-band);padding:40px 0;text-align:center;}
  .cs-eyebrow{font-size:14px;font-weight:800;letter-spacing:0.12em;color:var(--ink-soft);margin-bottom:8px;}
  .cs-phone{font-size:38px;font-weight:900;color:var(--blue);letter-spacing:-0.01em;}

  /* ---------- 공통 섹션 ---------- */
  .sect{padding:64px 0;}
  .sect-title{font-size:26px;font-weight:800;margin-bottom:10px;}
  .sect-sub{font-size:14px;color:var(--ink-soft);margin-bottom:32px;}

  /* 홈 - 통계/요약 */
  .stat-strip{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;}
  .stat-box{background:#fff;border:1px solid var(--line);border-radius:10px;padding:22px;text-align:center;}
  .stat-box b{display:block;font-size:26px;font-weight:900;color:var(--blue);}
  .stat-box span{font-size:12.5px;color:var(--ink-soft);}
  @media(max-width:760px){.stat-strip{grid-template-columns:repeat(2,1fr);}}

  .home-svc-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;}
  @media(max-width:900px){.home-svc-grid{grid-template-columns:repeat(2,1fr);}}
  .home-svc-card{border:1px solid var(--line);border-radius:10px;padding:22px;transition:box-shadow .2s;}
  .home-svc-card:hover{box-shadow:0 10px 24px rgba(0,0,0,0.06);}
  .home-svc-card .ic{width:38px;height:38px;border-radius:9px;background:var(--navy);display:flex;align-items:center;justify-content:center;margin-bottom:12px;}
  .home-svc-card .ic svg{width:18px;height:18px;stroke:var(--blue);}
  .home-svc-card h3{font-size:14.5px;font-weight:700;margin-bottom:5px;}
  .home-svc-card p{font-size:12.5px;color:var(--ink-soft);}

  /* ---------- 업체소개: 인사말 ---------- */
  .about-grid{display:grid;grid-template-columns:1.15fr 0.85fr;gap:48px;align-items:flex-start;}
  @media(max-width:820px){.about-grid{grid-template-columns:1fr;}}
  .about-grid h2{font-size:22px;margin-bottom:6px;}
  .about-grid h2 b{color:var(--blue);}
  .about-grid p{font-size:14.5px;color:var(--ink-soft);margin-bottom:14px;}
  .photo-panel{
    border-radius:12px;overflow:hidden;background:linear-gradient(135deg,#16324F,#0D1420);
    min-height:280px;display:flex;flex-direction:column;align-items:center;justify-content:center;color:rgba(255,255,255,0.85);gap:10px;
  }
  .photo-panel svg{width:56px;height:56px;stroke:var(--blue);}
  .photo-panel span{font-size:12px;color:rgba(255,255,255,0.5);}

  /* 연혁 */
  .founding-strip{display:flex;gap:12px;margin:22px 0;}
  .founding-cell{flex:1;background:var(--bg);border-radius:10px;padding:14px;text-align:center;}
  .founding-cell b{display:block;font-size:19px;font-weight:900;color:var(--blue);}
  .founding-cell span{font-size:11.5px;color:var(--ink-soft);}
  .timeline{position:relative;padding-left:24px;}
  .timeline::before{content:"";position:absolute;left:4px;top:4px;bottom:4px;width:2px;background:var(--line);}
  .tl-item{position:relative;padding-bottom:20px;}
  .tl-item::before{content:"";position:absolute;left:-24px;top:3px;width:10px;height:10px;border-radius:50%;background:var(--blue);}
  .tl-year{font-weight:900;color:var(--blue);font-size:15px;}
  .tl-text{font-size:13px;color:var(--ink-soft);margin-top:2px;}

  /* 오시는길 */
  .info-list div{padding:10px 0;border-bottom:1px solid var(--line);font-size:14px;color:var(--ink-soft);}
  .info-list b{display:inline-block;width:80px;color:var(--ink);font-weight:700;}
  .map-box{margin-top:16px;height:180px;border-radius:10px;background:repeating-linear-gradient(45deg,var(--bg),var(--bg) 10px,#eef1f4 10px,#eef1f4 20px);display:flex;align-items:center;justify-content:center;color:#98A2AC;font-size:13px;border:1px solid var(--line);}

  /* ---------- 서비스안내 ---------- */
  .svc-head{display:flex;align-items:center;gap:8px;margin:0 0 12px;font-size:16.5px;font-weight:800;}
  .svc-head .ring{width:9px;height:9px;border:2px solid var(--blue);border-radius:50%;}
  .svc-locations{font-size:14px;color:var(--ink-soft);margin-bottom:40px;}
  .svc-locations b{color:var(--blue);font-weight:700;}
  .check-block{margin-bottom:26px;}
  .check-title{font-size:15.5px;font-weight:800;color:var(--blue);margin-bottom:10px;display:flex;align-items:center;gap:8px;}
  .check-title .num{width:22px;height:22px;border-radius:5px;background:#E9F1FF;color:var(--blue);display:flex;align-items:center;justify-content:center;font-size:12.5px;}
  .check-sub{font-size:13.5px;color:var(--ink-soft);margin:4px 0 4px 30px;}
  .check-sub::before{content:"✔ ";color:var(--teal);font-weight:800;}
  .cert-list{display:flex;flex-wrap:wrap;gap:9px;margin-top:30px;}
  .cert-chip{font-size:12.5px;font-weight:700;color:var(--blue-dark);background:#E9F1FF;border:1px solid #CFE0FB;padding:8px 12px;border-radius:100px;}
  .cert-chip::before{content:"✓ ";}

  /* ---------- 포토갤러리 ---------- */
  .gallery-bar{display:flex;justify-content:space-between;align-items:center;background:var(--bg);border:1px solid var(--line);border-radius:8px;padding:12px 18px;margin-bottom:26px;font-size:13px;color:var(--ink-soft);}
  .gallery-bar b{color:var(--ink);}
  .gallery-note{font-size:11.8px;color:var(--ink-soft);background:var(--bg);border:1px dashed #D8DEE4;padding:8px 12px;border-radius:8px;margin-bottom:22px;}
  .gallery-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:18px;}
  @media(max-width:900px){.gallery-grid{grid-template-columns:repeat(2,1fr);}}
  .gallery-item{border-radius:8px;overflow:hidden;border:1px solid var(--line);}
  .gallery-thumb{height:130px;display:flex;align-items:center;justify-content:center;color:#fff;}
  .gallery-thumb svg{width:30px;height:30px;stroke:#fff;opacity:0.9;}
  .gallery-cap{padding:11px 12px;}
  .gallery-cap .yr{font-size:11px;font-weight:800;color:var(--blue);}
  .gallery-cap .tt{font-size:12.6px;color:var(--ink);margin-top:2px;line-height:1.4;}

  /* ---------- 공지사항 (수상이력) ---------- */
  .notice-item{border-bottom:1px solid var(--line);}
  .notice-head{display:flex;align-items:center;gap:12px;padding:16px 4px;cursor:pointer;}
  .notice-tag{font-size:11px;font-weight:800;color:#fff;background:var(--blue);padding:4px 9px;border-radius:5px;flex:none;}
  .notice-title{flex:1;font-size:14.5px;font-weight:700;}
  .notice-date{font-size:12.5px;color:var(--ink-soft);}
  .notice-body{display:none;padding:0 4px 18px 60px;font-size:13.3px;color:var(--ink-soft);}
  .notice-item.open .notice-body{display:block;}

  /* ---------- 온라인문의 ---------- */
  .board-layout{display:grid;grid-template-columns:1fr 1.25fr;gap:40px;align-items:start;}
  @media(max-width:860px){.board-layout{grid-template-columns:1fr;}}
  .board-form{background:var(--bg);border:1px solid var(--line);border-radius:12px;padding:26px;}
  .board-form h3{font-size:16px;font-weight:800;margin-bottom:16px;}
  .field{margin-bottom:13px;}
  .field label{display:block;font-size:12.5px;font-weight:700;color:var(--ink-soft);margin-bottom:6px;}
  .field input,.field textarea{width:100%;border:1px solid var(--line);border-radius:8px;padding:10px 12px;font-family:inherit;font-size:13.6px;background:#fff;}
  .field textarea{min-height:96px;resize:vertical;}
  .field-row{display:flex;gap:10px;}
  .field-row .field{flex:1;}
  .check-row{display:flex;align-items:center;gap:7px;font-size:13px;color:var(--ink-soft);margin-bottom:13px;}
  .check-row input{width:15px;height:15px;}
  .pw-inline{display:none;}
  .pw-inline.show{display:block;}
  .form-msg{font-size:12.5px;margin-top:9px;padding:8px 10px;border-radius:7px;display:none;}
  .form-msg.show{display:block;}
  .form-msg.ok{background:#E6F8F3;color:#0B7A5F;}
  .form-msg.err{background:#FCEBEA;color:#B23A34;}
  .btn-submit{width:100%;padding:13px;border-radius:9px;border:none;background:var(--blue);color:#fff;font-weight:800;font-size:13.8px;}
  .board-list-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:14px;}
  .board-list-head h3{font-size:15.5px;font-weight:800;}
  .admin-toggle{font-size:12px;color:var(--ink-soft);border:1px solid var(--line);padding:7px 13px;border-radius:100px;background:transparent;}
  .admin-toggle.on{color:#fff;background:var(--navy);border-color:var(--navy);}
  .qa-item{border:1px solid var(--line);border-radius:10px;margin-bottom:10px;overflow:hidden;background:#fff;}
  .qa-summary{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:14px 16px;cursor:pointer;}
  .qa-title{font-size:13.8px;font-weight:700;display:flex;align-items:center;gap:7px;}
  .qa-meta{font-size:11.5px;color:#8B95A0;white-space:nowrap;display:flex;align-items:center;gap:10px;}
  .badge{font-size:10.5px;font-weight:700;padding:3px 8px;border-radius:100px;}
  .badge-wait{background:#FDEFD9;color:#8A5B0C;}
  .badge-done{background:#E6F8F3;color:#0B7A5F;}
  .qa-detail{display:none;padding:0 16px 16px;border-top:1px solid var(--line);}
  .qa-detail.open{display:block;padding-top:13px;}
  .qa-content{font-size:13.6px;color:var(--ink-soft);white-space:pre-wrap;margin-bottom:12px;}
  .qa-answer{background:var(--bg);border-left:3px solid var(--blue);border-radius:0 8px 8px 0;padding:11px 13px;font-size:13px;white-space:pre-wrap;margin-bottom:10px;}
  .qa-answer b{color:var(--blue);display:block;font-size:11.5px;margin-bottom:5px;}
  .qa-admin-tools{display:flex;flex-direction:column;gap:8px;margin-top:8px;padding-top:10px;border-top:1px dashed var(--line);}
  .qa-admin-tools textarea{width:100%;border:1px solid var(--line);border-radius:8px;padding:9px;font-family:inherit;font-size:13px;min-height:70px;}
  .qa-admin-btns{display:flex;gap:8px;}
  .btn-sm{padding:7px 13px;border-radius:7px;font-size:12px;font-weight:700;border:1px solid transparent;}
  .btn-sm.reply{background:var(--navy);color:#fff;}
  .btn-sm.del{background:#fff;color:#B23A34;border-color:#f2c9c7;}
  .lock-form{display:flex;gap:8px;}
  .lock-form input{flex:1;border:1px solid var(--line);border-radius:8px;padding:8px 9px;font-size:12.8px;}
  .empty-state{padding:30px 14px;text-align:center;color:#98A2AC;font-size:13px;}

  /* ---------- 플로팅 요소 ---------- */
  .cta-ribbon{
    position:fixed;top:96px;right:22px;z-index:150;
    background:var(--red);color:#fff;border-radius:10px;
    padding:14px 12px;text-align:center;font-size:12.5px;font-weight:800;line-height:1.4;
    box-shadow:0 10px 24px rgba(229,66,63,0.35);width:76px;
    animation:pulse 2.4s ease-in-out infinite;
  }
  .cta-ribbon svg{width:20px;height:20px;stroke:#fff;margin:0 auto 4px;}
  @keyframes pulse{0%,100%{transform:scale(1);}50%{transform:scale(1.06);}}
  @media(prefers-reduced-motion:reduce){.cta-ribbon{animation:none;}}
  .quick-float{
    position:fixed;right:22px;bottom:26px;z-index:150;
    width:52px;height:52px;border-radius:50%;background:var(--navy);color:#fff;
    display:flex;align-items:center;justify-content:center;box-shadow:0 10px 24px rgba(0,0,0,0.25);
  }
  .quick-float svg{width:22px;height:22px;stroke:var(--blue);}
  @media(max-width:760px){.cta-ribbon{top:auto;bottom:90px;right:16px;} .quick-float{bottom:16px;right:16px;}}

  footer{background:var(--navy);color:rgba(255,255,255,0.72);padding:48px 0 28px;}
  .foot-grid{display:grid;grid-template-columns:1.3fr 1fr 1fr;gap:32px;margin-bottom:28px;}
  @media(max-width:760px){.foot-grid{grid-template-columns:1fr;}}
  footer h4{color:#fff;font-size:15px;margin-bottom:12px;}
  footer p,footer li{font-size:12.8px;line-height:1.9;}
  footer ul{list-style:none;}
  .foot-bottom{border-top:1px solid rgba(255,255,255,0.12);padding-top:18px;font-size:11.5px;color:rgba(255,255,255,0.45);}

  .page{display:none;}
  .page.active{display:block;}
</style>
</head>
<body>

<div id="sampleNotice">🧪 샘플 콘텐츠 템플릿입니다 — 실제 정보로 교체 후 사용해주세요
  <button onclick="document.getElementById('sampleNotice').style.display='none'">✕</button>
</div>

<header>
  <div class="wrap">
    <div class="logo">포항그린<b>방역</b></div>
    <nav class="mainnav">
      <div class="navitem"><a href="#" class="top" data-nav="about">업체소개</a>
        <div class="dropdown">
          <a href="#" data-nav="about" data-sub="greet">인사말</a>
          <a href="#" data-nav="about" data-sub="history">회사연혁</a>
          <a href="#" data-nav="about" data-sub="location">오시는길</a>
        </div>
      </div>
      <a href="#" class="top" data-nav="services">서비스안내</a>
      <a href="#" class="top" data-nav="gallery">포토갤러리</a>
      <a href="#" class="top" data-nav="board">온라인문의</a>
      <a href="#" class="top" data-nav="notice">공지사항</a>
      <a href="https://blog.naver.com/jaeuk1008" target="_blank" rel="noopener" class="top">블로그</a>
    </nav>
    <a href="#" class="hdr-cta" data-nav="board">온라인문의</a>
    <button class="navtoggle">☰</button>
  </div>
</header>

<!-- ===================== 홈 ===================== -->
<div class="page active" id="page-home">
  <div class="hero" id="heroHome">
    <div class="hero-slide active" style="background:linear-gradient(125deg,#0B2540,#123B3A);"></div>
    <div class="hero-slide" style="background:linear-gradient(125deg,#12203A,#0E3A34);"></div>
    <div class="hero-slide" style="background:linear-gradient(125deg,#182A44,#0B2C2A);"></div>
    <div class="hero-slide" style="background:linear-gradient(125deg,#0E1B30,#123534);"></div>
    <div class="wrap">
      <div class="hero-callout">
        <div class="hc-line">포항그린방역만의 <b>철저한 방역 시스템!</b></div>
        <div class="hc-line">믿을 수 있게! 더욱 <b>안전하고 깨끗하게!</b></div>
        <div class="hc-brand"><span class="b1">GREEN</span><span class="b2">포항그린방역</span> 에 맡겨보세요!</div>
        <div class="hc-tags">
          <span class="hc-tag">숙련된 방역 전문가 투입!</span>
          <span class="hc-tag">친환경 인증 약제 사용!</span>
        </div>
        <div class="hc-list">
          <span>소독전문</span><span>산업시설 방역</span><span>병해충 방제</span>
        </div>
        <div class="hc-note">친절상담! 무료견적!</div>
        <div class="hc-phone">054-000-0000</div>
      </div>
    </div>
    <div class="hero-arrows">
      <div class="hero-arrow" id="prevSlide">‹</div>
      <div class="hero-arrow" id="nextSlide">›</div>
    </div>
    <div class="hero-dots" id="heroDots"></div>
    <div class="scrolldown"><div class="line"></div>Scroll Down</div>
  </div>

  <div class="cs-band">
    <div class="cs-eyebrow">CS CENTER</div>
    <div class="cs-phone">054-000-0000</div>
  </div>

  <section class="sect">
    <div class="wrap">
      <div class="sect-title">포항그린방역, 숫자로 보는 신뢰</div>
      <div class="sect-sub">1998년부터 포항 지역을 지켜온 방역 전문기업입니다</div>
      <div class="stat-strip">
        <div class="stat-box"><b>1998</b><span>설립 연도</span></div>
        <div class="stat-box"><b>27년</b><span>지역 경력</span></div>
        <div class="stat-box"><b>600+</b><span>누적 현장</span></div>
        <div class="stat-box"><b>5개</b><span>보유 인허가·자격</span></div>
      </div>
    </div>
  </section>

  <section class="sect" style="background:var(--bg);">
    <div class="wrap">
      <div class="sect-title">핵심 서비스</div>
      <div class="sect-sub">현장 규모에 맞춘 방역 솔루션을 제공합니다</div>
      <div class="home-svc-grid">
        <div class="home-svc-card"><div class="ic"><svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 12h16M4 6h16M4 18h10"/></svg></div><h3>정기 방역·소독</h3><p>사업장·공동주택 정기 방문 소독</p></div>
        <div class="home-svc-card"><div class="ic"><svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2l3 6 6 1-4.5 4.5L18 20l-6-3-6 3 1.5-6.5L2 9l6-1z"/></svg></div><h3>병해충 방제</h3><p>바퀴·쥐·모기 등 맞춤 방제</p></div>
        <div class="home-svc-card"><div class="ic"><svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 21h18M5 21V7l7-4 7 4v14M9 21v-6h6v6"/></svg></div><h3>산업시설 대형 방역</h3><p>산업단지·물류창고 전면 시공</p></div>
        <div class="home-svc-card"><div class="ic"><svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="16" rx="2"/><path d="M3 9h18M8 4v16"/></svg></div><h3>사후관리·모니터링</h3><p>IoT 트랩으로 재발 여부 확인</p></div>
      </div>
    </div>
  </section>
  <div id="homeFooterSlot"></div>
</div>

<!-- ===================== 업체소개 ===================== -->
<div class="page" id="page-about">
  <div class="hero hero-sub" style="background:linear-gradient(125deg,#0B2540,#123B3A);">
    <div class="wrap">
      <h1 id="aboutHeroTitle">인사말</h1>
      <div class="hero-phone-pill">📞 054-000-0000</div>
    </div>
  </div>
  <div class="subtab-row"><div class="wrap">
    <a href="#" class="subtab" data-sub="greet">인사말</a>
    <a href="#" class="subtab" data-sub="history">회사연혁</a>
    <a href="#" class="subtab" data-sub="location">오시는길</a>
  </div></div>
  <div class="crumb-row"><div class="wrap">HOME <span>›</span> 업체소개 <span>›</span> <b id="aboutCrumb">인사말</b></div></div>

  <section class="sect">
    <div class="wrap">
      <div id="sub-greet">
        <div class="about-grid">
          <div>
            <h2>안녕하세요.<br><b>포항그린방역</b> 홈페이지를 방문해주셔서 감사합니다.</h2>
            <p>저희 포항그린방역은 1998년부터 포항 지역을 중심으로 소독·방역·병해충 방제 전문 서비스를 제공해온 종합 방역기업입니다.</p>
            <p>건강하고 안전한 생활을 위해 쾌적한 실내 환경과 철저한 위생 관리는 필수입니다. 최신 장비와 친환경 약제, 검증된 소독약품을 사용하여 주거공간, 사업장, 공공기관, 산업시설 등 다양한 공간을 완벽하게 방역해드립니다.</p>
            <p>"청결한 공간, 건강한 삶"을 목표로 최상의 서비스를 제공하겠습니다.</p>
          </div>
          <div class="photo-panel">
            <svg viewBox="0 0 24 24" fill="none" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M8 3a4 4 0 100 8 4 4 0 000-8zM16 3a4 4 0 100 8 4 4 0 000-8zM2 21v-2a4 4 0 014-4h4a4 4 0 014 4v2M14 21v-2a4 4 0 014-4h.5a3.5 3.5 0 013.5 3.5V21"/></svg>
            <span>현장 사진 (예시)</span>
          </div>
        </div>
      </div>

      <div id="sub-history" style="display:none;">
        <div class="founding-strip">
          <div class="founding-cell"><b>1998</b><span>설립 연도</span></div>
          <div class="founding-cell"><b>27년</b><span>지역 경력</span></div>
          <div class="founding-cell"><b>600+</b><span>누적 현장</span></div>
        </div>
        <div class="timeline">
          <div class="tl-item"><div class="tl-year">1998</div><div class="tl-text">개인 방역업 등록, 포항 지역 서비스 개시</div></div>
          <div class="tl-item"><div class="tl-year">2003</div><div class="tl-text">법인 전환 및 포항시 소독업 등록증 취득</div></div>
          <div class="tl-item"><div class="tl-year">2009</div><div class="tl-text">관내 학교 급식소 정기 방역 계약 체결</div></div>
          <div class="tl-item"><div class="tl-year">2014</div><div class="tl-text">친환경 약제 전면 도입, ISO 9001 인증 취득</div></div>
          <div class="tl-item"><div class="tl-year">2019</div><div class="tl-text">포항 산업단지 방역 총괄 대행사 선정</div></div>
          <div class="tl-item"><div class="tl-year">2023</div><div class="tl-text">IoT 트랩 기반 스마트 방제 시스템 도입</div></div>
        </div>
      </div>

      <div id="sub-location" style="display:none;">
        <div class="info-list">
          <div><b>주소</b>경상북도 포항시 남구 OO로 00 (샘플)</div>
          <div><b>전화</b>054-000-0000</div>
          <div><b>이메일</b>info@sample-bangyeok.co.kr</div>
          <div><b>운영시간</b>평일 09:00–18:00 · 토 09:00–13:00</div>
        </div>
        <div class="map-box">지도 영역 (실제 주소 연결 예정)</div>
      </div>
    </div>
  </section>
</div>

<!-- ===================== 서비스안내 ===================== -->
<div class="page" id="page-services">
  <div class="hero hero-sub" style="background:linear-gradient(125deg,#12203A,#0E3A34);">
    <div class="wrap"><h1>서비스안내</h1><div class="hero-phone-pill">📞 054-000-0000</div></div>
  </div>
  <div class="subtab-row"><div class="wrap"><a href="#" class="subtab active">서비스안내</a></div></div>
  <div class="crumb-row"><div class="wrap">HOME <span>›</span> <b>서비스안내</b></div></div>

  <section class="sect">
    <div class="wrap">
      <div class="svc-head"><span class="ring"></span>포항그린방역</div>
      <div class="svc-locations"><b>포항 남구소독전문업체</b>, <b>포항 북구방역전문업체</b>, <b>포항산업단지방역대행업체</b>, <b>포항학교급식소소독전문업체</b>, <b>경주소독전문업체</b></div>

      <div class="svc-head"><span class="ring"></span>방역·소독 서비스 안내</div>

      <div class="check-block">
        <div class="check-title"><span class="num">1</span>정기 방역·소독</div>
        <div class="check-sub">사업장·공동주택 대상 주/월 단위 정기 방문 소독</div>
        <div class="check-sub">친환경 세제 및 최신 장비 사용 — 인체에 무해한 제품으로 안전한 소독</div>
      </div>
      <div class="check-block">
        <div class="check-title"><span class="num">2</span>병해충 방제</div>
        <div class="check-sub">바퀴벌레, 쥐, 모기 등 생활 해충의 유입 및 번식 차단</div>
        <div class="check-sub">서식지 추적 후 맞춤 약제로 근본 원인 제거</div>
      </div>
      <div class="check-block">
        <div class="check-title"><span class="num">3</span>급식소·식품위생 소독</div>
        <div class="check-sub">학교·기관 급식소 위생 기준에 맞춘 정기 소독 및 점검</div>
      </div>
      <div class="check-block">
        <div class="check-title"><span class="num">4</span>산업시설 대형 방역</div>
        <div class="check-sub">산업단지, 물류창고 등 대형 시설 전면 방역 계획·시공</div>
      </div>
      <div class="check-block">
        <div class="check-title"><span class="num">5</span>실내 공기·바이러스 소독</div>
        <div class="check-sub">UV 및 초미세 분무 방식으로 공기 중 바이러스·세균까지 관리</div>
      </div>

      <div class="cert-list">
        <div class="cert-chip">방역업 등록증</div>
        <div class="cert-chip">소독업 등록증</div>
        <div class="cert-chip">유해화학물질 취급허가</div>
        <div class="cert-chip">ISO 9001</div>
        <div class="cert-chip">방제기능사 보유</div>
      </div>
    </div>
  </section>
</div>

<!-- ===================== 포토갤러리 ===================== -->
<div class="page" id="page-gallery">
  <div class="hero hero-sub" style="background:linear-gradient(125deg,#182A44,#0B2C2A);">
    <div class="wrap"><h1>포토갤러리</h1><div class="hero-phone-pill">📞 054-000-0000</div></div>
  </div>
  <div class="subtab-row"><div class="wrap"><a href="#" class="subtab active">포토갤러리</a></div></div>
  <div class="crumb-row"><div class="wrap">HOME <span>›</span> <b>포토갤러리</b></div></div>

  <section class="sect">
    <div class="wrap">
      <div class="gallery-note">※ 아래 사진은 예시이며, 실제 현장 사진으로 교체될 예정입니다.</div>
      <div class="gallery-bar"><span>연도별 주요 사업 진행 이력</span><span>전체: <b id="galCount">0</b> | 페이지: 1/1</span></div>
      <div class="gallery-grid" id="galleryGrid"></div>
    </div>
  </section>
</div>

<!-- ===================== 온라인문의 ===================== -->
<div class="page" id="page-board">
  <div class="hero hero-sub" style="background:linear-gradient(125deg,#0E1B30,#123534);">
    <div class="wrap"><h1>온라인문의</h1><div class="hero-phone-pill">📞 054-000-0000</div></div>
  </div>
  <div class="subtab-row"><div class="wrap"><a href="#" class="subtab active">온라인문의</a></div></div>
  <div class="crumb-row"><div class="wrap">HOME <span>›</span> <b>온라인문의</b></div></div>

  <section class="sect">
    <div class="wrap">
      <div class="board-layout">
        <div class="board-form">
          <h3>문의 작성</h3>
          <form id="qaForm">
            <div class="field-row">
              <div class="field"><label>이름</label><input type="text" id="qName" required></div>
              <div class="field"><label>연락처(선택)</label><input type="tel" id="qPhone" placeholder="010-0000-0000"></div>
            </div>
            <div class="field"><label>제목</label><input type="text" id="qTitle" required></div>
            <div class="field"><label>문의 내용</label><textarea id="qContent" required></textarea></div>
            <div class="check-row">
              <input type="checkbox" id="qPrivate">
              <label for="qPrivate" style="margin:0;">비밀글로 등록 (비밀번호로만 열람)</label>
            </div>
            <div class="field pw-inline" id="pwField">
              <label>열람 비밀번호 (숫자 4자리)</label>
              <input type="password" id="qPassword" maxlength="4" inputmode="numeric">
            </div>
            <button type="submit" class="btn-submit">문의 등록</button>
            <div class="form-msg" id="formMsg"></div>
          </form>
        </div>
        <div>
          <div class="board-list-head">
            <h3>문의 목록</h3>
            <button class="admin-toggle" id="adminToggle">관리자 로그인</button>
          </div>
          <div id="qaList"></div>
        </div>
      </div>
    </div>
  </section>
</div>

<!-- ===================== 공지사항 (수상이력) ===================== -->
<div class="page" id="page-notice">
  <div class="hero hero-sub" style="background:linear-gradient(125deg,#0B2540,#0D1420);">
    <div class="wrap"><h1>공지사항</h1><div class="hero-phone-pill">📞 054-000-0000</div></div>
  </div>
  <div class="subtab-row"><div class="wrap"><a href="#" class="subtab active">공지사항</a></div></div>
  <div class="crumb-row"><div class="wrap">HOME <span>›</span> <b>공지사항</b></div></div>

  <section class="sect">
    <div class="wrap">
      <div class="sect-sub" style="margin-bottom:20px;">기업 수상이력을 공지 형태로 안내드립니다.</div>

      <a href="https://blog.naver.com/jaeuk1008" target="_blank" rel="noopener"
         style="display:flex; align-items:center; justify-content:space-between; gap:16px; background:#0D1420; color:#fff; border-radius:10px; padding:20px 24px; margin-bottom:28px; text-decoration:none;">
        <div>
          <div style="font-size:12.5px; color:#8FB4FF; font-weight:700; margin-bottom:4px;">시공사례 · 실시간 소식</div>
          <div style="font-size:16px; font-weight:800;">더 자주 업데이트되는 소식은 네이버 블로그에서 확인하세요</div>
        </div>
        <div style="flex-shrink:0; background:#2F6FEB; padding:10px 18px; border-radius:100px; font-size:13.5px; font-weight:700; white-space:nowrap;">블로그 바로가기 →</div>
      </a>

      <div id="noticeList"></div>
    </div>
  </section>
</div>

<footer id="mainFooter">
  <div class="wrap">
    <div class="foot-grid">
      <div><h4>포항그린방역</h4><p>경상북도 포항시 남구 OO로 00 (샘플)<br>사업자등록번호 000-00-00000 (샘플)<br>대표자 홍길동 (샘플)</p></div>
      <div><h4>연락처</h4><ul><li>전화 054-000-0000</li><li>팩스 054-000-0001</li><li>이메일 info@sample-bangyeok.co.kr</li></ul></div>
      <div><h4>운영시간</h4><ul><li>평일 09:00–18:00</li><li>토요일 09:00–13:00</li><li>일요일·공휴일 휴무</li></ul></div>
    </div>
    <div class="foot-bottom">© 2026 포항그린방역(샘플). 본 페이지는 템플릿이며 실제 사업자 정보가 아닙니다.</div>
  </div>
</footer>

<div class="cta-ribbon" onclick="switchPage('board')">
  <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 11l3 3L22 4"/><path d="M21 12v7a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h11"/></svg>
  무료상담<br>신청
</div>
<div class="quick-float" onclick="switchPage('about','location')" title="오시는길">
  <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>
</div>

<script>
/* ============ 라우팅 ============ */
function switchPage(page, sub){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page-'+page).classList.add('active');
  document.querySelectorAll('nav.mainnav a.top').forEach(a=>a.classList.toggle('active', a.dataset.nav===page));
  if(page==='about'){ setAboutSub(sub||'greet'); }
  window.scrollTo({top:0, behavior:'instant' in window ? 'instant':'auto'});
}
document.querySelectorAll('[data-nav]').forEach(el=>{
  el.addEventListener('click', (e)=>{
    e.preventDefault();
    switchPage(el.dataset.nav, el.dataset.sub);
  });
});
function setAboutSub(sub){
  ['greet','history','location'].forEach(s=>{
    document.getElementById('sub-'+s).style.display = (s===sub) ? '' : 'none';
  });
  document.querySelectorAll('#page-about .subtab').forEach(t=> t.classList.toggle('active', t.dataset.sub===sub));
  document.getElementById('aboutHeroTitle').textContent = {greet:'인사말',history:'회사연혁',location:'오시는길'}[sub];
  document.getElementById('aboutCrumb').textContent = {greet:'인사말',history:'회사연혁',location:'오시는길'}[sub];
}
document.querySelectorAll('#page-about .subtab').forEach(t=>{
  t.addEventListener('click', e=>{ e.preventDefault(); setAboutSub(t.dataset.sub); window.scrollTo({top:0}); });
});
setAboutSub('greet');

/* ============ 홈 히어로 캐러셀 ============ */
const slides = document.querySelectorAll('#heroHome .hero-slide');
const dotsEl = document.getElementById('heroDots');
let curSlide = 0;
slides.forEach((s,i)=>{
  const d = document.createElement('div');
  d.className = 'hero-dot'+(i===0?' active':'');
  d.addEventListener('click', ()=>goSlide(i));
  dotsEl.appendChild(d);
});
function goSlide(i){
  slides[curSlide].classList.remove('active');
  dotsEl.children[curSlide].classList.remove('active');
  curSlide = (i+slides.length)%slides.length;
  slides[curSlide].classList.add('active');
  dotsEl.children[curSlide].classList.add('active');
}
document.getElementById('prevSlide').addEventListener('click', ()=>goSlide(curSlide-1));
document.getElementById('nextSlide').addEventListener('click', ()=>goSlide(curSlide+1));
let autoSlide = setInterval(()=>goSlide(curSlide+1), 5000);

/* ============ 포토갤러리 (연도별 사업이력) ============ */
const projects = [
  {year:'2024', title:'공공기관 청사 정기 방역 위탁', grad:'linear-gradient(135deg,#123B3A,#0B2540)', icon:'<path d="M3 21h18M5 21V7l7-4 7 4v14M9 21v-6h6v6"/>'},
  {year:'2023', title:'IoT 트랩 기반 스마트 방제 시범사업', grad:'linear-gradient(135deg,#0E3A34,#12203A)', icon:'<rect x="3" y="11" width="18" height="10" rx="2"/><path d="M7 11V7a5 5 0 0110 0v4"/>'},
  {year:'2022', title:'수산시장 특별 방역 지원', grad:'linear-gradient(135deg,#0B2C2A,#182A44)', icon:'<path d="M12 2l3 6 6 1-4.5 4.5L18 20l-6-3-6 3 1.5-6.5L2 9l6-1z"/>'},
  {year:'2021', title:'아파트 단지 8곳 정기 소독 계약', grad:'linear-gradient(135deg,#123534,#0E1B30)', icon:'<path d="M4 21V9l8-6 8 6v12M9 21v-6h6v6"/>'},
  {year:'2020', title:'관내 초중고 55개교 급식소 방역', grad:'linear-gradient(135deg,#0D1420,#0B2540)', icon:'<path d="M12 3L2 8l10 5 10-5-10-5z"/><path d="M6 10.5V16c0 1.5 2.7 3 6 3s6-1.5 6-3v-5.5"/>'},
  {year:'2019', title:'포항 산업단지 정기 방역 대행사 선정', grad:'linear-gradient(135deg,#123B3A,#182A44)', icon:'<path d="M3 21h18M5 21V11l4 3v-3l4 3v-3l4 3V4h-8"/>'},
  {year:'2017', title:'포항 남구 공동주택 정기 소독 계약', grad:'linear-gradient(135deg,#0E3A34,#0D1420)', icon:'<path d="M4 21V9l8-6 8 6v12M9 21v-6h6v6"/>'},
  {year:'2014', title:'친환경 약제 전면 도입 현장 적용', grad:'linear-gradient(135deg,#0B2C2A,#123B3A)', icon:'<path d="M12 2v4M12 18v4M4.9 4.9l2.8 2.8M16.3 16.3l2.8 2.8M2 12h4M18 12h4M4.9 19.1l2.8-2.8M16.3 7.7l2.8-2.8"/><circle cx="12" cy="12" r="4"/>'},
];
function renderGallery(){
  const grid = document.getElementById('galleryGrid');
  document.getElementById('galCount').textContent = projects.length;
  grid.innerHTML = projects.map(p=>`
    <div class="gallery-item">
      <div class="gallery-thumb" style="background:${p.grad}"><svg viewBox="0 0 24 24" fill="none" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round">${p.icon}</svg></div>
      <div class="gallery-cap"><div class="yr">${p.year}</div><div class="tt">${p.title}</div></div>
    </div>`).join('');
}
renderGallery();

/* ============ 공지사항 (수상이력) ============ */
const awards = [
  {year:'2015', title:'포항시장 표창 — 우수 방역업체 부문', body:'포항시로부터 우수 방역업체로 선정되어 시장 표창을 수여받았습니다.'},
  {year:'2018', title:'경상북도 환경분야 유공 표창', body:'지역 환경위생 개선에 기여한 공로로 경상북도로부터 유공 표창을 수여받았습니다.'},
  {year:'2021', title:'중소벤처기업부 우수기술기업 선정', body:'친환경 방역 기술력을 인정받아 중소벤처기업부 우수기술기업으로 선정되었습니다.'},
  {year:'2023', title:'포항상공회의소 모범납세기업 선정', body:'지역 경제 기여 및 모범적인 세무 관리로 포항상공회의소 모범납세기업에 선정되었습니다.'},
];
function renderNotice(){
  const el = document.getElementById('noticeList');
  el.innerHTML = awards.map((a,i)=>`
    <div class="notice-item" data-i="${i}">
      <div class="notice-head" data-toggle="${i}">
        <span class="notice-tag">수상</span>
        <span class="notice-title">${a.year}년 · ${a.title}</span>
        <span class="notice-date">${a.year}.00.00</span>
      </div>
      <div class="notice-body">${a.body}</div>
    </div>`).join('');
  el.querySelectorAll('.notice-head').forEach(h=>{
    h.addEventListener('click', ()=> h.closest('.notice-item').classList.toggle('open'));
  });
}
renderNotice();

/* ============ 온라인문의 (persistent storage) ============ */
const STORAGE_KEY = 'inquiries';
const ADMIN_PASSWORD = 'pohang2026'; // TODO: 실제 운영 전 반드시 변경하세요
let isAdmin = false;
let inquiries = [];

async function loadInquiries(){
  try{
    const res = await window.storage.get(STORAGE_KEY, true);
    inquiries = res && res.value ? JSON.parse(res.value) : [];
  }catch(e){ inquiries = []; }
  renderList();
}
async function saveInquiries(){
  try{ await window.storage.set(STORAGE_KEY, JSON.stringify(inquiries), true); }
  catch(e){ console.error('저장 실패', e); }
}
function maskName(name){ return name.length<=1 ? name+'*' : name[0]+'*'.repeat(name.length-1); }
function fmtDate(iso){ const d=new Date(iso); return `${d.getFullYear()}.${String(d.getMonth()+1).padStart(2,'0')}.${String(d.getDate()).padStart(2,'0')}`; }
function escapeHtml(str){ const div=document.createElement('div'); div.textContent=str; return div.innerHTML; }

function renderList(){
  const listEl = document.getElementById('qaList');
  if(!inquiries.length){
    listEl.innerHTML = `<div class="qa-item"><div class="empty-state">등록된 문의가 없습니다. 첫 문의를 남겨보세요.</div></div>`;
    return;
  }
  const sorted = [...inquiries].sort((a,b)=> new Date(b.createdAt)-new Date(a.createdAt));
  listEl.innerHTML = sorted.map(item=>{
    const locked = item.private && !isAdmin;
    return `
    <div class="qa-item" data-id="${item.id}">
      <div class="qa-summary" data-toggle="${item.id}">
        <div class="qa-title">${item.private?'🔒 ':''}${escapeHtml(item.title)}</div>
        <div class="qa-meta">
          <span class="badge ${item.answer?'badge-done':'badge-wait'}">${item.answer?'답변완료':'답변대기'}</span>
          <span>${maskName(item.name)} · ${fmtDate(item.createdAt)}</span>
        </div>
      </div>
      <div class="qa-detail" id="detail-${item.id}">
        ${locked ? lockedHtml(item.id) : detailHtml(item)}
      </div>
    </div>`;
  }).join('');
  listEl.querySelectorAll('.qa-summary').forEach(el=>{
    el.addEventListener('click', ()=> document.getElementById('detail-'+el.dataset.toggle).classList.toggle('open'));
  });
  listEl.querySelectorAll('.unlock-btn').forEach(el=>{
    el.addEventListener('click', (e)=>{
      e.stopPropagation();
      const id = el.dataset.id;
      const input = document.getElementById('unlock-'+id);
      const item = inquiries.find(x=>x.id===id);
      if(input.value === item.password){
        document.getElementById('detail-'+id).innerHTML = detailHtml(item);
        attachAdminHandlers(item);
      }else{
        input.style.borderColor = '#B23A34'; input.value=''; input.placeholder='비밀번호가 틀렸습니다';
      }
    });
  });
  listEl.querySelectorAll('.lock-form input, .lock-form button').forEach(el=> el.addEventListener('click', e=>e.stopPropagation()));
  if(isAdmin) inquiries.forEach(item=>attachAdminHandlers(item));
}
function lockedHtml(id){
  return `<div class="lock-form" onclick="event.stopPropagation()">
    <input type="password" maxlength="4" inputmode="numeric" id="unlock-${id}" placeholder="비밀번호 4자리">
    <button class="btn-sm reply unlock-btn" data-id="${id}">열람</button>
  </div>`;
}
function detailHtml(item){
  let html = `<div class="qa-content">${escapeHtml(item.content)}</div>`;
  if(item.phone){ html = `<div class="qa-content" style="margin-bottom:2px;">연락처: ${escapeHtml(item.phone)}</div>` + html; }
  if(item.answer){ html += `<div class="qa-answer"><b>운영자 답변 · ${fmtDate(item.answeredAt)}</b>${escapeHtml(item.answer)}</div>`; }
  if(isAdmin){
    html += `<div class="qa-admin-tools" onclick="event.stopPropagation()">
      <textarea placeholder="답변을 입력하세요" id="answer-${item.id}">${item.answer?escapeHtml(item.answer):''}</textarea>
      <div class="qa-admin-btns">
        <button class="btn-sm reply" data-reply="${item.id}">답변 저장</button>
        <button class="btn-sm del" data-del="${item.id}">문의 삭제</button>
      </div>
    </div>`;
  }
  return html;
}
function attachAdminHandlers(item){
  if(!isAdmin) return;
  const replyBtn = document.querySelector(`[data-reply="${item.id}"]`);
  const delBtn = document.querySelector(`[data-del="${item.id}"]`);
  if(replyBtn) replyBtn.addEventListener('click', async ()=>{
    item.answer = document.getElementById('answer-'+item.id).value.trim();
    item.answeredAt = new Date().toISOString();
    await saveInquiries(); renderList();
  });
  if(delBtn) delBtn.addEventListener('click', async ()=>{
    if(!confirm('이 문의를 삭제할까요? 삭제 후에는 복구할 수 없습니다.')) return;
    inquiries = inquiries.filter(x=>x.id!==item.id);
    await saveInquiries(); renderList();
  });
}
document.getElementById('qPrivate').addEventListener('change', e=>{
  document.getElementById('pwField').classList.toggle('show', e.target.checked);
});
document.getElementById('qaForm').addEventListener('submit', async (e)=>{
  e.preventDefault();
  const name = document.getElementById('qName').value.trim();
  const phone = document.getElementById('qPhone').value.trim();
  const title = document.getElementById('qTitle').value.trim();
  const content = document.getElementById('qContent').value.trim();
  const isPrivate = document.getElementById('qPrivate').checked;
  const password = document.getElementById('qPassword').value.trim();
  const msgEl = document.getElementById('formMsg');
  if(!name || !title || !content){ msgEl.textContent='이름, 제목, 내용을 모두 입력해주세요.'; msgEl.className='form-msg show err'; return; }
  if(isPrivate && password.length!==4){ msgEl.textContent='비밀글은 4자리 비밀번호가 필요합니다.'; msgEl.className='form-msg show err'; return; }
  inquiries.push({
    id: Date.now().toString(36)+Math.random().toString(36).slice(2,7),
    name, phone, title, content, private:isPrivate, password:isPrivate?password:'',
    createdAt: new Date().toISOString(), answer:null, answeredAt:null
  });
  await saveInquiries(); renderList();
  e.target.reset();
  document.getElementById('pwField').classList.remove('show');
  msgEl.textContent = '문의가 등록되었습니다. 답변까지 조금만 기다려주세요.';
  msgEl.className = 'form-msg show ok';
});
document.getElementById('adminToggle').addEventListener('click', ()=>{
  if(isAdmin){
    isAdmin=false;
    document.getElementById('adminToggle').textContent='관리자 로그인';
    document.getElementById('adminToggle').classList.remove('on');
    renderList(); return;
  }
  const pw = prompt('관리자 비밀번호를 입력하세요');
  if(pw===null) return;
  if(pw===ADMIN_PASSWORD){
    isAdmin=true;
    document.getElementById('adminToggle').textContent='관리자 모드 ON';
    document.getElementById('adminToggle').classList.add('on');
    renderList();
  }else{ alert('비밀번호가 올바르지 않습니다.'); }
});
loadInquiries();
</script>
</body>
</html>

</body></html># dh
