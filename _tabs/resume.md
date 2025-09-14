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
  <!-- Overlay actions -->
  <div class="resume-overlay">
    <a href="{{ resume_download }}" target="_blank" class="btn btn-primary resume-download">
      <i class="fas fa-download me-2"></i>Download PDF
    </a>
  </div>

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
    If the PDF doesn't load, please try refreshing the page or
    <a href="{{ resume_preview }}" target="_blank">view directly</a>.
  </div>
</div>

<style>
/* Pull the resume higher and reduce excess padding/margins */
.page .post-content, .page .content, .page .page__content {
  padding-top: 0 !important;
  margin-top: 0 !important;
}

/* Container + overlay */
.resume-container {
  position: relative;
  max-width: 100%;
  margin: 0 auto;
}

/* Button overlayed on top-right of the viewer */
.resume-overlay {
  position: absolute;
  top: 10px;
  right: 10px;
  z-index: 2;
  pointer-events: none; /* Let clicks fall through, except the button */
}

.resume-download {
  pointer-events: auto; /* Make the button clickable again */
  backdrop-filter: blur(6px);
  background: rgba(13,110,253,0.9); /* bootstrap primary-ish */
  border: none;
  box-shadow: 0 4px 14px rgba(0,0,0,0.15);
}

/* PDF frame styling */
.pdf-viewer {
  border: 1px solid var(--border-color);
  border-radius: 0.5rem;
  overflow: hidden;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  margin-top: 0.25rem;   /* tighter spacing above iframe */
  margin-bottom: 0.5rem; /* less padding below */
}

.pdf-viewer iframe {
  display: block;
  min-height: 70vh; /* ensure good height on tall screens */
}

/* Mobile tweaks */
@media (max-width: 768px) {
  .resume-overlay {
    top: 8px;
    right: 8px;
  }
  .resume-download {
    padding: 0.4rem 0.6rem;
    font-size: 0.875rem;
  }
  .pdf-viewer iframe {
    height: 70vh;
    min-height: 60vh;
  }
}
</style>
