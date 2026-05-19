---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 4
description: Curriculum vitae.
---

{% assign cv_pdf = '/PRITHWIJIT%20CHOWDHURY_resume.pdf' | relative_url %}

<div class="cv-pdf-actions">
  <a class="btn btn-sm z-depth-0" href="{{ cv_pdf }}" target="_blank" rel="noopener noreferrer">View PDF</a>
  <a class="btn btn-sm z-depth-0" href="{{ cv_pdf }}" download>Download</a>
</div>

<div class="cv-pdf-frame">
  <iframe src="{{ cv_pdf }}" title="Prithwijit Chowdhury resume"></iframe>
</div>
