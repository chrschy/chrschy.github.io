---
layout: page
permalink: /
title: about
nav: about
---

<div class="text-center mt-5">
  <img class="profile-img" src="{{ 'christopher.jpg' | prepend: '/assets/img/' | prepend: site.baseurl }}">
</div>

<div class="col mt-4">
  <h1 class="title text-center font-weight-bold">Christopher Schymura</h1>
</div>

<!-- Introduction -->

<div class="col text-justify p-0">
I am an experienced machine learning researcher, enjoying to make machine learning solutions tangible for real-world applications. My research interests particularly focus on combining probabilistic models with deep learning techniques to develop end-to-end trainable systems with meaningful uncertainty estimates. Currently, I am working as a data scientist at <a href="https://www.cropscience.bayer.com" target="_blank">Bayer Crop Science</a>. I am also a co-founder of the <a href="https://data-science-kitchen.github.io/" target="_blank">Data Science Kitchen</a>, a non-profit group which promotes open source research and regularly participates in data science challenges.

<br/><br/>
Before joining Bayer, I was a data scientist in the Cognitive Solutions team at <a href="https://digital.evonik.com/" target="_blank">Evonik Digital GmbH</a> and a postdoctoral researcher in the <a href="https://cognitive-signal-processing.de/" target="_blank">Cognitive Signal Processing Group</a> at <a href="https://etit.ruhr-uni-bochum.de/" target="_blank">Ruhr University Bochum</a>. My postdoctoral research focused on fusing classical probabilistic models with modern deep learning approaches for applications in audiovisual signal processing. I successfully conducted a joint research project with <a href="http://www.kecl.ntt.co.jp/english/" target="_blank">NTT Communication Science Labs</a>, which was geared towards deep learning models for probabilistic inference in multimodal time-series signals.
<br/><br/>
I obtained a PhD degree in Electrical Engineering and Information Technology from <a href="https://etit.ruhr-uni-bochum.de/" target="_blank">Ruhr University Bochum</a>, advised by <a href="https://etit.ruhr-uni-bochum.de/fakultaet/professuren/prof-dr-ing-dorothea-kolossa/" target="_blank">Dorothea Kolossa</a>. During my time as a doctoral researcher at the <a href="https://cognitive-signal-processing.de/" target="_blank">Cognitive Signal Processing Group</a>, I focused on probabilistic graphical models for multimodal data fusion. A central aspect of my <a href="https://hss-opus.ub.ruhr-uni-bochum.de/opus4/frontdoor/index/index/year/2020/docId/6987/" target="_blank">PhD thesis</a> was the derivation of the <a href="https://ieeexplore.ieee.org/document/9037104" target="_blank">Dynamic Stream Weight Kalman Filter</a> - a model for recursive Bayesian estimation in dynamical systems with multimodal observations, where time-varying uncertainty in different sensor inputs is explicitly taken into account. Other aspects of my PhD research included causal inference with application to acoustic signal processing tasks and Bayesian methods for robot audition, where the latter was primarily tackled within the <a href="http://twoears.eu/" target="_blank">Two!Ears</a> research consortium.
<br/><br/>
</div>

<!-- News 
<div class="news mt-3 p-0">
  <h1 class="title mb-4 p-0">news</h1>
  {% assign news = site.news | reverse %}
  {% for item in news limit: site.news_limit %}
    <div class="row p-0">
      <div class="col-sm-2 p-0">
        <span class="badge info-color-dark font-weight-bold text-uppercase align-middle date ml-3">
          {{ item.date | date: "%b %-d, %Y" }}
        </span>
      </div>
      <div class="col-sm-10 mt-2 mt-sm-0 ml-3 ml-md-0 p-0 font-weight-light text">
        <p>{{ item.content | remove: '<p>' | remove: '</p>' | emojify }}</p>
      </div>
    </div>
  {% endfor %}
</div>-->
