---
title: Ace
subtitle: Lorem ipsum dolor sit amet, consetetur sadipscing tempor invidunt ut labore et dolore magna aliquyam erat, sed diam consetetur sadipscing invidunt ut labore voluptua.
width: xsmall
image: /lilac-french-bulldog-ace/ace.jpg
topics: [Our Puppies]
navbar:
  sticky: true
  transparent: true
  transparent_color: light
header:
  layout: center # Options: center 1-2 or 2-3
  background_image: /lilac-french-bulldog-ace/ace.jpg
  background_overlay: "rgba(0, 0, 0, 0.5)"
  color: light
  header_size: xlarge
  parallax: true
permalink: /puppies/Ace-lilac-tan-french-bulldog/
---
## Ace's Details

| Available as of {{ site.time | date: '%m/%d/%y' }} | Coat Color  | Sex   |
| ----- |--------| -----:|
| Age     | Lorem       | $1600 |
| Gender     | Lorem       |   $12 |
| coat color     | Lorem       |    $1 |
| personality     | Lorem       |    $1 |
| Health     | Lorem       |    $1 |
| Feeding     | Lorem       |    $1 |
| Health Test    | Lorem       |    $1 |

{% include block.html 
  block="acespecs"
  section_size="medium"
  section_container="xsmall"
  section_header_align="center"
  section_title="About Ace"
  block_title="false"
%}

{% include gallery.html 
	grid="1-2"
	gallery="lilac-french-bulldog-ace"
	caption="true"
	lightbox="true"
  section_size="medium"
  section_padding_remove="top"
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
	src="/lilac-french-bulldog-ace/ace.jpg"
  alt="Some alt title"
  section_size="medium"
  section_padding_remove="top"
  section_container="small"
%}