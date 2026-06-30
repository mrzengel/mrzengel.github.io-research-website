---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
---

<div style="margin-bottom: 1rem;">
  <a href="/assets/pdf/cv.pdf" download class="btn btn-primary" style="display:inline-flex; align-items:center; gap:0.4rem;">
    <i class="fas fa-download"></i> Download CV
  </a>
</div>

<div class="pdf-desktop-viewer" style="width:100%; height:90vh;">
  <iframe src="/assets/pdf/cv.pdf" width="100%" height="100%" style="border:none;"></iframe>
</div>

<div class="pdf-mobile-notice" style="display:none; padding:1.5rem; background:#f8f9fa; border-radius:6px; text-align:center;">
  <p style="margin:0; color:#555;">PDF preview is not supported on this device. Use the download button above to view the CV.</p>
</div>

<style>
@media (max-width: 768px) {
  .pdf-desktop-viewer { display: none; }
  .pdf-mobile-notice { display: block !important; }
}
</style>
