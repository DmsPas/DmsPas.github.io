---
permalink: /
title: ""
excerpt: "Computational tasks on graphs."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral fellow at [Università della Svizzera italiana (USI)](http://usi.to/vh8) and the Chief Operating Officer (COO) of [Panua Technologies](https://panua.ch/), a spin off of the university.
The focus of my research is centered around algorithms for graph learning and combinatorial optimization for graph clustering and anomaly detection. 

I am the principal investigator (PI) of the project **Directed acyclic graph partitioning for scheduling tasks**, financed by the Huawei Research Center Zürich for 2025. My work is 
also supported by the joint German Research Foundation (DFG) and Swiss National Science Foundation (SNSF)
project [Numerical Algorithms, Frameworks, and Scalable Technologies for Extreme-Scale Computing](https://data.snf.ch/grants/grant/204817).

**For students**
- [Emerging topics in advanced computing](https://search.usi.ch/en/courses/35275751/emerging-topics-in-advanced-computing), Phd course, USI.
- [Data analytics for fraud detection](https://search.usi.ch/en/courses/35275991/data-analytics-for-fraud-detection), MSC, MFT, PhD course, USI.
- For MSc and BSc thesis topics, please contact via e-mail.

<!-- This is my [cv](http://DmsPas.github.io/files/CV_DPasadakis.pdf) (updated February 2024). -->
<!-- I completed my Phd at USI in February 2023, under the supervision of [Olaf Schenk](https://search.usi.ch/en/people/9a52a2fdb8d3d26ec16fb1569b590909/schenk-olaf). Prior to that, I worked on fluid-structure interaction problems as part of my MSc thesis on [Computational Science](https://www.usi.ch/en/education/master/computational-science) at USI, and studied Physics at the [Aristotle University of Thessaloniki](https://www.physics.auth.gr/en/) and [TU Berlin](https://www.tu.berlin/en/naturwissenschaften).  -->

<p align="center">
<img src="/images/USI_Panua_Logo.png" width="420" alt="USI_logo_full"> 
</p>

*** 
<!-- ===================== Research Highlights Carousel ===================== -->
<div id="research-highlights" aria-label="Research highlights carousel" style="max-width:820px;margin:24px auto;">
  <h3 style="text-align:center;margin:0 0 12px 0;"></h3>

  <div class="rc-wrapper" role="region">
    <!-- Slides -->
    <div class="rc-slide active">
      <a href="https://ieeexplore.ieee.org/document/10091452" target="_blank" rel="noopener">
        <img src="/images/SQUIC_fit_adj.png" alt="SQUIC_fit_adj" loading="lazy">
      </a>
      <div class="rc-caption">Adjacency matrix estimation via maximum likelihood</div>
    </div>

    <div class="rc-slide">
      <a href="https://arxiv.org/abs/2409.01834" target="_blank" rel="noopener">
        <img src="/images/NPR_graph_clust.png" alt="NPR_graph_clust" loading="lazy">
      </a>
      <div class="rc-caption">Nonlinear PageRank for local graph clusters</div>
    </div>

    <div class="rc-slide">
      <a href="https://arxiv.org/abs/2508.16173" target="_blank" rel="noopener">
        <img src="/images/Spectral_dir_topo.png" alt="Spectral_dir_topo" loading="lazy">
      </a>
      <div class="rc-caption">Directed spectral methods for topological ordering</div>
    </div>

    <!-- Prev / Next -->
    <button type="button" class="rc-nav rc-prev" aria-label="Previous slide" onclick="rcPrev('research-highlights')">&#10094;</button>
    <button type="button" class="rc-nav rc-next" aria-label="Next slide" onclick="rcNext('research-highlights')">&#10095;</button>

    <!-- Dots -->
    <div class="rc-dots" role="tablist" aria-label="Slide selectors"></div>
  </div>
</div>

<style>
/* ---- Carousel styles (scoped by .rc-*) ---- */
.rc-wrapper {
  position: relative;
  aspect-ratio: 16 / 9;
  background: #f5f5f5;
  border: 1px solid #ddd;
  border-radius: 14px;
  overflow: hidden;
  box-shadow: 0 6px 20px rgba(0,0,0,0.06);
}
.rc-slide {
  position: absolute;
  inset: 0;
  opacity: 0;
  transition: opacity .6s ease;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #fff;
}
.rc-slide.active { opacity: 1; }
.rc-slide img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
  display: block;
  user-select: none;
  -webkit-user-drag: none;
}
.rc-caption {
  position: absolute;
  left: 0; right: 0; bottom: 0;
  padding: 8px 12px;
  font-size: 13px;
  color: #333;
  background: rgba(255,255,255,0.88);
  border-top: 1px solid #eee;
  text-align: center;
  z-index: 1;
}
.rc-nav {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(255,255,255,0.95);
  border: 1px solid #ddd;
  border-radius: 999px;
  width: 36px; height: 36px;
  line-height: 36px;
  text-align: center;
  font-size: 20px;
  cursor: pointer;
  box-shadow: 0 2px 10px rgba(0,0,0,0.08);
  z-index: 9999;              /* ensure always on top */
  pointer-events: auto;       /* ensure clicks reach the buttons */
}
.rc-nav:hover { background: #fff; }
.rc-prev { left: 10px; }
.rc-next { right: 10px; }
.rc-dots {
  position: absolute;
  bottom: 8px; left: 0; right: 0;
  display: flex; gap: 6px; justify-content: center; align-items: center;
}
.rc-dots button {
  width: 8px; height: 8px; border-radius: 50%;
  border: 1px solid #bbb; background: #fff; opacity: .7;
  cursor: pointer;
}
.rc-dots button.active { background: #333; border-color: #333; opacity: 1; }
@media (max-width: 560px) { .rc-caption { font-size: 12px; } }
</style>

<script>
/* Works reliably on GitHub Pages + Jekyll */
(function () {
  window.__rc = window.__rc || {};

  function init(id){
    const root = document.getElementById(id);
    if (!root) return;
    const wrapper = root.querySelector('.rc-wrapper');
    const slides  = Array.from(wrapper.querySelectorAll('.rc-slide'));
    const prevBtn = wrapper.querySelector('.rc-prev');
    const nextBtn = wrapper.querySelector('.rc-next');
    const dotsEl  = wrapper.querySelector('.rc-dots');
    if (!slides.length) return;

    let index = 0, timer = null, hover = false;

    // Build dots
    dotsEl.innerHTML = '';
    slides.forEach((_, i) => {
      const b = document.createElement('button');
      b.setAttribute('aria-label', 'Go to slide ' + (i + 1));
      b.addEventListener('click', () => go(i, true));
      dotsEl.appendChild(b);
    });

    function setActive(i){
      slides.forEach((s,k)=> s.classList.toggle('active', k===i));
      dotsEl.querySelectorAll('button').forEach((d,k)=> d.classList.toggle('active', k===i));
    }
    function go(i, user=false){
      index = (i + slides.length) % slides.length;
      setActive(index);
      if (user) restart();
    }
    function next(){ go(index + 1); }
    function prev(){ go(index - 1); }

    function start(){ stop(); timer = setInterval(() => { if (!hover) next(); }, 5000); }
    function stop(){ if (timer) clearInterval(timer); }
    function restart(){ start(); }

    // Also wire the buttons here (in addition to inline onclick)
    prevBtn && prevBtn.addEventListener('click', prev);
    nextBtn && nextBtn.addEventListener('click', next);

    wrapper.addEventListener('mouseenter', () => hover = true);
    wrapper.addEventListener('mouseleave', () => hover = false);

    // Touch swipe
    let sx = 0, dx = 0;
    wrapper.addEventListener('touchstart', (e)=> { sx = e.touches[0].clientX; dx = 0; }, {passive:true});
    wrapper.addEventListener('touchmove',  (e)=> { dx = e.touches[0].clientX - sx; }, {passive:true});
    wrapper.addEventListener('touchend',   ()=> { if (Math.abs(dx) > 40) (dx < 0 ? next() : prev()); });

    setActive(0);
    start();

    // expose controls globally for inline handlers
    window.__rc[id] = { next, prev, go };
  }

  // public helpers for inline onclick
  window.rcNext = function(id){ const c = window.__rc[id]; if (c) c.next(); };
  window.rcPrev = function(id){ const c = window.__rc[id]; if (c) c.prev(); };
  window.rcGo   = function(id,i){ const c = window.__rc[id]; if (c) c.go(i,true); };

  // Ensure DOM is ready before initializing
  if (document.readyState === 'loading') {
    document.addEventListener('DOMContentLoaded', () => init('research-highlights'));
  } else {
    init('research-highlights');
  }
})();
</script>
<!-- =================== End Research Highlights Carousel =================== -->




<!-- <div style="text-align: center;">
  <h2>News</h2>
</div> -->

<div style="height: 200px; overflow-y: auto; background-color: #f9f9f9; padding: 6px; border: 3px solid #ddd; font-family: Arial, sans-serif; font-size: 14px;">
  <ul>
    <li>06/25: I will be presenting our work this summer at <a href="https://fam.tuwien.ac.at/events/vcmf2025/index.php" target="_blank">VCMF 25</a> (Vienna), <a href="https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=85240" target="_blank">SIAM FM 25</a> (Miami), and at the 
    <a href="https://cs.duke.edu/events/graph-learning-and-spectral-clustering-high-dimensional-data" target="_blank">Duke</a> Computer Science Colloquium (Durham).</li>
    <li>03/25: I will be visiting the Huawei Research Center Zürich in March.</li>
    <li>03/25: The second edition of the AI & compliance seminar is taking place in <a href="https://www.academyfinance.ch/artificial-intelligence-and-compliance-processes-2/" target="_blank">Zürich</a>.</li>
    <li>11/24: I am presenting the foundation of the AI tools used in compliance at the <a href="https://www.academyfinance.ch/artificial-intelligence-and-compliance-processes/" target="_blank">Academy & Finance</a> seminar in Geneva.</li>
    <li>10/24: I will be presenting our recent work at the Deloitte Zürich seminar <a href="https://mkto.deloitte.com/FY25-Q2-FA-EV-Graphaton-24-Zurich-CH_Registration-page-Social.html" target="_blank">The power of graph technology in Financial Crime</a>.</li>
    <li>09/24: Our article <a href="https://ieee-hpec.org/wp-content/uploads/2024/09/176.pdf" target="_blank">Multilevel diffusion based spectral graph clustering</a> has received the Outstanding Paper Award at <a href="https://ieee-hpec.org/" target="_blank">IEEE HPEC</a>.</li>
    <li>06/24: Our interview with Albert-Jan Yzelman at ACM PASC regarding high performance graph analytics is now available <a href="https://www.youtube.com/watch?v=wzn7zgDC4hs" target="_blank">online</a>.</li>
    <li>06/24: The poster accompanying our article <a href="https://ssl.lu.usi.ch/entityws/Allegati/3010824_638529309691881843.pdf" target="_blank">GAMLNet: a graph based framework for the detection of money laundering</a> has received the Best Poster Award at <a href="https://sds2024.ch/conference-program/" target="_blank">IEEE SDS24</a>.</li>
    <li>03/24: Our article <a href="https://dl.acm.org/doi/10.1145/3650108" target="_blank">Sparse Precision Matrix Estimation With SQUIC</a> is published in ACM Transactions on Mathematical Software.</li>
    <li>03/24: We are organizing the minisymposia "Learning and Clustering Tasks on Graphical Structures" at <a href="https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=78748" target="_blank">SIAM LA 24</a> in Paris, and "High Performance Graph Analytics" at <a href="https://pasc24.pasc-conference.org/program/minisymposia/" target="_blank">PASC 24</a> in Zürich.</li>
    <li>11/23: I have been awarded a <a href="https://ddsa.dk/" target="_blank">DDSA</a> grant to visit the <a href="https://vbn.aau.dk/en/organisations/institut-for-matematiske-fag" target="_blank">Department of Mathematical Science</a> of Aalborg University.</li>
    <li>09/23: Our article <a href="http://albert-jan.yzelman.net/PDFs/pasadakis23a-pp.pdf" target="_blank">Nonlinear spectral clustering with C++ GraphBLAS</a> has received the Outstanding Short Paper Award at <a href="https://ieee-hpec.org/index.php/ieee-hpec-2023-prelim-agenda/#4-P" target="_blank">IEEE HPEC</a>.</li>
    <li>04/23: Our article <a href="https://ieeexplore.ieee.org/document/10091452" target="_blank">Sparse Quadratic Approximation for Graph Learning</a> is published in IEEE Transactions on Pattern Analysis and Machine Intelligence.</li>
    <li>04/23: The Swiss National Science Foundation (SNSF) project <a href="https://search.usi.ch/projects/1036/balanced-graph-partition-refinement-using-the-graph-p-laplacian" target="_blank">Balanced Graph Partition Refinement Using the Graph p-Laplacian</a> that supported my Phd studies is now complete.</li>
    <li>03/23: I have successfully defended my Phd thesis entitled <a href="http://DmsPas.github.io/files/PhD_Thesis_Pasadakis_signed.pdf" target="_blank">Learning and clustering graphs from high dimensional data</a>.</li>
    <li>07/22: Chairing the <a href="https://pasc22.pasc-conference.org/program/schedule/index.html%3Fpost_type=page&p=11&sess=sess173.html" target="_blank">AP1B - ACM Papers Session 1B</a> in PASC'22.</li>
    <li>12/21: Our article <em>Multiway p-spectral graph cuts on Grassmann manifolds</em> was featured in the <a href="https://hpc.fau.de/files/2021/12/newsletter_nhr_december21.pdf" target="_blank">newsletter</a> of the National Centre for High Performance Computing of the University of Erlangen (NHR@FAU).</li>
  </ul>
</div>
