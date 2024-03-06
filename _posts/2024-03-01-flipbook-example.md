---
title: "Flipbook Example"
date: 2024-03-01T15:34:30-04:00
categories:
  - test
tags:
  - Javascript
---

<!-- IMPORT FLIPBOOK STYLES (Flipbook & Icons Stylesheets) -->
<!-- These lines must be added to the top of the .md file, just below the frontmatter -->
<link href="{{ 'assets/css/dflip.min.css' | absolute_url }}" rel="stylesheet" type="text/css">
<link href="{{ 'assets/css/themify-icons.min.css' | absolute_url }}" rel="stylesheet" type="text/css">


<!-- -----------------------------------------------------------------------------
MAIN FLIPBOOK CONTAINER
Place this code at the location where the PDF viewer should display in the post
  - 1. Add PDF file to the /assets/pdf/ directory of the project 
  - 2. Update the source attribute to reflect the PDF file to display in the widget
------------------------------------------------------------------------------ -->
<div class="container">
    <div class="row">
        <div class="col-xs-12">
            <div id="flipbook" class="_df_book" height="500" webgl="true"
                backgroundcolor="#0f477e"
                source="{{ 'assets/pdf/The-Case-for-Memory-Safe-Roadmaps-508c.pdf' | absolute_url }}">
            </div>
        </div>
    </div>
</div>


<!-- IMPORT FLIPBOOK JAVASCRIPT (jQuery & Main Flipbook JS) -->
<!-- These lines must be added to the bottom of the .md file -->
<script src="{{ 'assets/js/libs/jquery.min.js' | absolute_url }}" type="text/javascript"></script>
<script src="{{ 'assets/js/dflip.min.js' | absolute_url }}" type="text/javascript"></script>