---
layout: page
icon: fas fa-file-alt
order: 2
title: Resume
---

{%- assign drive_id = '1JDZGkzUf4TLeds3koGw_SB_SZPUPidMr' -%}
{%- assign resume_preview = "https://drive.google.com/file/d/" | append: drive_id | append: "/preview" -%}
{%- assign resume_download = "https://drive.google.com/uc?export=download&id=" | append: drive_id -%}

<div class="resume-container">
  <div class="d-flex justify-content-between align-items-center mb-4">
    <h1>Resume</h1>
    <a href="{{ resume_download }}" target="_blank" class="btn btn-primary">
      <i class="fas fa-download me-2"></i>Download PDF
    </a>
  </div>

  <div class="pdf-viewer">
    <iframe
      src="{{ resume_preview }}"
      width="100%"
      height="800px"
      frameborder="0"
      allowfullscreen>
    </iframe>
  </div>

  <div class="mt-4 text-muted">
    <small>
      <i class="fas fa-info-circle me-1"></i>
      If the PDF doesn't load, please try refreshing the page or
      <a href="{{ resume_preview }}" target="_blank">view directly</a>.
    </small>
  </div>
</div>

<style>
.resume-container {
  max-width: 100%;
  margin: 0 auto;
}

.pdf-viewer {
  border: 1px solid var(--border-color);
  border-radius: 0.5rem;
  overflow: hidden;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.pdf-viewer iframe {
  display: block;
  min-height: 600px;
}

@media (max-width: 768px) {
  .pdf-viewer iframe {
    height: 500px;
  }
}
</style>