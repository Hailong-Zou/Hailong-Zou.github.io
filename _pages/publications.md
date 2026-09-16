---
permalink: /publications/
lang: en
title: "Publications | Hailong Zou"
excerpt: "Complete publication list of Hailong Zou, including journal articles, conference papers, and preprints on efficient AI systems, on-device AI, and hardware-software co-design."
author_profile: true
---

<section class="publications-page-hero" data-page-title-zh="论文发表 | 邹海龙" data-page-description-zh="邹海龙的完整论文列表，包括高效人工智能系统、端侧智能与软硬件协同优化方向的期刊论文、会议论文和预印本。">
  <div class="publications-page-meta">
    <p class="intro-kicker" data-i18n="publications.pageKicker">Research Output</p>
    <nav class="language-switcher" aria-label="Language selection" data-i18n-aria-label="language.label">
      <button type="button" data-language-option="en" aria-pressed="true">EN</button>
      <button type="button" data-language-option="zh" aria-pressed="false">中文</button>
    </nav>
  </div>
  <h1 data-i18n="section.publications">Publications</h1>
  <p data-i18n="publications.pageIntro">Below is my complete publication list, organized into journal articles, conference papers, and preprints.</p>
  <a class="publications-back-link" href="/"><i class="fas fa-arrow-left" aria-hidden="true"></i><span data-i18n="publications.backHome">Back to Homepage</span></a>
</section>

<h2 data-i18n="section.journalArticles">Journal Articles</h2>

{% assign journal_publications = site.data.publications | where: "category", "journal" %}
{% for publication in journal_publications %}
{% include publication-card.html publication=publication %}
{% endfor %}

<h2 data-lang-en="Conference Papers" data-lang-zh="会议论文">Conference Papers</h2>

{% assign conference_publications = site.data.publications | where: "category", "conference" %}
{% for publication in conference_publications %}
{% include publication-card.html publication=publication %}
{% endfor %}

<h2 data-i18n="section.preprints">Preprints</h2>

{% assign preprint_publications = site.data.publications | where: "category", "preprint" %}
{% for publication in preprint_publications %}
{% include publication-card.html publication=publication %}
{% endfor %}

<p class="source-note" data-i18n-html="publications.source">For the complete and current publication list, please visit <a href="https://scholar.google.com/citations?user=cE-S7Q4AAAAJ&hl=en">Google Scholar</a>, <a href="https://orcid.org/0009-0004-0090-9553">ORCID</a>, and <a href="https://openreview.net/profile?id=%7EHailong_Zou1">OpenReview</a>.</p>
