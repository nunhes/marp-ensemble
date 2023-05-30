---
marp: true
theme: default
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }  
  @import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css'
  .fa-twitter { color: aqua; }
  .fa-mastodon { color: purple; }
  .fa-linkedin { color: blue; }
  .fa-window-maximize { color: skyblue; }
  svg[id^="mermaid-"] { 
    min-width: 480px; 
    max-width: 960px; 
    min-height: 360px; 
    max-height: 600px; 
  }
---

![bg opacity](https://picsum.photos/800/600?image=53)
## Slide 5

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

## Slide 6

<i class="fa-brands fa-twitter"></i> Twitter: 
<i class="fa-brands fa-mastodon"></i> Mastodon: 
<i class="fa-brands fa-linkedin"></i> LinkedIn: 
<i class="fa fa-window-maximize"></i> Blog: 
<i class="fa-brands fa-github"></i> GitHub: 

---

<!-- Add this anywhere in your Markdown file -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# Mermaid

<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
</div>