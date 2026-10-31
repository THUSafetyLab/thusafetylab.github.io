---
layout: page
title: Human-centered Risk Assessment & Safety Performance Evaluation
description: Human-centered methods that model driver attention, quantify integrated driving risk, predict occupant injury severity, and evaluate automated-vehicle safety by both collision occurrence and injury severity.
importance: 1
category: research
giscus_comments: false # 关闭评论
related_publications: false # 关闭引用文献区块
img: assets/img/Research_1/human-centered method.jpg

# Public resources. Update the empty URLs when datasets/code are released.
resources:
  ada_code: "https://github.com/ShunGan/ADA"
  vehicle_crash_database: "https://github.com/wangqf1997/Vehicle-Crash-Database"
  experimental_dataset: ""
---


<style>
.post-header,
.post-description {
  display: none !important;
}

.research-detail-page {
  --rd-purple: #5b21b6;
  --rd-purple-dark: #351063;
  --rd-purple-soft: #f4efff;
  --rd-purple-line: #ded2f6;
  --rd-text: #202033;
  --rd-muted: #67677a;
  --rd-border: #e7e4ee;
  --rd-card: #ffffff;
  color: var(--rd-text);
}

.research-detail-page a {
  text-decoration-thickness: 1px;
  text-underline-offset: 3px;
}

/* Hero */
.research-hero {
  position: relative;
  overflow: hidden;
  min-height: 430px;
  margin: 10px 0 22px;
  border: 1px solid var(--rd-border);
  border-radius: 22px;
  background: #fff;
  /* 背景图透明度：0 = 完全透明，1 = 完全不透明 */
  --hero-img-opacity: 1;
}

/* 背景图层 */
.research-hero::before {
  content: "";
  position: absolute;
  inset: 0;
  z-index: 0;
  background: url("{{ '/assets/img/Research_1/human-centered method.jpg' | relative_url }}") center / cover no-repeat;
  opacity: var(--hero-img-opacity);
}

/* 白色渐变遮罩层（保证左侧文字清晰） */
.research-hero::after {
  content: "";
  position: absolute;
  inset: 0;
  z-index: 1;
  background: linear-gradient(90deg,
    rgba(255,255,255,0.99) 0%,
    rgba(255,255,255,0.97) 40%,
    rgba(255,255,255,0.72) 62%,
    rgba(255,255,255,0.10) 100%);
}

.research-hero-inner {
  position: relative;
  z-index: 2;
  width: min(68%, 760px);
  padding: 66px 58px 58px;
}

.research-eyebrow {
  display: inline-flex;
  margin-bottom: 16px;
  color: var(--rd-purple);
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.research-hero h1 {
  margin: 0 0 20px;
  color: var(--rd-purple-dark);
  font-size: clamp(38px, 5vw, 62px);
  font-weight: 750;
  line-height: 1.05;
  letter-spacing: -0.035em;
}

.research-hero p {
  max-width: 720px;
  margin: 0;
  color: #3d3d4c;
  font-size: 18px;
  line-height: 1.72;
}

.research-flow {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 28px;
}

.research-flow span {
  padding: 8px 12px;
  border: 1px solid rgba(91,33,182,0.18);
  border-radius: 999px;
  background: rgba(255,255,255,0.84);
  color: var(--rd-purple-dark);
  font-size: 13px;
  font-weight: 650;
}

/* Metrics */
.research-metrics {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
  margin: 0 0 22px;
}

.metric-card {
  min-height: 118px;
  padding: 22px 24px;
  border: 1px solid var(--rd-border);
  border-radius: 16px;
  background: linear-gradient(135deg, #fff 0%, #f7f3ff 100%);
  box-shadow: 0 6px 22px rgba(42, 24, 72, 0.045);
}

.metric-value {
  margin-bottom: 5px;
  color: var(--rd-purple);
  font-size: 29px;
  font-weight: 780;
  line-height: 1;
}

.metric-title {
  margin-bottom: 5px;
  color: var(--rd-text);
  font-size: 15px;
  font-weight: 700;
}

.metric-note {
  color: var(--rd-muted);
  font-size: 13px;
  line-height: 1.5;
}

/* Sticky local navigation */
.research-subnav {
  position: sticky;
  top: 66px;
  z-index: 20;
  display: flex;
  gap: 2px;
  overflow-x: auto;
  margin: 0 0 42px;
  padding: 0 4px;
  border-bottom: 1px solid var(--rd-border);
  background: var(--global-bg-color, #fff);
  scrollbar-width: none;
}

.research-subnav::-webkit-scrollbar {
  display: none;
}

.research-subnav a {
  flex: 0 0 auto;
  padding: 15px 16px 13px;
  border-bottom: 2px solid transparent;
  color: var(--rd-muted) !important;
  font-size: 13px;
  font-weight: 650;
  text-decoration: none !important;
}

.research-subnav a:hover {
  border-bottom-color: var(--rd-purple);
  color: var(--rd-purple) !important;
}

/* Overview */
.research-overview {
  display: grid;
  grid-template-columns: minmax(150px, 0.32fr) minmax(0, 1.68fr);
  gap: 42px;
  align-items: start;
  margin-bottom: 72px;
  padding: 10px 0 48px;
  border-bottom: 1px solid var(--rd-border);
}

.overview-title {
  position: sticky;
  top: 128px;
}

.overview-kicker {
  display: inline-block;
  margin-bottom: 10px;
  color: var(--rd-purple);
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.overview-title h2,
.resources-section h2 {
  margin: 0;
  color: var(--rd-text);
  font-size: 32px;
  font-weight: 750;
  line-height: 1.15;
  letter-spacing: -0.02em;
}

.overview-content {
  min-width: 0;
}

.overview-objective {
  margin: 0 0 20px;
  padding: 22px 24px;
  border: 1px solid var(--rd-purple-line);
  border-left: 4px solid var(--rd-purple);
  border-radius: 12px;
  background: linear-gradient(135deg, #faf7ff 0%, var(--rd-purple-soft) 100%);
  color: #393345;
  font-size: 15px;
  line-height: 1.72;
}

.overview-content p {
  max-width: 900px;
  margin: 0;
  color: var(--rd-muted);
  font-size: 16px;
  line-height: 1.8;
}

/* Research sections */
.research-section {
  scroll-margin-top: 120px;
  margin: 0 0 74px;
  padding-top: 8px;
}

.section-heading {
  display: grid;
  grid-template-columns: 64px minmax(0, 1fr);
  gap: 18px;
  align-items: start;
  margin-bottom: 26px;
}

.section-number {
  color: var(--rd-purple);
  font-family: Georgia, "Times New Roman", serif;
  font-size: 52px;
  line-height: 0.95;
}

.section-heading h2 {
  margin: 0 0 7px;
  color: var(--rd-text);
  font-size: 28px;
  font-weight: 750;
  line-height: 1.18;
  letter-spacing: -0.02em;
}

.section-heading h2 a {
  color: inherit !important;
  text-decoration: none !important;
}

.section-lead {
  margin: 0;
  color: var(--rd-muted);
  font-size: 15px;
  line-height: 1.55;
}

.section-stats {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 13px;
}

.section-stats span {
  padding: 6px 10px;
  border: 1px solid var(--rd-purple-line);
  border-radius: 999px;
  background: var(--rd-purple-soft);
  color: var(--rd-purple-dark);
  font-size: 12px;
  font-weight: 650;
}

.research-section h3 {
  margin: 30px 0 13px;
  color: var(--rd-purple-dark);
  font-size: 19px;
  font-weight: 730;
}

.research-section p,
.research-section li {
  color: var(--rd-muted);
  font-size: 15px;
  line-height: 1.72;
}

.research-section > p {
  max-width: 980px;
}

.research-section strong {
  color: var(--rd-text);
}

.research-section .row {
  margin-top: 20px !important;
  margin-bottom: 8px !important;
}

.research-section figure,
.research-section img {
  border-radius: 12px;
}

.research-section .z-depth-1 {
  box-shadow: 0 8px 24px rgba(33, 25, 48, 0.08) !important;
}

.research-section .caption {
  margin-top: 9px !important;
  color: #858394;
  font-size: 12px;
  line-height: 1.45;
  text-align: center;
}

.research-section img[src$=".gif"] {
  border: 1px solid var(--rd-border);
  background: #fff;
}


/* =========================================================
   Paper layout: compact image gallery + text
   ========================================================= */

.paper-layout {
  display: grid;
  grid-template-columns: minmax(280px, 0.78fr) minmax(0, 1.22fr);
  gap: 38px;
  align-items: start;
  margin-top: 24px;
}

.paper-layout.gallery-right {
  grid-template-columns: minmax(0, 1.22fr) minmax(280px, 0.78fr);
}

.paper-layout.gallery-right .paper-gallery {
  order: 2;
  justify-self: end;
}

.paper-layout.gallery-right .paper-copy {
  order: 1;
}

.paper-copy {
  min-width: 0;
}

.paper-copy h3:first-child {
  margin-top: 0;
}

/* Gallery stays compact and follows the text while reading */
.paper-gallery {
  width: 100%;
  max-width: 430px;
  position: sticky;
  top: 120px;
  align-self: start;
}

.gallery-main {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 300px;
  padding: 12px;
  overflow: hidden;
  border: 1px solid var(--rd-border);
  border-radius: 14px;
  background: #fff;
  box-shadow: 0 8px 24px rgba(33, 25, 48, 0.06);
}

.gallery-main img {
  display: block;
  width: 100%;
  height: 100%;
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
  object-position: center;
  border-radius: 8px;
  box-shadow: none !important;
}

.gallery-main video {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: contain;
  border-radius: 8px;
  background: #000;
}

/* Keep hidden image/video out of the layout (overrides display: block above) */
.gallery-main [hidden] {
  display: none !important;
}

.gallery-caption {
  min-height: 38px;
  margin: 9px 2px 10px;
  color: #858394;
  font-size: 11.5px;
  line-height: 1.45;
  text-align: center;
}

.gallery-thumbs {
  display: flex;
  gap: 8px;
  overflow-x: auto;
  padding: 2px 1px 5px;
  scrollbar-width: thin;
}

.gallery-thumb {
  flex: 0 0 72px;
  width: 72px;
  height: 54px;
  padding: 3px;
  overflow: hidden;
  cursor: pointer;
  border: 1px solid var(--rd-border);
  border-radius: 8px;
  background: #fff;
  opacity: 0.72;
  transition:
    opacity 0.2s ease,
    border-color 0.2s ease,
    box-shadow 0.2s ease,
    transform 0.2s ease;
}

.gallery-thumb:hover {
  opacity: 1;
  transform: translateY(-1px);
}

.gallery-thumb.active {
  opacity: 1;
  border-color: var(--rd-purple);
  box-shadow: 0 0 0 2px rgba(91, 33, 182, 0.10);
}

.gallery-thumb img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 5px;
  box-shadow: none !important;
}

/* Video thumbnail: play label instead of a preview image */
.gallery-thumb-video {
  display: flex;
  align-items: center;
  justify-content: center;
  background: var(--rd-purple-soft);
  color: var(--rd-purple);
  font-size: 11px;
  font-weight: 700;
  white-space: nowrap;
}

/* Narrow table used only for the automation-level safety-benefit result */
.safety-benefit-table {
  width: min(100%, 680px);
  margin: 16px auto 24px;
}

.safety-benefit-table table {
  width: 100% !important;
  margin: 0 !important;
  font-size: 12.8px;
}

.safety-benefit-table th,
.safety-benefit-table td {
  padding: 9px 10px !important;
}

.safety-benefit-table th:first-child,
.safety-benefit-table td:first-child {
  white-space: nowrap;
}

/* Tablet/mobile */
@media (max-width: 900px) {
  .paper-layout,
  .paper-layout.gallery-right {
    grid-template-columns: 1fr;
    gap: 24px;
  }

  .paper-layout.gallery-right .paper-gallery,
  .paper-layout.gallery-right .paper-copy {
    order: initial;
  }

  .paper-gallery {
    position: static;
    max-width: 620px;
    justify-self: center !important;
  }

  .gallery-main {
    height: 340px;
  }
}

@media (max-width: 640px) {
  .gallery-main {
    height: 250px;
  }

  .gallery-thumb {
    flex-basis: 64px;
    width: 64px;
    height: 48px;
  }

  .safety-benefit-table {
    width: 100%;
    overflow-x: auto;
  }

  .safety-benefit-table table {
    min-width: 600px;
  }
}


/* Tables */
.research-detail-page table {
  width: 100%;
  margin: 18px 0 26px;
  overflow: hidden;
  border: 1px solid var(--rd-border);
  border-radius: 12px;
  border-collapse: separate;
  border-spacing: 0;
  background: #fff;
  font-size: 14px;
}

.research-detail-page thead th,
.research-detail-page th {
  padding: 12px 14px;
  border-bottom: 1px solid var(--rd-border);
  background: #f5f1fc;
  color: var(--rd-purple-dark);
  font-weight: 700;
}

.research-detail-page td {
  padding: 12px 14px;
  border-bottom: 1px solid #efedf3;
  color: var(--rd-muted);
  vertical-align: top;
}

.research-detail-page tr:last-child td {
  border-bottom: none;
}

/* Resources */
.resources-section {
  scroll-margin-top: 120px;
  margin-top: 34px;
  padding-top: 42px;
  border-top: 1px solid var(--rd-border);
}

.resources-intro {
  margin-bottom: 22px;
  color: var(--rd-muted);
}

.resources-section table td:first-child {
  width: 78%;
}

.resources-section table td:last-child {
  width: 22%;
  text-align: center;
}

.resources-section table a {
  font-weight: 620;
}

/* Responsive */
@media (max-width: 900px) {
  .research-hero {
    min-height: 0;
  }

  .research-hero::after {
    background: linear-gradient(rgba(255,255,255,0.93), rgba(255,255,255,0.95));
  }

  .research-hero-inner {
    width: 100%;
    padding: 46px 32px;
  }

  .research-metrics,
  .research-overview {
    grid-template-columns: 1fr;
  }

  .overview-title {
    position: static;
  }

  .research-subnav {
    top: 56px;
  }
}

@media (max-width: 640px) {
  .research-hero {
    border-radius: 14px;
  }

  .research-hero-inner {
    padding: 38px 22px;
  }

  .research-hero h1 {
    font-size: 38px;
  }

  .research-hero p {
    font-size: 16px;
  }

  .research-metrics {
    grid-template-columns: 1fr;
  }

  .section-heading {
    grid-template-columns: 48px minmax(0, 1fr);
    gap: 12px;
  }

  .section-number {
    font-size: 42px;
  }

  .section-heading h2 {
    font-size: 23px;
  }

  .research-detail-page table {
    display: block;
    overflow-x: auto;
  }
}

/* Five study metrics: three cards in the first row, two wider cards in the second */
.research-metrics { grid-template-columns: repeat(6, minmax(0, 1fr)); }
.research-metrics .metric-card { grid-column: span 2; }
.research-metrics .metric-card:nth-child(n+4) { grid-column: span 3; }

/* One-sentence summary of a closely related study */
.research-section .related-study {
  margin: 18px 0 0;
  padding: 13px 16px;
  border-left: 3px solid var(--rd-purple-line);
  border-radius: 8px;
  background: #faf8ff;
  font-size: 14px;
  line-height: 1.65;
}

@media (max-width: 900px) {
  .research-metrics { grid-template-columns: 1fr; }
  .research-metrics .metric-card,
  .research-metrics .metric-card:nth-child(n+4) { grid-column: auto; }
}
</style>


<div class="research-detail-page">

<section class="research-hero">
  <div class="research-hero-inner">
    <div class="research-eyebrow">Autonomous vehicle safety research</div>
    <h1>Human-centered Risk Assessment &amp; Safety Performance Evaluation</h1>
    <p>
      In safety-critical scenarios, drivers are both the people we protect and the experts we learn from. We model where drivers look, quantify how likely and how severe an emerging collision is, predict occupant injury quickly and with fewer costly simulations, and evaluate automated vehicles by both collision occurrence and injury severity.
    </p>

    <div class="research-flow">
      <span>Driver attention</span>
      <span>Integrated driving risk</span>
      <span>Injury prediction</span>
      <span>Safety evaluation</span>
    </div>
  </div>
</section>

<div class="research-metrics">
  <div class="metric-card">
    <div class="metric-value">Domain-Adaptive</div>
    <div class="metric-title">Driver attention prediction model</div>
    <div class="metric-note">Jointly trained on four driver-attention datasets, our model ranks best across seven metrics.</div>
  </div>

  <div class="metric-card">
    <div class="metric-value">0.5 s</div>
    <div class="metric-title">Earlier risk warning</div>
    <div class="metric-note">Average gain of PIRAM, which fuses collision probability and severity into one risk metric.</div>
  </div>

  <div class="metric-card">
    <div class="metric-value">85.4%</div>
    <div class="metric-title">Head-injury severity prediction accuracy</div>
    <div class="metric-note">Near-real-time prediction requiring only 1.2 ± 0.4 ms per case.</div>
  </div>

  <div class="metric-card">
    <div class="metric-value">17.6%</div>
    <div class="metric-title">Lower injury-prediction error</div>
    <div class="metric-note">Versus high-fidelity-only learning with 500 cases, by reusing low-fidelity physics priors.</div>
  </div>

  <div class="metric-card">
    <div class="metric-value">L3≈L2</div>
    <div class="metric-title">Unified safety performance</div>
    <div class="metric-note">L3 had fewer collisions than L2 but more severe injuries when collisions occurred.</div>
  </div>
</div>

<nav class="research-subnav" aria-label="Research page sections">
  <a href="#overview">Overview</a>
  <a href="#risk-perception">Risk Perception</a>
  <a href="#risk-quantification">Risk Quantification</a>
  <a href="#injury-estimation">Injury Estimation</a>
  <a href="#safety-evaluation">Safety Evaluation</a>
  <a href="#publications-data">Publications &amp; Resources</a>
</nav>


<section id="overview" class="research-overview">

  <div class="overview-title">
    <span class="overview-kicker">Research framework</span>
    <h2>Objective</h2>
  </div>

  <div class="overview-content">

    <div class="overview-objective">
      The rapid development of intelligent vehicles is reshaping how road safety is assessed and managed.
      <strong>A comprehensive safety framework requires intelligent vehicles to understand, as humans do, how risk develops, how severe the resulting impact may be, and what consequences different outcomes may have for occupants</strong>.
      Our research therefore connects traffic-level interactions with vehicle-level collision dynamics and occupant-level injury outcomes: we model driver attention to latent hazards, quantify integrated driving risk, predict occupant injury severity, and evaluate safety performance across levels of driving automation.
    </div>

  </div>

</section>


<section id="risk-perception" class="research-section" markdown="1">

<div class="section-heading">
  <div class="section-number">01</div>
  <div>
    <h2><a href="https://doi.org/10.1109/TITS.2022.3177640">Human-centered risk perception</a></h2>
    <p class="section-lead">Model how human drivers perceive and prioritize latent risks across heterogeneous and interactive traffic scenes.</p>
    <div class="section-stats">
      <span>4 jointly trained datasets</span>
      <span>Best across 7 metrics</span>
      <span>Held-out PSAD evaluation</span>
    </div>
  </div>
</div>

<div class="paper-layout">

  <aside class="paper-gallery" data-gallery="gan-2022">
    <div class="gallery-main">
      <img
        src="{{ '/assets/img/Research_1/paper_gan_2022_1.jpg' | relative_url }}"
        alt="Illustration of adaptive driver attention prediction in different driving scenes collected from multiple datasets"
      >
    </div>

    <div class="gallery-caption">
      Illustration of adaptive driver attention prediction in different driving scenes collected from multiple datasets
    </div>

    <div class="gallery-thumbs">
      <button type="button" class="gallery-thumb active"
        data-src="{{ '/assets/img/Research_1/paper_gan_2022_1.jpg' | relative_url }}"
        data-caption="Illustration of adaptive driver attention prediction in different driving scenes collected from multiple datasets"
        aria-label="Show driver-attention dataset illustration">
        <img src="{{ '/assets/img/Research_1/paper_gan_2022_1.jpg' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_gan_2022.jpg' | relative_url }}"
        data-caption="Overview of the Adaptive Driver Attention framework"
        aria-label="Show Adaptive Driver Attention framework">
        <img src="{{ '/assets/img/Research_1/paper_gan_2022.jpg' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_gan_2022_2.jpg' | relative_url }}"
        data-caption="Qualitative evaluation on four driver-attention datasets"
        aria-label="Show qualitative evaluation">
        <img src="{{ '/assets/img/Research_1/paper_gan_2022_2.jpg' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_gan_2022_5.gif' | relative_url }}"
        data-caption="Driver gaze saliency based on model prediction — example 1"
        aria-label="Show gaze saliency example 1">
        <img src="{{ '/assets/img/Research_1/paper_gan_2022_5.gif' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_gan_2022_7.gif' | relative_url }}"
        data-caption="Driver gaze saliency based on model prediction — example 2"
        aria-label="Show gaze saliency example 2">
        <img src="{{ '/assets/img/Research_1/paper_gan_2022_7.gif' | relative_url }}" alt="">
      </button>
    </div>
  </aside>

  <div class="paper-copy" markdown="1">

Human drivers do not process all visual information equally. Their attention is selectively allocated to traffic elements that are relevant to the current driving task. We developed an **Adaptive Driver Attention (ADA)** model that uses domain-adaption modules to mitigate data heterogeneity across driver-attention datasets and task-driven attention modules to replicate human-like perceptual patterns.

Jointly trained on four public driver-attention datasets — **BDD-A, DADA-2000, DReyeVE, and EyeTrack** — ADA achieved the best performance against state-of-the-art methods across **seven metrics**, and it also reached state-of-the-art performance among ten methods on **PSAD**, which was held out from joint training. With **5.63 M parameters**, it had the lowest average computation per frame among the ten methods. The predicted attention reproduces human perceptual patterns in cruising, following, turning, and crash scenes and can shift toward **latent conflict regions and relevant interacting vehicles**, providing a basis for identifying where human drivers are likely to allocate attention before and during safety-critical events.

  </div>

</div>

</section>


<section id="risk-quantification" class="research-section" markdown="1">

<div class="section-heading">
  <div class="section-number">02</div>
  <div>
    <h2><a href="https://doi.org/10.1016/j.aap.2025.108266">Physics-informed integrated driving risk</a></h2>
    <p class="section-lead">Fuse collision probability and collision severity into one integrated driving risk (IDR) metric for timely warning and occupant protection.</p>
    <div class="section-stats">
      <span>1,879 safety-critical events</span>
      <span>8.0% lower IDR MAE</span>
      <span>0.5 s earlier warnings</span>
    </div>
  </div>
</div>

<div class="paper-layout gallery-right">

  <aside class="paper-gallery" data-gallery="lu-2025">
    <div class="gallery-main">
      <img
        src="{{ '/assets/img/Research_1/paper_lu_2025_piram_framework.jpg' | relative_url }}"
        alt="Physics-informed training combines neural prediction and vehicle-dynamics guidance (Fig. 4)"
      >
    </div>

    <div class="gallery-caption">
      Physics-informed training combines neural prediction and vehicle-dynamics guidance (Fig. 4)
    </div>

    <div class="gallery-thumbs">
      <button type="button" class="gallery-thumb active"
        data-src="{{ '/assets/img/Research_1/paper_lu_2025_piram_framework.jpg' | relative_url }}"
        data-caption="Physics-informed training combines neural prediction and vehicle-dynamics guidance (Fig. 4)"
        aria-label="Show PIRAM framework">
        <img src="{{ '/assets/img/Research_1/paper_lu_2025_piram_framework.jpg' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_lu_2025_piram_risk_metric.jpg' | relative_url }}"
        data-caption="Collision probability and severity form the integrated driving risk metric (Fig. 5)"
        aria-label="Show integrated driving risk metric">
        <img src="{{ '/assets/img/Research_1/paper_lu_2025_piram_risk_metric.jpg' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_lu_2025_piram_case_result.jpg' | relative_url }}"
        data-caption="Risk evolution and protection-threshold timing in a reconstructed CIDAS crash (Fig. 8)"
        aria-label="Show real-crash case result">
        <img src="{{ '/assets/img/Research_1/paper_lu_2025_piram_case_result.jpg' | relative_url }}" alt="">
      </button>
    </div>
  </aside>

  <div class="paper-copy" markdown="1">

Collision likelihood alone cannot describe the potential harm of an emerging conflict. We built an **integrated driving risk prediction dataset (IDRPD)** from driving-simulator experiments in CARLA, containing **1,879 safety-critical events**. The **physics-informed integrated risk assessment model (PIRAM)** uses an attention mechanism to capture spatiotemporal dependencies in vehicle trajectories and map information, and a dynamic bicycle model as a physical constraint, to predict collision time and collision velocity. These predictions are converted into collision probability and MAIS-based collision severity and fused into an IDR metric.

Compared with the baseline models, PIRAM improved prediction accuracy for collision probability and severity by **7.9% and 3.2%** and prediction stability by **10.3% and 5.9%**. Its IDR MAE was **3.291 versus 3.577** for the best baseline (GRU), an **8.0%** reduction, and it enabled risk warnings **0.5 s earlier on average**. In a reconstructed real-world intersection crash from CIDAS, PIRAM reached the Level III protection threshold about **0.45 s earlier than TTC**, providing a quantitative basis for occupant protection strategies in automated vehicles.

  </div>

</div>

</section>


<section id="injury-estimation" class="research-section" markdown="1">

<div class="section-heading">
  <div class="section-number">03</div>
  <div>
    <h2><a href="https://doi.org/10.1016/j.aap.2021.106149">Occupant injury severity estimation</a></h2>
    <p class="section-lead">Predict occupant injury severity from crash dynamics, occupant characteristics, and restraint conditions with near-real-time computation.</p>
    <div class="section-stats">
      <span>28,000 numerical cases</span>
      <span>85.4% head-injury accuracy</span>
      <span>1.2 ± 0.4 ms inference</span>
      <span>192 real-world validation cases</span>
    </div>
  </div>
</div>

<div class="paper-layout">

  <aside class="paper-gallery" data-gallery="wang-2021">
    <div class="gallery-main">
      <img
        src="{{ '/assets/img/Research_1/paper_wang_2021_1.png' | relative_url }}"
        alt="Technical framework of near-real-time occupant injury prediction"
      >
    </div>

    <div class="gallery-caption">
      Technical framework of near-real-time occupant injury prediction
    </div>

    <div class="gallery-thumbs">
      <button type="button" class="gallery-thumb active"
        data-src="{{ '/assets/img/Research_1/paper_wang_2021_1.png' | relative_url }}"
        data-caption="Technical framework of near-real-time occupant injury prediction"
        aria-label="Show injury prediction framework">
        <img src="{{ '/assets/img/Research_1/paper_wang_2021_1.png' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_wang_2021_2.png' | relative_url }}"
        data-caption="Ratios of cases with different AIS levels in the numerical database"
        aria-label="Show AIS-level distribution">
        <img src="{{ '/assets/img/Research_1/paper_wang_2021_2.png' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_wang_2021.png' | relative_url }}"
        data-caption="Optimized architectures of RNN and CNN"
        aria-label="Show optimized RNN and CNN architectures">
        <img src="{{ '/assets/img/Research_1/paper_wang_2021.png' | relative_url }}" alt="">
      </button>
    </div>
  </aside>

  <div class="paper-copy" markdown="1">

Occupant injury is governed by complex interactions among vehicle crash dynamics, occupant characteristics, and restraint conditions, making rapid and reliable injury assessment challenging. Using a **28,000-case numerical database** of frontal crashes, we first trained a convolutional neural network to predict occupant kinetics and injury severity. Guided by visualization of this network, we then extracted simplified kinematic features from vehicle crash pulses and combined them with a low-complexity machine-learning model, greatly reducing computation while maintaining accuracy.

On the numerical database, the final model predicted head injury severity with **85.4%** accuracy, comparable to the CNN-based model (86.1%). On an independent dataset of **192 real-world collisions** with seven injury severity levels, it achieved **78.7%** accuracy, a precision of 0.636, a recall of 0.787, and an AUC of 0.698. Each prediction takes only **1.2 ± 0.4 ms**, providing a decision reference for pre-crash trajectory planning and in-crash adaptive restraint systems.

  </div>

</div>

</section>


<section id="multi-fidelity-injury" class="research-section" markdown="1">

<div class="section-heading">
  <div class="section-number">04</div>
  <div>
    <h2><a href="https://doi.org/10.1016/j.aei.2026.105117">Knowledge-guided multi-fidelity injury prediction</a></h2>
    <p class="section-lead">Reduce the dependence of injury prediction on expensive high-fidelity crash simulations by reusing physics priors from low-fidelity simulations.</p>
    <div class="section-stats">
      <span>17.6% lower MAE</span>
      <span>500 HF + 4,000 LF cases</span>
      <span>598-case test set</span>
    </div>
  </div>
</div>

<div class="paper-layout gallery-right">

  <aside class="paper-gallery" data-gallery="lu-2026">
    <div class="gallery-main">
      <img
        src="{{ '/assets/img/Research_1/paper_lu_2026_mfpgrnet_framework.jpg' | relative_url }}"
        alt="Low-fidelity prior retrieval and high-fidelity residual learning (Fig. 2)"
      >
    </div>

    <div class="gallery-caption">
      Low-fidelity prior retrieval and high-fidelity residual learning (Fig. 2)
    </div>

    <div class="gallery-thumbs">
      <button type="button" class="gallery-thumb active"
        data-src="{{ '/assets/img/Research_1/paper_lu_2026_mfpgrnet_framework.jpg' | relative_url }}"
        data-caption="Low-fidelity prior retrieval and high-fidelity residual learning (Fig. 2)"
        aria-label="Show MF-PGRNet framework">
        <img src="{{ '/assets/img/Research_1/paper_lu_2026_mfpgrnet_framework.jpg' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_lu_2026_mfpgrnet_sample_efficiency.jpg' | relative_url }}"
        data-caption="Prediction error and R-squared across high-fidelity training-set sizes (Fig. 4)"
        aria-label="Show sample-efficiency results">
        <img src="{{ '/assets/img/Research_1/paper_lu_2026_mfpgrnet_sample_efficiency.jpg' | relative_url }}" alt="">
      </button>
    </div>
  </aside>

  <div class="paper-copy" markdown="1">

High-fidelity (HF) crash simulations capture human injury mechanisms more realistically but are expensive to generate at scale, especially early in vehicle development. Low-fidelity (LF) simulations are cheap but carry systematic biases and have no one-to-one correspondence with HF cases. **MF-PGRNet** retrieves relevant LF physics priors for each HF query through learnable prototypes, decomposes the prediction into an LF-derived trend and an HF-specific residual correction, and uses a relational knowledge-distillation loss to stabilize learning when HF data are scarce.

Trained on **500 HF and 4,000 LF rear-end crash simulations**, MF-PGRNet reduced MAE by **17.6%** on average across HIC, Nij, and Dmax compared with an HF-only model. On the same **598-case test set**, its HIC MAE with 500 HF cases (**78.34**) was lower than that of the HF-only model trained with **1,000 HF cases (82.85)**, roughly halving the HF simulations required for comparable accuracy.

  </div>

</div>

</section>


<section id="safety-evaluation" class="research-section" markdown="1">

<div class="section-heading">
  <div class="section-number">05</div>
  <div>
    <h2><a href="https://doi.org/10.1016/j.aap.2025.108273">Safety performance evaluation</a></h2>
    <p class="section-lead">Evaluate automated-driving safety by jointly considering collision occurrence and occupant injury severity under standardized safety-critical scenarios.</p>
    <div class="section-stats">
      <span>30 participants</span>
      <span>1,859 interactions</span>
      <span>337 collisions</span>
      <span>SAE L0/L2/L3/L4 comparison</span>
    </div>
  </div>
</div>

<div class="paper-layout">

  <aside class="paper-gallery" data-gallery="shen-2025">
    <div class="gallery-main">
      <img
        src="{{ '/assets/img/Research_1/paper_shen_2025_1.jpg' | relative_url }}"
        alt="Simulated highway safety-critical scenarios and experimental procedure"
        hidden
      >
      <!-- The video is shown first; the gallery script switches to images when their thumbnails are clicked -->
      <video controls playsinline preload="metadata"
        src="{{ '/assets/img/Research_1/paper_shen_2025_5.mp4' | relative_url }}"
        aria-label="Driving-simulator experiment video"></video>
    </div>

    <div class="gallery-caption">
      Driving-simulator experiment video
    </div>

    <div class="gallery-thumbs">
      <button type="button" class="gallery-thumb gallery-thumb-video active"
        data-type="video"
        data-src="{{ '/assets/img/Research_1/paper_shen_2025_5.mp4' | relative_url }}"
        data-caption="Driving-simulator experiment video"
        aria-label="Play driving-simulator experiment video">
        <span aria-hidden="true">&#9654; Video</span>
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_shen_2025_1.jpg' | relative_url }}"
        data-caption="Simulated highway safety-critical scenarios and experimental procedure"
        aria-label="Show experimental framework">
        <img src="{{ '/assets/img/Research_1/paper_shen_2025_1.jpg' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_shen_2025_4.jpg' | relative_url }}"
        data-caption="Distribution of safety performance evaluation datasets across different levels of driving automation"
        aria-label="Show safety-evaluation dataset distribution">
        <img src="{{ '/assets/img/Research_1/paper_shen_2025_4.jpg' | relative_url }}" alt="">
      </button>

      <button type="button" class="gallery-thumb"
        data-src="{{ '/assets/img/Research_1/paper_shen_2025.png' | relative_url }}"
        data-caption="Limitations of existing safety evaluation approaches and the proposed unified experimental framework"
        aria-label="Show unified experimental framework">
        <img src="{{ '/assets/img/Research_1/paper_shen_2025.png' | relative_url }}" alt="">
      </button>
    </div>
  </aside>

  <div class="paper-copy" markdown="1">

Existing real-world datasets for evaluating the safety protection performance of automated vehicles differ substantially from those of conventional vehicles in terms of accumulated mileage, crash types, and other characteristics, making direct comparisons across manufacturers and levels of driving automation difficult. To address this issue, we developed a unified driving-simulator-based framework that integrates automated vehicle models at different levels of automation, an accelerated generation algorithm for highway safety-critical scenarios, and a data-driven occupant injury quantification model, enabling fair comparisons under comparable road scenarios, similar urgency levels, and consistent evaluation metrics.

The final dataset comprised 30 valid participants and 1,859 safety-critical vehicle interactions, including 337 collisions. We developed a metric (**unified safety benefit**) that evaluates automated-driving safety through both **collision occurrence and occupant injury severity**. Vehicles representing **attentive manual driving (AMD, a subset of SAE L0) and SAE L2, L3, and L4 automation** were compared. Under the designed safety-critical scenarios, the study reported:

<div class="safety-benefit-table" markdown="1">

| Automation level | Collision rate | Probability of severe injury in collisions (MAIS3+) | Unified safety benefit |
| --- | ---: | ---: | ---: |
| AMD (L0) | 12.6% | 8.7% | 94.0% |
| L2 | 24.3% | 11.1% | 90.0% |
| L3 | 21.4% | 21.6% | 89.0% |
| L4 | 14.1% | 9.2% | 95.0% |

</div>

The results show that **a lower collision rate does not necessarily translate into a proportionally higher overall safety benefit**. **Level 3 automation reduced collision occurrence relative to Level 2 but exhibited higher injury severity when collisions occurred, resulting in comparable unified safety benefits**. Level 4 achieved the highest unified safety benefit, mainly because of its lower collision rate, while injury severity once a collision occurred remained similar to that of Level 2.

<p class="related-study"><strong>Related study:</strong> <a href="https://doi.org/10.1109/THMS.2025.3567611">Qin et al. (IEEE THMS 2025)</a> modeled drivers' perception-response time as visual evidence accumulation; across 864 safety-critical trials from 24 experienced drivers, the model predicted response time more accurately than a fixed-threshold model (MSE 1.15 × 10<sup>−2</sup> vs. 2.99 × 10<sup>−2</sup>), supporting personalized ADAS activation timing.</p>

  </div>

</div>

</section>


<section id="publications-data" class="resources-section" markdown="1">

## Publications & Resources

| Paper | Data & Code |
| :--- | :---: |
| [**Gan, S., et al.** (2022). Multisource Adaption for Driver Attention Prediction in Arbitrary Driving Scenes. *IEEE Transactions on Intelligent Transportation Systems, 23*(11), 20912–20925. https://doi.org/10.1109/TITS.2022.3177640](https://doi.org/10.1109/TITS.2022.3177640) | {% if page.resources.ada_code and page.resources.ada_code != "" %}[ADA code]({{ page.resources.ada_code }}){% else %}ADA code{% endif %} |
| [**Lu, T., et al.** (2025). A physics-informed attention model for integrated driving risk assessment. *Accident Analysis & Prevention, 223*, 108266. https://doi.org/10.1016/j.aap.2025.108266](https://doi.org/10.1016/j.aap.2025.108266) | Data available on request |
| [**Wang, Q., et al.** (2021). A data-driven, kinematic feature-based, near real-time algorithm for injury severity prediction of vehicle occupants. *Accident Analysis & Prevention, 156*, 106149. https://doi.org/10.1016/j.aap.2021.106149](https://doi.org/10.1016/j.aap.2021.106149) | {% if page.resources.vehicle_crash_database and page.resources.vehicle_crash_database != "" %}[Vehicle-crash dataset]({{ page.resources.vehicle_crash_database }}){% else %}Vehicle-crash dataset{% endif %} |
| [**Lu, T., et al.** (2026). A knowledge-guided multi-fidelity residual learning framework for occupant injury prediction from crash simulations. *Advanced Engineering Informatics, 76*, 105117. https://doi.org/10.1016/j.aei.2026.105117](https://doi.org/10.1016/j.aei.2026.105117) | Data available on request |
| [**Shen, J., et al.** (2025). A unified experimental framework for estimating collision rates and occupant injury severity across different levels of driving automation. *Accident Analysis & Prevention, 223*, 108273. https://doi.org/10.1016/j.aap.2025.108273](https://doi.org/10.1016/j.aap.2025.108273) | {% if page.resources.experimental_dataset and page.resources.experimental_dataset != "" %}[Experimental dataset]({{ page.resources.experimental_dataset }}){% else %}Experimental dataset (release in preparation){% endif %} |
| [**Qin, D., et al.** (2025). When do drivers maneuver: Experimental investigation and inference of perception-response time for tailored safety systems in intelligent vehicles. *IEEE Transactions on Human-Machine Systems, 55*(4), 609–618. https://doi.org/10.1109/THMS.2025.3567611](https://doi.org/10.1109/THMS.2025.3567611) | — |

</section>


<script>
document.addEventListener("DOMContentLoaded", function () {
  document.querySelectorAll(".paper-gallery").forEach(function (gallery) {
    const mainImage = gallery.querySelector(".gallery-main img");
    const mainVideo = gallery.querySelector(".gallery-main video");
    const caption = gallery.querySelector(".gallery-caption");
    const thumbs = gallery.querySelectorAll(".gallery-thumb");

    thumbs.forEach(function (thumb) {
      thumb.addEventListener("click", function () {
        const nextSrc = thumb.dataset.src;
        const nextCaption = thumb.dataset.caption || "";
        const isVideo = thumb.dataset.type === "video" && mainVideo;

        if (nextSrc && isVideo) {
          mainImage.hidden = true;
          mainVideo.hidden = false;
          if (mainVideo.getAttribute("src") !== nextSrc) {
            mainVideo.src = nextSrc;
          }
          mainVideo.setAttribute("aria-label", nextCaption);
        } else if (nextSrc) {
          if (mainVideo) {
            mainVideo.pause();
            mainVideo.hidden = true;
          }
          mainImage.hidden = false;
          mainImage.src = nextSrc;
          mainImage.alt = nextCaption;
        }

        caption.textContent = nextCaption;

        thumbs.forEach(function (item) {
          item.classList.remove("active");
        });

        thumb.classList.add("active");
      });
    });
  });
});
</script>


</div>
