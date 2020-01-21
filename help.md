## gist-reveal Help
* Implemented using reveal.js [external markdown](https://github.com/rectalogic/gist-reveal/blob/gh-pages/README.md#external-markdown) support
* Use `---` (markdown horizontal rule) on a line by itself to separate slides
* Use `VVV` on a line by itself to separate vertical slides

---

## Slide background
* Specify [slide attributes](https://github.com/rectalogic/gist-reveal/blob/gh-pages/README.md#slide-attributes) using an HTML comment

```markdown
  ---

  <!-- .slide: data-background="#ff0000" -->
  ## Slide with red background
```

---

## Fragments
* Specify [element attributes](https://github.com/rectalogic/gist-reveal/blob/gh-pages/README.md#element-attributes) using an HTML comment

```markdown
  ## Fragments
  * item 1 <!-- .element: class="fragment" -->
  * item 2 <!-- .element: class="fragment" -->
```