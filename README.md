[hong-kong-business-environment-bilingual.html](https://github.com/user-attachments/files/31766289/hong-kong-business-environment-bilingual.html)
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Unit 1 Business Environment of Hong Kong | 單元一 香港的營商環境</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;500;700;900&family=Inter:wght@400;500;600;700&display=swap');

  *{margin:0;padding:0;box-sizing:border-box}
  :root{
    --gold:#d4a000;--red:#e04848;--cyan:#0090c0;--green:#1a9a52;
    --purple:#7c3aed;--dark:#0a0a1a;--card:#111122;
  }
  body{font-family:'Noto Sans TC','Inter',sans-serif;background:#ffffff;color:#222;overflow-x:hidden}

  /* ===== Hero ===== */
  .hero{position:relative;min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;background:linear-gradient(135deg,#e8f4fd,#f0f4ff 40%,#fdf6e3);overflow:hidden}
  .hero::before{content:'';position:absolute;width:600px;height:600px;background:radial-gradient(circle,rgba(212,160,0,.1) 0%,transparent 70%);top:-200px;right:-200px;animation:pulse 8s ease-in-out infinite}
  .hero::after{content:'';position:absolute;width:500px;height:500px;background:radial-gradient(circle,rgba(224,72,72,.06) 0%,transparent 70%);bottom:-150px;left:-150px;animation:pulse 10s ease-in-out infinite reverse}
  @keyframes pulse{0%,100%{transform:translate(0,0)}50%{transform:translate(30px,-30px)}}

  .hero-badge{display:inline-flex;align-items:center;gap:.5rem;padding:.5rem 1.2rem;border:1px solid rgba(212,160,0,.3);border-radius:50px;font-size:.85rem;color:var(--gold);margin-bottom:1.5rem;backdrop-filter:blur(10px);background:rgba(212,160,0,.08);z-index:1}

  .hero h1{font-size:clamp(2rem,5vw,4.2rem);font-weight:900;background:linear-gradient(135deg,#b8860b,#c0392b,#b8860b);background-size:200% 200%;-webkit-background-clip:text;-webkit-text-fill-color:transparent;animation:shimmer 3s ease-in-out infinite;z-index:1;line-height:1.3}
  .hero h1 small{display:block;font-size:.45em;font-weight:500;background:linear-gradient(90deg,#555,#333,#555);-webkit-background-clip:text;-webkit-text-fill-color:transparent;letter-spacing:1px}
  @keyframes shimmer{0%,100%{background-position:0% 50%}50%{background-position:100% 50%}}

  .hero-sub{font-size:1.1rem;color:#666;margin-top:1rem;z-index:1;max-width:600px;line-height:1.7}
  .hero-sub em{color:#333;font-style:normal}

  .hero-meta{margin-top:2rem;display:flex;gap:1rem;flex-wrap:wrap;justify-content:center;z-index:1}
  .hero-meta span{padding:.4rem 1rem;border-radius:20px;font-size:.82rem;border:1px solid #ddd;color:#666}

  .scroll-cue{position:absolute;bottom:2rem;z-index:1;animation:bounce 2s infinite;color:var(--gold);font-size:1.8rem}
  @keyframes bounce{0%,100%{transform:translateY(0)}50%{transform:translateY(10px)}}

  /* ===== Nav ===== */
  nav{position:sticky;top:0;z-index:100;background:rgba(255,255,255,.95);backdrop-filter:blur(20px);border-bottom:1px solid rgba(212,160,0,.2);padding:.8rem 1.5rem;display:flex;justify-content:center;gap:.6rem;flex-wrap:wrap}
  nav a{text-decoration:none;color:#888;padding:.45rem 1rem;border-radius:20px;font-size:.88rem;border:1px solid transparent;transition:all .3s}
  nav a:hover,nav a.active{color:var(--gold);border-color:rgba(212,160,0,.4);background:rgba(212,160,0,.08)}

  /* ===== Section ===== */
  section{max-width:1100px;margin:0 auto;padding:4rem 2rem}
  .sec-tag{display:inline-block;padding:.3rem .8rem;border-radius:20px;font-size:.75rem;font-weight:600;letter-spacing:1px;text-transform:uppercase;margin-bottom:.8rem}
  .sec-title{font-size:2.2rem;font-weight:900;margin-bottom:.3rem;color:#222}
  .sec-title small{font-size:.5em;color:#888;font-weight:500;display:block;margin-top:.3rem}

  /* ===== Intro Banner ===== */
  .intro-banner{background:linear-gradient(135deg,rgba(0,210,255,.08),rgba(168,85,247,.08));border:1px solid rgba(0,210,255,.2);border-radius:20px;padding:2rem;margin-bottom:3rem}
  .intro-banner p{color:#bbb;line-height:1.8;font-size:1rem}
  .intro-banner em{color:#fff;font-style:normal;font-weight:600}
  .intro-banner .en{margin-top:.5rem;color:#999;font-size:.95rem}

  /* ===== Timeline ===== */
  .timeline{position:relative;padding:2rem 0}
  .timeline::before{content:'';position:absolute;left:50%;top:0;bottom:0;width:3px;background:linear-gradient(to bottom,var(--cyan),var(--gold),var(--red),var(--green),var(--purple));transform:translateX(-50%);border-radius:3px;opacity:.4}

  .tl-item{position:relative;width:45%;padding:1.8rem;border-radius:18px;margin-bottom:2rem;transition:transform .3s,box-shadow .3s;opacity:0;transform:translateY(30px);overflow:visible}
  .tl-item.visible{opacity:1;transform:translateY(0);transition:opacity .6s,transform .6s}
  .tl-item:nth-child(odd){margin-left:4%}
  .tl-item:nth-child(even){margin-left:51%}
  .tl-item:hover{transform:translateY(-5px)!important;box-shadow:0 10px 30px rgba(0,0,0,.1)}

  .tl-item .dot{position:absolute;width:18px;height:18px;border-radius:50%;top:2rem;z-index:2}
  .tl-item:nth-child(odd) .dot{right:-40px}
  .tl-item:nth-child(even) .dot{left:-40px}

  .tl-fishing{background:linear-gradient(135deg,#e8f4fd,#d4ecfa);border:1px solid rgba(0,144,200,.2)}
  .tl-fishing .dot{background:var(--cyan);box-shadow:0 0 10px rgba(0,144,200,.3)}
  .tl-port{background:linear-gradient(135deg,#fdf3e0,#fae8c0);border:1px solid rgba(200,140,0,.2)}
  .tl-port .dot{background:#c88a00;box-shadow:0 0 10px rgba(200,140,0,.3)}
  .tl-industry{background:linear-gradient(135deg,#f3e8ff,#e8d5f9);border:1px solid rgba(124,58,237,.2)}
  .tl-industry .dot{background:var(--purple);box-shadow:0 0 10px rgba(124,58,237,.3)}
  .tl-finance{background:linear-gradient(135deg,#e6f9ef,#d0f0e0);border:1px solid rgba(26,154,82,.2)}
  .tl-finance .dot{background:var(--green);box-shadow:0 0 10px rgba(26,154,82,.3)}
  .tl-knowledge{background:linear-gradient(135deg,#fdf8e0,#faf0c0);border:1px solid rgba(180,140,0,.2)}
  .tl-knowledge .dot{background:var(--gold);box-shadow:0 0 10px rgba(180,140,0,.3)}

  .tl-img{width:100%;height:auto;max-height:250px;border-radius:12px;object-fit:contain;margin-bottom:.8rem;border:1px solid rgba(0,0,0,.08);background:#f0f0f0;display:block}
  .tl-img[src=""]{display:none}
  .tl-img-edit{position:absolute;top:8px;right:8px;width:30px;height:30px;border-radius:50%;background:rgba(0,0,0,.5);border:none;cursor:pointer;display:none;align-items:center;justify-content:center;font-size:.9rem;transition:all .2s;z-index:10;color:#fff}
  .tl-img-edit:hover{background:var(--gold);transform:scale(1.1)}
  .tl-example{background:rgba(0,0,0,.04);border-left:3px solid;border-radius:0 10px 10px 0;padding:.8rem 1rem;margin-top:.8rem;font-size:.88rem;line-height:1.7}
  .tl-example strong{display:block;margin-bottom:.3rem;font-size:.82rem;text-transform:uppercase;letter-spacing:1px}
  .tl-fishing .tl-example{border-color:var(--cyan);color:#555}
  .tl-port .tl-example{border-color:#c88a00;color:#555}
  .tl-industry .tl-example{border-color:var(--purple);color:#555}
  .tl-finance .tl-example{border-color:var(--green);color:#555}
  .tl-knowledge .tl-example{border-color:var(--gold);color:#555}
  .tl-funfact{display:inline-block;margin-top:.5rem;padding:.2rem .6rem;border-radius:8px;font-size:.78rem;background:rgba(212,160,0,.08);color:var(--gold);border:1px solid rgba(212,160,0,.2)}
  .tl-item h3{font-size:1.3rem;margin-bottom:.2rem;color:#222}
  .tl-item h3 small{font-size:.65em;color:#888;font-weight:400}
  .tl-item .zh{color:#444;line-height:1.7;font-size:.9rem;margin-top:.6rem}
  .tl-item .en{color:#444;line-height:1.7;font-size:.85rem;margin-top:.3rem}
  .tl-item .page-ref{display:inline-block;margin-top:.8rem;padding:.2rem .6rem;border-radius:12px;font-size:.7rem;background:rgba(0,0,0,.04);color:#999;border:1px solid #e0e0e0}

  /* ===== Flowchart ===== */
  .flowchart-box{background:#f8f9fa;border:1px solid #e0e0e0;border-radius:18px;padding:2.5rem;margin-top:2rem;text-align:center}
  .flowchart-box h3{font-size:1.2rem;color:var(--gold);margin-bottom:1.5rem}
  .flow-path{display:flex;align-items:center;justify-content:center;gap:.5rem;flex-wrap:wrap;padding:1rem 0}
  .flow-node{padding:.6rem 1.2rem;border-radius:12px;font-weight:700;font-size:.9rem;border:2px solid;background:#fff}
  .flow-arrow{font-size:1.5rem;color:#999}
  .fn-1{border-color:var(--cyan);color:var(--cyan);background:rgba(0,144,200,.06)}
  .fn-2{border-color:#c88a00;color:#c88a00;background:rgba(200,140,0,.06)}
  .fn-3{border-color:var(--purple);color:var(--purple);background:rgba(124,58,237,.06)}
  .fn-4{border-color:var(--green);color:var(--green);background:rgba(26,154,82,.06)}
  .fn-5{border-color:var(--gold);color:var(--gold);background:rgba(212,160,0,.06)}

  .fill-exercise{margin-top:1.5rem;padding:1.5rem;background:rgba(212,160,0,.05);border:1px dashed rgba(212,160,0,.35);border-radius:12px;text-align:left}
  .fill-exercise h4{color:var(--gold);font-size:.95rem;margin-bottom:.8rem}
  .fill-q{color:#555;line-height:1.8;font-size:.9rem}
  .fill-a{display:none;margin-top:1rem;padding-top:.8rem;border-top:1px solid #e0e0e0}
  .fill-a p{color:#666;font-size:.85rem;line-height:1.7}
  .reveal-btn{margin-top:.8rem;padding:.4rem 1rem;border:1px solid rgba(212,160,0,.35);border-radius:20px;background:transparent;color:var(--gold);cursor:pointer;font-size:.82rem;transition:all .3s}
  .reveal-btn:hover{background:rgba(212,160,0,.1)}

  /* ===== Five Pillars ===== */
  .pillars{display:flex;flex-direction:column;gap:1.5rem;margin-top:2rem}
  .pillar{border-radius:18px;padding:2rem;position:relative;overflow:hidden;transition:transform .3s,box-shadow .3s}
  .pillar:hover{transform:translateY(-6px);box-shadow:0 12px 35px rgba(0,0,0,.1)}
  .pillar .p-num{position:absolute;top:1.2rem;right:1.5rem;font-size:4rem;font-weight:900;opacity:.06;line-height:1;color:#333}
  .pillar .p-icon{font-size:2.5rem;margin-bottom:.8rem}
  .pillar-img{width:100%;height:auto;max-height:300px;border-radius:12px;object-fit:contain;margin-bottom:1rem;border:1px solid rgba(0,0,0,.08);background:#f0f0f0}
  .pillar h3{font-size:1.15rem;margin-bottom:.2rem;color:#222}
  .pillar h3 small{font-size:.6em;color:#888;font-weight:400;display:block}
  .pillar .divider{width:40px;height:3px;border-radius:3px;margin:.8rem 0}
  .pillar .zh-list{list-style:none;margin:.8rem 0}
  .pillar .zh-list li{position:relative;padding-left:1.2rem;color:#444;font-size:.92rem;line-height:1.8;margin-bottom:.3rem}
  .pillar .zh-list li::before{content:'';position:absolute;left:0;top:.55rem;width:6px;height:6px;border-radius:50%}
  .pillar .en-block{background:rgba(0,0,0,.04);border-radius:10px;padding:1rem;margin-top:.8rem}
  .pillar .en-block p{color:#666;font-size:.85rem;line-height:1.7}
  .pillar .en-block strong{color:#444}
  .pillar .en-list{list-style:none;padding:0;margin:0}
  .pillar .en-list li{position:relative;padding-left:1rem;color:#666;font-size:.85rem;line-height:1.7;margin-bottom:.5rem}
  .pillar .en-list li::before{content:'●';position:absolute;left:0;color:#aaa;font-size:.6rem;top:.35rem}

  .pillar-points{display:flex;flex-direction:column;gap:.6rem;margin:.8rem 0}
  .pillar-point{display:flex;flex-direction:column;gap:.3rem;padding:.8rem 1rem;border-radius:12px;background:rgba(0,0,0,.03);border:1px solid rgba(0,0,0,.05);position:relative}
  .pillar-point .pp-zh{font-size:.9rem;line-height:1.7;color:#444}
  .pillar-point .pp-zh strong{color:#333}
  .pillar-point .pp-en{font-size:.85rem;line-height:1.7;color:#444}
  .pillar-point .pp-en strong{color:#333}
  .pillar-point .pp-img{width:100%;max-height:250px;border-radius:10px;object-fit:contain;margin-top:.5rem;border:1px solid rgba(0,0,0,.08);background:#f8f8f8;display:none}
  .pillar-point .pp-img.has-img{display:block}
  .pp-img-btn{position:absolute;top:6px;right:6px;width:28px;height:28px;border-radius:50%;background:rgba(0,0,0,.06);border:1px solid rgba(0,0,0,.1);cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:.85rem;opacity:0;transition:all .2s;z-index:5}
  .pillar-point:hover .pp-img-btn{opacity:1}
  .pp-img-btn:hover{background:rgba(212,160,0,.15);border-color:var(--gold)}
  .pp-img-del{position:absolute;top:6px;right:40px;width:28px;height:28px;border-radius:50%;background:rgba(224,72,72,.08);border:1px solid rgba(224,72,72,.2);cursor:pointer;display:none;align-items:center;justify-content:center;font-size:.75rem;transition:all .2s;z-index:5}
  .pillar-point:hover .pp-img-del.show{display:flex}
  .pp-img-del:hover{background:rgba(224,72,72,.2)}

  /* ===== Image Insert Modal ===== */
  .img-modal-overlay{position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,.4);z-index:2000;display:none;align-items:center;justify-content:center}
  .img-modal-overlay.show{display:flex}
  .img-modal{background:#fff;border-radius:18px;padding:2rem;max-width:480px;width:90%;box-shadow:0 20px 60px rgba(0,0,0,.2);position:relative}
  .img-modal h3{font-size:1.1rem;color:#333;margin-bottom:1rem;text-align:center}
  .img-modal input[type="text"]{width:100%;padding:.7rem 1rem;border:1px solid #ddd;border-radius:10px;font-size:.9rem;margin-bottom:1rem;box-sizing:border-box}
  .img-modal input[type="text"]:focus{outline:none;border-color:var(--gold)}
  .img-modal .or-divider{text-align:center;color:#aaa;font-size:.8rem;margin-bottom:1rem;position:relative}
  .img-modal .or-divider::before,.img-modal .or-divider::after{content:'';position:absolute;top:50%;width:35%;height:1px;background:#e0e0e0}
  .img-modal .or-divider::before{left:0}
  .img-modal .or-divider::after{right:0}
  .img-modal .file-label{display:block;width:100%;padding:.7rem;border:2px dashed #ddd;border-radius:10px;text-align:center;color:#888;font-size:.88rem;cursor:pointer;transition:all .2s;margin-bottom:1rem}
  .img-modal .file-label:hover{border-color:var(--gold);color:var(--gold);background:rgba(212,160,0,.03)}
  .img-modal .file-label input{display:none}
  .img-modal .preview-box{width:100%;max-height:200px;overflow:hidden;border-radius:10px;margin-bottom:1rem;display:none;background:#f5f5f5;text-align:center}
  .img-modal .preview-box img{width:100%;max-height:200px;object-fit:contain}
  .img-modal .preview-box.show{display:block}
  .img-modal .modal-btns{display:flex;gap:.8rem;justify-content:flex-end}
  .img-modal .modal-btns button{padding:.5rem 1.2rem;border-radius:10px;font-size:.88rem;cursor:pointer;border:none;transition:all .2s}
  .img-modal .btn-cancel{background:#f0f0f0;color:#666}
  .img-modal .btn-cancel:hover{background:#e0e0e0}
  .img-modal .btn-confirm{background:var(--gold);color:#fff;font-weight:600}
  .img-modal .btn-confirm:hover{background:#b8860b}
  .p1 .pillar-point{border-left:3px solid var(--purple)}
  .p2 .pillar-point{border-left:3px solid var(--cyan)}
  .p3 .pillar-point{border-left:3px solid var(--green)}
  .p4 .pillar-point{border-left:3px solid #c88a00}
  .p5 .pillar-point{border-left:3px solid var(--red)}
  .pillar .pillar-example{background:rgba(0,0,0,.03);border-radius:10px;padding:.8rem 1rem;margin-top:.8rem;border-left:3px solid}
  .pillar .pillar-example p{font-size:.88rem;line-height:1.7;color:#555}
  .p1 .pillar-example{border-color:var(--purple)}
  .p2 .pillar-example{border-color:var(--cyan)}
  .p3 .pillar-example{border-color:var(--green)}
  .p4 .pillar-example{border-color:#c88a00}
  .p5 .pillar-example{border-color:var(--red)}
  .pillar .page-ref{display:inline-block;margin-top:.8rem;padding:.2rem .6rem;border-radius:12px;font-size:.7rem;background:rgba(0,0,0,.04);color:#999;border:1px solid #e0e0e0}

  .p1{background:linear-gradient(135deg,#f5f0ff,#ede5ff);border:1px solid rgba(124,58,237,.12)}
  .p1 .divider{background:var(--purple)}.p1 .zh-list li::before{background:var(--purple)}
  .p2{background:linear-gradient(135deg,#e8f4fd,#dceeff);border:1px solid rgba(0,144,200,.12)}
  .p2 .divider{background:var(--cyan)}.p2 .zh-list li::before{background:var(--cyan)}
  .p3{background:linear-gradient(135deg,#e8f9f0,#d8f2e5);border:1px solid rgba(26,154,82,.12)}
  .p3 .divider{background:var(--green)}.p3 .zh-list li::before{background:var(--green)}
  .p4{background:linear-gradient(135deg,#fdf6e8,#faf0d0);border:1px solid rgba(200,140,0,.12)}
  .p4 .divider{background:#c88a00}.p4 .zh-list li::before{background:#c88a00}
  .p5{background:linear-gradient(135deg,#fdf0f0,#fae5e5);border:1px solid rgba(224,72,72,.12)}
  .p5 .divider{background:var(--red)}.p5 .zh-list li::before{background:var(--red)}

  /* ===== Tax Table ===== */
  .tax-wrap{margin-top:1rem}
  .tax-table{width:100%;border-collapse:separate;border-spacing:0;border-radius:14px;overflow:hidden;background:#fff;border:1px solid #e0e0e0}
  .tax-table thead th{background:linear-gradient(135deg,#d4a000,#c0392b);color:#fff;padding:1rem;font-weight:700;font-size:.95rem;text-align:center}
  .tax-table tbody td{padding:.8rem 1rem;border-bottom:1px solid #eee;text-align:center;font-size:.9rem;color:#444}
  .tax-table tbody tr:last-child td{border-bottom:none}
  .tax-table tbody tr:hover{background:rgba(212,160,0,.04)}
  .tax-table .ti{font-size:1.5rem;display:block;margin-bottom:.2rem}

  /* ===== Stat Counters ===== */
  .stat-bar{display:flex;justify-content:center;gap:3rem;flex-wrap:wrap;margin:3rem 0}
  .stat-item{text-align:center;min-width:140px}
  .stat-num{font-size:3rem;font-weight:900;background:linear-gradient(135deg,#b8860b,#c0392b);-webkit-background-clip:text;-webkit-text-fill-color:transparent}
  .stat-label{color:#888;font-size:.85rem;margin-top:.2rem}

  /* ===== Metaphor ===== */
  .metaphor{background:linear-gradient(135deg,rgba(212,160,0,.06),rgba(224,72,72,.06));border:1px solid rgba(212,160,0,.2);border-radius:16px;padding:1.5rem 2rem;margin:2rem 0;position:relative;overflow:hidden}
  .metaphor::before{content:'💡';position:absolute;font-size:3.5rem;opacity:.12;top:-8px;right:-8px}
  .metaphor .mlabel{color:var(--gold);font-weight:700;font-size:.78rem;text-transform:uppercase;letter-spacing:2px;margin-bottom:.5rem}
  .metaphor p{font-size:1rem;line-height:1.8;color:#333}

  /* ===== Video ===== */
  .video-box{text-align:center;margin:3rem 0}
  .video-box a{display:inline-flex;align-items:center;gap:.5rem;padding:.8rem 2rem;border:2px solid var(--red);border-radius:50px;color:var(--red);text-decoration:none;font-weight:700;font-size:1rem;transition:all .3s}
  .video-box a:hover{background:var(--red);color:#fff;transform:scale(1.05)}

  /* ===== Footer ===== */
  footer{text-align:center;padding:3rem 2rem;color:#999;font-size:.82rem;border-top:1px solid #eee;margin-top:2rem}
  footer a{color:var(--gold);text-decoration:none}

  /* ===== Quiz ===== */
  .quiz-section{background:linear-gradient(135deg,#f8f9fa,#f0f2f5);border-radius:20px;padding:2.5rem;margin-top:2rem;border:1px solid #e0e0e0}
  .quiz-section h3{font-size:1.3rem;color:#333;margin-bottom:1.5rem;text-align:center}
  .quiz-item{background:#fff;border:1px solid #e8e8e8;border-radius:14px;padding:1.2rem 1.5rem;margin-bottom:1rem;cursor:pointer;transition:all .3s}
  .quiz-item:hover{border-color:var(--gold);box-shadow:0 4px 15px rgba(0,0,0,.06)}
  .quiz-item h4{font-size:.95rem;color:#333;margin-bottom:.3rem;display:flex;flex-direction:column;gap:.2rem}
  .quiz-item h4 .q-num{display:inline-flex;align-items:center;justify-content:center;width:26px;height:26px;border-radius:50%;background:var(--gold);color:#fff;font-size:.78rem;font-weight:700;flex-shrink:0}
  .quiz-options{display:flex;flex-direction:column;gap:.5rem;margin-top:.8rem}
  .quiz-opt{padding:.6rem .8rem;border-radius:8px;border:1px solid #e0e0e0;font-size:.85rem;color:#555;cursor:pointer;transition:all .2s;text-align:left}
  .quiz-opt:hover{border-color:var(--gold);background:rgba(212,160,0,.05)}
  .quiz-opt.selected{border-color:var(--gold);background:rgba(212,160,0,.1);color:#333;font-weight:600}
  .quiz-opt.correct{border-color:var(--green);background:rgba(46,204,113,.1);color:var(--green);font-weight:600}
  .quiz-opt.wrong{border-color:var(--red);background:rgba(224,72,72,.1);color:var(--red);font-weight:600}
  .quiz-feedback{display:none;margin-top:.8rem;padding:.8rem 1rem;border-radius:10px;font-size:.88rem;line-height:1.6}
  .quiz-feedback.show{display:block}
  .quiz-feedback.correct{background:rgba(46,204,113,.08);border:1px solid rgba(46,204,113,.2);color:#1a6b3a}
  .quiz-feedback.wrong{background:rgba(224,72,72,.08);border:1px solid rgba(224,72,72,.2);color:#a03030}
  .quiz-score{text-align:center;margin-top:1.5rem;padding:1.5rem;background:#fff;border-radius:14px;border:1px solid #e8e8e8}
  .quiz-score .score-num{font-size:2.5rem;font-weight:900;background:linear-gradient(135deg,var(--gold),var(--red));-webkit-background-clip:text;-webkit-text-fill-color:transparent}
  .quiz-reset{margin-top:1rem;padding:.5rem 1.5rem;border:2px solid var(--gold);border-radius:25px;background:transparent;color:var(--gold);font-weight:700;cursor:pointer;font-size:.9rem;transition:all .3s}
  .quiz-reset:hover{background:var(--gold);color:#fff}

  /* ===== Responsive ===== */
  @media(max-width:768px){
    .timeline::before{left:18px}
    .tl-item{width:82%!important;margin-left:45px!important}
    .tl-item .dot{left:-36px!important;right:auto!important}
    .stat-num{font-size:2rem}
    .hero h1{font-size:2rem}
    nav a{font-size:.78rem;padding:.35rem .7rem}
    section{padding:3rem 1rem}
    .flow-path{flex-direction:column}
    .flow-arrow{transform:rotate(90deg)}
  }

  /* ===== Highlight Pen ===== */
  .hl-toolbar{position:fixed;top:50%;right:20px;transform:translateY(-50%);z-index:999;display:flex;flex-direction:column;gap:6px;background:#fff;padding:10px 8px;border-radius:16px;box-shadow:0 4px 20px rgba(0,0,0,.12);border:1px solid #e0e0e0;transition:opacity .3s}
  .hl-toolbar.hidden{opacity:0;pointer-events:none}
  .hl-btn{width:36px;height:36px;border-radius:50%;border:2px solid transparent;cursor:pointer;transition:all .2s;display:flex;align-items:center;justify-content:center;font-size:1.1rem;background:#f5f5f5}
  .hl-btn:hover{transform:scale(1.15);box-shadow:0 2px 8px rgba(0,0,0,.15)}
  .hl-btn.active{border-color:#333;box-shadow:0 0 0 2px rgba(0,0,0,.1)}
  .hl-btn[data-color="yellow"]{background:#fff3b0}
  .hl-btn[data-color="green"]{background:#b0f5c1}
  .hl-btn[data-color="blue"]{background:#b0d4f5}
  .hl-btn[data-color="pink"]{background:#f5b0c8}
  .hl-btn[data-color="orange"]{background:#f5d4b0}
  .hl-btn[data-color="eraser"]{background:#f5f5f5}
  .hl-toggle{position:fixed;top:50%;right:20px;transform:translateY(-50%);z-index:1000;width:48px;height:48px;border-radius:50%;background:linear-gradient(135deg,var(--gold),var(--red));color:#fff;border:none;cursor:pointer;font-size:1.4rem;box-shadow:0 4px 15px rgba(0,0,0,.2);transition:all .3s;display:flex;align-items:center;justify-content:center}
  .hl-toggle:hover{transform:translateY(-50%) scale(1.1)}
  .hl-toggle.shift-right{right:80px}
  mark.hl-highlight{padding:2px 0;border-radius:3px;cursor:pointer;transition:background .2s}
  mark.hl-highlight:hover{filter:brightness(.9)}
  .hl-clear{font-size:.7rem;text-align:center;color:#999;cursor:pointer;padding:4px;border-radius:8px;background:#f5f5f5;border:1px solid #e0e0e0;transition:all .2s}
  .hl-clear:hover{background:#ffe0e0;color:var(--red)}
</style>
</head>
<body>

<!-- ==================== HERO ==================== -->
<section class="hero">
  <div class="hero-badge">🏫 加拿大神召會嘉智中學 | PAOC Ka Chi Secondary School</div>
  <h1>
    單元一 香港的營商環境
    <small>Unit 1 Business Environment of Hong Kong</small>
  </h1>
  <p class="hero-sub">
    香港的經濟狀況在過去數十年經歷了巨大的轉變，由最初的<em>漁港</em>逐步演變成<em>知識型經濟</em>。<br>
    <span style="color:#888">The economic situation of Hong Kong has changed significantly in past decades, evolving from a fishing village to a knowledge-based economy.</span>
  </p>
  <div class="hero-meta">
    <span>📚 中一級 F.1 Junior Commerce</span>
    <span>📖 Ver2</span>
  </div>
  <div class="scroll-cue">↓</div>
</section>

<!-- ==================== NAV ==================== -->
<nav id="mainNav">
  <a href="#objectives">🎯 學習目標</a>
  <a href="#timeline">📜 五個階段</a>
  <a href="#flowchart">🔄 路徑圖</a>
  <a href="#pillars">🏛️ 五大基石</a>
  <a href="#pillarindustries">📊 四大支柱及六大產業</a>
  <a href="#video">🎬 教學影片</a>
  <a href="#quiz">📝 小測試</a>
</nav>

<!-- ==================== OBJECTIVES ==================== -->
<section id="objectives">
  <span class="sec-tag" style="background:rgba(212,160,0,.1);color:var(--gold)">Learning Objectives</span>
  <h2 class="sec-title">學習目標 <small>Learning Objectives</small></h2>

  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1.2rem;margin-top:1.5rem">
    <div style="background:linear-gradient(135deg,#f8f9fa,#f0f2f5);border:1px solid rgba(212,160,0,.2);border-radius:14px;padding:1.5rem">
      <div style="font-size:2rem;margin-bottom:.5rem">①</div>
      <p style="color:#333;font-size:1rem;line-height:1.6"><strong>了解香港經濟的發展過程</strong></p>
      <p style="color:#888;font-size:.88rem;margin-top:.3rem">Understand the economic development of Hong Kong</p>
    </div>
    <div style="background:linear-gradient(135deg,#f8f9fa,#f0f2f5);border:1px solid rgba(0,144,200,.2);border-radius:14px;padding:1.5rem">
      <div style="font-size:2rem;margin-bottom:.5rem">②</div>
      <p style="color:#333;font-size:1rem;line-height:1.6"><strong>了解香港經濟的特徵</strong></p>
      <p style="color:#888;font-size:.88rem;margin-top:.3rem">Understand the characteristics of the Hong Kong economy</p>
    </div>
    <div style="background:linear-gradient(135deg,#f8f9fa,#f0f2f5);border:1px solid rgba(26,154,82,.2);border-radius:14px;padding:1.5rem">
      <div style="font-size:2rem;margin-bottom:.5rem">③</div>
      <p style="color:#333;font-size:1rem;line-height:1.6"><strong>認識香港四大經濟支柱及六大產業</strong></p>
      <p style="color:#888;font-size:.88rem;margin-top:.3rem">Understand the Four Pillars and Six Industries in Hong Kong</p>
      <p style="color:#aaa;font-size:.78rem;margin-top:.3rem">（註：本單元主要涵蓋目標 1 與 2）</p>
    </div>
  </div>
</section>

<!-- ==================== TIMELINE ==================== -->
<section id="timeline">
  <span class="sec-tag" style="background:rgba(0,144,200,.1);color:var(--cyan)">Economic Development</span>
  <h2 class="sec-title">香港經濟發展的五個階段 <small>The Five Stages of Hong Kong's Economic Development</small></h2>

  <div class="timeline">

    <!-- 1. 漁港 -->
    <div class="tl-item tl-fishing">
      <div class="dot"></div>
      <img class="tl-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/Sampans_in_Hong_Kong.jpg/960px-Sampans_in_Hong_Kong.jpg" alt="香港昔日漁港" loading="lazy">
      <div class="tl-era">🎣</div>
      <h3 style="color:var(--cyan)">漁港 <small>Fishing Village</small></h3>
      <p class="zh">● 香港位處珠江三角洲，原本是一個漁港。</p>
      <p class="en">● Hong Kong is located within the Pearl River Delta. Originally a fishing village.</p>
      <div class="tl-example">
        <strong> example 生動解說：</strong>
        想像一下，數百年前嘅香港，到處都係漁船同漁網，漁民每日日出捕魚、日落歸家。香港仔、筲箕灣、長洲呢啲地方，到今日都仲保留住漁村嘅痕跡！
      </div>
      <span class="tl-funfact"> fish 漁民至今仍喺香港仔避風塘生活緊</span>
    </div>

    <!-- 2. 轉口港 -->
    <div class="tl-item tl-port">
      <div class="dot"></div>
      <img class="tl-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/China_unknown_artist_-_late_1850s_-_Hong_Kong_harbour_-_oil_on_canvas_IMG_9403_Museum_of_Asian_Civilisation.jpg/960px-China_unknown_artist_-_late_1850s_-_Hong_Kong_harbour_-_oil_on_canvas_IMG_9403_Museum_of_Asian_Civilisation.jpg" alt="維多利亞港 - 轉口港" loading="lazy">
      <div class="tl-era">⚓</div>
      <h3 style="color:#ffa500">轉口港 <small>Entrepot</small></h3>
      <p class="zh">● 1840年，鴉片戰爭爆發。<br>● 1841年英國接管後，在香港實行自由港政策。<br>● 自這時始，香港發展成一轉口港。</p>
      <p class="en">● In 1840, the First Anglo-Chinese War (or First Opium War) broke out.<br>● In 1841, the British government took possession of Hong Kong and adopted a free trade port policy.<br>● Since then, Hong Kong developed as an entrepot.</p>
      <div class="tl-example">
        <strong> example 生動解說：</strong>
        轉口港就好似一個「中間人」——世界各地嘅貨物經香港轉運去其他地方，香港賺取「過路費」。就好似你喺商場買嘢，商場唔使自己生產，靠收租金同管理費賺錢！
      </div>
      <span class="tl-funfact"> ship 當時維多利亞港擠滿來自世界各地嘅商船</span>
    </div>

    <!-- 3. 工業中心 -->
    <div class="tl-item tl-industry">
      <div class="dot"></div>
      <img class="tl-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Garment_Plant_%285345488574%29.jpg/960px-Garment_Plant_%285345488574%29.jpg" alt="香港1960年代工廠流水線" loading="lazy">
      <div class="tl-era">🏭</div>
      <h3 style="color:var(--purple)">工業中心 <small>Industrial Centre</small></h3>
      <p class="zh">● 1946年，中國發生內戰。很多中國人逃難到香港。不少中國企業家亦帶同資金、技術、設備，移居香港。<br>● 1953年，韓戰爆發，聯合國向中國內地實施禁運。香港不能再成為一轉口港，於是轉為發展製造業，製造業成為香港最普及的行業。<br>● 自1970年代至1990年代期間，香港、韓國、臺灣及新加坡被譽為「亞洲四小龍」。</p>
      <p class="en">● In 1946, civil war broke out in China. A lot of Chinese businessmen moved to Hong Kong with capital, technology, and equipment.<br>● In 1953, the Korean War broke out. The United Nations imposed an embargo on China. Hong Kong stopped its entrepot trade and developed its own manufacturing industries.<br>● Since the 1970s to 1990s, Hong Kong, South Korea, Taiwan, and Singapore were named the "Four Asian Tigers" or "Four Asian Little Dragons".</p>
      <div class="tl-example">
        <strong> example 生動解說：</strong>
        韓戰禁運令香港冇得做轉口，但香港人「死里逃生」——工廠由無到有，由細到大。觀塘、九龍灣到處都係紡織廠、塑膠廠、電子廠。當時香港製造嘅塑膠花、玩具、鐘錶行銷全世界！1970年代更與韓國、台灣、新加坡並稱「亞洲四小龍」，經濟飛速發展。
      </div>
      <span class="tl-funfact"> factory 1960年代香港係全球最大嘅紡織品出口地之一</span>
    </div>

    <!-- 4. 國際貿易及金融中心 -->
    <div class="tl-item tl-finance">
      <div class="dot"></div>
      <img class="tl-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b3/HK_International_Finance_Centre_200809.jpg/960px-HK_International_Finance_Centre_200809.jpg" alt="香港國際金融中心IFC" loading="lazy">
      <div class="tl-era">🌐</div>
      <h3 style="color:var(--green)">國際貿易及金融中心 <small>International Trade & Financial Centre</small></h3>
      <p class="zh">● 1978年，中國實行改革開放政策，香港製造業工廠北移至內地。<br>● 香港利用此契機，重新發展轉口貿易。這帶動了金融、銀行及其他服務業（如旅遊業）的蓬勃發展。<br>● 到了1990年代，香港已成功轉型為國際貿易及金融中心。<br>● 其後，香港更集中推動服務性行業的發展。</p>
      <p class="en">● In 1978, China adopted the reform and open-door policy. Many Hong Kong factories moved to mainland China.<br>● Hong Kong took this opportunity to revive its entrepot trade, which boosted its banking, financial, and other service industries (e.g., tourism).<br>● During the 1990s, Hong Kong successfully developed into an international trade and financial centre.<br>● Later, Hong Kong further developed its services industries.</p>
      <div class="tl-example">
        <strong> example 生動解說：</strong>
        1978年中國改革開放，香港工廠紛紛搬到深圳、東莞等內地城市生產。香港就轉型做「大腦」——負責設計、行銷、金融、物流。中環、金鐘一帶變成了銀行同跨国公司嘅集中地，匯豐、中銀、渣打等大行林立，香港成為亞洲金融心臟！
      </div>
      <span class="tl-funfact"> bank 1990年代香港已係全球第三大金融中心</span>
    </div>

    <!-- 5. 知識型經濟 -->
    <div class="tl-item tl-knowledge">
      <div class="dot"></div>
      <img class="tl-img" src="https://gia.info.gov.hk/general/202608/27/P2026082700427_photo_1337226.jpg" alt="全民AI普惠計劃啟動禮" loading="lazy">
      <div class="tl-era">💡</div>
      <h3 style="color:var(--gold)">知識型經濟 <small>A Knowledge-based Economy</small></h3>
      <p class="zh">● 注重運用知識、高科技、創意和設計來發展經濟。</p>
      <p class="en">● Emphasises the use of knowledge, high technologies, creativity, and design to develop the economy.</p>
      <div class="tl-example">
        <strong> example 生動解說：</strong>
        今日嘅香港唔止做金融，仲搞科技！科學園、數碼港培育咗唔少初創企業，涵蓋人工智能、生物醫學、微電子等領域。好似大疆創新（DJI）就係從香港起步，而家係全球無人機霸主！香港正朝「創科之都」進發。
      </div>
      <span class="tl-funfact"> rocket 科學園已有超過1,400間科技企業進駐</span>
    </div>

  </div>

</section>
<section id="flowchart">
  <div class="flowchart-box">
    <h3>🔄 香港經濟轉變軌跡 | Path of Hong Kong's Economic Evolution</h3>
    <div class="flow-path">
      <div class="flow-node fn-1">漁港<br><small>Fishing Village</small></div>
      <span class="flow-arrow">→</span>
      <div class="flow-node fn-2">轉口港<br><small>Entrepot</small></div>
      <span class="flow-arrow">→</span>
      <div class="flow-node fn-3">工業中心<br><small>Industrial Centre</small></div>
      <span class="flow-arrow">→</span>
      <div class="flow-node fn-4">國際貿易及金融中心<br><small>International Trade & Financial Centre</small></div>
      <span class="flow-arrow">→</span>
      <div class="flow-node fn-5">知識型經濟<br><small>Knowledge-based Economy</small></div>
    </div>

    <div class="fill-exercise">
      <h4>📝 學生筆記與填空練習 | Student's Notes & Blanks</h4>
      <p class="fill-q">學生可利用以下路徑圖進行複習與填空練習：<br>
      Students can use the following flowchart to review the economic path:</p>
      <p class="fill-q" style="margin-top:.5rem">
        漁港 (<em>Fishing Village</em>) → ① <u>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</u> → ② <u>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</u> → ③ <u>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</u> → ④ <u>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</u>
      </p>
      <button class="reveal-btn" onclick="document.getElementById('answerKey').style.display=document.getElementById('answerKey').style.display==='block'?'none':'block'">顯示答案 | Show Answers</button>
      <div id="answerKey" class="fill-a">
        <p>
          <strong>答案提示 / Answer Key:</strong><br>
          ① 轉口港 (<em>Entrepot</em>)<br>
          ② 工業中心 (<em>Industrial Centre</em>)<br>
          ③ 國際貿易及金融中心 (<em>International Trade and Financial Centre</em>)<br>
          ④ 知識型經濟 (<em>Knowledge-based economy</em>)
        </p>
      </div>
    </div>
  </div>
</section>

<!-- ==================== FIVE PILLARS ==================== -->
<section id="pillars">
  <span class="sec-tag" style="background:rgba(124,58,237,.1);color:var(--purple)">Characteristics</span>
  <h2 class="sec-title">了解香港經濟的特徵 <small>Understand the Characteristics of the Hong Kong Economy</small></h2>
  <p style="color:#666;margin-top:.5rem;line-height:1.7">
    香港擁有獨特的營商環境，其經濟特徵可歸納為以下五大基石：<br>
    <em style="color:#999">Hong Kong has a unique business environment. The characteristics of its economy can be summarized in the following five pillars:</em>
  </p>

  <div class="pillars">

    <!-- Pillar 1 -->
    <div class="pillar p1">
      <span class="p-num">1</span>
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d6/International_Trade_What_Keeps_Hong_Kong_Busy_%285801360783%29.jpg/960px-International_Trade_What_Keeps_Hong_Kong_Busy_%285801360783%29.jpg" alt="自由貿易港口" loading="lazy">
      <div class="p-icon">🅰️</div>
      <h3>資本主義經濟及自由市場經濟 <small>Capitalist Economy and Free Market Economy</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">🏛️ <strong>政府干預少：</strong>政府甚少干預市場。</div>
          <div class="pp-en">Minimal Intervention: The market is free. There is little government intervention in the market.</div>
        </div>
        <div class="pillar-point">
          <div class="pp-zh">💰 <strong>資金自由進出：</strong>資金可從不同地方流入或流出香港，不設外匯管制。</div>
          <div class="pp-en">Free Flow of Capital: Capital from different places can flow freely into and out of Hong Kong. There is no exchange control.</div>
        </div>
        <div class="pillar-point">
          <div class="pp-zh">🚢 <strong>無貿易障礙：</strong>香港不設貿易障礙，大部分進出口貨品均不須繳付關稅。</div>
          <div class="pp-en">No Trade Barriers: There are no trade barriers in Hong Kong. Most goods are free of tariff (tax).</div>
        </div>
      </div>
      <div class="pillar-example">
        <p> 生動解說：香港宛如一個「經濟樂園」——無需排隊、無需會員證，任何人都可前來經商！政府不會規定商品價格或僱員數量，資金可自由進出。猶如一座沒有圍牆的商場，人人自由進出，難怪眾多外國企業選擇香港作為亞洲總部！</p>
      </div>
      <span class="page-ref">P.1.4 (中/英)</span>
    </div>

    <!-- Pillar 2 -->
    <div class="pillar p2">
      <span class="p-num">2</span>
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/HK_Hung_Hum_Container_Pier_02.JPG/960px-HK_Hung_Hum_Container_Pier_02.JPG" alt="貨櫃碼頭 - 外向型經濟" loading="lazy">
      <div class="p-icon">🅱️</div>
      <h3>外向型經濟 <small>Externally-oriented Economy</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">📦 <strong>出口貿易主導：</strong>香港是以出口貿易為主導的經濟模式。</div>
          <div class="pp-en">Export-led Mode: Export trade contributes largely to the economy.</div>
        </div>
        <div class="pillar-point">
          <div class="pp-zh">🌍 <strong>受外在環境影響：</strong>由於出口貿易是香港經濟收入的重要來源，因此其他國家的經濟狀況會直接影響香港的經濟。當香港主要貿易伙伴的經濟下滑時，便可能會拖緩香港的經濟發展；反之亦然。</div>
          <div class="pp-en">Vulnerability to External Conditions: Since export trade is the main source of income, Hong Kong's economic development is directly affected by the economic conditions of other countries. If trading partners suffer from an economic downturn, it will hinder Hong Kong's economic development, and vice versa.</div>
        </div>
      </div>
      <div class="pillar-example">
        <p> 生動解說：香港猶如一艘「順風車」——美國經濟向好，香港跟隨向好；中國經濟起飛，香港受惠最大。但反過來，2008年美國金融海嘯爆發，香港出口即時大跌。可見香港經濟好壞，很大程度取決於貿易夥伴的表現！</p>
      </div>
      <span class="page-ref">P.1.4 (中/英)</span>
    </div>

    <!-- Pillar 3 -->
    <div class="pillar p3">
      <span class="p-num">3</span>
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b3/HK_International_Finance_Centre_200809.jpg/960px-HK_International_Finance_Centre_200809.jpg" alt="國際金融中心 - 服務業" loading="lazy">
      <div class="p-icon">🅲</div>
      <h3>服務性行業為主 <small>Service-oriented Economy</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">📈 <strong>服務業崛起：</strong>自1980年代起，製造業開始式微，服務性行業對香港經濟發展變得愈來愈重要。</div>
          <div class="pp-en">Rise of Services: The service industry has become increasingly important to Hong Kong's economic development since the decline of the manufacturing industry in the 1980s.</div>
        </div>
        <div class="pillar-point">
          <div class="pp-zh">👥 <strong>高就業佔比：</strong>香港有超過八成（80%）的勞動人口從事服務性行業。</div>
          <div class="pp-en">High Employment Share: Over 80% of Hong Kong's working population work in the services industry.</div>
        </div>
      </div>
      <div class="pillar-example">
        <p> 生動解說：昔日香港是「世界工廠」，如今已蛻變為「世界服務員」！每10名勞動者中有8人從事服務業——銀行、旅遊、零售、物流、教育、醫療等領域無所不包。猶如一間公司由「生產部」轉型為「客服部」，人力需求截然不同！</p>
      </div>
      <span class="page-ref">P.1.4 (中/英)</span>
    </div>

    <!-- Pillar 4 -->
    <div class="pillar p4">
      <span class="p-num">4</span>
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/HK_Mong_Kok_Fa_Yuen_Street_evening_food_shop_Sept-2012.JPG/960px-HK_Mong_Kok_Fa_Yuen_Street_evening_food_shop_Sept-2012.JPG" alt="旺角街頭 - 中小型企業" loading="lazy">
      <div class="p-icon">🅳</div>
      <h3>中小型企業為主 <small>Predominance of SMEs</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">🏢 <strong>數量龐大：</strong>香港大約有 <strong>34萬</strong> 家中小型企業，佔香港整體商業社會超過 <strong>98%</strong>。</div>
          <div class="pp-en">Massive Quantity: There are more than 300,000 (approx. 340,000) SMEs in Hong Kong, making up over 98% of Hong Kong's business units.</div>
        </div>
        <div class="pillar-point">
          <div class="pp-zh">⚡ <strong>高效率與敏銳度：</strong>本港中小型企業的效率一般較高，並擁有敏銳的商業觸覺。</div>
          <div class="pp-en">High Efficiency: They are highly efficient and cost-effective.</div>
        </div>
      </div>
      <div class="pillar-example">
        <p> 生動解說：香港商業世界並非「大象」當道，而是「螞蟻兵團」！98%均為中小企，如街邊茶餐廳、麵包店、設計工作室等，規模雖小但反應迅速、靈活多變。一間店舖可能僅僱用3至5人，但決策速度比大企業快十倍！</p>
      </div>
      <span class="page-ref">P.1.4 (中/英)</span>
    </div>

    <!-- Pillar 5 -->
    <div class="pillar p5">
      <span class="p-num">5</span>
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Aerial_view_of_the_Hong_Kong_Convention_and_Exhibition_Centre.jpg/960px-Aerial_view_of_the_Hong_Kong_Convention_and_Exhibition_Centre.jpg" alt="會展中心 - 低稅率吸引企業" loading="lazy">
      <div class="p-icon">🅴</div>
      <h3>簡單稅制和低稅率 <small>Simple Tax System and Low Tax Rate</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">📋 <strong>奉行低稅：</strong>特區政府一向奉行簡單稅制及低稅率。</div>
          <div class="pp-en">Tax Policy: The HKSAR Government adopts a simple tax system and low tax rate.</div>
        </div>
        <div class="pillar-point">
          <div class="pp-zh">💷 <strong>三大直接稅：</strong>香港只有三種直接稅 —— <strong>利得稅</strong>、<strong>薪俸稅</strong>及<strong>物業稅</strong>。</div>
          <div class="pp-en">Three Direct Taxes: There are only three types of direct taxes: Profit Tax, Salary Tax, and Property Tax.</div>
        </div>
        <div class="pillar-point">
          <div class="pp-zh">🌐 <strong>國際優勢：</strong>香港的稅率比歐美及許多亞洲國家都要低。</div>
          <div class="pp-en">Competitive Edge: Hong Kong's tax rate is much lower than that of the USA, European countries, and many other Asian countries.</div>
        </div>
      </div>
      <div class="pillar-example">
        <p> 生動解說：香港僅徵收三種稅——公司盈利繳利得稅、僱員繳薪俸稅、業主收租繳物業稅。無消費稅、無資本增值稅、無遺產稅！相比美國需填報數十頁稅表，香港報稅簡便至「一張紙便可完成」。難怪眾多跨國企業表示：「到香港開公司，節省稅務與時間！」</p>
      </div>

      <div class="tax-wrap">
        <table class="tax-table">
          <thead><tr><th>稅種 Tax</th><th>對象 Target</th><th>說明 Description</th></tr></thead>
          <tbody>
            <tr>
              <td><span class="ti">🏢</span><strong>利得稅</strong><br><small>Profit Tax</small></td>
              <td>公司利潤<br><small>Corporate Profits</small></td>
              <td>企業在香港賺取的利潤需繳稅<br><small>Profits earned by companies in HK</small></td>
            </tr>
            <tr>
              <td><span class="ti">👤</span><strong>薪俸稅</strong><br><small>Salary Tax</small></td>
              <td>個人入息<br><small>Personal Income</small></td>
              <td>個人在香港的薪金收入需繳稅<br><small>Salary income earned in HK</small></td>
            </tr>
            <tr>
              <td><span class="ti">🏠</span><strong>物業稅</strong><br><small>Property Tax</small></td>
              <td>租金收入<br><small>Rental Income</small></td>
              <td>業主從物業收取的租金需繳稅<br><small>Rental income from property in HK</small></td>
            </tr>
          </tbody>
        </table>
      </div>

      <span class="page-ref">P.1.4 - P.1.5 (中/英)</span>
    </div>

  </div>

  <!-- Stat Counters -->
  <div class="stat-bar">
    <div class="stat-item">
      <div class="stat-num" data-target="340000">0</div>
      <div class="stat-label">中小型企業<br><small>SMEs</small></div>
    </div>
    <div class="stat-item">
      <div class="stat-num" data-target="98">0</div>
      <div class="stat-label">% 商業佔比<br><small>% of Business Units</small></div>
    </div>
    <div class="stat-item">
      <div class="stat-num" data-target="80">0</div>
      <div class="stat-label">% 服務業人口<br><small>% in Services</small></div>
    </div>
    <div class="stat-item">
      <div class="stat-num" data-target="3">0</div>
      <div class="stat-label">種直接稅<br><small>Direct Taxes</small></div>
    </div>
  </div>

  <div class="metaphor">
    <div class="mlabel">生動比喻 | Vivid Metaphor</div>
    <p>一個彈丸之地，創造了<strong>34萬間</strong>中小企、容納了<strong>80%</strong>服務業人口，仲用<strong>3種</strong>稅項管理整個經濟體——香港，真係「細細粒，猛料」！</p>
    <p style="color:#666;font-size:.9rem;margin-top:.3rem">A tiny land that created 340,000 SMEs, employs 80% in services, and runs its economy with just 3 taxes — Hong Kong is truly small but mighty!</p>
  </div>
</section>

<!-- ==================== FOUR PILLARS & SIX INDUSTRIES ==================== -->
<section id="pillarindustries">
  <span class="sec-tag" style="background:rgba(212,160,0,.1);color:var(--gold)">Four Pillars & Six Industries</span>
  <h2 class="sec-title">四大經濟支柱及六大優勢產業 <small>Four Pillar Industries & Six Industries with Advantages</small></h2>

  <!-- 四大經濟支柱 -->
  <div class="pillar-grid" style="margin-top:2rem">
    <div class="pillar" style="border-top:4px solid #d4a000">
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/HKIFC_and_Central_dusk_201901.jpg/960px-HKIFC_and_Central_dusk_201901.jpg" alt="金融服務業 - 國際金融中心" loading="lazy">
      <div class="p-icon">💰</div>
      <h3>金融服務業 <small>Financial Services</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">香港是全球主要的金融中心之一，提供銀行、證券、保險及資產管理等服務。</div>
          <div class="pp-en">Hong Kong is one of the world's leading financial centres, offering banking, securities, insurance, and asset management services.</div>
        </div>
      </div>
    </div>

    <div class="pillar" style="border-top:4px solid #e04848">
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Symphony_of_Lights_%28Victoria_Harbour%29_201902.jpg/960px-Symphony_of_Lights_%28Victoria_Harbour%29_201902.jpg" alt="旅遊業 - 維港幻彩詠香江" loading="lazy">
      <div class="p-icon">✈️</div>
      <h3>旅遊業 <small>Tourism</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">四大支柱中規模最小的支柱，但增長迅速，創造了大量就業機會。</div>
          <div class="pp-en">The smallest pillar in terms of GDP, but grew rapidly and generated many new jobs.</div>
        </div>
      </div>
    </div>

    <div class="pillar" style="border-top:4px solid #0090c8">
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/HK_Hung_Hum_Container_Pier_02.JPG/960px-HK_Hung_Hum_Container_Pier_02.JPG" alt="貿易及物流業 - 貨櫃碼頭" loading="lazy">
      <div class="p-icon">🚢</div>
      <h3>貿易及物流業 <small>Trading and Logistics</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">四大支柱中規模最大的支柱，在GDP和就業方面均居首位。</div>
          <div class="pp-en">The largest pillar industry in GDP and employment.</div>
        </div>
      </div>
    </div>

    <div class="pillar" style="border-top:4px solid #50b848">
      <img class="pillar-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Central_Plaza%2C_Hong_Kong.jpg/960px-Central_Plaza%2C_Hong_Kong.jpg" alt="專業服務 - 中環商廈" loading="lazy">
      <div class="p-icon">💼</div>
      <h3>專業服務及其他工商業支援服務 <small>Professional & Producer Services</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">包括法律、會計、管理顧問等專業服務，為工商業提供支援。</div>
          <div class="pp-en">Includes legal, accounting, and management consulting services that support business operations.</div>
        </div>
      </div>
    </div>
  </div>

  <!-- 六大優勢產業 -->
  <h3 style="margin-top:3rem;font-size:1.2rem;color:#333;text-align:center">六大優勢產業 <small>Six Industries with Clear Advantages</small></h3>
  <p style="text-align:center;color:#666;font-size:.9rem;margin-bottom:1.5rem">政府推動的六項具備優勢的產業 / Six industries with competitive advantages promoted by the government</p>

  <div class="pillar-grid">
    <div class="pillar" style="border-top:4px solid #9b59b6">
      <img class="pillar-img" src="cultural.jpg" alt="文化及創意產業 - M+博物館" loading="lazy">
      <div class="p-icon">🎨</div>
      <h3>文化及創意產業 <small>Cultural & Creative Industries</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">六大產業中唯一在本地生產總值所佔比重錄得顯著增長，且僱用最多從業員的產業。</div>
          <div class="pp-en">The only industry among the six to achieve significant GDP growth and employ the most people.</div>
        </div>
      </div>
    </div>

    <div class="pillar" style="border-top:4px solid #3498db">
      <img class="pillar-img" src="education.jpg" alt="教育產業 - 中文大學" loading="lazy">
      <div class="p-icon">📚</div>
      <h3>教育產業 <small>Education Services</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">包括各級教育及培訓服務，為本港及海外學生提供教育。</div>
          <div class="pp-en">Includes education and training services at various levels for local and overseas students.</div>
        </div>
      </div>
    </div>

    <div class="pillar" style="border-top:4px solid #e74c3c">
      <img class="pillar-img" src="medical.jpg" alt="醫療產業 - 養和醫院" loading="lazy">
      <div class="p-icon">🏥</div>
      <h3>醫療產業 <small>Medical Services</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">提供醫療及相關服務，吸引了大量海外病人來港就醫。</div>
          <div class="pp-en">Provides medical and related services, attracting a large number of overseas patients to Hong Kong.</div>
        </div>
      </div>
    </div>

    <div class="pillar" style="border-top:4px solid #27ae60">
      <img class="pillar-img" src="environmental.jpg" alt="環保產業 - 綠色建築" loading="lazy">
      <div class="p-icon">🌱</div>
      <h3>環保產業 <small>Environmental Industries</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">涵蓋廢物管理、綠色建築及環境諮詢等領域。</div>
          <div class="pp-en">Covers waste management, green building, and environmental consulting services.</div>
        </div>
      </div>
    </div>

    <div class="pillar" style="border-top:4px solid #f39c12">
      <img class="pillar-img" src="testing.jpg" alt="檢測及認證產業 - STC實驗室" loading="lazy">
      <div class="p-icon">🔬</div>
      <h3>檢測及認證產業 <small>Testing & Certification</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">提供產品檢測及認證服務，確保符合國際標準。</div>
          <div class="pp-en">Provides product testing and certification services to ensure compliance with international standards.</div>
        </div>
      </div>
    </div>

    <div class="pillar" style="border-top:4px solid #1abc9c">
      <img class="pillar-img" src="innovation.jpg" alt="創新科技活動 - 數碼港" loading="lazy">
      <div class="p-icon">💡</div>
      <h3>創新科技活動 <small>Innovation & Technology</small></h3>
      <div class="divider"></div>
      <div class="pillar-points">
        <div class="pillar-point">
          <div class="pp-zh">包括公私營科研機構進行的研究及發展活動。</div>
          <div class="pp-en">Includes research and development activities conducted by public and private scientific research institutions.</div>
        </div>
      </div>
    </div>
  </div>

  <div class="metaphor" style="margin-top:2rem">
    <div class="mlabel">教學重點 | Key Takeaway</div>
    <p>六大優勢產業在本地生產總值（GDP）所佔的比重依然不高，仍然不足以成為香港的新經濟支柱。香港還未能成功轉型，仍需要依賴四大支柱來維持本港的經濟發展。</p>
    <p style="color:#666;font-size:.9rem;margin-top:.3rem">The value of the Six Industries remains a small proportion of GDP and cannot replace the pillars yet. Hong Kong has not successfully transformed and still relies heavily on the Four Pillars.</p>
  </div>
  <span class="page-ref">P.1.14 (中/英)</span>
</section>

<!-- ==================== VIDEO ==================== -->
<section id="video">
  <span class="sec-tag" style="background:rgba(224,72,72,.1);color:var(--red)">Teaching Video</span>
  <h2 class="sec-title">教學影片 <small>Teaching Video</small></h2>

  <div style="margin-top:1.5rem">
    <div class="video-box" style="margin:0">
      <div style="background:linear-gradient(135deg,#e8f4fd,#dceeff);border-radius:14px;padding:2rem;border:1px solid rgba(0,144,200,.15);max-width:500px;margin:0 auto">
        <div style="font-size:2.5rem;margin-bottom:.8rem">🏦</div>
        <h4 style="color:#333;font-size:1rem;margin-bottom:.5rem">香港開埠以來，如何發展成爲亞洲金融中心？</h4>
        <p style="color:#888;font-size:.85rem;line-height:1.6;margin-bottom:1rem">香港經濟發展中的兩個奇蹟轉折</p>
        <a href="https://www.youtube.com/watch?v=0SJF2nAF9Fw" target="_blank" style="display:inline-flex;align-items:center;gap:.5rem;padding:.6rem 1.5rem;border:2px solid var(--cyan);border-radius:50px;color:var(--cyan);text-decoration:none;font-weight:700;font-size:.9rem;transition:all .3s">
          ▶ 點此觀看 | Watch
        </a>
      </div>
    </div>
  </div>
</section>

<!-- ==================== QUIZ ==================== -->
<section id="quiz">
  <span class="sec-tag" style="background:rgba(212,160,0,.1);color:var(--gold)">Quiz</span>
  <h2 class="sec-title">小測試 <small>Quick Quiz</small></h2>

  <div class="quiz-section">
    <h3>📝 測試你對香港營商環境嘅認識！<br><small>Test Your Knowledge of Hong Kong's Business Environment!</small></h3>

    <div class="quiz-item" data-answer="2">
      <h4><span class="q-num">1</span> <div>香港原本是一個甚麼地方？</div><div style="font-weight:400;font-size:.85rem;color:#666">What was Hong Kong originally?</div></h4>
      <div class="quiz-options">
        <div class="quiz-opt" data-idx="0"><div>A. 農業中心</div><div style="font-size:.78rem;color:#888">Agricultural Centre</div></div>
        <div class="quiz-opt" data-idx="1"><div>B. 工業城市</div><div style="font-size:.78rem;color:#888">Industrial City</div></div>
        <div class="quiz-opt" data-idx="2"><div>C. 漁港</div><div style="font-size:.78rem;color:#888">Fishing Village</div></div>
        <div class="quiz-opt" data-idx="3"><div>D. 金融中心</div><div style="font-size:.78rem;color:#888">Financial Centre</div></div>
      </div>
      <div class="quiz-feedback"></div>
    </div>

    <div class="quiz-item" data-answer="1">
      <h4><span class="q-num">2</span> <div>1841年英國接管後，在香港實行甚麼政策？</div><div style="font-weight:400;font-size:.85rem;color:#666">After the British took over in 1841, what policy was adopted in Hong Kong?</div></h4>
      <div class="quiz-options">
        <div class="quiz-opt" data-idx="0"><div>A. 保護關稅政策</div><div style="font-size:.78rem;color:#888">Protectionist Tariff Policy</div></div>
        <div class="quiz-opt" data-idx="1"><div>B. 自由港政策</div><div style="font-size:.78rem;color:#888">Free Port Policy</div></div>
        <div class="quiz-opt" data-idx="2"><div>C. 禁運政策</div><div style="font-size:.78rem;color:#888">Embargo Policy</div></div>
        <div class="quiz-opt" data-idx="3"><div>D. 工業化政策</div><div style="font-size:.78rem;color:#888">Industrialisation Policy</div></div>
      </div>
      <div class="quiz-feedback"></div>
    </div>

    <div class="quiz-item" data-answer="3">
      <h4><span class="q-num">3</span> <div>1953年韓戰爆發後，香港轉為發展什麼行業？</div><div style="font-weight:400;font-size:.85rem;color:#666">After the Korean War broke out in 1953, what industry did Hong Kong develop?</div></h4>
      <div class="quiz-options">
        <div class="quiz-opt" data-idx="0"><div>A. 金融業</div><div style="font-size:.78rem;color:#888">Financial Industry</div></div>
        <div class="quiz-opt" data-idx="1"><div>B. 旅遊業</div><div style="font-size:.78rem;color:#888">Tourism Industry</div></div>
        <div class="quiz-opt" data-idx="2"><div>C. 轉口貿易</div><div style="font-size:.78rem;color:#888">Entrepot Trade</div></div>
        <div class="quiz-opt" data-idx="3"><div>D. 製造業</div><div style="font-size:.78rem;color:#888">Manufacturing Industry</div></div>
      </div>
      <div class="quiz-feedback"></div>
    </div>

    <div class="quiz-item" data-answer="2">
      <h4><span class="q-num">4</span> <div>香港、韓國、臺灣及新加坡被譽為什麼？</div><div style="font-weight:400;font-size:.85rem;color:#666">What are Hong Kong, South Korea, Taiwan, and Singapore known as?</div></h4>
      <div class="quiz-options">
        <div class="quiz-opt" data-idx="0"><div>A. 亞洲四巨龍</div><div style="font-size:.78rem;color:#888">Four Asian Dragons</div></div>
        <div class="quiz-opt" data-idx="1"><div>B. 亞洲四虎</div><div style="font-size:.78rem;color:#888">Four Asian Tigers</div></div>
        <div class="quiz-opt" data-idx="2"><div>C. 亞洲四小龍</div><div style="font-size:.78rem;color:#888">Four Asian Little Dragons</div></div>
        <div class="quiz-opt" data-idx="3"><div>D. 亞洲四強</div><div style="font-size:.78rem;color:#888">Four Asian Powers</div></div>
      </div>
      <div class="quiz-feedback"></div>
    </div>

    <div class="quiz-item" data-answer="0">
      <h4><span class="q-num">5</span> <div>香港有多少種直接稅？</div><div style="font-weight:400;font-size:.85rem;color:#666">How many types of direct taxes are there in Hong Kong?</div></h4>
      <div class="quiz-options">
        <div class="quiz-opt" data-idx="0"><div>A. 3種</div><div style="font-size:.78rem;color:#888">3 Types</div></div>
        <div class="quiz-opt" data-idx="1"><div>B. 5種</div><div style="font-size:.78rem;color:#888">5 Types</div></div>
        <div class="quiz-opt" data-idx="2"><div>C. 7種</div><div style="font-size:.78rem;color:#888">7 Types</div></div>
        <div class="quiz-opt" data-idx="3"><div>D. 10種</div><div style="font-size:.78rem;color:#888">10 Types</div></div>
      </div>
      <div class="quiz-feedback"></div>
    </div>

    <div class="quiz-item" data-answer="1">
      <h4><span class="q-num">6</span> <div>香港大約有多少家中小型企業？</div><div style="font-weight:400;font-size:.85rem;color:#666">Approximately how many SMEs are there in Hong Kong?</div></h4>
      <div class="quiz-options">
        <div class="quiz-opt" data-idx="0"><div>A. 約10萬家</div><div style="font-size:.78rem;color:#888">Approx. 100,000</div></div>
        <div class="quiz-opt" data-idx="1"><div>B. 約34萬家</div><div style="font-size:.78rem;color:#888">Approx. 340,000</div></div>
        <div class="quiz-opt" data-idx="2"><div>C. 約50萬家</div><div style="font-size:.78rem;color:#888">Approx. 500,000</div></div>
        <div class="quiz-opt" data-idx="3"><div>D. 約100萬家</div><div style="font-size:.78rem;color:#888">Approx. 1,000,000</div></div>
      </div>
      <div class="quiz-feedback"></div>
    </div>

    <div class="quiz-item" data-answer="3">
      <h4><span class="q-num">7</span> <div>超過多少百分比的勞動人口從事服務性行業？</div><div style="font-weight:400;font-size:.85rem;color:#666">What percentage of the working population is employed in the services industry?</div></h4>
      <div class="quiz-options">
        <div class="quiz-opt" data-idx="0"><div>A. 50%</div></div>
        <div class="quiz-opt" data-idx="1"><div>B. 60%</div></div>
        <div class="quiz-opt" data-idx="2"><div>C. 70%</div></div>
        <div class="quiz-opt" data-idx="3"><div>D. 80%</div></div>
      </div>
      <div class="quiz-feedback"></div>
    </div>

    <div class="quiz-item" data-answer="2">
      <h4><span class="q-num">8</span> <div>1978年中國實行什麼政策，令香港工廠北移？</div><div style="font-weight:400;font-size:.85rem;color:#666">What policy did China adopt in 1978 that caused Hong Kong factories to move north?</div></h4>
      <div class="quiz-options">
        <div class="quiz-opt" data-idx="0"><div>A. 禁運政策</div><div style="font-size:.78rem;color:#888">Embargo Policy</div></div>
        <div class="quiz-opt" data-idx="1"><div>B. 國有化政策</div><div style="font-size:.78rem;color:#888">Nationalisation Policy</div></div>
        <div class="quiz-opt" data-idx="2"><div>C. 改革開放政策</div><div style="font-size:.78rem;color:#888">Reform and Open-door Policy</div></div>
        <div class="quiz-opt" data-idx="3"><div>D. 一帶一路政策</div><div style="font-size:.78rem;color:#888">Belt and Road Initiative</div></div>
      </div>
      <div class="quiz-feedback"></div>
    </div>

    <div class="quiz-score">
      <p style="color:#888;font-size:.9rem;margin-bottom:.5rem">你的分數 Your Score</p>
      <div class="score-num" id="quizScore">0 / 8</div>
      <button class="quiz-reset" onclick="resetQuiz()">重新作答 Reset</button>
    </div>
  </div>
</section>

<!-- ==================== FOOTER ==================== -->
<footer>
  <p>📚 資料來源 | Source: 加拿大神召會嘉智中學 中一商業教材 (Ver2) | PAOC Ka Chi Secondary School</p>
  <p style="margin-top:.5rem">📖 對應頁碼 | Pages: P.1.2 - P.1.5 (中/英)</p>
  <p style="margin-top:1rem;color:#ccc">© 2024 S1 Junior Commerce Bilingual Study Guide</p>
</footer>

<!-- ==================== SCRIPTS ==================== -->
<script>
// Counter Animation
const counters = document.querySelectorAll('.stat-num');
const animateCounters = () => {
  counters.forEach(counter => {
    const target = +counter.dataset.target;
    const inc = target / 200;
    let current = 0;
    const update = () => {
      current += inc;
      if (current < target) {
        counter.textContent = Math.ceil(current).toLocaleString();
        requestAnimationFrame(update);
      } else {
        counter.textContent = target.toLocaleString();
      }
    };
    update();
  });
};

const counterObs = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      counters.forEach(c => c.textContent = '0');
      animateCounters();
      counterObs.unobserve(entry.target);
    }
  });
}, { threshold: 0.5 });
counterObs.observe(document.querySelector('.stat-bar'));

// Timeline fade-in
const tlItems = document.querySelectorAll('.tl-item');
const tlObs = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) entry.target.classList.add('visible');
  });
}, { threshold: 0.15 });
tlItems.forEach(item => tlObs.observe(item));

// Smooth scroll
document.querySelectorAll('nav a').forEach(a => {
  a.addEventListener('click', e => {
    e.preventDefault();
    const t = document.querySelector(a.getAttribute('href'));
    if (t) t.scrollIntoView({ behavior: 'smooth', block: 'start' });
  });
});

// Active nav
const secs = document.querySelectorAll('section[id]');
window.addEventListener('scroll', () => {
  let cur = '';
  secs.forEach(s => { if (pageYOffset >= s.offsetTop - 100) cur = s.id; });
  document.querySelectorAll('nav a').forEach(a => {
    a.classList.toggle('active', a.getAttribute('href') === '#' + cur);
  });
});

// ===== Highlight Pen =====
const hlColors = {yellow:'#fff3b0',green:'#b0f5c1',blue:'#b0d4f5',pink:'#f5b0c8',orange:'#f5d4b0'};
let hlMode = null;
const hlStorageKey = 'hk_biz_highlights';

// Create toggle button
const hlToggle = document.createElement('button');
hlToggle.className = 'hl-toggle';
hlToggle.innerHTML = '🖊️';
hlToggle.title = '螢光筆 Highlight Pen';
document.body.appendChild(hlToggle);

// Create toolbar
const toolbar = document.createElement('div');
toolbar.className = 'hl-toolbar hidden';
toolbar.innerHTML = `
  <button class="hl-btn" data-color="yellow" title="黃色 Yellow">🖊️</button>
  <button class="hl-btn" data-color="green" title="綠色 Green">🖊️</button>
  <button class="hl-btn" data-color="blue" title="藍色 Blue">🖊️</button>
  <button class="hl-btn" data-color="pink" title="粉色 Pink">🖊️</button>
  <button class="hl-btn" data-color="orange" title="橙色 Orange">🖊️</button>
  <button class="hl-btn" data-color="eraser" title="橡皮擦 Eraser">🧹</button>
  <div class="hl-clear" title="清除全部 Clear All">清除全部</div>
`;
document.body.appendChild(toolbar);

// Toggle toolbar
hlToggle.addEventListener('click', () => {
  toolbar.classList.toggle('hidden');
  hlToggle.classList.toggle('shift-right');
  if (!toolbar.classList.contains('hidden') && !hlMode) {
    hlMode = 'yellow';
    updateActiveBtn();
  }
});

// Color buttons
toolbar.querySelectorAll('.hl-btn').forEach(btn => {
  btn.addEventListener('click', () => {
    const c = btn.dataset.color;
    hlMode = (hlMode === c && c !== 'eraser') ? null : c;
    updateActiveBtn();
  });
});

function updateActiveBtn() {
  toolbar.querySelectorAll('.hl-btn').forEach(b => b.classList.toggle('active', b.dataset.color === hlMode));
  hlToggle.style.cursor = hlMode ? 'crosshair' : 'pointer';
}

// Highlight on mouseup
document.addEventListener('mouseup', () => {
  if (!hlMode) return;
  const sel = window.getSelection();
  if (!sel.rangeCount || sel.isCollapsed) return;
  const range = sel.getRangeAt(0);
  if (!document.body.contains(range.commonAncestorContainer)) return;

  if (hlMode === 'eraser') {
    // Remove highlights in selection
    const parent = range.commonAncestorContainer;
    if (parent.nodeType === 1 && parent.tagName === 'MARK' && parent.classList.contains('hl-highlight')) {
      parent.replaceWith(document.createTextNode(parent.textContent));
    } else {
      range.extractContents();
      const frag = document.createDocumentFragment();
      frag.appendChild(range.cloneContents());
      // Remove any marks in the extracted content
      frag.querySelectorAll('mark.hl-highlight').forEach(m => m.replaceWith(document.createTextNode(m.textContent)));
      range.insertNode(frag);
    }
    sel.removeAllRanges();
    saveHighlights();
    return;
  }

  // Don't highlight inside images, buttons, inputs
  if (range.commonAncestorContainer.nodeType === 1 &&
      ['IMG','BUTTON','INPUT','SELECT','TEXTAREA'].includes(range.commonAncestorContainer.tagName)) return;

  const text = sel.toString().trim();
  if (!text) return;

  // Check if selection is inside a highlight - skip if so
  let parent = range.commonAncestorContainer;
  while (parent && parent !== document.body) {
    if (parent.nodeType === 1 && parent.classList && parent.classList.contains('hl-highlight')) {
      sel.removeAllRanges();
      return;
    }
    parent = parent.parentNode;
  }

  try {
    const mark = document.createElement('mark');
    mark.className = 'hl-highlight';
    mark.style.background = hlColors[hlMode];
    mark.dataset.color = hlMode;
    range.surroundContents(mark);
    sel.removeAllRanges();
    saveHighlights();
  } catch(e) {}
});

// Save highlights to localStorage
function saveHighlights() {
  const marks = document.querySelectorAll('mark.hl-highlight');
  const data = [];
  marks.forEach(m => {
    const path = getPath(m);
    data.push({text: m.textContent, color: m.dataset.color, path: path});
  });
  try { localStorage.setItem(hlStorageKey, JSON.stringify(data)); } catch(e) {}
}

function getPath(el) {
  const path = [];
  while (el && el !== document.body) {
    let idx = 0;
    let sib = el;
    while (sib.previousElementSibling) { idx++; sib = sib.previousElementSibling; }
    path.unshift(el.tagName + ':' + idx);
    el = el.parentNode;
  }
  return path.join('>');
}

// Remove highlight on click
document.addEventListener('click', e => {
  if (e.target.classList.contains('hl-highlight')) {
    e.target.replaceWith(document.createTextNode(e.target.textContent));
    saveHighlights();
  }
});

// Clear all
toolbar.querySelector('.hl-clear').addEventListener('click', () => {
  if (!confirm('確定清除所有螢光筆標記？\nClear all highlights?')) return;
  document.querySelectorAll('mark.hl-highlight').forEach(m => m.replaceWith(document.createTextNode(m.textContent)));
  try { localStorage.removeItem(hlStorageKey); } catch(e) {}
});

// ===== Quiz =====
let quizAnswered = 0;
let quizCorrect = 0;
const quizTotal = document.querySelectorAll('.quiz-item').length;

document.querySelectorAll('.quiz-item').forEach(item => {
  const answer = +item.dataset.answer;
  const feedback = item.querySelector('.quiz-feedback');
  const opts = item.querySelectorAll('.quiz-opt');

  opts.forEach(opt => {
    opt.addEventListener('click', () => {
      if (item.classList.contains('answered')) return;
      item.classList.add('answered');
      quizAnswered++;

      const idx = +opt.dataset.idx;
      if (idx === answer) {
        opt.classList.add('correct');
        feedback.className = 'quiz-feedback show correct';
        feedback.textContent = '✓ 正確！Correct!';
        quizCorrect++;
      } else {
        opt.classList.add('wrong');
        opts[answer].classList.add('correct');
        feedback.className = 'quiz-feedback show wrong';
        feedback.textContent = '✗ 答錯了！正確答案係 ' + opts[answer].textContent;
      }

      if (quizAnswered === quizTotal) {
        document.getElementById('quizScore').textContent = quizCorrect + ' / ' + quizTotal;
      }
    });
  });
});

function resetQuiz() {
  quizAnswered = 0;
  quizCorrect = 0;
  document.getElementById('quizScore').textContent = '0 / ' + quizTotal;
  document.querySelectorAll('.quiz-item').forEach(item => {
    item.classList.remove('answered');
    item.querySelectorAll('.quiz-opt').forEach(o => {
      o.classList.remove('selected','correct','wrong');
    });
    const fb = item.querySelector('.quiz-feedback');
    fb.className = 'quiz-feedback';
    fb.textContent = '';
  });
}

// ===== Image Insert =====
const imgStorageKey = 'hk_biz_point_images';
let imgTargetPoint = null;

// Create insert image buttons for all pillar-points
function setupImgButtons() {
  document.querySelectorAll('.pillar-point').forEach((pt, i) => {
    // Add image element if not exists
    if (!pt.querySelector('.pp-img')) {
      const img = document.createElement('img');
      img.className = 'pp-img';
      img.alt = '插入的圖片';
      pt.appendChild(img);
    }
    // Add insert button
    if (!pt.querySelector('.pp-img-btn')) {
      const btn = document.createElement('button');
      btn.className = 'pp-img-btn';
      btn.title = '插入圖片 Insert Image';
      btn.textContent = '📷';
      btn.addEventListener('click', e => {
        e.stopPropagation();
        imgTargetPoint = pt;
        openImgModal('📷 插入圖片 | Insert Image');
      });
      pt.appendChild(btn);
    }
    // Add delete button
    if (!pt.querySelector('.pp-img-del')) {
      const del = document.createElement('button');
      del.className = 'pp-img-del';
      del.title = '刪除圖片 Remove Image';
      del.textContent = '✕';
      del.addEventListener('click', e => {
        e.stopPropagation();
        const img = pt.querySelector('.pp-img');
        if (img) { img.src = ''; img.classList.remove('has-img'); }
        del.classList.remove('show');
        savePointImages();
      });
      pt.appendChild(del);
    }
  });
}
setupImgButtons();

// Restore saved images
function restorePointImages() {
  try {
    const data = JSON.parse(localStorage.getItem(imgStorageKey) || '{}');
    document.querySelectorAll('.pillar-point').forEach((pt, i) => {
      if (data[i]) {
        const img = pt.querySelector('.pp-img');
        if (img) { img.src = data[i]; img.classList.add('has-img'); }
        const del = pt.querySelector('.pp-img-del');
        if (del) del.classList.add('show');
      }
    });
  } catch(e) {}
}
restorePointImages();

// Save images to localStorage
function savePointImages() {
  const data = {};
  document.querySelectorAll('.pillar-point').forEach((pt, i) => {
    const img = pt.querySelector('.pp-img');
    if (img && img.src && img.classList.contains('has-img')) {
      data[i] = img.src;
    }
  });
  try { localStorage.setItem(imgStorageKey, JSON.stringify(data)); } catch(e) {}
}

// Modal
const imgModal = document.getElementById('imgModal');
const imgUrlInput = document.getElementById('imgUrlInput');
const imgFileInput = document.getElementById('imgFileInput');
const imgPreview = document.getElementById('imgPreview');
let pendingImgSrc = null;

function openImgModal(title) {
  imgUrlInput.value = '';
  imgFileInput.value = '';
  imgPreview.innerHTML = '';
  imgPreview.classList.remove('show');
  pendingImgSrc = null;
  imgModal.querySelector('h3').textContent = title || '📷 插入圖片 | Insert Image';
  imgModal.classList.add('show');
}

function closeImgModal() {
  imgModal.classList.remove('show');
  imgTargetPoint = null;
  pendingImgSrc = null;
}

document.getElementById('imgModalCancel').addEventListener('click', closeImgModal);
imgModal.addEventListener('click', e => { if (e.target === imgModal) closeImgModal(); });

// URL input preview
imgUrlInput.addEventListener('input', () => {
  const url = imgUrlInput.value.trim();
  if (url) {
    imgPreview.innerHTML = '<img src="' + url + '" onerror="this.parentNode.classList.remove(\'show\')">';
    imgPreview.classList.add('show');
    pendingImgSrc = url;
  } else {
    imgPreview.classList.remove('show');
    pendingImgSrc = null;
  }
});

// File upload preview
imgFileInput.addEventListener('change', () => {
  const file = imgFileInput.files[0];
  if (file) {
    const reader = new FileReader();
    reader.onload = e => {
      imgPreview.innerHTML = '<img src="' + e.target.result + '">';
      imgPreview.classList.add('show');
      pendingImgSrc = e.target.result;
    };
    reader.readAsDataURL(file);
  }
});

// Confirm insert
document.getElementById('imgModalConfirm').addEventListener('click', () => {
  const src = pendingImgSrc || imgUrlInput.value.trim();
  if (!src) return;

  // Edit tl-img mode
  if (tlImgTarget) {
    tlImgTarget.src = src;
    saveTlImages();
    tlImgTarget = null;
    closeImgModal();
    return;
  }

  // Insert into pillar-point mode
  if (!imgTargetPoint) return;
  const img = imgTargetPoint.querySelector('.pp-img');
  if (img) {
    img.src = src;
    img.classList.add('has-img');
  }
  const del = imgTargetPoint.querySelector('.pp-img-del');
  if (del) del.classList.add('show');
  savePointImages();
  closeImgModal();
});

// ===== Timeline Image Edit =====
const tlImgStorageKey = 'hk_biz_tl_images';
let tlImgTarget = null;

function setupTlImgEdit() {
  document.querySelectorAll('.tl-img').forEach(img => {
    // Make parent position:relative if not already
    const parent = img.parentNode;
    if (getComputedStyle(parent).position === 'static') {
      parent.style.position = 'relative';
    }
    // Add edit button after the image
    const btn = document.createElement('button');
    btn.className = 'tl-img-edit';
    btn.title = '修改圖片 Edit Image';
    btn.textContent = '✏️';
    btn.addEventListener('click', e => {
      e.stopPropagation();
      tlImgTarget = img;
      openImgModal('修改圖片 | Edit Image');
    });
    parent.insertBefore(btn, img.nextSibling);
    // Show/hide on hover
    parent.addEventListener('mouseenter', () => btn.style.display = 'flex');
    parent.addEventListener('mouseleave', () => btn.style.display = 'none');
  });
}
setupTlImgEdit();

// Restore saved tl images
function restoreTlImages() {
  try {
    const data = JSON.parse(localStorage.getItem(tlImgStorageKey) || '{}');
    document.querySelectorAll('.tl-img').forEach((img, i) => {
      if (data[i]) img.src = data[i];
    });
  } catch(e) {}
}
restoreTlImages();

// Save tl images
function saveTlImages() {
  const data = {};
  document.querySelectorAll('.tl-img').forEach((img, i) => {
    if (img.src) data[i] = img.src;
  });
  try { localStorage.setItem(tlImgStorageKey, JSON.stringify(data)); } catch(e) {}
}
</script>

<!-- Image Insert Modal -->
<div class="img-modal-overlay" id="imgModal">
  <div class="img-modal">
    <h3>📷 插入圖片 | Insert Image</h3>
    <input type="text" id="imgUrlInput" placeholder="貼上圖片網址 / Paste image URL...">
    <div class="or-divider">或 / OR</div>
    <label class="file-label">
      <input type="file" id="imgFileInput" accept="image/*">
      📂 上傳本地圖片 / Upload local image
    </label>
    <div class="preview-box" id="imgPreview"></div>
    <div class="modal-btns">
      <button class="btn-cancel" id="imgModalCancel">取消 Cancel</button>
      <button class="btn-confirm" id="imgModalConfirm">確認插入 Insert</button>
    </div>
  </div>
</div>

</body>
</html>
