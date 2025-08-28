---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<!-- <embed src="https://Coaster41.github.io/files/cv.pdf" type="application/pdf" /> -->
<iframe src="https://Coaster41.github.io/files/cv.pdf" width="100%" height="800px">
    <p>Your browser does not support iframes. <a href="https://Coaster41.github.io/files/cv.pdf">Download the PDF</a> instead.</p>
</iframe> <br> <br>

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of California, Irvine, 2029 (expected)
* B.S. in Computer Science, University of California, Santa Cruz, 2024

Work experience
======
* Summer 2024: Software Engineering II Intern
  * IoT Cisco Systems
  * Built a REST API asset connection workflow engine in Golang utilizing Ollama and Splunk for device health and securty monitoring

* Summer 2023: Software Engineering I Intern
  * IoT Cisco Systems
  * Developed an IoT troubleshooting dashboard and a microservice application manager in Java applying Apache Freemarker templating for runtime workflow modification

* Summer 2022: Software Engineering I Intern
  * Webex Cisco Systems
  * Reduced K8s and Docker cloud costs by up to 80\%, through transitioning to AWS Spot EC2 and Graviton ARM instances and implementing automatic node shutdown and cluster scaling.
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
