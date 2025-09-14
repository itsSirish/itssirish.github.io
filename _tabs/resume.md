---
layout: page
icon: fas fa-file-alt
order: 2
title: Resume
---

{%- assign drive_id = '1JDZGkzUf4TLeds3koGw_SB_SZPUPidMr' -%}
{%- assign resume_preview = "https://drive.google.com/file/d/" | append: drive_id | append: "/preview" -%}

<div class="resume-container">
  <div class="pdf-viewer">
    <iframe
      src="{{ resume_preview }}"
      width="100%"
      height="80vh"
      frameborder="0"
      allowfullscreen
      loading="lazy">
    </iframe>
  </div>

  <div class="mt-2 text-muted small">
    <i class="fas fa-info-circle me-1"></i>
    If the PDF doesn't load, please refresh or
    <a href="{{ resume_preview }}" target="_blank" rel="noopener">open it directly</a>.
  </div>
</div>

<style>
.page .post-content, .page .content, .page .page__content {
  padding-top: 0 !important;
  margin-top: 0 !important;
}

.resume-container {
  position: relative;
  max-width: 100%;
  margin: 0 auto;
}

.pdf-viewer {
  border: 1px solid var(--border-color);
  border-radius: 0.5rem;
  overflow: hidden;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  margin-top: 0.25rem;
  margin-bottom: 0.5rem;
}

.pdf-viewer iframe {
  display: block;
  min-height: 70vh;
}

@media (max-width: 768px) {
  .pdf-viewer iframe {
    height: 70vh;
    min-height: 60vh;
  }
}
</style>
