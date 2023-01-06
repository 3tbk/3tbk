---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Research
<div class="jumbotron">
  <h4>Quantum computing for partial differential equations</h4>
  <p>Computational fluid dynamics simulations use the lion’s share of the world’s HPC resources.
These simulations are based on PDEs and are thus expensive, both in node hours and dollars.
They are also inefficient: A staggering quantity of the marshaled computational resources are required to represent the effects of microscopically small features that accumulate to have macroscopic effects.</p>
  <div class="row align-items-end">
    <div class="col-md-9 col-sm-12">
      <ul>
        <li>Our group works on <strong>quantum algorithms</strong> for the PDEs that govern fluid flows and other phenomena to gain exponential speedups</li>
        <li>We develop quantum lattice-based algorithms like quantum lattice Boltzmann and lattice gas</li>
        <li>Quantum <em>simulation</em> is used to scale our algorithms to large HPC resources for analysis</li>
      </ul>
    </div>
    <div class="col-md-3 col-sm-12" style="background-color:transparent">
      <p><img width="100%" src="/images/respic/qlbm.png" /></p>
    </div>
  </div>
</div>

<div class="jumbotron">
  <div class="row align-items-end">
    <div class="col-md-9 col-sm-12">
      <h4>Cavitation as a gateway to better therapies</h4>
      <p>Cavitating bubbles can ablate cancer cells, fragment tissues, and deliver drugs, among other functions.
We create high-fidelity computational methods to simulate these dynamics.
Examples are:</p>
      <ul>
        <li>Euler–Euler and Euler–Lagrange <a href="/papers/bryngelson-IJMF-19.pdf" target="_blank">sub-grid bubble cloud models</a></li>
        <li>Accelerated models using a <a href="/papers/bryngelson-IJMF-20.pdf" target="_blank">statistical paradigm and neural networks</a></li>
        <li>Implementation in our open-source solver <a href="/papers/bryngelson-CPC-20.pdf" target="_blank">MFC</a></li>
      </ul>

      <p>These enable realistic simulation of the bubble populations that nucleate during treatment.
This has impacted application-specific treatments, including:</p>
      <ul>
        <li>Improved <em>burst-wave lithotripsy administration</em> in human trials</li>
        <li>Understanding of <a href="/papers/schmidmayer-JCP-20.pdf" target="_blank">bubble-collapse-rebound</a> dynamics</li>
        <li>Cavitation-induced <a href="/papers/trummler-JFM-20.pdf" target="_blank">erosion potential</a> for rough materials</li>
      </ul>
    </div>
    <div class="col-md-3 col-sm-12" style="background-color:transparent;">
      <iframe src="https://player.vimeo.com/video/455888052?autoplay=1&amp;loop=1&amp;autopause=0&amp;muted=1&amp;quality=240p&amp;background=1" height="182px" frameborder="0" allow="autoplay"></iframe>
    </div>
  </div>
</div>


