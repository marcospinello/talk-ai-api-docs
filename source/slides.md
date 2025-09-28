---
marp: true
description: AI-enhanced docs pipelines can make stuff up
keywords: [AI, API, documentation, automation pipeline]

header:
footer: "[`Back to Contents`](#2)"

paginate: true
transition: none

size: 16:9
lang: en

style: |
    .fa-twitter { color: aqua; }
    .fa-linkedin { color: blue; }
    @import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css'
---

<!-- 
<script type="module">
    import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
</script>
-->

## When AI goes off script

### Tales from the docs pipelines

by

Marco Spinello
Senior technical writer
Booking.com

![bg left:50%](../assets/img/ai-generated-8764598_1280.jpg)

---

![bg right:45%](../assets/img/good-the-bad-and-the-ugly.jpg)

### <i class="fa-regular fa-face-smile"></i><br />The good
<br /><br /><br />

### <i class="fa-regular fa-face-frown"></i><br />The bad
<br /><br /><br />

### <i class="fa-regular fa-face-angry"></i><br />The ugly

---

## About me

![bg left:50%](../assets/img/valley-of-fires-105.jpg)

- ✍️ Tech writer with no CS background
- 🔍 Before AI, Google and StackOverflow were my job security
- 🐾 As curious as a cat

---

## Docs automation

Docs automation workflow main ingredients:

- 🏗️ CI/CD pipelines
- 📝 Scripts and config files
- 🐳 Containers
- 🌐 APIs for data exchange and interoperability 
- ...

---

![bg right:65%](../assets/img/ai-generated-8583250_1280.jpg)

... Oh yes, and AI to turn a robust pipeline into a house of cards 🙄

---

## AI-enhanced docs pipelines

![bg left:50%](../assets/img/metropolis-clock-1927.jpg)

AI helps with ancillary tasks:

- 😌 Simple
- 🔁 Repetitive
- ⏳ Time-consuming

---

<pre class="mermaid">
---
config:
  theme: forest
  look: handDrawn
---
flowchart TB
    A["AI docs<br>automation<br>workflows"] --> B["Gather<br>and review<br>information"] & C["Author docs"] & D["SME<br>Review<br>docs, code"] & E["Bulk<br>operations"] & F["APIs"]
    B --> G["Code repos<br>Jira issues"] & H["Wiki<br>GDocs"]
    C --> J["Code<br>comments"] & K["README<br>in repos"]
    D --> L["Code comments<br>Git PRs/MRs"] & M["README in repos<br>Wiki, GDocs articles"]
    E --> N["img alt text"] & O["Missing<br>descriptions<br>"] & P["Translations"]
    F --> Q["CRUD on data"] & R["Orchestration"]
    R --> S["Coordinate<br>AI agents<br>"] & T["Triggers,<br>events,<br>actions,<br>notifications"] & U["Manage and<br>process<br>tasks/jobs"] & V["Indexing"]
    A@{ shape: rounded}
    B@{ shape: rounded}
    C@{ shape: rounded}
    D@{ shape: rounded}
    E@{ shape: rounded}
    F@{ shape: rounded}
    G@{ shape: rounded}
    H@{ shape: rounded}
    J@{ shape: rounded}
    K@{ shape: rounded}
    L@{ shape: rounded}
    M@{ shape: rounded}
    N@{ shape: rounded}
    O@{ shape: rounded}
    P@{ shape: rounded}
    Q@{ shape: rounded}
    R@{ shape: rounded}
    S@{ shape: rounded}
    T@{ shape: rounded}
    U@{ shape: rounded}
    V@{ shape: rounded}
    style A color:#616161
    style F fill:#FFD600,stroke:#FF6D00
    style Q fill:#FFD600,stroke:#FF6D00
    style R fill:#FFD600,stroke:#FF6D00
    style S fill:#FFD600,stroke:#FF6D00
    style T fill:#FFD600,stroke:#FF6D00
    style U stroke:#FF6D00,fill:#FFD600
    style V fill:#FFD600,stroke:#FF6D00
    linkStyle 4 stroke:#000000,fill:none
    linkStyle 14 stroke:#000000,fill:none
</pre>

---

![bg left:50%](../assets/img/ai-creepy-doll-1280.jpg)

So far, results have been a mixed bag:
- Some good 👍
- Some bad 👎
- Some ugly 💩

---

## Good 👍



---

## Bad 👎



---

## Ugly 💩



---

## The value of APIs

APIs are the foundational plumbing of the pipelines:

| Gophers | Orchestrators |
|---|---|
| Retrieve data | Coordinate AI agents |
| Create new data | AI sidekick for MCP interactions (ex: MCP tools and resources) |
| Modify existing data | Manage tasks (queue, run, monitor) |
| Delete data | Initiate actions (ex: webhooks) |
| | Handle notifications |

---

![bg contain](../assets/img/ai-api-docs-workflows-5.jpg)

---

![bg contain](../assets/img/ai-api-docs-workflows.jpg)

---

## AI fails

- [Therapy chatbot](https://futurism.com/therapy-chatbot-addict-meth)
- [Blackmailing colleague](https://www.bbc.com/news/articles/cpqeng9d20go)
- [Lying an scheming](https://time.com/7202784/ai-research-strategic-lying/)
- [Running a company](https://futurism.com/professors-company-ai-agents) \
  See also [The Agent Company](https://the-agent-company.com/)
- [Customer support](https://futurism.com/klarna-ai-automation-engineers)

---

## AI fail winner

...

<i class="fa-solid fa-drum"></i>

...

---

![bg contain](../assets/img/gen-ai-ethical-ai.png)

---

## Merci beaucoup!

![bg left:56%](../assets/img/the-good-the-bad-and-the-ugly-fr.jpg)

Merci beaucoup!

---

## 9. Speaker notes and images

<!-- Can also do a multiline
comment that will show in notes -->
