---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<!-- <embed src="https://Coaster41.github.io/files/cv.pdf" type="application/pdf" /> -->
<iframe src="https://Coaster41.github.io/files/cv.pdf" style="width: 100%; aspect-ratio: 1 / 1;">
    <p>Your browser does not support iframes. <a href="https://Coaster41.github.io/files/cv.pdf">Download the PDF</a> instead.</p>
</iframe> <br> <br>

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of California, Irvine, 2024 - 2029 (expected)
  * Advisor: Professor Padhraic Smyth
* B.S. in Computer Science, University of California, Santa Cruz, 2021 - 2024
  * Advisors: Professors Leilani Gilpin, Luca de Alfaro

Research interests
======
* Mechanistic Interpretability, eXplainable AI (XAI), Time Series and Tabular Foundation Models, Anomaly Detection

Work experience
======
* Summer 2024: Software Engineering II Intern
  * Secure Equipment Access, Cisco Systems
  * Built an extensible REST API asset connection workflow engine in Golang utilizing Ollama and Splunk for device health and security monitoring, and reduced batch computing overhead through multi-threaded integration in the REST API server and SSH client engine

* Summer 2023: Software Engineering I Intern
  * Internet of Things, Cisco Systems
  * Developed an IoT troubleshooting dashboard and a microservice application manager in Java applying Apache Freemarker templating for runtime workflow modification

* Summer 2022: Software Engineering I Intern
  * Webex, Cisco Systems
  * Reduced K8s and Docker cloud costs by up to 80%, through transitioning to AWS Spot EC2 and Graviton ARM instances and implementing automatic node shutdown and cluster scaling

Research experience
======
* The DataLab, UC Irvine (September 2024 - Present)
  * Advisor: Professor Padhraic Smyth
  * Time series and tabular foundation models: mechanistic interpretability and calibration of TSFMs using sparse autoencoders, anomaly detection in large-scale univariate time series with Google using SHAP, Integrated Gradients, and GradCAM to explain false positives, and evaluation of tabular foundation models against fine-tuned LLM baselines

* ACM Undergraduate AI Research Lab, UC Santa Cruz (March 2023 - June 2024)
  * Advisors: Coen Adler, Arnav Kartikeya
  * Undergraduate AI-focused research lab introducing AI research to undergraduate students: usage of Meta's Segment Anything Model on GRAD-CAM for medical segmentation, and applications of Physics-Informed Neural Networks on complex geometric aerodynamics

* Artificial Intelligence Accountability Explainability Lab, UC Santa Cruz (December 2021 - June 2024)
  * Advisor: Professor Leilani Gilpin
  * Explainable AI with work in robust and fair AI systems: GAN applications in AV robustness, benchmarking disagreements of SHAP and LIME explanations, and fair augmentation of decision trees. Led lab organization and resource/computing usage

* Computational Ecology Lab, UC Santa Cruz (December 2021 - June 2024)
  * Advisor: Professor Luca de Alfaro
  * Applications of game theory and machine learning to the study of interactions: diffusion model for mapping forest bird habitat connectivity, and architecture for a bird mapping browser tool

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

Student leadership
======
* UCSC ACM Chapter, President (Sep 2022 - June 2024)
  * UCSC's largest CSE student organization, with 1,000+ members. Co-founded the undergraduate AI research lab and organized weekly technical workshops and the annual hackathon

* Santa Cruz Artificial Intelligence, Director of Instruction (Sep 2022 - June 2024)
  * Designed the AI/ML curriculum and led weekly workshops for UCSC's student AI/ML organization

* Google Developer Student Club, Director of Instruction (Sep 2022 - June 2024)
  * Developed and taught weekly coding workshops on Google Cloud Platform, TensorFlow, and Kubernetes for UCSC's GDSC chapter

Honors and scholarships
======
* UC Irvine Computer Science Department Research Fellowship (UCI), 2024
* Chancellor's Undergraduate Research Award (UCSC), 2024
* Dean's Undergraduate Research Award (UCSC), 2024
* Dean's Award (UCSC), 2021 - 2024

Skills
======
* Tools: Git, Kubernetes, Slurm, Docker, PostgreSQL, OpenAPI, GCP, AWS, Gradle, Helm, Neo4j
* Frameworks: PyTorch, TensorFlow, SpringBoot, Pandas, NumPy, Ollama, Scikit-learn
* Languages: Python, Golang, Java, C/C++, SQL, R, Flutter/Dart

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
