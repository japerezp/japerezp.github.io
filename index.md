---
layout: home
intro: |  # This should be Markdown
  Professor, **[University of Groningen](http://www.rug.nl/)**, the Netherlands.

  Leader, **[Fundamental Computing group](https://www.rug.nl/fse/fc)**.

  Board member / chair of the board, **[Bernoulli Institute](http://www.rug.nl/research/bernoulli)**.

  Lead PI, **[Cyclic Structures in Programs and Proofs](https://cyclic-structures.nl/)** (2025-2030).

  Editorial board member, [**Information and Computation**](https://www.sciencedirect.com/journal/information-and-computation).

  Chair, [**IFIP Working Group 6.1**: Architectures and Protocols for Distributed Systems](https://tc6.ifip.org/wg-6-1-architectures-and-protocols-for-distributed-systems/).

  **[My CV](http://japerezp.github.io/files/PerezCV.pdf)** 
  // [DBLP](https://dblp.uni-trier.de/pid/p/JorgeAPerez.html) 
  // [Google Scholar](http://scholar.google.com/citations?user=NJ4UhIwAAAAJ) 
  // [ORCID](http://orcid.org/0000-0002-1452-6180) 
  // [ACM DL](http://dl.acm.org/author_page.cfm?id=81339521988)
details: |  # This should be Markdown
  ## Research Interests
  **My research addresses the urgent need for rigorous foundations in reliable communicating programs, particularly as automated tools produce unreliable code at an unprecedented scale.** I focus on the design, analysis, and verification of programs for concurrent and distributed computing, exploring:

  - **Formal models for concurrent and distributed systems** (especially [process calculi](https://en.wikipedia.org/wiki/Process_calculus)) and their verification techniques for ensuring correctness
  - **Type systems for concurrent programming**, with a focus on [session types](https://en.wikipedia.org/wiki/Session_type) and their **logical foundations**
  - The **expressive power of concurrent models** to better understand their strenghts and limitations in modeling real-world systems.
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