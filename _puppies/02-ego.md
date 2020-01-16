---
title: Ego
subtitle: I’m a Blue French Bulldog puppy for sale located in New York City. And not just a regular Blue, i'm the **cutest** blue you'll ever see.
width: xsmall
image: /ego.jpg
topics: [Our Puppies, Blue French Bulldog]
navbar:
  sticky: true
  transparent: true
  transparent_color: light
header:
  layout: center # Options: center 1-2 or 2-3
  background_image: /french-bulldog-wallpaper.jpg
  background_overlay: "rgba(0, 0, 0, 0.5)"
  color: light
  header_size: medium
  parallax: true
permalink: /puppies/ego/
chat: true
---

{% include image.html 
	src="/ego.jpg"
  alt="Ego"
  section_size="large"
  section_padding_remove="bottom"
  section_title="Ego"
  section_header_align="center"
  section_container="small"
  lightbox="true"
%}


| Coat Color     | Blue   |
| personality     | Super Friendly / Outgoing  |
| Health     |  {% include label.html text="Cleared " style="success" %}|
|Available as of {{ site.time | date: '%m/%d/%y' }}  | {% include label.html text="Available" style="success" %} |

{% include gallery.html 
	grid="1-2"
	gallery="blue-french-bulldog-ego"
	caption="true"
	lightbox="true"
  section_size="medium"
  section_padding_remove="top"
%}

{% include block.html 
  block="apuppyegospecs"
  section_size="medium"
  section_container="xsmall"
  section_header_align="center"
  section_title="About Ego"
  block_title="false"
%}


{% include block.html 
  block="acespecs2"
  section_size="medium"
  section_padding_remove="top"
  section_container="xsmall"
  section_header_align="center"
  section_title="Apply for further consideration."
  block_title="false"
%}

{% include image.html 
	src="/ego.jpg"
  alt="Ego the Frenchie"
  section_size="medium"
  section_padding_remove="top"
  section_container="small"
%}