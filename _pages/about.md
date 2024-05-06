---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div class="main" id="about2"></div>
# About
Hi there! I am a current postdoc at MIT working on <strong>heat transfer estimation procedures for spatial temporal multiscale problems</strong>. During my PhD, I developed reduced order models for the efficient solution of non-linear solid mechanics with applications to mechanical metamaterials. My thesis can be downloaded [here](files/thesis.pdf).

My CV can be found [here](files/cv.pdf).

**Keywords**: estimation methods, reduced order modeling, metamaterials, multi-scale problems, numerical methods for PDEs, machine learning

<div style="margin-top: 50px;"></div>
<div class="main" id="news2"></div>
# News
- 2024.03 Relocated to Boston and started my postdoc at MIT!
- 2024.02 Successfully graduated my PhD!
- 2023.09 Best poster award at MORTECH 2023!

<div style="margin-top: 50px;"></div>
<div class="main" id="experiences2"></div>
# Experiences
<style>
  .bubble {
    display: inline-block;
    padding: 8px 12px;
    border-radius: 10px; /* Adjust the border-radius to make it more square-like */
    background-color: #f0f0f0;
    color: #333;
    font-size: 1.4em; /* Adjust the font size */
  }
  
  table {
    border-collapse: collapse;
    width: 100%;
  }
  
  td {
    border: 1px solid transparent; /* Invisible border */
    padding: 10px; /* Adjust the padding */
  }
  
  .job {
    font-size: 1.4em; /* Adjust the font size of the job */
  }
</style>

<table>
  <tr>
    <td><span class="bubble">Mar 2024 - Now</span></td>
    <td>&nbsp;</td> <!-- Non-breaking space for spacing -->
    <td><span class="job">Postdoctoral Associate, <strong>MIT</strong> <br> Advisor: <a href="https://cse.mit.edu/people/anthony-t-patera/">Anthony Patera</a></span></td>
  </tr>
  <tr>
    <td><span class="bubble">Feb 2020 - Feb 2024</span></td>
    <td>&nbsp;</td> <!-- Non-breaking space for spacing -->
    <td><span class="job">PhD Candidate, <strong>TU Eindhoven</strong> <br> Advisors: <a href="https://www.tue.nl/en/research/researchers/karen-veroy-grepl">Karen Veroy</a>, <a href="https://www.tue.nl/en/research/researchers/ondrej-rokos">Ondřej Rokoš</a></span></td>
  </tr>
</table>



<div style="margin-top: 50px;"></div>
<div class="main" id="publications2"></div>
# Publications

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;"> Recent publications</summary>
  <div markdown="1" style="font-size: 0.8em;">

  {% assign reversed_publications = site.publications | reverse %}
  {% for post in reversed_publications limit:3 %}
      {% include archive-single.html %}
  {% endfor %}
  </div>
</details>

<details>
  <summary style="font-size: 1.2em; font-weight: bold;"> Other publications</summary>
  <div markdown="1" style="font-size: 0.8em;">

  {% assign reversed_publications = site.publications | reverse %}
  {% assign excluded_publications = reversed_publications | slice: 3, reversed_publications.size %}
  {% for post in excluded_publications %}
      {% include archive-single.html %}
  {% endfor %}

  </div>
</details>

<!-- <div style="margin-top: 50px;"></div>
# Talks -->



<!-- ## About me
In my free time, I am interested in a variety of things including:
- Bouldering (mostly indoors but planning on going outdoors as well)
- Cycling and hiking
- Playing table tennis and badminton
- Cooking/baking
- Experimenting with coffee
- Looking for and exploring new cuisines from different countries
- Piano -->