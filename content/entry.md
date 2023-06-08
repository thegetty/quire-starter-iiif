---
title: IIIF Figures in an Entry Page Lightbox
layout: entry
order: 20
presentation: side-by-side
object:
  - id: 1
---
## The `ref` Shortcode

Show the {% ref fig='checkbox-annotations' text='photograph' %}.

Show the {% ref fig='checkbox-annotations' anno='scratches' text='scratches' %} annotation.

Zoom in on the {% ref fig='checkbox-annotations' anno='scratches' text='scratches' region="300,250,600,800" %} annotation.


### `ref` with rotating images

Show the {% ref fig='rotating' text='rotating image' %}.

Scrolling to this point will show a {% ref fig='rotating' start='037' text='different point on the rotating image' onscroll='true' %} starting at '037'.

Scrolling to this point will show a {% ref fig='rotating' start='013' transition="false" text='different point on the rotating image' onscroll='true' %} starting at '013' with no transition.

Scrolling to this point will show a {% ref fig='rotating' start='001' text='different point on the rotating image' onscroll='true' %} starting at '001'.

Scrolling to this point will show the {% ref fig='rotating' start='116' text='rotating image' onscroll='true' %} starting at image '116'.

Try the {% ref fig='rotating-annotation' text='second rotating image' %}.

Show a {% ref fig='rotating-annotation' start='fountain02_00088' text='different point on the second rotating image' %}.
