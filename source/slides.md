---
marp: true
theme: dracula
headingDivider: 2
header: ''
footer: ''
paginate: true
style: |
    .fa-twitter { color: aqua; }
    .fa-mastodon { color: purple; }
    .fa-linkedin { color: blue; }
    .fa-window-maximize { color: skyblue; }
    @import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css'
---

<script
    src="https://kit.fontawesome.com/51cb23fdb1.js" crossorigin="anonymous">
</script>

## When AI goes off piste

### Tales from the docs pipelines

by

Marco Spinello
Senior technical writer
Booking.com

![bg left:50%](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/ai-generated-8764598_1280.jpg)

---

![bg left:40%](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/good-the-bad-and-the-ugly.jpg)

### <i class="fa-regular fa-face-smile"></i> The good
<br /><br /><br />

### <i class="fa-regular fa-face-frown"></i> The bad
<br /><br /><br />

### <i class="fa-regular fa-face-angry"></i> The ugly

---

# Split backgrounds

The space of a slide content will shrink to the right side.



#### The good

#### The bad

#### The ugly

An overview of what you can do with Marp.

---

## Docs


---

## AI

---

## APIs

---

## The good

APIs

- orchestrators
- gophers


---

## The bad

Docs

---

## The ugly

AI

---




## 5. Images

![bg right:40%](https://picsum.photos/800/600)

You can include local images in your slides.

This image is from your `assets/img` folder.

---

## 6. Videos

You can also embed videos from sources like YouTube.

<iframe width="800" height="450" src="https://www.youtube.com/embed/k_3Qp2ocI40"></iframe>

<video src="https://www.youtube.com/embed/k_3Qp2ocI40" type="video/mp4">video</video>

## 6a. HTML

<h2 style="color: teal;">This is rendered as raw HTML</h2>
<ul>
  <li>HTML is supported with the right flags/settings!</li>
  <li>Works in Marp preview and when exporting.</li>
</ul>

---

<!-- backgroundColor: #2a2a2a -->
## 7. Marp Directives

### Local Directives (for a single slide)

- `<!-- backgroundColor: #2a2a2a -->`
- `<!-- color: #ffffff -->`
- `<!-- header: 'Custom Slide Header' -->`

---



## 9. Speaker notes and images

<!-- Can also do a multiline
comment that will show in notes -->

![Image](https://picsum.photos/800/600)

---

## 10. Centered images

You can center images

![center](https://picsum.photos/800/600)

---

## 11. Slide 4

> This is a quote.

---

![bg opacity](https://picsum.photos/800/600?image=53)

## 13. Columns

<div class="columns">
<div>

### Left

- 1
- 2

</div>
<div>

### Right

- 3
- 4

</div>
</div>

---

## 14. Icons

<i class="fa-brands fa-twitter"></i> Twitter: 
<i class="fa-brands fa-mastodon"></i> Mastodon: 
<i class="fa-brands fa-linkedin"></i> LinkedIn: 
<i class="fa fa-window-maximize"></i> Blog: 
<i class="fa-brands fa-github"></i> GitHub: 

[:fa fa-twitter:]

[[:fa fa-solid fa fa-camera fa fa-stack-1x:]{.blue} [:fa fa-solid fa-ban fa fa-stack-2x:]{.red}]


---

## 15. <!--fit--> Large Text

---


## 16. Mermaid
<!-- backgroundColor:rgb(236, 239, 202) -->

<!-- Add this anywhere in your Markdown file -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>


### Mermaid

<div class="mermaid">
mindmap
  root((mindmap))
    Origins
      Long history
      Popularization
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
 </div>

---

<!-- class: center -->

## This slide is centered

You can use the `center` class to center all the text on a slide.

---
