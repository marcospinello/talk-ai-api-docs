---
marp: true
theme: gaia
footer: 'Marp Presentation Examples'
---

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# 1. Marp Presentation Examples

An overview of what you can do with Marp.

---

## 2. Text, Lists, and Tables

You can format text as **bold**, *italic*, or `code`.

- Unordered List Item 1
- Unordered List Item 2

1. Ordered List Item 1
2. Ordered List Item 2

| Header 1 | Header 2 |
| :--- | :--- |
| Cell 1 | Cell 2 |
| Cell 3 | Cell 4 |

---

## 3. Code Examples

```python
import marp

def hello_marp():
    """This is a sample function."""
    print("Hello, Marp!")

hello_marp()
```

---

## 4. Mermaid Diagrams

<div class="mermaid">
graph TD
    A[Start] --> B{Is it Friday?};
    B -- Yes --> C[Relax!];
    B -- No --> D[Keep working...];
    C --> E[End];
    D --> E[End];
</div>

---

## 5. Images

![bg right:40%](https://picsum.photos/800/600)

You can include local images in your slides.

This image is from your `assets/img` folder.

---

## 6. Videos

You can also embed videos from sources like YouTube.

<iframe width="800" height="450" src="https://www.youtube.com/embed/k_3Qp2ocI40" frameborder="0"></iframe>

---

<!-- backgroundColor: #2a2a2a -->
## 7. Marp Directives

Directives control the appearance of your slides.

**Global Directives (in the top YAML section):**
- `theme`: `gaia`, `default`, `uncover`
- `size`: `16:9` (default), `4:3`
- `paginate`: `true` (shows page numbers)

**Local Directives (for a single slide):**
- `<!-- backgroundColor: #2a2a2a -->`
- `<!-- color: #ffffff -->`
- `<!-- header: 'Custom Slide Header' -->`

---

## 8. Speaker nots and Lists

- Item 1
- Item 2
- Item 3
<!-- Can have multiple on a slide -->

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

## 12. Tables

| Column 1 | Column 2 |
| -------- | -------- |
| Item 1   | Item 2   |
| Item 3   | Item 4   |

---

![bg opacity](https://picsum.photos/800/600?image=53)
## 13. Columns

<div class="columns">
<div>

## Left

- 1
- 2

</div>
<div>

## Right

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

---

# 15. <!--fit--> Large Text

---

<!-- Needed for mermaid, can be anywhere in file except frontmatter -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# 16. Mermaid

<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
</div>