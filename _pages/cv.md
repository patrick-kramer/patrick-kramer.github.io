---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 5
description: 
---

Here is a short version of my CV.

<div class="post">
  <header class="post-header">
    <p class="post-description">
      <a href="{{ '/assets/pdf/CV.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" class="float-right">
        <i class="fas fa-file-pdf"></i> Download PDF
      </a>
    </p>
  </header>

  <article>
    <div class="cv-embed" style="margin-top: 20px;">
      <iframe src="{{ '/assets/pdf/CV.pdf' | relative_url }}" width="100%" height="1000px" style="border: 1px solid #ddd;">
        <p>It looks like your browser doesn't support embedded PDFs. 
           <a href="{{ '/assets/pdf/CV.pdf' | relative_url }}">Click here to download the PDF file.</a>
        </p>
      </iframe>
    </div>
  </article>
</div>