---
title: About Us
subtitle: A small boutique family run French Bulldog Breeder
width: full
navbar:
  sticky: true
  scroll_up: true
  animation: true
  transparent: true
  transparent_color: light
header:
  layout: center # Options: left, center, 1-1, 1-2, 1-3 or 2-3
  background_image: header-6.jpg
  background_overlay: "rgba(0, 0, 0, 0.45)"
  color: light
  header_size: large
  heading_size: medium
  parallax: true
extraseoabout: true
---
{% include block.html 
  block="content-about-us"
  block_title="false"
  section_size="large"
  section_title="How it all began"
  section_padding_remove="bottom"
  section_container="xsmall"
  section_header_align="center"
%}

{% include instagram.html 
  section_size="large"
  section_padding_remove="bottom"
  section_container="default"
  section_title="Instagram Images"
  section_header_align="center"
  grid="1-4" 
  count="8" 
  gutter="small"
%}

{% include 
  team.html 
  authors="james, renee, butch, ely" 
  section_title="A Family & Friends Run Business" 
  section_subtitle="We're here to answer any questions" 
  section_size="large"
  section_container="expand"
  section_header_align="center"
  section_background="muted"
%}
