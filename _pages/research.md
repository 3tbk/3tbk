<!DOCTYPE html>
<html>

  <body>

  
<nav class="navbar sticky-top navbar-expand-md navbar-dark bg-dark justify-content-center">
    <div class="container-fluid">
    <a class="navbar-brand" href="/">
        <img src="/favicon.ico" width="30" height="30" style="margin-right:5px" class="d-inline-block align-top" alt="">
        Comp. Physics @ GT CSE
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item dropdown">
                <li class="nav-item">
                  <a class="nav-link" href="/">Home</a>
                </li> 
                
                    <li class="nav-item">
                        <a class="nav-link" href="/team">Team</a>
                    </li> 
                
                    <li class="nav-item">
                        <a class="nav-link" href="/papers">Papers</a>
                    </li> 
                
                    <li class="nav-item">
                        <a class="nav-link" href="/research">Research</a>
                    </li> 
                
                    <li class="nav-item">
                        <a class="nav-link" href="/teaching">Teaching</a>
                    </li> 
                
                    <li class="nav-item">
                        <a class="nav-link" href="/software">Software</a>
                    </li> 
                
                    <li class="nav-item">
                        <a class="nav-link" href="/hardware">Hardware</a>
                    </li> 
                
                <!-- <a class="nav-link" href="/GSCS22">GSCS22</a> -->
            </li>
        </ul>
    </div>
    </div>
</nav>


    <div class="container-fluid">
      <div class="row">
        <div id="gridid" class="col-sm-12 col-xs-12">
  <h2 id="research">Research</h2>

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
  <!-- border: 1px solid black; -->
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

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

<p><!-- <iframe src="https://player.vimeo.com/video/455887852?autoplay=1&loop=1&autopause=0&muted=1&quality=240p&background=1" height="142px" frameborder="0" allow="autoplay"></iframe> --></p>

<div class="jumbotron">
  <div class="row align-items-end">
    <div class="col-md-9 col-sm-12">
      <h4>Learning from animals: Humpback whales</h4>
      <p>Perspective on bubble utilization can come from a surprising source: <strong>animals</strong>.
<a href="https://www.youtube.com/watch?v=Q8iDcLTD9wQ" target="_blank">Humpback whales hunt</a> using bubbly regions (called bubble nets) and loud vocalizations.
Specifically, they</p>
      <ul>
        <li>Release air from their blowholes while swimming, spiraling downwards</li>
        <li>Surround their prey with a wall of bubbles</li>
        <li>Vocalize from the exterior, trapping small fish in loud sound (~190dB!)</li>
        <li>Swim up and through the interior, lunge feeding on the fish</li>
      </ul>

      <p>While fascinating, the acoustic mechanisms enabling this behavior are not understood.
Our ensemble-averaged bubbly flow model simulates the relevant acoustic phenomena, <a href="/papers/bryngelson-JASA-20.pdf" target="_blank">advancing our interpretation of this behavior</a>.
Similar outcomes are desirable for sensitive, implanted biomedical devices.</p>
    </div>
    <div class="col-md-3 col-sm-12">
      <iframe src="https://player.vimeo.com/video/455688521?autoplay=1&amp;loop=1&amp;autopause=0&amp;muted=1&amp;quality=240p&amp;background=1" height="192px" frameborder="0" allow="autoplay"></iframe>
    </div>
  </div>
</div>

<div class="jumbotron">
  <div class="row align-items-end">
    <div class="col-md-9 col-sm-12">
      <h4>Therapy design via adjoint-based optimization</h4>
      <p>Designing medical therapies requires efficient optimization algorithms. 
Current methods fail to account for the <em>material interfaces</em> or <em>shock waves</em> that occur during treatments like lithotripsy and histotripsy.
We created an adjoint-based technique for navigating these complications and computes the gradient-based information required for such <a href="/papers/bryngelson-xpacc-18.pdf" target="_blank">optimization and sensitivity analysis</a>.</p>
    </div>
    <div class="col-md-3 col-sm-12" style="background-color:transparent">
      <p><img src="/images/respic/lithotripsy.jpg" width="175px" /></p>
    </div>
  </div>
</div>

<script src="/assets/javascript/bootstrap/jquery.min.js"></script>
<!-- <script src="/assets/javascript/popper/dist/umd/popper.min.js"></script> -->
<script src="/assets/javascript/bootstrap/bootstrap.bundle.min.js"></script>
<!-- <script src="/assets/javascript/shb.js"></script> -->



  </body>

</html>
