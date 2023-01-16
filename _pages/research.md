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
<div class="row align-items-end">
  <div class="col-md-12 col-sm-12">   
  <h4><b>Development of IoT-based Monitoring System for Offshore Wind</b></h4>
  <i>Objective</i>    
  <p>Development of smart safety evaluation technology for offshore wind power support structures using digital twin technology </p>
  <i>Concept of Digital Twin</i>    
   <ul>
        <li>A numerical model of an offshore wind turbine is created using ANSYS software.</li>
        <li>Having the wind turbine fully characterized, the FEM is calibrated using data from Data Acquisition. Both measured and simulated responses allow the identification and validation of structural dynamic properties and dynamic performances.</li>
        <li>The developed digital twin model will be used to provide a tool for continuous tracking of accumulated fatigue damage and evaluation of alternative operation strategies.</li>
   </ul>
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/digital twin 1.png" width="70%"/></p>
   </ul>
    
   <i>Development of Digital Twin</i>
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/digital twin 2.png" width="70%"/></p>
   </ul>
  </div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
  <div class="col-md-12 col-sm-12">   
  <h4><b>Structural Safety Improvement of Wind Tower</b></h4>
  <i>Introduction</i>  
  <p>Ring flange joint with preloaded high strength bolts is the most common solution used to attach wind tower segments to each other. During the operating conditions, the flange may be separated or the bolt may be ruptured, leading to the complete failure of the wind tower structure. Therefore, it is necessary to understand the performance of the flange joints in practical design.</p>
  <i>Existing Failure Modeling </i>
  <p>The main failures in the bolted flange joint can be classified into three different modes:</p>
   <ul>
        <li>Failure mode A: bolt failure only</li>
        <li>Failure mode B: bolt failure along with plastic hinge in flange-to-shell junction</li>
        <li>Failure mode C: plastic hinge in flange and flange-to-shell junction</li>
        <li>Failure mode D: plastic hinge in the flange at the bolt hole center and flange-to-shell junction</li>
        <li>Failure mode E: plastic hinge in the flange next to the bolt hole center and flange-to-shell junction</li>
   </ul>
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/flange joint 1.png" width="70%"/></p>
   </ul>
    
  <i>New failure modes</i>
   <ul>
        <li>Failure mode B*: yielding of bolt only</li>
        <li>Failure mode B**: yielding of flange-to-shell junction only</li>
   </ul>
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/flange joint 2.png" width="70%"/></p>
   </ul>
  </div>
</div>
</div>



<div class="jumbotron">
<div class="row align-items-end">
  <div class="col-md-12 col-sm-12">   
  <h4><b>Development of Numerical Model for Nuclear Facilities</b></h4>
  <i>Introduction</i>  
  <p>In the nuclear industry, the electric cabinet is an indispensable component, which contains many electrical types of equipment installed inside, such as distribution panel, switchboard, lighting panel, and other types of electrical devices for different purposes. Due to the very large number of configurations, it is impossible to perform an experiment test. It is necessary to develop the numerical models to evaluate the dynamic behavior of the full range of electric cabinet.</p>
  </div>
  <div class="col-md-5 col-sm-12">
   <ul>    
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/cabinet 1.png" height="200"/></p>
   </ul>
  </div>
  <div class="col-md-7 col-sm-12" style="background-color:transparent">
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/cabinet 2.png" height="200"/></p>
   </ul>   
  </div>
  <div class="col-md-12 col-sm-12">   
  <i>Numerical model of cabinet</i>  
  <p>Three models, including the beam stick model, bare-frame model, and full finite element model, are developed that consider the nonlinear effects. Detailed explaination are as:</p>
  </div>
  <div class="col-md-3 col-sm-12" style="background-color:transparent"> 
   <ul>    
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/cabinet 3.png" height="200"/></p>
     Beam-stick model
        <li>Nonlinear model</li>
        <li>Cabinet is modelled as vertical beam</li>
        <li>Consider effect of axial force and restoring force</li>
        <li>Fixed boundary conditions at base</li>
   </ul>
  </div>
  <div class="col-md-5 col-sm-12" style="background-color:transparent">
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/cabinet 4.png" height="200"/></p>
     Bare-frame model
        <li>Nonlinear model</li>
        <li>Cabinet is modelled with frame element only</li>
        <li>Consider the local buckling modese</li>
        <li>Fixed boundary conditions at base</li>
   </ul>   
  </div>
  <div class="col-md-4 col-sm-12" style="background-color:transparent">
   <ul>
     <p><img src="{{ site.url }}{{ site.baseurl }}/images/research/cabinet 5.png" height="200"/></p>
     Full FEM model
        <li>Nonlinear model</li>
        <li>Full cabinet model with plate and frame members</li>
        <li>Nonlinear connections between plate and frame </li>
        <li>Consider effect of anchor bolts at base</li>
   </ul>   
  </div>
</div>
</div>
