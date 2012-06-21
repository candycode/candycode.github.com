---
layout: default
---

...just a test site to check if I can port my wordpress site to jekyll

#Tests

## Latex test

[MatJax](/site/projects/ambient_occlusion)

## Image galleries test

Checkout the _portfolio_ page

## Video test

Checkout the _portfolio_ page

## Table test

| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     
| column     |      column |    column    
| will       |        will |     will     
| be         |          be |      be      
| left       |       right |    center    
| aligned    |     aligned |   aligned


##External gallery

[Click here](gallerypage.html#opengallery)


#Status

* Changed theme
* Tested with maroku, rdiscount and kramdown: *use kramdown* since it's the one
that works best with MathJax


---

#Tests

##Single image

<a href="gallery/bones_ao.jpg" 
 rel="lightbox" 
 title="Synthetic bone model with ambient occlusion">image</a>


##Multiple images
<a href="gallery/chaperonine_no_ao.jpg"
 rel="lightbox[ao1]"
 title="Chaperonine molecule: no ambient occlusion">image</a>
<a href="gallery/chaperonine_ao.jpg"
 rel="lightbox[ao1]"
 title="Chaperonine molecule: ambient occlusion">image</a>
<a href="gallery/chaperonine_ao_phong.jpg"
 rel="lightbox[ao1]"
 title="Chaperonine molecule: ambient occlusion and phong shading">image</a>

##Thumbnails

<table style='border-collapse: collapse'>
<tr style='border-bottom: 0'>
<td style='border-bottom: 0'><a href="gallery/chaperonine_no_ao.jpg"
 rel="lightbox[ao2]"
 title="Chaperonine molecule: no ambient occlusion">
 <img src="gallery/thumbs/thumbs_chaperonine_no_ao.jpg"/>
</a></td>
<td>
<a href="gallery/chaperonine_ao.jpg"
 rel="lightbox[ao2]"
 title="Chaperonine molecule: ambient occlusion">
 <img src="gallery/thumbs/thumbs_chaperonine_ao.jpg"/>
</a>
</td>
</tr>
</table>

##Video(Youtube)

To center: wrap iframe with

```
<div style="text-align: center">
...
```

To avoid having the youtube video cover other items on the page add ```?wmode=transparent``` to the youtube embed url.



<div style="text-align: center">
<iframe width="560" height="315" style="margin: 0 auto" src="http://www.youtube.com/embed/p3mS-BkFxec?wmode=transparent" frameborder="0" allowtransparency="true" allowfullscreen="true"></iframe>
</div>






