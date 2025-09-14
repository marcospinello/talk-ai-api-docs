---
marp: true
theme: dracula
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

<script src="https://kit.fontawesome.com/51cb23fdb1.js" crossorigin="anonymous"></script>

<!-- Add this anywhere in your Markdown file -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
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

## About me

![bg left:50%](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/valley-of-fires-105.jpg)

- Tech writer with no CS background
- Before AI, Google and StackOverflow were my job security
- As curious as a cat

---

## Docs automation

Docs automation workflow main ingredients:

- CI/CD pipelines
- Lots of scripts and config files
- Containers
- APIs for data exchange and interoperability

...

---

![bg left:60%](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/ai-generated-8583250_1280.jpg)

Oh yes and AI to turn a robust pipeline into a house of cards

---

## AI-enhanced docs pipelines

AI helps automate ancillary tasks:

- Simple
- Repetitive
- Time-consuming

---

![bg contain](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/ai-api-docs-workflows-1.jpg)

---

So far, results have been a rather mixed bag.

Let's dig into the good, the bad, and the ugly.

---

## Good

![bg contain](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/ai-api-docs-workflows-2.jpg)  

---

## Bad

![bg contain](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/ai-api-docs-workflows-3.jpg)

---

## Ugly

![bg contain](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/ai-api-docs-workflows-4.jpg)

---

## The value of APIs

- orchestrators:
  - coordinate AI agents
  - manage tasks (queue, run, monitor)
  - trigger actions (ex: webhooks)
  - trigger notifications

- gophers
  - CRUD on data
  - AI sidekick when using MCP tools and resources

---

![bg contain](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/ai-api-docs-workflows.jpg)

---

## AI fails

- [Therapy chatbot](https://futurism.com/therapy-chatbot-addict-meth)
- [Blackmailing colleague](https://www.bbc.com/news/articles/cpqeng9d20go)
- [Lying an scheming](https://time.com/7202784/ai-research-strategic-lying/)
- [Running a company](https://futurism.com/professors-company-ai-agents) \
  See also [The Agent Company](https://the-agent-company.com/)
- [Customer support](https://futurism.com/klarna-ai-automation-engineers)

---

## Thank you!

![bg left:57%](/Users/mspinello/Documents/repos/gh/talk-ai-api-docs/assets/img/good-the-bad-and-the-ugly-fr.jpg)

Thank you!

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


---


## 14. Icons

<i class="fa-brands fa-twitter"></i> Twitter: 
<i class="fa-brands fa-mastodon"></i> Mastodon: 
<i class="fa-brands fa-linkedin"></i> LinkedIn: 
<i class="fa fa-window-maximize"></i> Blog: 
<i class="fa-brands fa-github"></i> GitHub: 

---

## 15. <!--fit--> Large Text

---

## 16. Mermaid

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
