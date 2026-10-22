# -snow-divination
lin
<!doctype html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, initial-scale=1, viewport-fit=cover">
  <meta name="theme-color" content="#edf2f5">
  <meta name="description"
        content="林以澈的雪原占卜馆。细雪、来信与回响，在冬日里听见缘分。">
  <title>林以澈 · 雪原占卜馆</title>
  <link rel="stylesheet" href="./style.css">
  <script defer src="./app.js"></script>
</head>
<body>
  <div class="winter-background" aria-hidden="true"></div>
  <canvas id="snow" aria-hidden="true"></canvas>

  <section id="opening" class="opening" aria-labelledby="opening-title">
    <div class="opening-content">
      <span class="opening-mark" aria-hidden="true">❄</span>
      <h1 id="opening-title">一封夹杂着细雪的神谕</h1>
      <p class="english">AN ORACLE IN THE SNOW</p>
      <button id="enter-button" class="mist-button enter-button" type="button">
        启喻
      </button>
      <p class="opening-poem">我叹缘分浅浅如雨渐渐</p>
    </div>
    <p class="opening-bottom">林以澈 · 雪原占卜馆</p>
  </section>

  <div id="site" class="site" inert aria-hidden="true">
    <header class="site-header">
      <a class="brand" href="#snow" data-page="snow">
        <span aria-hidden="true">❄</span>
        <span>林以澈<small>雪原占卜馆</small></span>
      </a>

      <button id="music-button" class="mist-button music-button"
              type="button" aria-pressed="false">
        <span id="music-icon" aria-hidden="true">♫</span>
        <span id="music-label">雪音 · 未播放</span>
      </button>
    </header>

    <main id="main" tabindex="-1">
      <section id="page-snow" class="page" aria-labelledby="snow-title">
        <div class="page-heading">
          <p class="eyebrow">A LITTLE ABOUT ME</p>
          <h2 id="snow-title" tabindex="-1">细雪</h2>
          <p class="intro">天地霏雨，人与人之间，藕断丝连</p>
        </div>

        <div class="profile-layout">
          <div class="winter-window portrait-window" aria-hidden="true">
            <div class="distant-hill hill-one"></div>
            <div class="distant-hill hill-two"></div>
            <span class="window-cross"></span>
            <span class="window-word">雪落无声</span>
          </div>

          <article class="glass-card profile-card">
            <span class="tiny-snow" aria-hidden="true">❄</span>
            <p class="eyebrow">THE KEEPER OF THIS PLACE</p>
            <h3>林以澈</h3>
            <p class="profile-description">在细雪落下的地方，读一封关于你的来信。</p>

            <dl class="facts">
              <div><dt>年龄</dt><dd>21岁</dd></div>
              <div><dt>星座</dt><dd>射手座</dd></div>
              <div><dt>人格</dt><dd>INTJ</dd></div>
              <div><dt>卜龄</dt><dd>7年</dd></div>
            </dl>

            <div class="cards-used">
              <p class="small-label">常用牌卡</p>
              <span class="pill">清醒梦</span>
              <span class="pill">温柔猫</span>
            </div>
          </article>
        </div>

        <p class="poem">
          接一片雪花融在手心<br>
          水顺着掌纹蜿蜒命运
        </p>
        <a class="text-link" href="#letters" data-page="letters">
          向雪原寄一封信 <span aria-hidden="true">↗</span>
        </a>
      </section>

      <section id="page-letters" class="page" hidden
               aria-labelledby="letters-title">
        <div class="page-heading">
          <p class="eyebrow">LETTERS THROUGH THE SNOW</p>
          <h2 id="letters-title" tabindex="-1">来信</h2>
          <p class="intro">有些心事，适合在落雪时慢慢说。</p>
        </div>

        <div class="winter-window letter-window" aria-hidden="true">
          <div class="distant-hill hill-one"></div>
          <div class="distant-hill hill-two"></div>
          <span class="window-cross"></span>
          <span class="window-word">愿每一封来信，都被温柔听见</span>
        </div>

        <div class="services">
          <article class="glass-card service-card">
            <span class="service-number">01 / DREAM</span>
            <h3>梦向</h3>
            <p>将难以言明的牵念，写成一封来信。在牌面之间，轻轻梳理心中的疑问。</p>
          </article>
          <article class="glass-card service-card">
            <span class="service-number">02 / MESSAGE</span>
            <h3>传讯</h3>
            <p>留一点安静给内心的声音，也留一点时间，听见此刻想要抵达你的讯息。</p>
          </article>
          <article class="glass-card service-card">
            <span class="service-number">03 / COMPANION</span>
            <h3>宠物沟通</h3>
            <p>关于陪伴，关于那些没有说出口的话。把你与小小生命之间的牵挂，温柔安放。</p>
          </article>
        </div>

        <p class="service-note">委托说明 · 不接受寻物委托</p>

        <!--
          有联系地址后，将下面的 hidden 删除，并替换 href。
          邮箱示例：href="mailto:你的邮箱"
          不要填入不属于你的联系方式。
        -->
        <a id="contact-link" class="mist-button contact-link" href="" hidden>
          写一封来信
        </a>

        <p class="poem">
          暗许的因果 明晰的缘分<br>
          在你我之间 不作声哑
        </p>
      </section>

      <section id="page-echoes" class="page" hidden
               aria-labelledby="echoes-title">
        <div class="page-heading">
          <p class="eyebrow">ECHOES IN THE QUIET</p>
          <h2 id="echoes-title" tabindex="-1">回响</h2>
          <p class="intro">那些被认真读过的心事，后来有了回音。</p>
        </div>

        <p id="feedback-hint" class="gallery-hint" hidden>
          轻触图片放大 · 放大后可左右滑动
        </p>
        <div id="feedback-gallery" class="feedback-gallery"></div>

        <div id="feedback-empty" class="glass-card empty-state">
          <span aria-hidden="true">❄</span>
          <p>回信正在穿过雪原</p>
          <small>客户反馈将在整理后陈列于此。</small>
        </div>

        <p class="poem">一片雪，一封信，一段回响。</p>
      </section>
    </main>

    <footer class="site-footer">
      <span>林以澈 · 雪原占卜馆</span>
      <span>愿你心中，长有晴雪。</span>
    </footer>

    <nav class="bottom-nav" aria-label="主要栏目">
      <a class="nav-item active" href="#snow" data-page="snow"
         aria-current="page">
        <span class="nav-snow" aria-hidden="true">❄</span>
        <span>细雪</span>
      </a>
      <a class="nav-item" href="#letters" data-page="letters">
        <span class="nav-snow" aria-hidden="true">❄</span>
        <span>来信</span>
      </a>
      <a class="nav-item" href="#echoes" data-page="echoes">
        <span class="nav-snow" aria-hidden="true">❄</span>
        <span>回响</span>
      </a>
    </nav>
  </div>

  <div id="lightbox" class="lightbox" role="dialog" aria-modal="true"
       aria-label="客户反馈图片查看器" hidden>
    <div class="lightbox-toolbar">
      <span id="lightbox-count" aria-live="polite"></span>
      <button id="lightbox-close" class="mist-button" type="button">
        关闭 <span aria-hidden="true">×</span>
      </button>
    </div>
    <div id="lightbox-stage" class="lightbox-stage">
      <img id="lightbox-image" alt="">
    </div>
    <div class="lightbox-controls">
      <button id="lightbox-prev" class="mist-button" type="button"
              aria-label="上一张反馈">←</button>
      <span>左右滑动查看</span>
      <button id="lightbox-next" class="mist-button" type="button"
              aria-label="下一张反馈">→</button>
    </div>
  </div>

  <p id="status" class="status" role="status" aria-live="polite"></p>

  <audio id="background-music" loop preload="none">
    <source src="./assets/audio/snow.mp3" type="audio/mpeg">
  </audio>

  <noscript>
    <style>
      #opening, .bottom-nav, .music-button { display: none; }
      #site { visibility: visible; }
    </style>
    <p class="noscript-message">请开启 JavaScript，以使用栏目切换和图片查看功能。</p>
  </noscript>
</body>
</html>
:root {
  color-scheme: light;
  --ink: #425562;
  --muted: #657a88;
  --faint: #7c8f9b;
  --line: rgba(112, 140, 157, .18);
  --glass: rgba(255, 255, 255, .46);
  --shadow: 0 16px 55px rgba(79, 108, 128, .06);
}

* { box-sizing: border-box; }

html {
  min-height: 100%;
  background: #edf2f5;
  -webkit-text-size-adjust: 100%;
}

body {
  margin: 0;
  color: var(--ink);
  font-family: "Songti SC", "STSong", "Noto Serif SC",
    "PingFang SC", serif;
  font-weight: 400;
  line-height: 1.8;
  overflow-wrap: break-word;
}

body.intro-locked,
body.modal-open {
  overflow: hidden;
}

[hidden] { display: none !important; }

button, a { -webkit-tap-highlight-color: transparent; }

button {
  font: inherit;
  color: inherit;
  cursor: pointer;
}

a {
  color: inherit;
  text-decoration: none;
}

button, a {
  touch-action: manipulation;
}

:focus-visible {
  outline: 2px solid #63859b;
  outline-offset: 6px;
}

h2:focus,
main:focus { outline: none; }

.winter-background {
  position: fixed;
  inset: 0;
  z-index: -2;
  pointer-events: none;
  background:
    radial-gradient(ellipse at 18% 12%, #ffffffc9, transparent 48%),
    radial-gradient(ellipse at 86% 40%, #c6d8e370, transparent 47%),
    linear-gradient(165deg, #e9f0f4 0%, #f5f6f5 52%, #e1eaf0 100%);
}

#snow {
  position: fixed;
  inset: 0;
  width: 100%;
  height: 100%;
  z-index: 2;
  pointer-events: none;
}

.mist-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 9px;
  min-height: 44px;
  padding: 10px 22px;
  border: 1px solid rgba(255,255,255,.8);
  border-radius: 999px;
  background: rgba(255,255,255,.48);
  box-shadow: 0 5px 22px rgba(95,121,139,.07);
  -webkit-backdrop-filter: blur(12px);
  backdrop-filter: blur(12px);
  transition: background .35s, box-shadow .35s, transform .35s;
}

.mist-button:active { transform: scale(.97); }

@media (hover: hover) {
  .mist-button:hover {
    background: rgba(255,255,255,.85);
    box-shadow: 0 8px 26px rgba(95,121,139,.12);
  }
}

.opening {
  position: fixed;
  inset: 0;
  z-index: 20;
  display: grid;
  place-items: center;
  min-height: 100vh;
  min-height: 100svh;
  overflow: hidden;
  background:
    radial-gradient(ellipse at 50% 35%, #ffffffa8, transparent 65%),
    linear-gradient(170deg, #e6edf2, #f3f5f5 56%, #dce7ee);
  opacity: 1;
  filter: blur(0);
  transition: opacity 3.4s ease-in-out, filter 3.4s ease-in-out;
}

.opening::before,
.opening::after {
  content: "";
  position: absolute;
  bottom: -24%;
  left: -20%;
  width: 150%;
  height: 46%;
  border-radius: 50%;
  background: #c9d9e454;
  transform: rotate(-8deg);
  filter: blur(12px);
}

.opening::after {
  bottom: -30%;
  left: -35%;
  background: #ffffffbd;
  transform: rotate(10deg);
}

.opening.leaving {
  opacity: 0;
  filter: blur(6px);
  pointer-events: none;
}

.opening-content {
  position: relative;
  z-index: 1;
  width: 100%;
  padding: 28px;
  text-align: center;
  transform: translateY(-20px);
}

.opening-mark {
  display: block;
  margin-bottom: 38px;
  font-size: 24px;
  color: #91a9b9;
}

.opening h1 {
  margin: 0 0 27px;
  font-size: clamp(20px, 4.9vw, 34px);
  font-weight: 400;
  letter-spacing: .15em;
}

.english {
  margin: 0;
  font-family: Georgia, serif;
  font-size: 10px;
  letter-spacing: .22em;
  color: var(--muted);
}

.enter-button {
  margin: 47px 0 32px;
  min-width: 132px;
  padding: 13px 28px 13px 36px;
  font-size: 19px;
  letter-spacing: .45em;
}

.opening-poem {
  margin: 0;
  color: var(--muted);
  font-size: 12px;
  letter-spacing: .12em;
}

.opening-bottom {
  position: absolute;
  bottom: calc(30px + env(safe-area-inset-bottom, 0px));
  z-index: 1;
  color: var(--muted);
  font-size: 10px;
  letter-spacing: .2em;
}

.site {
  position: relative;
  visibility: hidden;
  min-height: 100vh;
  padding-bottom: calc(105px + env(safe-area-inset-bottom, 0px));
}

.site.revealed { visibility: visible; }

.site-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  max-width: 1120px;
  margin: auto;
  padding: calc(24px + env(safe-area-inset-top, 0px)) 24px 20px;
}

.brand {
  display: flex;
  align-items: center;
  gap: 12px;
  font-size: 17px;
  letter-spacing: .12em;
}

.brand > span:first-child {
  color: #8ca5b5;
  font-size: 24px;
}

.brand small {
  display: block;
  margin-top: 1px;
  color: var(--muted);
  font-size: 10px;
  letter-spacing: .2em;
}

.music-button {
  padding: 8px 13px;
  font-size: 10px;
  white-space: nowrap;
}

#music-icon { font-size: 16px; }

main {
  max-width: 1000px;
  margin: 0 auto;
  padding: 0 24px;
}

.page {
  opacity: 1;
  transform: translateY(0);
  transition: opacity .5s ease, transform .5s ease;
}

.page.faded {
  opacity: 0;
  transform: translateY(7px);
}

.page-heading {
  padding: 40px 0 32px;
  text-align: center;
}

.eyebrow {
  margin: 0 0 14px;
  font-family: Georgia, serif;
  font-size: 9px;
  color: var(--muted);
  letter-spacing: .2em;
}

h2 {
  margin: 0;
  font-size: 34px;
  font-weight: 400;
  letter-spacing: .28em;
  text-indent: .28em;
}

.intro {
  margin: 20px 0 0;
  color: var(--muted);
  font-size: 12px;
  line-height: 2;
  letter-spacing: .06em;
}

.profile-layout {
  display: grid;
  gap: 20px;
}

.winter-window {
  position: relative;
  isolation: isolate;
  overflow: hidden;
  border: 8px solid rgba(255,255,255,.55);
  border-radius: 100px 100px 14px 14px;
  background:
    radial-gradient(circle at 68% 26%, #ffffffd9 0, #ffffff00 20%),
    linear-gradient(#cedde8, #e4edf2 60%, #f6f8f8);
  box-shadow: var(--shadow), inset 0 0 35px #ffffff8c;
}

.portrait-window { min-height: 270px; }

.distant-hill {
  position: absolute;
  bottom: -20%;
  left: -35%;
  width: 140%;
  height: 70%;
  border-radius: 50%;
  transform: rotate(-14deg);
  background: #b4c9d68c;
  filter: blur(3px);
}

.hill-two {
  bottom: -37%;
  left: -5%;
  width: 150%;
  height: 85%;
  transform: rotate(15deg);
  background: #f5f9fc;
  filter: blur(1px);
}

.window-cross {
  position: absolute;
  inset: 0;
  background:
    linear-gradient(90deg,
      transparent calc(50% - 3px),
      #ffffffb3 calc(50% - 3px),
      #ffffffb3 calc(50% + 3px),
      transparent calc(50% + 3px)),
    linear-gradient(0deg,
      transparent calc(42% - 3px),
      #ffffffa6 calc(42% - 3px),
      #ffffffa6 calc(42% + 3px),
      transparent calc(42% + 3px));
}

.window-word {
  position: absolute;
  bottom: 22px;
  left: 12px;
  right: 12px;
  text-align: center;
  color: #536c7c;
  font-size: 11px;
  letter-spacing: .2em;
}

.glass-card {
  border: 1px solid #ffffffa8;
  border-radius: 24px;
  background: var(--glass);
  box-shadow: var(--shadow);
}

.profile-card {
  position: relative;
  padding: 30px 25px;
}

.tiny-snow {
  position: absolute;
  top: 22px;
  right: 24px;
  color: #91a9b9;
}

h3 {
  margin: 0 0 14px;
  font-size: 25px;
  font-weight: 400;
  letter-spacing: .12em;
}

.profile-description,
.service-card p {
  color: var(--muted);
  font-size: 13px;
  line-height: 2.1;
}

.facts {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 18px 20px;
  padding: 24px 0;
  margin: 20px 0;
  border-top: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
}

.facts div { display: flex; gap: 14px; }
.facts dt { color: var(--muted); font-size: 12px; }
.facts dd { margin: 0; font-size: 13px; }

.small-label {
  margin: 0 0 12px;
  color: var(--muted);
  font-size: 11px;
  letter-spacing: .1em;
}

.pill {
  display: inline-block;
  margin-right: 7px;
  padding: 4px 16px;
  border-radius: 999px;
  background: #e2ebf170;
  font-size: 12px;
}

.poem {
  margin: 44px 0 25px;
  text-align: center;
  color: var(--muted);
  font-size: 12px;
  line-height: 2.5;
  letter-spacing: .12em;
}

.text-link {
  display: block;
  width: fit-content;
  margin: 0 auto;
  padding: 10px;
  border-bottom: 1px solid var(--line);
  font-size: 12px;
}

.text-link span { margin-left: 14px; }

.letter-window {
  height: 210px;
  margin-bottom: 24px;
  border-radius: 90px 90px 16px 16px;
}

.services { display: grid; gap: 16px; }

.service-card { padding: 26px; }

.service-number {
  display: block;
  margin-bottom: 20px;
  font-family: Georgia, serif;
  font-size: 9px;
  color: var(--muted);
  letter-spacing: .17em;
}

.service-card h3 { font-size: 22px; }
.service-card p { margin: 0; }

.service-note {
  margin: 24px 0;
  text-align: center;
  color: var(--muted);
  font-size: 12px;
}

.contact-link {
  display: flex;
  width: fit-content;
  margin: 24px auto;
}

.gallery-hint {
  margin: 0 0 22px;
  text-align: center;
  font-size: 11px;
  color: var(--muted);
}

.feedback-gallery {
  columns: 2;
  column-gap: 14px;
}

.feedback-item {
  display: block;
  width: 100%;
  margin: 0 0 14px;
  padding: 8px;
  break-inside: avoid;
  border: 1px solid #ffffffbf;
  border-radius: 15px;
  background: #ffffff70;
  box-shadow: var(--shadow);
  overflow: hidden;
}

.feedback-item img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 9px;
}

.feedback-caption {
  display: block;
  padding: 9px 2px 3px;
  color: var(--muted);
  font-size: 10px;
  text-align: left;
}

.empty-state {
  padding: 55px 22px;
  text-align: center;
}

.empty-state > span { font-size: 28px; color: #91a9b9; }
.empty-state p { margin: 16px 0 8px; font-size: 15px; }
.empty-state small { color: var(--muted); font-size: 11px; }

.site-footer {
  display: grid;
  gap: 5px;
  padding: 45px 24px 20px;
  text-align: center;
  color: var(--muted);
  font-size: 10px;
  letter-spacing: .12em;
}

.bottom-nav {
  position: fixed;
  z-index: 10;
  left: 50%;
  bottom: calc(16px + env(safe-area-inset-bottom, 0px));
  display: flex;
  justify-content: space-around;
  width: min(340px, calc(100% - 40px));
  padding: 8px 13px;
  border: 1px solid #ffffffbf;
  border-radius: 999px;
  background: #f7fafbd9;
  box-shadow: 0 8px 40px #647f9321;
  -webkit-backdrop-filter: blur(18px);
  backdrop-filter: blur(18px);
  transform: translateX(-50%);
}

.nav-item {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 7px;
  min-width: 78px;
  min-height: 44px;
  border-radius: 999px;
  color: var(--muted);
  font-size: 12px;
  transition: background .5s, color .5s;
}

.nav-item.active {
  color: #3f5e72;
  background: #dce7ef99;
}

.nav-snow {
  display: inline-block;
  font-size: 18px;
  transition: transform 1s ease;
}

.nav-item.turning .nav-snow { transform: rotate(120deg); }

.lightbox {
  position: fixed;
  inset: 0;
  z-index: 50;
  display: grid;
  grid-template-rows: auto minmax(0, 1fr) auto;
  padding: env(safe-area-inset-top, 0px) 0
           env(safe-area-inset-bottom, 0px);
  background: #eaf0f6f5;
  -webkit-backdrop-filter: blur(18px);
  backdrop-filter: blur(18px);
}

.lightbox-toolbar,
.lightbox-controls {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 14px;
  padding: 16px 20px;
  font-size: 12px;
}

.lightbox-stage {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 0;
  padding: 8px 16px;
  overflow: hidden;
  touch-action: pan-y pinch-zoom;
}

.lightbox-stage img {
  display: block;
  max-width: 100%;
  max-height: 100%;
  width: auto;
  height: auto;
  object-fit: contain;
  border-radius: 8px;
}

.lightbox-controls > span {
  color: var(--muted);
  font-size: 11px;
}

.status {
  position: fixed;
  z-index: 70;
  top: calc(20px + env(safe-area-inset-top, 0px));
  left: 50%;
  width: max-content;
  max-width: calc(100% - 40px);
  margin: 0;
  padding: 11px 18px;
  border-radius: 18px;
  background: #f9fcfcf5;
  box-shadow: var(--shadow);
  font-size: 12px;
  opacity: 0;
  transform: translate(-50%, -12px);
  transition: opacity .3s, transform .3s;
  pointer-events: none;
}

.status.visible { opacity: 1; transform: translate(-50%, 0); }

.noscript-message {
  position: relative;
  padding: 20px;
  text-align: center;
}

@media (min-width: 700px) {
  .site-header { padding-left: 40px; padding-right: 40px; }
  main { padding: 0 40px; }
  .page-heading { padding: 60px 0 42px; }
  h2 { font-size: 40px; }
  .profile-layout {
    grid-template-columns: .85fr 1.15fr;
    gap: 28px;
  }
  .portrait-window { min-height: 420px; }
  .profile-card { padding: 40px; }
  .services { grid-template-columns: repeat(3, 1fr); }
  .letter-window { height: 270px; }
  .feedback-gallery { columns: 3; column-gap: 20px; }
  .feedback-item { margin-bottom: 20px; }
  .poem { margin-top: 50px; }
}

@media (prefers-reduced-motion: reduce) {
  /* 保留进入时的渐隐，取消位移、模糊和旋转。 */
  .opening { transition: opacity 3.4s ease; }
  .opening.leaving { filter: none; }
  .page { transform: none !important; transition: opacity .15s; }
  .nav-snow { transition: none; transform: none !important; }
  .mist-button { transition: background .2s; }
}
"use strict";

/*
 * 客户反馈图片配置。
 * 图片放在 assets/images/feedback/，然后在此逐条添加。
 * 支持 jpg、png、webp，以及不同宽高比例。
 *
 * 示例：
 * { src: "./assets/images/feedback/01.jpg", alt: "客户反馈 01" },
 * { src: "./assets/images/feedback/02.png", alt: "客户反馈 02" },
 *
 * 未取得原来的38张截图，因此不预填虚假反馈或不存在的图片。
 */
const FEEDBACK_IMAGES = [
  // 在这里添加图片。
];

const $ = (selector) => document.querySelector(selector);
const opening = $("#opening");
const site = $("#site");
const enterButton = $("#enter-button");
const music = $("#background-music");
const musicButton = $("#music-button");
const musicLabel = $("#music-label");
const reducedMotion = window.matchMedia(
  "(prefers-reduced-motion: reduce)"
);

const pages = {
  snow: $("#page-snow"),
  letters: $("#page-letters"),
  echoes: $("#page-echoes")
};

const state = {
  entered: false,
  entering: false,
  currentPage: "snow",
  requestedPage: "snow",
  switching: false,
  lightboxIndex: 0,
  previousFocus: null
};

document.body.classList.add("intro-locked");

function setSiteInteractive(enabled) {
  site.inert = !enabled;
  if (enabled) {
    site.removeAttribute("inert");
    site.removeAttribute("aria-hidden");
  } else {
    site.setAttribute("inert", "");
    site.setAttribute("aria-hidden", "true");
  }
}

setSiteInteractive(false);

/* 所有状态提示共用一个计时器。 */
let statusTimer;

function notify(message) {
  const status = $("#status");
  clearTimeout(statusTimer);
  status.textContent = message;
  status.classList.add("visible");
  statusTimer = setTimeout(() => {
    status.classList.remove("visible");
  }, 3800);
}

/*
 * 音乐播放直接在点击事件中调用。
 * iOS Safari 需要用户手势，不能等开屏动画结束后才调用。
 */
function updateMusicState() {
  const playing = !music.paused && !music.ended;
  musicButton.setAttribute("aria-pressed", String(playing));
  musicLabel.textContent = playing ? "雪音 · 播放中" : "雪音 · 未播放";
}

async function playMusic(quiet = false) {
  music.volume = 0.35;

  try {
    await music.play();
  } catch (error) {
    if (!quiet) {
      const missing = music.error ||
        error.name === "NotSupportedError";
      notify(missing
        ? "雪音尚未放入馆中，请添加 assets/audio/snow.mp3"
        : "暂时无法播放，请再轻触一次雪音按钮。");
    }
  }

  updateMusicState();
}

music.addEventListener("play", updateMusicState);
music.addEventListener("pause", updateMusicState);
music.addEventListener("error", updateMusicState);

musicButton.addEventListener("click", () => {
  if (music.paused) {
    void playMusic(false);
  } else {
    music.pause();
  }
});

/*
 * 开屏只有这一套动画逻辑：
 * CSS负责3.4秒渐隐，JS负责开启和完成后的交互状态。
 * 不依赖 transitionend，避免浏览器未触发事件时卡住。
 */
enterButton.addEventListener("click", () => {
  if (state.entering || state.entered) return;

  state.entering = true;
  enterButton.disabled = true;
  enterButton.textContent = "雪信已启";

  void playMusic(true);

  site.classList.add("revealed");
  // 确保下层页面已经参与渲染，再启动开屏渐隐。
  void site.offsetWidth;
  opening.classList.add("leaving");

  window.setTimeout(() => {
    opening.hidden = true;
    state.entering = false;
    state.entered = true;
    document.body.classList.remove("intro-locked");
    setSiteInteractive(true);
    $("#snow-title").focus({ preventScroll: true });

    const requested = pageFromHash();
    if (requested !== "snow") {
      void navigate(requested);
    }
  }, 3450);
});

function wait(ms) {
  return new Promise((resolve) => setTimeout(resolve, ms));
}

function nextFrame() {
  return new Promise((resolve) => {
    requestAnimationFrame(() => requestAnimationFrame(resolve));
  });
}

function pageFromHash() {
  const value = location.hash.slice(1);
  return Object.hasOwn(pages, value) ? value : "snow";
}

function updateNavigation(pageName) {
  document.querySelectorAll(".nav-item").forEach((link) => {
    const active = link.dataset.page === pageName;
    link.classList.toggle("active", active);
    if (active) {
      link.setAttribute("aria-current", "page");
    } else {
      link.removeAttribute("aria-current");
    }
  });
}

/*
 * 单一切换队列。
 * 快速连点只更新目标，不会同时启动多组页面动画。
 */
async function navigate(target) {
  if (!state.entered || !Object.hasOwn(pages, target)) return;

  state.requestedPage = target;
  if (state.switching || state.currentPage === target) return;

  state.switching = true;
  $("#main").setAttribute("aria-busy", "true");

  try {
    while (state.currentPage !== state.requestedPage) {
      const oldPage = pages[state.currentPage];
      oldPage.classList.add("faded");
      await wait(reducedMotion.matches ? 160 : 520);

      oldPage.hidden = true;
      oldPage.classList.remove("faded");

      const nextName = state.requestedPage;
      const nextPage = pages[nextName];

      nextPage.classList.add("faded");
      nextPage.hidden = false;
      state.currentPage = nextName;
      updateNavigation(nextName);
      window.scrollTo({ top: 0, left: 0, behavior: "instant" });

      await nextFrame();
      nextPage.classList.remove("faded");
      await wait(reducedMotion.matches ? 160 : 520);
    }
  } finally {
    state.switching = false;
    $("#main").removeAttribute("aria-busy");
    pages[state.currentPage].querySelector("h2")
      .focus({ preventScroll: true });
  }
}

document.querySelectorAll("[data-page]").forEach((link) => {
  link.addEventListener("click", (event) => {
    event.preventDefault();
    if (!state.entered) return;

    const target = link.dataset.page;

    if (link.classList.contains("nav-item")) {
      link.classList.remove("turning");
      void link.offsetWidth;
      link.classList.add("turning");
    }

    if (location.hash !== `#${target}`) {
      location.hash = target;
    }
    void navigate(target);
  });
});

window.addEventListener("hashchange", () => {
  void navigate(pageFromHash());
});

/* 反馈列表：不使用 innerHTML 拼接配置内容。 */
const gallery = $("#feedback-gallery");
const feedbackButtons = [];

FEEDBACK_IMAGES.forEach((item, index) => {
  const button = document.createElement("button");
  button.type = "button";
  button.className = "feedback-item";
  button.setAttribute("aria-label", `放大${item.alt || `客户反馈 ${index + 1}`}`);

  const img = document.createElement("img");
  img.src = item.src;
  img.alt = item.alt || `客户反馈 ${index + 1}`;
  img.loading = "lazy";
  img.decoding = "async";

  const caption = document.createElement("span");
  caption.className = "feedback-caption";
  caption.textContent = `雪原回信 · ${String(index + 1).padStart(2, "0")}`;

  img.addEventListener("error", () => {
    caption.textContent = "图片暂未抵达，请检查文件路径";
  }, { once: true });

  button.append(img, caption);
  button.addEventListener("click", () => openLightbox(index));
  gallery.append(button);
  feedbackButtons.push(button);
});

if (FEEDBACK_IMAGES.length > 0) {
  $("#feedback-empty").hidden = true;
  $("#feedback-hint").hidden = false;
}

/* 图片查看器。 */
const lightbox = $("#lightbox");
const lightboxImage = $("#lightbox-image");
const closeButton = $("#lightbox-close");
let savedScroll = 0;

function renderLightbox() {
  const item = FEEDBACK_IMAGES[state.lightboxIndex];
  if (!item) return;

  lightboxImage.alt = item.alt ||
    `客户反馈 ${state.lightboxIndex + 1}`;
  lightboxImage.src = item.src;

  $("#lightbox-count").textContent =
    `${state.lightboxIndex + 1} / ${FEEDBACK_IMAGES.length}`;

  const onlyOne = FEEDBACK_IMAGES.length < 2;
  $("#lightbox-prev").disabled = onlyOne;
  $("#lightbox-next").disabled = onlyOne;
}

lightboxImage.addEventListener("error", () => {
  if (!lightbox.hidden) {
    notify("这张图片未能加载，请检查图片路径。");
  }
});

function openLightbox(index) {
  if (!FEEDBACK_IMAGES[index]) return;

  state.lightboxIndex = index;
  state.previousFocus = document.activeElement;
  savedScroll = window.scrollY;

  renderLightbox();
  lightbox.hidden = false;
  setSiteInteractive(false);

  // 固定body可避免iPhone Safari中弹层背后的页面滚动。
  document.body.classList.add("modal-open");
  document.body.style.position = "fixed";
  document.body.style.top = `-${savedScroll}px`;
  document.body.style.width = "100%";

  closeButton.focus();
}

function closeLightbox() {
  if (lightbox.hidden) return;

  lightbox.hidden = true;
  document.body.classList.remove("modal-open");
  document.body.style.position = "";
  document.body.style.top = "";
  document.body.style.width = "";
  setSiteInteractive(true);
  window.scrollTo(0, savedScroll);
  state.previousFocus?.focus({ preventScroll: true });
}

function moveLightbox(direction) {
  if (FEEDBACK_IMAGES.length < 2) return;

  state.lightboxIndex = (
    state.lightboxIndex + direction + FEEDBACK_IMAGES.length
  ) % FEEDBACK_IMAGES.length;

  renderLightbox();
}

closeButton.addEventListener("click", closeLightbox);
$("#lightbox-prev").addEventListener("click", () => moveLightbox(-1));
$("#lightbox-next").addEventListener("click", () => moveLightbox(1));

$("#lightbox-stage").addEventListener("click", (event) => {
  if (event.target === event.currentTarget) closeLightbox();
});

document.addEventListener("keydown", (event) => {
  if (lightbox.hidden) return;

  if (event.key === "Escape") closeLightbox();
  if (event.key === "ArrowLeft") moveLightbox(-1);
  if (event.key === "ArrowRight") moveLightbox(1);

  if (event.key === "Tab") {
    const controls = [...lightbox.querySelectorAll("button")]
      .filter((button) => !button.disabled);

    const first = controls[0];
    const last = controls[controls.length - 1];

    if (event.shiftKey && document.activeElement === first) {
      event.preventDefault();
      last.focus();
    } else if (!event.shiftKey && document.activeElement === last) {
      event.preventDefault();
      first.focus();
    }
  }
});

/* 单指横向滑动换图；多指操作留给浏览器缩放。 */
let touchStart = null;
const stage = $("#lightbox-stage");

stage.addEventListener("touchstart", (event) => {
  if (event.touches.length !== 1) {
    touchStart = null;
    return;
  }

  touchStart = {
    x: event.touches[0].clientX,
    y: event.touches[0].clientY
  };
}, { passive: true });

stage.addEventListener("touchend", (event) => {
  if (!touchStart || event.touches.length > 0) return;

  const end = event.changedTouches[0];
  const dx = end.clientX - touchStart.x;
  const dy = end.clientY - touchStart.y;

  if (Math.abs(dx) > 55 && Math.abs(dx) > Math.abs(dy) * 1.4) {
    moveLightbox(dx < 0 ? 1 : -1);
  }

  touchStart = null;
}, { passive: true });

stage.addEventListener("touchcancel", () => {
  touchStart = null;
}, { passive: true });

/*
 * Canvas细雪：一个requestAnimationFrame循环。
 * 页面隐藏或用户要求减少动态效果时暂停。
 */
const canvas = $("#snow");
const context = canvas.getContext("2d");
let flakes = [];
let snowFrame = 0;
let snowWidth = 0;
let snowHeight = 0;
let lastTime = 0;

function resizeSnow() {
  if (!context) return;

  snowWidth = window.innerWidth;
  snowHeight = window.innerHeight;
  const ratio = Math.min(window.devicePixelRatio || 1, 2);

  canvas.width = Math.round(snowWidth * ratio);
  canvas.height = Math.round(snowHeight * ratio);
  context.setTransform(ratio, 0, 0, ratio, 0, 0);

  const count = snowWidth < 700 ? 38 : 68;
  flakes = Array.from({ length: count }, () => ({
    x: Math.random() * snowWidth,
    y: Math.random() * snowHeight,
    radius: .6 + Math.random() * 1.7,
    speed: 9 + Math.random() * 17,
    drift: Math.random() * Math.PI * 2,
    opacity: .25 + Math.random() * .5
  }));

  if (reducedMotion.matches) {
    context.clearRect(0, 0, snowWidth, snowHeight);
  }
}

function drawSnow(time) {
  const dt = lastTime ? Math.min((time - lastTime) / 1000, .05) : 0;
  lastTime = time;
  context.clearRect(0, 0, snowWidth, snowHeight);

  for (const flake of flakes) {
    flake.y += flake.speed * dt;
    flake.x += Math.sin(time / 3500 + flake.drift) * dt * 5;

    if (flake.y > snowHeight + 5) {
      flake.y = -5;
      flake.x = Math.random() * snowWidth;
    }

    if (flake.x < -5) flake.x = snowWidth + 5;
    if (flake.x > snowWidth + 5) flake.x = -5;

    context.beginPath();
    context.arc(flake.x, flake.y, flake.radius, 0, Math.PI * 2);
    context.fillStyle = `rgba(255,255,255,${flake.opacity})`;
    context.fill();
  }

  snowFrame = requestAnimationFrame(drawSnow);
}

function syncSnow() {
  if (!context) return;

  cancelAnimationFrame(snowFrame);
  lastTime = 0;

  if (!document.hidden && !reducedMotion.matches) {
    snowFrame = requestAnimationFrame(drawSnow);
  } else {
    context.clearRect(0, 0, snowWidth, snowHeight);
  }
}

window.addEventListener("resize", resizeSnow, { passive: true });
document.addEventListener("visibilitychange", syncSnow);

if (reducedMotion.addEventListener) {
  reducedMotion.addEventListener("change", syncSnow);
} else {
  reducedMotion.addListener(syncSnow);
}

resizeSnow();
syncSnow();
