---
title: "Achievement" 
layout: gridlay
sitemap: false
permalink: /achievement/
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
