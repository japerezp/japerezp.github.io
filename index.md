---
layout: home
intro: |  # This should be Markdown
  Professor, **[University of Groningen](http://www.rug.nl/), The Netherlands**.

  Leader, **[Fundamental Computing group](https://www.rug.nl/fse/fc)**.

  Member of the board / Head of department Computer Science, **[Bernoulli Institute](http://www.rug.nl/research/bernoulli)**.

  Project coordinator (lead PI), **[Cyclic Structures in Programs and Proofs](https://cyclic-structures.gitlab.io/)** (2025-2030).
  
  **[My CV](http://japerezp.github.io/files/PerezCV.pdf)** 
  // [DBLP](https://dblp.uni-trier.de/pid/p/JorgeAPerez.html) 
  // [Google Scholar](http://scholar.google.com/citations?user=NJ4UhIwAAAAJ) 
  // [ORCID](http://orcid.org/0000-0002-1452-6180) 
  // [ACM DL](http://dl.acm.org/author_page.cfm?id=81339521988)
details: |  # This should be Markdown
  ## Research Interests
  I study how to design, analyze, and verify reliable programs for concurrent and distributed programming. A key challenge is ensuring that complex software systems behave as intended, even when many components interact at once.
  - **Formal models for concurrent and distributed systems** (especially [process calculi](https://en.wikipedia.org/wiki/Process_calculus)) and their rigorous verification techniques.
  - **Type systems for concurrent programming**, with a focus on [session types](https://en.wikipedia.org/wiki/Session_type) and their **logical foundations**.
  - Exploring the **expressive power of concurrent models** to understand their strenghts and limitations in modeling real-world programs and systems.
---

<div class="home intro">
    <div class="column left">
        <img id="jap_photo" src="{{ "/assets/img/jorgeaperez.jpg" | relative_url }}" alt="Jorge A. Pérez" />
    </div>
    <div class="column right">
        {{ page.intro | markdownify }}
    </div>
</div>
<div class="spacer"></div>
<div>{{ page.details | markdownify }}</div>