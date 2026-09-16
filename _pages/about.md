---
permalink: /
lang: en
title: ""
excerpt: "Hailong Zou is a Ph.D. Student at Peking University working on efficient AI systems, on-device and edge AI, and hardware-software co-design for foundation-model inference."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<section class="intro-card">
  <div class="intro-copy">
    <div class="intro-meta">
      <p class="intro-kicker" data-i18n="intro.kicker">Ph.D. Student · Efficient AI Systems · On-device AI · Hardware-Software Co-Design</p>
      <nav class="language-switcher" aria-label="Language selection" data-i18n-aria-label="language.label">
        <button type="button" data-language-option="en" aria-pressed="true">EN</button>
        <button type="button" data-language-option="zh" aria-pressed="false">中文</button>
      </nav>
    </div>
    <h1 data-i18n="profile.name">Hailong Zou</h1>
    <p class="intro-lead" data-i18n-html="intro.lead">I am a Ph.D. Student in Computer Science and Technology at the School of Computer Science, Peking University, starting in September 2026. At the <a href="https://if-lab-pku.github.io/">Intelligence Fusion Laboratory (IF-Lab)</a>, I am advised by <a href="https://cs.pku.edu.cn/info/1210/2865.htm">Prof. Xiang Chen</a>. I work on efficient AI systems, with a focus on on-device foundation-model inference and hardware-software co-design for heterogeneous, resource-constrained platforms.</p>
    <p data-i18n="intro.education">I received my M.Eng. in Circuits and Systems from the Institute of Microelectronics, Chinese Academy of Sciences, and my B.Eng. in Electronic Information Engineering from Wuhan University.</p>
  </div>
</section>

<span class="anchor" id="research"></span>

<h2 data-i18n="section.research">Research Interests</h2>

<div class="focus-grid">
  <div class="focus-card">
    <h3><span class="card-icon"><i class="fas fa-bolt" aria-hidden="true"></i></span><span data-i18n="focus.efficient.title">Efficient AI Systems</span></h3>
    <p data-i18n="focus.efficient.description">Efficient inference for foundation models, including LLM and MoE systems, caching, and model-system techniques that reduce memory and computation.</p>
  </div>
  <div class="focus-card">
    <h3><span class="card-icon"><i class="fas fa-microchip" aria-hidden="true"></i></span><span data-i18n="focus.codesign.title">Hardware-Software Co-Design</span></h3>
    <p data-i18n="focus.codesign.description">Architecture-aware optimization across models, compilers, runtimes, and heterogeneous CPU, NPU, and accelerator platforms.</p>
  </div>
  <div class="focus-card">
    <h3><span class="card-icon"><i class="fas fa-network-wired" aria-hidden="true"></i></span><span data-i18n="focus.edge.title">On-device &amp; Edge AI</span></h3>
    <p data-i18n="focus.edge.description">On-device deployment and edge-cloud collaboration under practical memory, storage, bandwidth, and latency constraints.</p>
  </div>
</div>

<span class="anchor" id="selected-research"></span>

<h2 data-i18n="section.selectedResearch">Selected Research</h2>

<div class="research-grid">
  <article class="research-card">
    <span class="research-label" data-i18n="selected.bigmomo.label">Efficient AI Systems · On-device AI</span>
    <h3>BigMoMo</h3>
    <p data-i18n="selected.bigmomo.description">Mobile MoE inference is constrained by limited DRAM and costly expert-weight movement. BigMoMo uses speculative decoding to reuse weights, reorganize flash access, and overlap transfers with NPU computation, enabling efficient inference of MoE models up to 30B parameters on mobile devices.</p>
    <p class="research-links"><a href="https://arxiv.org/abs/2609.14643" aria-label="BigMoMo paper on arXiv"><span data-i18n="common.paper">Paper</span></a></p>
  </article>
</div>

<span class="anchor" id="publications"></span>

<h2 data-i18n="section.recentPublications">Recent Publications</h2>

{% assign recent_publications = site.data.publications | where: "show_on_home", true | sort: "home_order" %}
{% for publication in recent_publications %}
{% include publication-card.html publication=publication compact=true %}
{% endfor %}

<p class="publications-actions"><a class="publications-page-link" href="/publications/"><span data-i18n="publications.viewAll">View All Publications</span><i class="fas fa-arrow-right" aria-hidden="true"></i></a></p>

<span class="anchor" id="experience"></span>

<h2 data-i18n="section.experience">Research &amp; Industry Experience</h2>

<div class="timeline experience">
  <div class="timeline-item experience-item experience-item--pkucs">
    <span class="experience-watermark" aria-hidden="true"><img src="/images/experience/pkucs-logo.png" alt=""></span>
    <div class="timeline-date">2026.09 -</div>
    <div>
      <h3 data-i18n="experience.iflab.institution">Intelligence Fusion Laboratory (IF-Lab), Peking University</h3>
      <p><strong data-i18n="experience.iflab.role">Ph.D. Student · Advisor: Prof. Xiang Chen</strong></p>
      <p data-i18n="experience.iflab.description">Research on efficient AI systems, on-device foundation-model inference, hardware-software co-design, and heterogeneous acceleration.</p>
    </div>
  </div>
  <div class="timeline-item experience-item experience-item--imecas">
    <span class="experience-watermark" aria-hidden="true"><img src="/images/experience/imecas-standard-combination.png" alt=""></span>
    <div class="timeline-date">2024.07 - 2026.06</div>
    <div>
      <h3 data-i18n="experience.neuromorphic.institution">Institute of Microelectronics, Chinese Academy of Sciences</h3>
      <p><strong data-i18n="experience.neuromorphic.role">Core Team Member · Energy-Efficient Neuromorphic Processing Chip Project</strong></p>
      <p data-i18n="experience.neuromorphic.description">Developed a PCIe host-to-DDR data-transfer module and optimized YOLOv3-SpikeformerV2 through pretraining and quantization-aware training.</p>
    </div>
  </div>
  <div class="timeline-item experience-item experience-item--empyrean">
    <span class="experience-watermark" aria-hidden="true"><img src="/images/experience/empyrean-logo.png" alt=""></span>
    <div class="timeline-date">2022.11 - 2023.05</div>
    <div>
      <h3 data-i18n="experience.empyrean.institution">Empyrean Technology, Chengdu</h3>
      <p><strong data-i18n="experience.empyrean.role">Software Engineering Intern · BTG Team</strong></p>
      <p data-i18n="experience.empyrean.description">Contributed to pyAether by exposing core C++ capabilities of the Aether EDA platform through Python APIs and validating interface correctness and coverage.</p>
    </div>
  </div>
</div>

<span class="anchor" id="education"></span>

<h2 data-i18n="section.education">Education</h2>

<div class="timeline education">
  <div class="timeline-item education-item education-item--pku">
    <span class="education-watermark" aria-hidden="true"><img src="/images/education/pku-seal.png" alt=""></span>
    <div class="timeline-date">2026.09 -</div>
    <div>
      <h3 data-i18n="education.pku.institution">Peking University</h3>
      <p data-i18n-html="education.pku.description">Ph.D. in Computer Science and Technology, School of Computer Science.<br><a href="https://if-lab-pku.github.io/">Intelligence Fusion Laboratory (IF-Lab)</a>, Advisor: <a href="https://cs.pku.edu.cn/info/1210/2865.htm">Prof. Xiang Chen</a>.</p>
    </div>
  </div>
  <div class="timeline-item education-item education-item--ucas">
    <span class="education-watermark" aria-hidden="true"><img src="/images/education/ucas-seal.png" alt=""></span>
    <div class="timeline-date">2023.09 - 2026.06</div>
    <div>
      <h3 data-i18n="education.ucas.institution">University of Chinese Academy of Sciences</h3>
      <p data-i18n="education.ucas.description">M.Eng. in Circuits and Systems, Institute of Microelectronics, Chinese Academy of Sciences.</p>
    </div>
  </div>
  <div class="timeline-item education-item education-item--whu">
    <span class="education-watermark" aria-hidden="true"><img src="/images/education/whu-seal.png" alt=""></span>
    <div class="timeline-date">2019.09 - 2023.06</div>
    <div>
      <h3 data-i18n="education.whu.institution">Wuhan University</h3>
      <p data-i18n="education.whu.description">B.Eng. in Electronic Information Engineering, Excellence Engineer Program.</p>
    </div>
  </div>
</div>

<span class="anchor" id="honors"></span>

<h2 data-i18n="section.honors">Honors &amp; Awards</h2>

<ul class="honors-list">
  <li data-i18n-html="honors.1"><strong>UCAS Outstanding Student</strong>, 2023-2024</li>
  <li data-i18n-html="honors.2"><strong>UCAS Outstanding Youth League Member</strong>, 2023-2024</li>
  <li data-i18n-html="honors.3"><strong>Hubei Undergraduate Electronic Design Contest (TI Cup), Special Prize</strong>, 2020-2021</li>
  <li data-i18n-html="honors.4"><strong>Wuhan University Outstanding Student &amp; Third-Class Scholarship</strong>, 2020-2021</li>
  <li data-i18n-html="honors.5"><strong>Wuhan University Social Engagement Award</strong>, 2021-2022</li>
  <li data-i18n-html="honors.6"><strong>Outstanding Activity Organizer, China Foundation for Poverty Alleviation</strong>, 2021-2022</li>
</ul>

<span class="anchor" id="service"></span>

<h2 data-i18n="section.service">Academic Service &amp; Activities</h2>

<div class="service-grid">
  <div>
    <h3><span class="card-icon small"><i class="fas fa-clipboard-check" aria-hidden="true"></i></span><span data-i18n="service.reviewer.title">Conference Reviewer</span></h3>
    <p data-i18n="service.reviewer.description">Conference on Neural Information Processing Systems (NeurIPS), IEEE/ACM International Conference on Computer-Aided Design (ICCAD), and IEEE International Conference on Computer Design (ICCD).</p>
  </div>
  <div>
    <h3><span class="card-icon small"><i class="fas fa-users" aria-hidden="true"></i></span><span data-i18n="service.leadership.title">Leadership &amp; Service</span></h3>
    <p data-i18n="service.leadership.description">Former Director of External Relations, Wuhan University Youth Volunteers Association.</p>
  </div>
  <div>
    <h3><span class="card-icon small"><i class="fas fa-camera-retro" aria-hidden="true"></i></span><span data-i18n="service.photography.title">Photography</span></h3>
    <p data-i18n-html="service.photography.description"><strong>Contract Photographer at Visual China Group (VCG)</strong> and <strong>Contract Contributor at Tuchong</strong>.</p>
  </div>
</div>

<span class="anchor" id="photography"></span>

<h2 data-i18n="section.photography">Photography</h2>

<p class="photography-intro" data-i18n="photography.intro">Selected photographic works. Click any image to view it in full.</p>

<div class="photo-gallery">
  <figure class="photo-card">
    <a href="/images/photography/yan-yuan-sunset.jpg" title="Sunset over Yan Yuan" data-i18n-title="photography.1.title">
      <img src="/images/photography/yan-yuan-sunset.jpg" alt="Sunset over the Yan Yuan campus and Boya Pagoda" data-i18n-alt="photography.1.alt" width="2275" height="1280" loading="lazy" decoding="async">
    </a>
    <figcaption><strong data-i18n="photography.1.title">Sunset over Yan Yuan</strong></figcaption>
  </figure>
  <figure class="photo-card">
    <a href="/images/photography/graduation-day.jpg" title="Graduation Day" data-i18n-title="photography.2.title">
      <img src="/images/photography/graduation-day.jpg" alt="University of Chinese Academy of Sciences graduation ceremony" data-i18n-alt="photography.2.alt" width="2275" height="1280" loading="lazy" decoding="async">
    </a>
    <figcaption><strong data-i18n="photography.2.title">Graduation Day</strong></figcaption>
  </figure>
  <figure class="photo-card">
    <a href="/images/photography/grassland-clouds.jpg" title="Grassland beneath the Clouds" data-i18n-title="photography.3.title">
      <img src="/images/photography/grassland-clouds.jpg" alt="Green grassland and a trail beneath a blue sky" data-i18n-alt="photography.3.alt" width="2276" height="1280" loading="lazy" decoding="async">
    </a>
    <figcaption><strong data-i18n="photography.3.title">Grassland beneath the Clouds</strong></figcaption>
  </figure>
  <figure class="photo-card">
    <a href="/images/photography/lakeside-afterglow.jpg" title="Lakeside Afterglow" data-i18n-title="photography.4.title">
      <img src="/images/photography/lakeside-afterglow.jpg" alt="Sunset reflected on a lake with distant architectural silhouettes" data-i18n-alt="photography.4.alt" width="2282" height="1280" loading="lazy" decoding="async">
    </a>
    <figcaption><strong data-i18n="photography.4.title">Lakeside Afterglow</strong></figcaption>
  </figure>
</div>
