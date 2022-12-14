---
title: "Software"
layout: gridlay
sitemap: false
permalink: /software/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}
</style>

## Software

<div class="jumbotron">
<div class="row align-items-end">
  <div class="col-md-12 col-sm-12">   
  <h4><b>PSHAKE: Probabilistic Site Response Analysis</b></h4>
  <a href="https://1drv.ms/u/s!AiUeXuxJtpnDweEUizhx64Z_4dG3hA?e=i9YCoO" target="_blank"><button class="btn btn-success btn-sm">SOURCE</button></a>
  <a href="{{ site.url }}{{ site.baseurl }}/software/pshake/pShake.pdf" target="_blank"><button class="btn btn-info btn-sm">MANUAL</button></a>
  <a href="{{ site.url }}{{ site.baseurl }}/papers/2020-Tran-ASCE.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a>
  <a href="{{ site.url }}{{ site.baseurl }}/software/pshake/Copyright.pdf" target="_blank"><button class="btn btn-warning btn-sm">COPYRIGHT</button></a>
    
  <b>Authors:</b>
  <i>Thanh-Tuan Tran and Dookie Kim</i>
  </div>
  
  <div class="col-md-6 col-sm-12">      
PSHAKE is a program for probabilistic site response analysis based on the Monte Carlo Simulation. The solution can consider the uncertainties of geotechnical parameters:

   <ul>
        <li>shear wave velocity</li>
        <li>layer thickness</li>
        <li>unit weight</li>
        <li>material degradation</li>
   </ul>
  </div>
  <div class="col-md-6 col-sm-12" style="background-color:transparent">
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/software/pshake/pshake.png" width="100%"/></p>
   </ul>
  </div>
    
  </div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
  <div class="col-md-12 col-sm-12">   
  <h4><b>KSMAP: Korea Seismicity Map</b></h4>
  <a href="https://1drv.ms/u/s!AiUeXuxJtpnDweEWKe_Kvf1E-LhNwA?e=Fy5nuE" target="_blank"><button class="btn btn-success btn-sm">SOURCE</button></a>
  <a href="{{ site.url }}{{ site.baseurl }}/software/ksmap/KS_MAP.pdf" target="_blank"><button class="btn btn-info btn-sm">MANUAL</button></a>
  <a href="{{ site.url }}{{ site.baseurl }}/papers/2019-Cao-NT.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> 
  <a href="{{ site.url }}{{ site.baseurl }}/software/ksmap/copyright.pdf" target="_blank"><button class="btn btn-warning btn-sm">COPYRIGHT</button></a> 
      
  <b>Authors:</b>
  <i>Thanh-Tuan Tran and Dookie Kim</i>
  </div>
  
  <div class="col-md-6 col-sm-12">      
KSMAP is a tool for calculating the peak ground acceleration (PGA) in Korean Peninsula. The procedure is as below:

   <ul>
        <li>STEP 1: Select the map (e.g., 2013-0050)</li>
        <li>STEP 2: Set the coordinate from the map</li>
        <li>STEP 3: Compute the PGA value (g)</li>
   </ul>
  </div>
  <div class="col-md-6 col-sm-12" style="background-color:transparent">
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/software/ksmap/ksmap.png" width="100%"/></p>
   </ul>
  </div>
    
  </div>
</div>



<div class="jumbotron">
<div class="row align-items-end">
  <div class="col-md-12 col-sm-12">   
  <h4><b>UQSSL: Uncertainty Quantification in Structural Seismic Responses </b></h4>
  <a href="{{ site.url }}{{ site.baseurl }}/papers/2019-Tran-NED.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> 
  
  <b>Authors:</b>
  <i>Thanh-Tuan Tran</i>
    
Program UQSSL has been developed and implemented in MATLAB environment. A main process of probabilistically solving the stated in the following steps:

   <ul>
        <li>Determine the statistical parameters of the structural properties</li>
        <li>Generate a set of input variables, in terms of number, n, (number of interval) and shape (triangular, trapezoidal, Gaussian) of the fuzzy inputs</li>
        <li>Perform analysis by solving the EoM for each input variables in step 2 to calculate the outputs</li>
        <li>Statistical analysis of the results and determine the related input and outputs</li>
    </ul>
  </div>
  <div class="col-md-6 col-sm-12" style="background-color:transparent"> 
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/software/uqssl/uqssl.png" width="100%"/></p>
   </ul>
  </div>
      
  <div class="col-md-6 col-sm-12" style="background-color:transparent">
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/software/uqssl/uqssl2.png" width="100%"/></p>
   </ul>
  </div>
    
  </div>
</div>



<div class="jumbotron">
<div class="row align-items-end">
  <div class="col-md-12 col-sm-12">   
  <h4><b>VC4OWT: Vibration Control of Offshore Wind Turbine</b></h4>
  <a href="https://1drv.ms/u/s!AiUeXuxJtpnDweEmJPFPgx0JaYLRPQ?e=6v4TyY" target="_blank"><button class="btn btn-success btn-sm">SOURCE</button></a>
  <a href="{{ site.url }}{{ site.baseurl }}/software/vc4owt/VC4OWT.pdf" target="_blank"><button class="btn btn-info btn-sm">MANUAL</button></a>
  <a href="{{ site.url }}{{ site.baseurl }}/papers/2018-Tran-VSOE.PDF" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> 
  <a href="{{ site.url }}{{ site.baseurl }}/software/vc4owt/copyright.pdf" target="_blank"><button class="btn btn-warning btn-sm">COPYRIGHT</button></a> 
  
  <b>Authors:</b>
  <i>Thanh-Tuan Tran, Minh-Luong Le and Dookie Kim</i>
  </div>
  
  <div class="col-md-6 col-sm-12">      
VC4OWT is a graphical user interface for vibration control of the OWT structure based on OpenSees. The tool can consider the structural performances of OWT in the case of: 
    
   <ul>
        <li>w/wo friction damper</li>
        <li>w/wo SSI</li>
   </ul>
    
 The software consists of five main groups:
    
   <ul>
         <li>Group 1: Input</li>
         <li>Group 2: Analysis cases</li>
         <li>Group 3: Analysis types</li>
         <li>Group 4: Results</li>
         <li>Group 5: Graphic</li>
   </ul>
    
  </div>
  <div class="col-md-6 col-sm-12" style="background-color:transparent">
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/software/vc4owt/vc4owt.png" width="100%"/></p>
   </ul>
  </div>
    
  </div>
</div>
