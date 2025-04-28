---
permalink: /
title: "Welcome to my website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am **Alihan Teke**, a researcher specializing in **Remote Sensing**, **Geographic Information Systems (GIS)**, and **Machine Learning** applications for environmental sciences.

I hold a Master's degree in Geomatics Engineering, and my academic interests focus on the prediction and mapping of natural hazards such as landslides, wildfires, and drought. My work particularly explores the integration of artificial intelligence techniques, such as explainable AI (XAI), into geospatial modeling to enhance the interpretability and robustness of hazard predictions.

Currently, my research emphasizes the causal inference of environmental processes using remote sensing data and machine learning algorithms. I am passionate about developing solutions that address complex environmental challenges through data-driven insights and spatial analytics.

Beyond research, I am committed to advancing interdisciplinary approaches that bridge the gap between Earth observation technologies and sustainable development goals.

> "Science is the engine that drives human progress. Let’s use it wisely."

Feel free to connect with me through my [LinkedIn](https://linkedin.com/in/kullanici-adin) or check out my latest publications on [Google Scholar](https://scholar.google.com/citations?user=Scholar-ID).

<hr>

## 🌍 Research Footprint Map

<div id="map" style="width: 100%; height: 500px; margin-top: 20px; border-radius: 10px;"></div>

<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<script>
  var map = L.map('map').setView([38.9637, 35.2433], 5); // Turkey

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; OpenStreetMap contributors'
  }).addTo(map);

  // Example Markers
  L.marker([36.8969, 30.7133]).addTo(map) // Antalya
    .bindPopup("<b>Manavgat Wildfire Study Area</b>");

  L.marker([41.0082, 28.9784]).addTo(map) // Istanbul
    .bindPopup("<b>Istanbul Urban Study</b>");
</script>

