---
title: "Publications" 
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

 <div class="container">
                <div class="row">
                    <div class="col-md-3">
                        <nav id="navi">
                            <ul>
                                <li><a href="#page-1p">Peer-reviewed Articles</a></li>
                                <li><a href="#page-2p">Book Chapters</a></li>
                                <li><a href="#page-3p">Conference Proceedings</a></li>                               
                            </ul>
                        </nav>
                    </div>
                    <div class="col-md-9">
                        <div id="page-1p" class="page one">
                            <h2 class="heading">Peer-reviewed Articles</h2>
                            <div class="resume-wrap d-flex ftco-animate">
                                <div class="text pl-3">
                                    <div class="jumbotron">
                                        ### Invited talks
                                        {% bibliography --query @misc %}
                                    </div>
                                </div>
                            </div>			
                        </div>
                    </div>
                </div>
    </div>
                        
<div class="jumbotron">
### Invited talks
{% bibliography --query @misc %}
</div>


<div class="jumbotron">
### Books
{% bibliography --query @book %}
</div>

<div class="jumbotron">
### Journal articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Conference proceedings
{% bibliography --query @inproceedings %}
</div>
