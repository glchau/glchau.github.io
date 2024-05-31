---
layout: default
permalink: /cv/
title: cv
nav: true
nav_order: 5
cv_pdf: cv.pdf
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
---


<html>
    <div class="post">
        <header class="post-header">
        <h1 class="post-title">CV</h1>
        </header>
        <object data="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url }}#toolbar=1&navpanes=0" style="min-height:100vh;width:100%" type='application/pdf'/>
    </div>
</html>