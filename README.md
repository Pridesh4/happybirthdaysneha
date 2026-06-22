# salcomp-testing
salcomp test deptment

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
  <title>✨ Happy 25th Birthday Sneha ❤️</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,700&family=Inter:wght@300;400;500;600;700&family=Dancing+Script:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html, body {
      height: 100%;
      font-family: 'Inter', sans-serif;
      color: #2e1f1e;
      overflow-x: hidden;
      scroll-behavior: smooth;
      text-align: center;
      position: relative;
      background: #f5e3dd;
    }
    body {
      padding: 0;
      display: flex;
      align-items: flex-start;
      justify-content: center;
      min-height: 100vh;
      padding-top: 10px;
    }
    
    body::before {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-image: url('pic1.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      filter: blur(12px) brightness(0.75);
      -webkit-filter: blur(12px) brightness(0.75);
      transform: scale(1.02);
      z-index: -2;
      opacity: 0.9;
      will-change: transform;
    }
    body::after {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(255, 245, 240, 0.2);
      z-index: -1;
      pointer-events: none;
    }
    
    .glass {
      background: rgba(255, 245, 240, 0.55);
      backdrop-filter: blur(8px);
      -webkit-backdrop-filter: blur(8px);
      border: 1px solid rgba(255, 215, 210, 0.35);
      box-shadow: 0 15px 30px -12px rgba(90, 40, 30, 0.12);
      border-radius: 28px;
      padding: 20px 16px;
      margin: 8px auto;
      max-width: 500px;
      width: 100%;
      text-align: center;
      position: relative;
      z-index: 1;
    }
    .section {
      background: rgba(255, 245, 240, 0.5);
      backdrop-filter: blur(6px);
      -webkit-backdrop-filter: blur(6px);
      border: 1px solid rgba(255, 210, 200, 0.25);
      border-radius: 24px;
      padding: 18px 14px;
      margin: 8px auto;
      max-width: 500px;
      width: 100%;
      box-shadow: 0 8px 20px rgba(100, 50, 40, 0.05);
      text-align: center;
      position: relative;
      z-index: 1;
    }
    .hero {
      padding: 24px 16px 20px;
      background: rgba(255, 235, 225, 0.4);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border-radius: 28px;
      border: 1px solid rgba(255, 220, 210, 0.5);
      position: relative;
      overflow: hidden;
      box-shadow: 0 15px 35px -15px rgba(120, 50, 40, 0.12);
      text-align: center;
      width: 100%;
    }
    .hero::after {
      content: "✨";
      font-size: 70px;
      position: absolute;
      bottom: -15px;
      right: -8px;
      opacity: 0.06;
      transform: rotate(-8deg);
      pointer-events: none;
    }
    
    /* ===== PAGE 1 - PREMIUM HERO with BIG 1:1 Image ===== */
    .premium-hero {
      position: relative;
      padding: 0;
      border-radius: 28px;
      overflow: hidden;
      background: rgba(255, 235, 225, 0.3);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border: 1px solid rgba(255, 220, 210, 0.4);
      box-shadow: 0 20px 40px -15px rgba(90, 40, 30, 0.2);
    }
    .premium-hero .hero-image-wrapper {
      width: 340px;
      height: 340px;
      margin: 20px auto 10px;
      border-radius: 50%;
      overflow: hidden;
      border: 6px solid rgba(255, 255, 255, 0.8);
      box-shadow: 0 8px 40px rgba(160, 60, 60, 0.3), inset 0 0 40px rgba(255, 215, 210, 0.1);
      position: relative;
      animation: imageGlow 3s ease-in-out infinite;
    }
    @keyframes imageGlow {
      0%, 100% { box-shadow: 0 8px 40px rgba(160, 60, 60, 0.3), inset 0 0 40px rgba(255, 215, 210, 0.1); }
      50% { box-shadow: 0 8px 60px rgba(160, 60, 60, 0.4), inset 0 0 60px rgba(255, 215, 210, 0.2); }
    }
    .premium-hero .hero-image-wrapper::after {
      content: '❤️';
      position: absolute;
      bottom: 10px;
      right: 10px;
      font-size: 32px;
      background: rgba(255, 255, 255, 0.95);
      border-radius: 50%;
      padding: 2px 8px;
      box-shadow: 0 2px 15px rgba(0,0,0,0.15);
      animation: heartBeat 1.5s ease-in-out infinite;
    }
    @keyframes heartBeat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.15); }
    }
    .premium-hero .hero-image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }
    .premium-hero .hero-content {
      padding: 10px 20px 24px;
      position: relative;
      background: linear-gradient(180deg, rgba(255, 245, 240, 0.1) 0%, rgba(255, 245, 240, 0.7) 100%);
    }
    .premium-hero .hero-content::before {
      content: '✨';
      position: absolute;
      top: -12px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 28px;
      background: rgba(255, 245, 240, 0.9);
      padding: 0 14px;
      border-radius: 50%;
      backdrop-filter: blur(4px);
      box-shadow: 0 2px 15px rgba(160, 60, 60, 0.08);
    }
    .premium-hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.1rem;
      font-weight: 700;
      letter-spacing: -0.5px;
      background: linear-gradient(145deg, #a84c4c, #6a2525);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 4px;
      line-height: 1.2;
      text-align: center;
    }
    .premium-hero .subtitle {
      font-size: 0.95rem;
      font-weight: 300;
      color: #402b29;
      max-width: 380px;
      margin: 0 auto 8px;
      line-height: 1.6;
      letter-spacing: 0.3px;
      text-align: center;
      font-style: italic;
    }
    .premium-hero .subtitle span {
      font-weight: 600;
      color: #a94444;
      font-style: normal;
    }
    
    /* Premium Countdown - Glowing Design */
    .premium-hero .countdown-wrapper {
      background: linear-gradient(135deg, rgba(255, 235, 225, 0.6), rgba(255, 215, 210, 0.3));
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border-radius: 60px;
      padding: 14px 24px;
      display: inline-block;
      border: 2px solid rgba(169, 68, 68, 0.15);
      box-shadow: 0 0 30px rgba(169, 68, 68, 0.08), inset 0 0 30px rgba(169, 68, 68, 0.03);
      margin-bottom: 14px;
      position: relative;
    }
    .premium-hero .countdown-wrapper::before {
      content: '';
      position: absolute;
      top: -2px;
      left: -2px;
      right: -2px;
      bottom: -2px;
      border-radius: 60px;
      background: linear-gradient(135deg, rgba(169, 68, 68, 0.2), transparent, rgba(169, 68, 68, 0.2));
      z-index: -1;
      animation: glowPulse 2s ease-in-out infinite;
    }
    @keyframes glowPulse {
      0%, 100% { opacity: 0.5; }
      50% { opacity: 1; }
    }
    .premium-hero .countdown-wrapper .countdown {
      font-size: 2.3rem;
      font-weight: 800;
      color: #a94444;
      letter-spacing: 3px;
      background: transparent;
      padding: 0;
      border: none;
      box-shadow: none;
      backdrop-filter: none;
      font-family: 'Playfair Display', serif;
      display: inline-block;
      text-shadow: 0 0 30px rgba(169, 68, 68, 0.15);
    }
    .premium-hero .countdown-wrapper .countdown-label {
      display: block;
      font-size: 0.7rem;
      text-transform: uppercase;
      letter-spacing: 4px;
      color: #8a5a5a;
      font-weight: 600;
      margin-top: 2px;
      opacity: 0.7;
    }
    .premium-hero .countdown-wrapper .countdown-icon {
      display: inline-block;
      animation: sparkle 1.5s ease-in-out infinite;
      margin-right: 6px;
    }
    @keyframes sparkle {
      0%, 100% { opacity: 0.6; transform: scale(0.9); }
      50% { opacity: 1; transform: scale(1.1); }
    }
    
    .premium-hero .btn-premium {
      display: inline-block;
      padding: 15px 44px;
      background: linear-gradient(135deg, #cb6b6b, #a94444);
      color: #fff;
      border: none;
      border-radius: 50px;
      font-weight: 700;
      font-size: 1.05rem;
      text-decoration: none;
      box-shadow: 0 10px 35px -8px rgba(160, 60, 60, 0.4);
      transition: all 0.3s ease;
      letter-spacing: 0.6px;
      border: 1px solid rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(4px);
      text-align: center;
      cursor: pointer;
      position: relative;
      overflow: hidden;
    }
    .premium-hero .btn-premium::after {
      content: '✨';
      margin-left: 8px;
    }
    .premium-hero .btn-premium:hover {
      transform: translateY(-4px) scale(1.03);
      box-shadow: 0 16px 40px -8px #a94444b3;
      background: linear-gradient(135deg, #d67a7a, #a94444);
    }
    .premium-hero .btn-premium:active {
      transform: scale(0.97);
    }
    .premium-hero .signature-line {
      margin-top: 12px;
      font-size: 0.75rem;
      opacity: 0.5;
      letter-spacing: 0.5px;
      font-weight: 300;
      color: #5a3a38;
      font-family: 'Dancing Script', cursive;
      font-size: 1.15rem;
    }
    .premium-hero .decorative-line {
      width: 60px;
      height: 2px;
      background: linear-gradient(90deg, transparent, #dba0a0, transparent);
      margin: 6px auto;
      border-radius: 6px;
    }
    
    .button {
      display: inline-block;
      padding: 12px 32px;
      background: linear-gradient(135deg, #cb6b6b, #a94444);
      color: #fff;
      border: none;
      border-radius: 50px;
      font-weight: 600;
      font-size: 0.9rem;
      text-decoration: none;
      box-shadow: 0 8px 20px -8px rgba(160, 60, 60, 0.35);
      transition: all 0.3s ease;
      letter-spacing: 0.4px;
      border: 1px solid rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(4px);
      text-align: center;
      cursor: pointer;
    }
    .button:hover {
      transform: translateY(-3px) scale(1.02);
      box-shadow: 0 12px 25px -8px #a94444b3;
      background: linear-gradient(135deg, #d67a7a, #a94444);
    }
    .button-small {
      padding: 10px 26px;
      font-size: 0.8rem;
    }
    .reply-btn {
      display: inline-block;
      padding: 12px 32px;
      background: linear-gradient(135deg, #25D366, #128C7E);
      color: #fff;
      border: none;
      border-radius: 50px;
      font-weight: 700;
      font-size: 0.95rem;
      text-decoration: none;
      box-shadow: 0 10px 25px -8px rgba(37, 211, 102, 0.4);
      transition: all 0.3s ease;
      letter-spacing: 0.4px;
      border: 2px solid rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(4px);
      text-align: center;
      cursor: pointer;
      position: relative;
      overflow: hidden;
    }
    .reply-btn::before {
      content: "💬";
      margin-right: 8px;
      font-size: 1.1rem;
    }
    .reply-btn:hover {
      transform: translateY(-3px) scale(1.03);
      box-shadow: 0 15px 30px -8px rgba(37, 211, 102, 0.5);
      background: linear-gradient(135deg, #31d66a, #128C7E);
    }
    .reply-btn:active {
      transform: scale(0.97);
    }
    
    /* Download Button */
    .download-btn {
      display: inline-block;
      padding: 8px 20px;
      background: linear-gradient(135deg, #6c5ce7, #a855f7);
      color: #fff;
      border: none;
      border-radius: 50px;
      font-weight: 600;
      font-size: 0.7rem;
      text-decoration: none;
      box-shadow: 0 6px 18px -6px rgba(108, 92, 231, 0.35);
      transition: all 0.3s ease;
      letter-spacing: 0.3px;
      border: 1px solid rgba(255, 255, 255, 0.15);
      cursor: pointer;
      margin-top: 6px;
    }
    .download-btn:hover {
      transform: translateY(-2px) scale(1.02);
      box-shadow: 0 10px 22px -6px rgba(108, 92, 231, 0.5);
      background: linear-gradient(135deg, #7c6cf7, #b86cf7);
    }
    
    h2 {
      font-family: 'Playfair Display', serif;
      font-size: 1.6rem;
      font-weight: 700;
      color: #402220;
      margin-bottom: 8px;
      letter-spacing: -0.2px;
      text-align: center;
    }
    .countdown {
      font-size: 1.2rem;
      font-weight: 600;
      color: #a94444;
      background: rgba(255, 235, 225, 0.6);
      padding: 6px 14px;
      border-radius: 40px;
      display: inline-block;
      backdrop-filter: blur(4px);
      border: 1px solid rgba(190, 120, 110, 0.2);
      letter-spacing: 0.3px;
      box-shadow: 0 4px 12px rgba(140, 60, 60, 0.04);
      text-align: center;
      margin: 0 auto;
    }
    
    /* PAGE 3 - 2 COLUMNS */
    .gallery {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
      margin: 10px 0;
      text-align: center;
      max-width: 440px;
      margin-left: auto;
      margin-right: auto;
      max-height: 620px;
      overflow-y: auto;
      padding: 6px 8px 6px 8px;
      scrollbar-width: thin;
      scrollbar-color: #dba0a0 rgba(255, 235, 225, 0.3);
    }
    .gallery::-webkit-scrollbar {
      width: 5px;
    }
    .gallery::-webkit-scrollbar-track {
      background: rgba(255, 235, 225, 0.3);
      border-radius: 10px;
    }
    .gallery::-webkit-scrollbar-thumb {
      background: #dba0a0;
      border-radius: 10px;
    }
    /* Default: 2:3 ratio for all images */
    .gallery img {
      width: 100%;
      aspect-ratio: 2 / 3;
      object-fit: cover;
      border-radius: 16px;
      box-shadow: 0 6px 14px -10px rgba(60, 30, 30, 0.12);
      border: 2px solid rgba(255, 220, 210, 0.3);
      transition: all 0.3s ease;
      background: #f5e3dd;
      will-change: transform;
    }
    /* Special: 1:1 ratio for last two images (pic9.JPG and pic10.JPG) */
    .gallery img:nth-last-child(2),
    .gallery img:nth-last-child(1) {
      aspect-ratio: 1 / 1;
    }
    .gallery img:hover {
      transform: scale(1.03) translateY(-3px);
      box-shadow: 0 12px 22px -10px #a0555580;
      border-color: #dba0a0;
    }
    
    /* Page 3 - Next Button with Opacity on Scroll */
    .gallery-next-btn {
      display: block;
      margin: 10px auto 4px;
      padding: 10px 26px;
      background: linear-gradient(135deg, #cb6b6b, #a94444);
      color: #fff;
      border: none;
      border-radius: 50px;
      font-weight: 600;
      font-size: 0.8rem;
      text-decoration: none;
      box-shadow: 0 8px 20px -8px rgba(160, 60, 60, 0.35);
      transition: all 0.3s ease;
      letter-spacing: 0.4px;
      border: 1px solid rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(4px);
      text-align: center;
      cursor: pointer;
      position: sticky;
      bottom: 0;
      z-index: 10;
      opacity: 1;
      transition: opacity 0.3s ease;
    }
    .gallery-next-btn:hover {
      transform: translateY(-3px) scale(1.02);
      box-shadow: 0 12px 25px -8px #a94444b3;
      background: linear-gradient(135deg, #d67a7a, #a94444);
    }
    .gallery-next-btn.fade {
      opacity: 0.3;
    }
    
    .letter-content {
      font-size: 0.9rem;
      line-height: 1.6;
      font-weight: 400;
      color: #352221;
      background: rgba(255, 245, 240, 0.25);
      padding: 12px 14px;
      border-radius: 18px;
      border-left: 3px solid #dba0a0;
      border-right: 3px solid #dba0a0;
      text-align: center;
      max-width: 440px;
      margin: 6px auto;
      font-family: 'Inter', sans-serif;
    }
    .letter-content .short-note {
      font-size: 0.82rem;
      line-height: 1.6;
      padding: 3px 0;
      border-bottom: 1px dashed rgba(180, 120, 110, 0.08);
    }
    .letter-content .short-note:last-child {
      border-bottom: none;
    }
    .letter-content .note-emoji {
      font-size: 1.0rem;
      margin-right: 4px;
    }
    .letter-content strong {
      font-weight: 600;
      color: #9e4040;
    }
    .letter-content .signature {
      font-family: 'Dancing Script', cursive;
      font-size: 1.4rem;
      color: #a94444;
      margin-top: 4px;
    }
    .reason-grid {
      display: flex;
      flex-direction: column;
      gap: 8px;
      margin: 10px 0;
      text-align: center;
      max-width: 420px;
      margin-left: auto;
      margin-right: auto;
    }
    .reason-item {
      background: rgba(255, 235, 225, 0.45);
      backdrop-filter: blur(4px);
      border-radius: 25px;
      padding: 12px 8px;
      font-weight: 500;
      border: 1px solid rgba(200, 145, 135, 0.2);
      font-size: 0.85rem;
      color: #352221;
      transition: 0.2s;
      box-shadow: 0 3px 8px rgba(0,0,0,0.02);
      text-align: center;
    }
    .reason-item:hover {
      background: rgba(210, 160, 150, 0.2);
      transform: scale(1.02);
    }
    .reason-item.highlight {
      background: rgba(200, 120, 110, 0.2);
      border-color: #b38a7a;
    }
    .reason-item .bold-text {
      font-weight: 700;
      color: #a94444;
    }
    .footer {
      padding: 16px 14px;
      font-size: 0.9rem;
      font-weight: 300;
      color: #352221;
      background: rgba(235, 210, 200, 0.3);
      backdrop-filter: blur(4px);
      border-radius: 20px;
      margin: 8px auto;
      max-width: 500px;
      width: 100%;
      border: 1px solid rgba(190, 150, 140, 0.2);
      text-align: center;
      position: relative;
      z-index: 1;
    }
    .footer strong {
      font-weight: 600;
      color: #9e4040;
      font-family: 'Playfair Display', serif;
    }
    .divider {
      width: 40px;
      height: 2px;
      background: linear-gradient(90deg, #dba0a0, #b34a4a, #dba0a0);
      margin: 8px auto;
      border-radius: 6px;
    }
    .heart-float {
      position: fixed;
      bottom: -80px;
      font-size: 1.5rem;
      animation: floatUp 14s linear infinite;
      opacity: 0.1;
      pointer-events: none;
      z-index: 0;
      will-change: transform;
    }
    @keyframes floatUp {
      0% { transform: translateY(0) scale(0.8) rotate(0deg); opacity: 0.1; }
      100% { transform: translateY(-140vh) scale(1.3) rotate(360deg); opacity: 0; }
    }
    #fireworks-canvas {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 9999;
      display: block;
    }
    .music-indicator {
      position: fixed;
      bottom: 10px;
      right: 10px;
      background: rgba(255, 235, 225, 0.6);
      backdrop-filter: blur(8px);
      padding: 5px 12px;
      border-radius: 30px;
      font-size: 0.6rem;
      color: #5a3a38;
      border: 1px solid rgba(255, 200, 190, 0.3);
      z-index: 999;
      display: flex;
      align-items: center;
      gap: 4px;
      box-shadow: 0 4px 12px rgba(100, 50, 40, 0.06);
      pointer-events: none;
      opacity: 0.6;
    }
    .music-indicator span {
      display: inline-block;
      animation: pulse 1.5s ease-in-out infinite;
    }
    @keyframes pulse {
      0%, 100% { opacity: 0.4; transform: scale(0.9); }
      50% { opacity: 1; transform: scale(1.1); }
    }
    .poem {
      font-family: 'Playfair Display', serif;
      font-size: 0.85rem;
      line-height: 1.7;
      color: #4d2e2b;
      font-style: italic;
      padding: 4px 0;
    }
    .poem span {
      display: block;
    }
    .floating-roses {
      font-size: 1.4rem;
      animation: floatRose 8s ease-in-out infinite;
      display: inline-block;
    }
    @keyframes floatRose {
      0%, 100% { transform: translateY(0) rotate(0deg); }
      50% { transform: translateY(-6px) rotate(5deg); }
    }
    .emotional-promise {
      font-size: 0.82rem;
      line-height: 1.9;
      color: #4d2e2b;
      background: rgba(255, 235, 225, 0.3);
      padding: 12px 14px;
      border-radius: 18px;
      border: 2px dashed #dba0a0;
      max-width: 440px;
      margin: 8px auto;
      font-weight: 400;
    }
    .emotional-promise .promise-heart {
      color: #a94444;
      font-size: 1.1rem;
    }
    .emotional-promise .highlight-text {
      color: #a94444;
      font-weight: 600;
    }

    /* ===== PAGE NAVIGATION ===== */
    .page {
      display: none;
      animation: pageFade 0.4s ease forwards;
      width: 100%;
      max-width: 500px;
      margin: 0 auto;
      padding: 6px;
    }
    .page.active {
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      min-height: 100vh;
    }
    @keyframes pageFade {
      from { opacity: 0; transform: translateY(15px) scale(0.98); }
      to { opacity: 1; transform: translateY(0) scale(1); }
    }

    /* ALL PAGES - TOP ALIGNED */
    #page1.active,
    #page2.active,
    #page3.active,
    #page4.active,
    #page5.active,
    #page6.active,
    #page7.active {
      justify-content: flex-start;
      min-height: 100vh;
    }

    /* ===== GIFT BOX - MUCH BIGGER ===== */
    .gift-wrapper {
      position: relative;
      width: 340px;
      height: 340px;
      margin: 8px auto 10px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .gift-box {
      position: relative;
      width: 260px;
      height: 220px;
      cursor: pointer;
      transition: transform 0.3s ease;
    }
    .gift-box:hover {
      transform: scale(1.04);
    }
    .gift-lid {
      position: absolute;
      top: -28px;
      left: 50%;
      transform: translateX(-50%);
      width: 250px;
      height: 40px;
      background: linear-gradient(145deg, #e84c4c, #c0392b);
      border-radius: 14px 14px 0 0;
      box-shadow: 0 -3px 10px rgba(0,0,0,0.1);
      transition: all 1s cubic-bezier(0.34, 1.56, 0.64, 1);
      transform-origin: bottom center;
      z-index: 2;
    }
    .gift-lid::after {
      content: '🎀';
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 2.8rem;
    }
    .gift-body {
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 250px;
      height: 195px;
      background: linear-gradient(145deg, #e84c4c, #c0392b);
      border-radius: 0 0 18px 18px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.2);
      z-index: 1;
      transition: all 0.8s cubic-bezier(0.34, 1.56, 0.64, 1);
    }
    .gift-body::before {
      content: '';
      position: absolute;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 16px;
      height: 100%;
      background: rgba(255,215,0,0.4);
      border-radius: 3px;
    }
    .gift-body::after {
      content: '';
      position: absolute;
      top: 50%;
      left: 0;
      transform: translateY(-50%);
      width: 100%;
      height: 16px;
      background: rgba(255,215,0,0.4);
      border-radius: 3px;
    }
    .gift-ribbon {
      position: absolute;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 20px;
      height: 100%;
      background: rgba(255,215,0,0.5);
      border-radius: 3px;
      z-index: 3;
    }
    .gift-box.burst .gift-lid {
      transform: translateX(-50%) rotateX(-150deg) translateY(-25px) scale(1.1);
      opacity: 0;
    }
    .gift-box.burst .gift-body {
      transform: translateX(-50%) scale(1.25);
      opacity: 0;
    }
    .emerge-image {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) scale(0.3);
      opacity: 0;
      width: 260px;
      height: 260px;
      border-radius: 24px;
      object-fit: cover;
      box-shadow: 0 10px 25px rgba(0,0,0,0.25);
      border: 3px solid rgba(255,255,255,0.7);
      z-index: 5;
      transition: all 1.2s cubic-bezier(0.34, 1.56, 0.64, 1);
      pointer-events: none;
    }
    .emerge-image.show {
      transform: translate(-50%, -50%) scale(1);
      opacity: 1;
    }
    .gift-quote {
      opacity: 0;
      transform: translateY(12px);
      transition: all 0.8s ease 0.5s;
      margin-top: 14px;
      padding: 10px 14px;
      font-family: 'Playfair Display', serif;
      font-size: 1.05rem;
      color: #5a2d2d;
      line-height: 1.6;
      background: rgba(255, 245, 240, 0.4);
      border-radius: 18px;
      backdrop-filter: blur(4px);
      border: 1px solid rgba(255, 215, 210, 0.3);
    }
    .gift-quote.show {
      opacity: 1;
      transform: translateY(0);
    }
    .gift-quote .heart-glow {
      color: #a94444;
      font-size: 1.4rem;
    }
    .gift-quote .highlight {
      color: #a94444;
      font-weight: 600;
    }

    /* ===== VIDEO PAGE ===== */
    .video-container {
      position: relative;
      width: 100%;
      max-width: 400px;
      margin: 10px auto;
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 12px 30px rgba(0,0,0,0.15);
      background: #000;
    }
    .video-container video {
      width: 100%;
      display: block;
      border-radius: 20px;
    }
    .video-container .play-btn-overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 55px;
      height: 55px;
      background: rgba(255, 255, 255, 0.9);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2.0rem;
      cursor: pointer;
      transition: all 0.3s ease;
      box-shadow: 0 6px 18px rgba(0,0,0,0.25);
      z-index: 10;
    }
    .video-container .play-btn-overlay:hover {
      transform: translate(-50%, -50%) scale(1.08);
      background: #fff;
    }
    .video-container .play-btn-overlay.hidden {
      opacity: 0;
      pointer-events: none;
    }
    .video-controls {
      display: flex;
      justify-content: center;
      gap: 12px;
      margin-top: 8px;
      flex-wrap: wrap;
    }

    .sparkle-container {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 9998;
      overflow: hidden;
    }
    .sparkle {
      position: absolute;
      width: 7px;
      height: 7px;
      border-radius: 50%;
      animation: sparkleAnim 1.5s ease forwards;
    }
    @keyframes sparkleAnim {
      0% { transform: scale(0) rotate(0deg); opacity: 1; }
      100% { transform: scale(1.5) rotate(720deg) translateY(-160px); opacity: 0; }
    }

    .hero-countdown {
      margin-top: 8px;
    }
    .hero-countdown .countdown {
      font-size: 1.0rem;
      padding: 5px 12px;
    }

    /* Page specific fixes */
    #page1 .hero {
      padding: 22px 14px 18px;
    }
    #page1 .hero h1 {
      font-size: 1.9rem;
    }
    #page1 .hero p {
      font-size: 0.9rem;
    }
    
    #page2 .section {
      padding: 16px 12px;
    }
    
    #page3 .section {
      padding: 14px 10px;
    }
    
    #page4 .section {
      padding: 14px 10px;
    }
    #page4 .letter-content {
      padding: 10px 12px;
      font-size: 0.85rem;
    }
    #page4 .short-note {
      font-size: 0.8rem;
      padding: 3px 0;
    }
    
    #page5 .section {
      padding: 14px 10px;
    }
    #page5 .reason-grid {
      gap: 8px;
      max-width: 400px;
    }
    #page5 .reason-item {
      font-size: 0.85rem;
      padding: 12px 8px;
      border-radius: 25px;
    }
    
    #page6 .section {
      padding: 14px 10px;
    }
    #page6 .emotional-promise {
      font-size: 0.78rem;
      padding: 10px 12px;
      line-height: 1.8;
    }
    #page6 .emotional-promise .highlight-text {
      font-size: 0.9rem !important;
    }
    #page6 h2 {
      font-size: 1.4rem;
    }
    
    #page7 .section {
      padding: 12px 10px;
    }
    #page7 h2 {
      font-size: 1.3rem;
    }
    #page7 .video-container {
      max-width: 360px;
    }

    @media (max-width: 480px) {
      .glass { padding: 14px 10px; border-radius: 20px; }
      .section { padding: 12px 8px; border-radius: 18px; }
      .hero { padding: 16px 10px 14px; border-radius: 20px; }
      .hero h1 { font-size: 1.5rem; }
      .hero p { font-size: 0.8rem; max-width: 300px; }
      h2 { font-size: 1.3rem; }
      .countdown { font-size: 0.85rem; padding: 4px 10px; }
      .button { padding: 10px 24px; font-size: 0.8rem; }
      .button-small { padding: 8px 18px; font-size: 0.7rem; }
      .reply-btn { padding: 10px 24px; font-size: 0.85rem; }
      .reply-btn::before { font-size: 0.9rem; }
      
      /* Page 1 - Premium Mobile - BIGGER 1:1 Image */
      .premium-hero .hero-image-wrapper { width: 220px; height: 220px; margin: 16px auto 8px; }
      .premium-hero .hero-image-wrapper::after { font-size: 24px; bottom: 6px; right: 6px; }
      .premium-hero h1 { font-size: 1.5rem; }
      .premium-hero .subtitle { font-size: 0.8rem; }
      .premium-hero .countdown-wrapper .countdown { font-size: 1.6rem; }
      .premium-hero .countdown-wrapper { padding: 10px 16px; }
      .premium-hero .btn-premium { padding: 12px 28px; font-size: 0.85rem; }
      .premium-hero .hero-content { padding: 12px 14px 18px; }
      
      /* Page 2 - Mobile adjustments */
      .gift-wrapper { width: 260px; height: 260px; margin: 6px auto; }
      .gift-box { width: 190px; height: 165px; }
      .gift-lid { width: 182px; height: 32px; top: -22px; }
      .gift-lid::after { font-size: 2.2rem; }
      .gift-body { width: 182px; height: 148px; }
      .emerge-image { width: 190px; height: 190px; }
      
      /* Page 3 - Mobile */
      .gallery { 
        grid-template-columns: repeat(2, 1fr); 
        gap: 10px; 
        max-height: 480px; 
        padding: 4px 6px; 
      }
      .gallery img { aspect-ratio: 2 / 3; border-radius: 14px; }
      .gallery img:nth-last-child(2),
      .gallery img:nth-last-child(1) {
        aspect-ratio: 1 / 1;
      }
      .gallery-next-btn { font-size: 0.7rem; padding: 8px 20px; }
      
      .letter-content { font-size: 0.78rem; padding: 8px 10px; }
      .letter-content .short-note { font-size: 0.72rem; }
      .reason-grid { gap: 6px; max-width: 320px; }
      #page5 .reason-item { font-size: 0.75rem; padding: 10px 6px; border-radius: 22px; }
      .footer { font-size: 0.75rem; padding: 12px 10px; }
      .emotional-promise { font-size: 0.7rem; padding: 8px 10px; }
      .gift-quote { font-size: 0.85rem; padding: 8px 12px; }
      .video-container .play-btn-overlay { width: 45px; height: 45px; font-size: 1.5rem; }
      .video-container { max-width: 100%; }
      .music-indicator { bottom: 6px; right: 6px; padding: 3px 8px; font-size: 0.5rem; }
      .hero-countdown .countdown { font-size: 0.8rem; padding: 3px 10px; }
      .poem { font-size: 0.78rem; }
      .letter-content .signature { font-size: 1.2rem; }
      #page6 .emotional-promise { font-size: 0.65rem; padding: 8px 10px; }
      #page6 .emotional-promise .highlight-text { font-size: 0.8rem !important; }
      #page7 h2 { font-size: 1.1rem; }
      #page7 .video-container { max-width: 300px; }
      .footer { font-size: 0.7rem; padding: 10px 8px; }
      .download-btn { font-size: 0.65rem; padding: 6px 16px; }
    }
  </style>
</head>
<body>

  <!-- Floating hearts & roses -->
  <div class="heart-float" style="left:4%">❤️‍🔥</div>
  <div class="heart-float" style="left:16%; animation-delay: 3s">🌹</div>
  <div class="heart-float" style="left:32%; animation-delay: 6s">💗</div>
  <div class="heart-float" style="left:50%; animation-delay: 1.5s">✨</div>
  <div class="heart-float" style="left:68%; animation-delay: 4.5s">🌹</div>
  <div class="heart-float" style="left:84%; animation-delay: 8s">💖</div>

  <!-- Fireworks Canvas -->
  <canvas id="fireworks-canvas"></canvas>

  <!-- Background Music -->
  <audio id="bgmusic" loop preload="auto" crossorigin="anonymous">
    <source src="Music.mp3" type="audio/mpeg">
  </audio>

  <!-- Music indicator -->
  <div class="music-indicator">
    <span>🎵</span> Music <span>❤️</span>
  </div>

  <!-- ====== PAGE 1: PREMIUM HERO ====== -->
  <div class="page active" id="page1">
    <div class="premium-hero glass">
      <div class="hero-image-wrapper">
        <img src="pic12.jpg" alt="Sneha ❤️" class="hero-image">
      </div>
      <div class="hero-content">
        <h1>🎂 Happy 25th Birthday<br>My Beautiful Wife Sneha ❤️</h1>
        <div class="decorative-line"></div>
        <p class="subtitle">
          You are my happiness, my peace, my best friend,<br>
          and God's greatest blessing in my life. <span>✨</span>
        </p>
        
        <div class="countdown-wrapper">
          <span class="countdown-icon">⏳</span>
          <span id="countdown-hero" class="countdown"></span>
          <span class="countdown-label">Until Your Special Day</span>
        </div>
        
        <button class="btn-premium" onclick="goToPage(2)">Open My Surprise</button>
        <div class="signature-line">— forever yours, Pridesh ❤️ —</div>
      </div>
    </div>
  </div>

  <!-- ====== PAGE 2: GIFT BOX ====== -->
  <div class="page" id="page2">
    <div class="section">
      <h2>🎁 A Special Gift For You</h2>
      <div class="divider"></div>
      
      <div class="gift-wrapper">
        <div class="gift-box" id="giftBox" onclick="openGift()">
          <div class="gift-lid"></div>
          <div class="gift-body">
            <div class="gift-ribbon"></div>
          </div>
        </div>
        <img src="pic11.jpg" alt="Special Memory ❤️" class="emerge-image" id="emergeImage">
      </div>
      
      <div class="gift-quote" id="giftQuote">
        <span class="heart-glow">💖</span><br>
        Happy Birthday Sneha ❤️<br>
        You are my today and all of my tomorrows.<br>
        <span class="highlight">I fall in love with you more and more</span><br>
        <span class="highlight">with every passing moment.</span><br>
        <span style="font-size:1.5rem;">❤️</span>
      </div>
      
      <p style="margin-top:6px; font-size:0.7rem; opacity:0.4;">Click the gift box to open it 🎁</p>
      <button class="button button-small" onclick="goToPage(3)" style="margin-top:8px;">Next →</button>
    </div>
  </div>

  <!-- ====== PAGE 3: MEMORIES ====== -->
  <div class="page" id="page3">
    <div class="section">
      <h2>📸 Our Beautiful Memories</h2>
      <div class="divider"></div>
      
      <div class="gallery" id="galleryContainer">
        <img src="pic1.jpg" alt="memory" loading="lazy">
        <img src="pic2.jpg" alt="memory" loading="lazy">
        <img src="pic3.JPG" alt="memory" loading="lazy">
        <img src="pic4.jpg" alt="memory" loading="lazy">
        <img src="pic5.JPG" alt="memory" loading="lazy">
        <img src="pic6.JPG" alt="memory" loading="lazy">
        <img src="pic7.JPG" alt="memory" loading="lazy">
        <img src="pic8.JPG" alt="memory" loading="lazy">
        <img src="pic9.JPG" alt="memory" loading="lazy">
        <img src="pic10.JPG" alt="memory" loading="lazy">
      </div>
      
      <button class="gallery-next-btn" id="galleryNextBtn" onclick="goToPage(4)">Next →</button>
    </div>
  </div>

  <!-- ====== PAGE 4: LETTER ====== -->
  <div class="page" id="page4">
    <div class="section" id="letter">
      <h2>💌 My Letter To You</h2>
      <div class="divider"></div>
      <div class="letter-content">
        <p><strong>My Dearest Sneha ❤️</strong></p>
        
        <div class="short-note"><span class="note-emoji">💫</span> You walked into my life and made it beautiful.</div>
        <div class="short-note"><span class="note-emoji">🌅</span> Every morning with you is a blessing.</div>
        <div class="short-note"><span class="note-emoji">💕</span> Your smile heals my soul.</div>
        <div class="short-note"><span class="note-emoji">🌟</span> You are my strength and my peace.</div>
        <div class="short-note"><span class="note-emoji">🤝</span> Thank you for loving me.</div>
        <div class="short-note"><span class="note-emoji">🔥</span> I will always choose you.</div>
        <div class="short-note"><span class="note-emoji">💖</span> You are my miracle.</div>
        
        <div class="poem" style="margin-top:6px;">
          <span>🌹 With every heartbeat, I promise you,</span>
          <span>My love will remain forever true.</span>
          <span>Through all the years, through joy and pain,</span>
          <span>I'll love you more with each new day again.</span>
          <span>🌹</span>
        </div>
        
        <p style="font-size:1.0rem; font-weight:600; color:#a94444; margin-top:6px;">Happy 25th Birthday My Love ❤️</p>
        <p style="margin-top:8px;">Forever Yours,<br><span class="signature">Pridesh ❤️</span></p>
      </div>
      <button class="button button-small" onclick="goToPage(5)" style="margin-top:6px;">Next →</button>
    </div>
  </div>

  <!-- ====== PAGE 5: REASONS - "Your Sacrifice" BOLD ====== -->
  <div class="page" id="page5">
    <div class="section">
      <h2>🎁 10 Reasons I Love You</h2>
      <div class="divider"></div>
      <div class="reason-grid">
        <div class="reason-item">❤️ Your Smile - It lights up my whole world</div>
        <div class="reason-item">❤️ Your Heart - So pure and full of love</div>
        <div class="reason-item">❤️ Your Support - You always believe in me</div>
        <div class="reason-item">❤️ Your Care - You always put others first</div>
        <div class="reason-item"><span class="bold-text">❤️ Your Sacrifice</span> - You give so much for us</div>
        <div class="reason-item">❤️ Your Honesty - You are always true to me</div>
        <div class="reason-item">❤️ Your Laughter - The most beautiful sound</div>
        <div class="reason-item">❤️ Your Love - It's the greatest gift I've ever received</div>
        <div class="reason-item">❤️ Your Presence - You make everything better</div>
        <div class="reason-item highlight">💖 You Are You - And that's more than enough</div>
      </div>
      
      <button class="button button-small" onclick="goToPage(6)" style="margin-top:8px;">Next →</button>
    </div>
  </div>

  <!-- ====== PAGE 6: FINAL PROMISE ====== -->
  <div class="page" id="page6">
    <div class="section" style="background: rgba(240, 215, 205, 0.4);">
      <h2>💍 One Last Surprise</h2>
      <div class="divider"></div>
      
      <div style="font-size:1.5rem; margin:4px 0;">
        <span class="floating-roses">🌹</span>
        <span class="floating-roses" style="animation-delay: 2s;">🌹</span>
        <span class="floating-roses" style="animation-delay: 4s;">🌹</span>
      </div>
      
      <p style="font-size:1.15rem; font-weight:300; color:#352221; margin:6px 0;">
        Will You Keep Loving Me<br> For The Rest Of Our Lives? ❤️
      </p>
      <div style="font-size:1.9rem; margin:6px 0;">💖</div>
      <p style="font-family:'Playfair Display', serif; font-size:1.0rem; color:#9e4040;">— yes, forever —</p>
      
      <div class="emotional-promise">
        <span class="promise-heart">❤️</span> I may not be the perfect husband...<br>
        But I promise to <span class="highlight-text">love</span> you,<br>
        <span class="highlight-text">respect</span> you,<br>
        <span class="highlight-text">protect</span> you,<br>
        <span class="highlight-text">pray</span> for you,<br>
        and <span class="highlight-text">stand beside</span> you<br><br>
        Until my last heartbeat...<br>
        <span class="highlight-text" style="font-size:0.95rem;">you will always be my first choice.</span><br><br>
        <span class="promise-heart">❤️ Forever & Always ❤️</span>
      </div>
      
      <button class="button" onclick="goToPage(7)" style="background: linear-gradient(135deg, #e84c4c, #c0392b); box-shadow: 0 8px 20px -8px rgba(232, 76, 76, 0.35); font-size:0.85rem; padding:10px 28px; margin-top:6px;">
        🎵 Let's Go! 🎵
      </button>
    </div>
  </div>

  <!-- ====== PAGE 7: VIDEO PAGE ====== -->
  <div class="page" id="page7">
    <div class="section" style="background: rgba(240, 215, 205, 0.3);">
      <h2>🎵 Happy Birthday Sneha! 🎵</h2>
      <div class="divider"></div>
      <p style="font-size:0.8rem; font-weight:300; color:#5a2d2d; margin-bottom:8px;">
        A special song just for you my love ❤️
      </p>
      
      <div class="video-container">
        <video id="birthdayVideo" preload="metadata" playsinline>
          <source src="birthday.MP4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <div class="play-btn-overlay" id="playBtn" onclick="playVideo()">
          ▶️
        </div>
      </div>
      
      <div class="video-controls">
        <button class="button button-small" onclick="togglePlay()" style="background: linear-gradient(135deg, #cb6b6b, #a94444); box-shadow: 0 6px 18px -6px rgba(160, 60, 60, 0.3);">
          ⏯️ Play/Pause
        </button>
        <a href="birthday.MP4" download="Happy_Birthday_Sneha.mp4" class="download-btn">
          ⬇️ Download Video
        </a>
      </div>
      
      <div style="margin-top:10px; font-size:0.85rem; color:#5a2d2d;">
        <span style="font-size:1.2rem;">🎂</span> Happy 25th Birthday Sneha! <span style="font-size:1.2rem;">🎂</span>
        <br><br>
        <span style="font-family:'Dancing Script', cursive; font-size:1.4rem; color:#a94444;">I Love You Forever ❤️</span>
      </div>
      
      <div style="margin-top:12px;">
        <a href="https://wa.me/919500134256" target="_blank" class="reply-btn">
          Reply To My Love ❤️
        </a>
        <p style="margin-top:4px; font-size:0.40rem; opacity:0.4; font-weight:200;">
          Click to send your reply on WhatsApp 💬
        </p>
      </div>
    </div>
    
    <div class="footer">
      ❤️ Since <strong>01 June 2026</strong> ❤️
      <br><br>
      Happy 25th Birthday <strong>Sneha</strong> ❤️
      <br><br>
      <span style="font-size:1.5rem; display:block; margin-top:4px;">✨🕊️✨</span>
      <div style="margin-top:4px; font-size:0.6rem; opacity:0.4;">
        "Every day with you is a gift from above"
      </div>
    </div>
  </div>

  <script>
    // ========== PAGE NAVIGATION ==========
    function goToPage(pageNum) {
      document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
      const target = document.getElementById('page' + pageNum);
      if (target) {
        target.classList.add('active');
        window.scrollTo({ top: 0, behavior: 'smooth' });
        
        if (pageNum === 2) {
          setTimeout(() => {
            document.getElementById('giftBox').classList.add('burst');
            setTimeout(() => {
              document.getElementById('emergeImage').classList.add('show');
            }, 600);
            setTimeout(() => {
              document.getElementById('giftQuote').classList.add('show');
              createSparkles();
              for (let i = 0; i < 4; i++) {
                setTimeout(() => window.autoBurst(), i * 350 + 200);
              }
            }, 1200);
          }, 300);
        }
      }
    }

    // ========== GIFT BOX ==========
    function openGift() {
      const giftBox = document.getElementById('giftBox');
      const emergeImage = document.getElementById('emergeImage');
      const giftQuote = document.getElementById('giftQuote');
      
      if (!giftBox.classList.contains('burst')) {
        giftBox.classList.add('burst');
        setTimeout(() => {
          emergeImage.classList.add('show');
        }, 600);
        setTimeout(() => {
          giftQuote.classList.add('show');
          createSparkles();
          for (let i = 0; i < 4; i++) {
            setTimeout(() => window.autoBurst(), i * 350 + 200);
          }
        }, 1200);
      }
    }

    // ========== PAGE 3 - SCROLL OPACITY FOR NEXT BUTTON ==========
    document.addEventListener('DOMContentLoaded', function() {
      const gallery = document.getElementById('galleryContainer');
      const nextBtn = document.getElementById('galleryNextBtn');
      
      if (gallery && nextBtn) {
        gallery.addEventListener('scroll', function() {
          const scrollTop = gallery.scrollTop;
          const maxScroll = gallery.scrollHeight - gallery.clientHeight;
          const scrollPercent = maxScroll > 0 ? scrollTop / maxScroll : 0;
          const opacity = 1 - (scrollPercent * 0.6);
          nextBtn.style.opacity = Math.max(0.4, opacity);
        });
      }
    });

    // ====== VIDEO PLAYER ======
    let bgMusicVolume = 0.35;
    let isVideoPlaying = false;

    function playVideo() {
      const video = document.getElementById('birthdayVideo');
      const playBtn = document.getElementById('playBtn');
      const bgMusic = document.getElementById('bgmusic');
      
      if (video.paused) {
        bgMusicVolume = bgMusic.volume;
        let vol = bgMusic.volume;
        const fadeInterval = setInterval(() => {
          vol = Math.max(vol - 0.05, 0.02);
          bgMusic.volume = vol;
          if (vol <= 0.02) {
            clearInterval(fadeInterval);
          }
        }, 100);
        
        video.play();
        playBtn.classList.add('hidden');
        isVideoPlaying = true;
        
        for (let i = 0; i < 6; i++) {
          setTimeout(() => window.autoBurst(), i * 400 + 100);
        }
        setTimeout(createSparkles, 500);
        
        video.onended = function() {
          isVideoPlaying = false;
          let vol2 = bgMusic.volume;
          const fadeUpInterval = setInterval(() => {
            vol2 = Math.min(vol2 + 0.05, bgMusicVolume);
            bgMusic.volume = vol2;
            if (vol2 >= bgMusicVolume) {
              clearInterval(fadeUpInterval);
            }
          }, 100);
          playBtn.classList.remove('hidden');
        };
      }
    }

    function togglePlay() {
      const video = document.getElementById('birthdayVideo');
      if (video.paused) {
        playVideo();
      } else {
        video.pause();
        document.getElementById('playBtn').classList.remove('hidden');
        isVideoPlaying = false;
      }
    }

    // ====== SPARKLE EFFECT ======
    function createSparkles() {
      const container = document.createElement('div');
      container.className = 'sparkle-container';
      document.body.appendChild(container);
      
      const colors = ['#FFD700', '#FF6B6B', '#FF69B4', '#FF1493', '#FFA500', '#FFD700', '#FF4500', '#FF6347'];
      for (let i = 0; i < 45; i++) {
        const sparkle = document.createElement('div');
        sparkle.className = 'sparkle';
        sparkle.style.left = Math.random() * 100 + '%';
        sparkle.style.top = Math.random() * 100 + '%';
        const size = Math.random() * 8 + 3;
        sparkle.style.width = size + 'px';
        sparkle.style.height = size + 'px';
        sparkle.style.background = colors[Math.floor(Math.random() * colors.length)];
        sparkle.style.animationDuration = (Math.random() * 0.8 + 0.5) + 's';
        sparkle.style.animationDelay = (Math.random() * 0.4) + 's';
        sparkle.style.boxShadow = '0 0 12px ' + sparkle.style.background + ', 0 0 25px ' + sparkle.style.background;
        container.appendChild(sparkle);
      }
      
      setTimeout(() => {
        container.remove();
      }, 2000);
    }

    // ========== COUNTDOWN ==========
    var birthday = new Date("June 26, 2026 00:00:00").getTime();
    
    function updateCountdowns() {
      var now = new Date().getTime();
      var distance = birthday - now;
      if (distance < 0) {
        document.getElementById("countdown-hero").innerHTML = "🎉 It's Your Birthday! 🎉";
        return;
      }
      var days = Math.floor(distance / (1000 * 60 * 60 * 24));
      var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      var seconds = Math.floor((distance % (1000 * 60)) / 1000);
      
      document.getElementById("countdown-hero").innerHTML = days + "d " + hours + "h " + minutes + "m " + seconds + "s";
    }
    
    setInterval(updateCountdowns, 1000);
    updateCountdowns();

    // ========== MUSIC ==========
    (function() {
      const audio = document.getElementById('bgmusic');
      let isPlaying = false;
      let fadeInterval = null;
      let targetVolume = 0.35;

      audio.volume = 0;

      function fadeIn() {
        if (fadeInterval) {
          clearInterval(fadeInterval);
          fadeInterval = null;
        }
        let vol = 0;
        audio.volume = 0;
        const step = 0.03;
        const intervalMs = 120;
        fadeInterval = setInterval(() => {
          vol = Math.min(vol + step, targetVolume);
          audio.volume = vol;
          if (vol >= targetVolume) {
            clearInterval(fadeInterval);
            fadeInterval = null;
          }
        }, intervalMs);
      }

      function startMusic() {
        if (isPlaying) return;
        audio.play().then(() => {
          isPlaying = true;
          fadeIn();
        }).catch(() => {
          setTimeout(startMusic, 500);
        });
      }

      function tryAutoPlay() {
        if (isPlaying) return;
        audio.play().then(() => {
          isPlaying = true;
          fadeIn();
        }).catch(() => {
          setTimeout(tryAutoPlay, 400);
        });
      }

      setTimeout(tryAutoPlay, 200);
      setTimeout(tryAutoPlay, 600);
      setTimeout(tryAutoPlay, 1200);

      document.addEventListener('click', function() {
        if (!isPlaying) startMusic();
      }, { once: false, passive: true });

      document.addEventListener('touchstart', function() {
        if (!isPlaying) startMusic();
      }, { once: false, passive: true });

      document.addEventListener('visibilitychange', function() {
        if (!document.hidden && !isPlaying) tryAutoPlay();
      });

      window.addEventListener('load', function() {
        setTimeout(tryAutoPlay, 300);
      });
    })();

    // ========== FIREWORKS ==========
    (function() {
      const canvas = document.getElementById('fireworks-canvas');
      const ctx = canvas.getContext('2d');
      let width, height;
      let particles = [];
      const MAX_PARTICLES = 100;
      const rand = (min, max) => Math.random() * (max - min) + min;

      function resize() {
        width = window.innerWidth;
        height = window.innerHeight;
        canvas.width = width;
        canvas.height = height;
      }
      window.addEventListener('resize', resize);
      resize();

      function createBurst(cx, cy) {
        const count = 20 + Math.floor(Math.random() * 20);
        const hue = Math.floor(Math.random() * 60) + 330;
        for (let i = 0; i < count; i++) {
          const angle = rand(0, Math.PI * 2);
          const speed = rand(0.8, 3.5);
          const size = rand(2, 4);
          particles.push({
            x: cx,
            y: cy,
            vx: Math.cos(angle) * speed * rand(0.6, 1.2),
            vy: Math.sin(angle) * speed * rand(0.6, 1.2) - 0.3,
            life: 1.0,
            decay: rand(0.01, 0.03),
            size: size,
            hue: hue + rand(-18, 18),
            saturation: 92,
            lightness: 72 + Math.random() * 18,
          });
        }
        if (particles.length > MAX_PARTICLES) {
          particles = particles.slice(-MAX_PARTICLES);
        }
      }

      let burstTimer = 0;
      function autoBurst() {
        const cx = rand(width * 0.1, width * 0.9);
        const cy = rand(height * 0.15, height * 0.5);
        createBurst(cx, cy);
        if (Math.random() > 0.65) {
          setTimeout(() => {
            createBurst(rand(width * 0.1, width * 0.9), rand(height * 0.15, height * 0.5));
          }, 80);
        }
      }

      for (let i = 0; i < 3; i++) {
        setTimeout(() => autoBurst(), i * 150);
      }

      function animate() {
        ctx.clearRect(0, 0, width, height);

        for (let i = particles.length - 1; i >= 0; i--) {
          const p = particles[i];
          p.x += p.vx;
          p.y += p.vy;
          p.vy += 0.04;
          p.vx *= 0.99;
          p.vy *= 0.99;
          p.life -= p.decay;
          if (p.life <= 0 || p.y > height + 50) {
            particles.splice(i, 1);
            continue;
          }
          const alpha = p.life * 0.9;
          ctx.beginPath();
          ctx.arc(p.x, p.y, p.size * p.life * 0.7 + 0.5, 0, Math.PI * 2);
          ctx.fillStyle = `hsla(${p.hue}, ${p.saturation}%, ${p.lightness}%, ${alpha})`;
          ctx.fill();
          if (p.size > 3) {
            ctx.shadowColor = `hsla(${p.hue}, 90%, 70%, 0.12)`;
            ctx.shadowBlur = 8;
            ctx.fill();
            ctx.shadowBlur = 0;
          }
        }

        burstTimer += 1;
        if (burstTimer > 30 + Math.random() * 40) {
          burstTimer = 0;
          autoBurst();
          if (Math.random() > 0.55) {
            setTimeout(autoBurst, 100);
          }
        }

        requestAnimationFrame(animate);
      }

      animate();
      window.autoBurst = autoBurst;
    })();
  </script>
</body>
</html>
