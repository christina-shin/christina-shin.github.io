---
layout: page
title: Research
---

With the growing deployment of vehicular communication technologies (e.g., V2X and 5G cellular), vehicles and infrastructure are becoming connected to each other and to the cloud. This connectivity enables a fundamental shift: rather than confining 3D data operations to individual vehicles or sensors, 3D data can now be *streamed, aggregated, interpreted, and delivered across the network*. This shift introduces new opportunities but also new challenges: not just how to sense or store 3D data, but how to operate and manipulate it effectively in a cloud-connected vehicular ecosystem.

My research explores **how 3D data can be harnessed as a shared and networked resource in vehicular systems**:
- **[Reconstruction]** How to collect and reconstruct 3D traffic scenes by aggregating data from distributed sensors
- **[Interpretation]** How to extract semantic understanding from the reconstructed scene in the cloud in real-time
- **[Delivery]** How to deliver rich 3D content from the cloud to vehicles to support immersive in-vehicle visualization applications

Ultimately, my research envisions a future where 3D data is no longer treated merely as a local sensing artifact, but **as a shared medium that enables collaborative perception, coordinated decision making, and immersive vehicular experiences**.

<details open>
  <summary>Reconstruction</summary>
    {% assign pub = site.data.pub | where: "ID", "recap" | first %}
    <a href="{{ pub.url }}">
        <strong><span style="color:#4281A4; font-size:1.2rem;">{{ pub.title }}</span></strong>
    </a>

    <div class="media-pair">
      <div class="media-item">
        <div class="media-wrapper">
          <img src="/assets/img_recap.png" alt="Description of image">
        </div>
        <!-- <p class="media-caption">Figure 1: Example image</p> -->
      </div>

      <div class="media-item">
        <div class="media-wrapper">
          <iframe src="https://www.youtube.com/embed/SSTa3OhqiO4?autoplay=1&mute=1" 
                  frameborder="0" 
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                  allowfullscreen>
          </iframe>
        </div>
        <!-- <p class="media-caption">Figure 2: Example video</p> -->
      </div>
    </div>

    RECAP focuses on vehicle-to-cloud 3D sensor data streaming and explores how vehicles equipped with onboard 3D sensors can offload their data to the cloud while the cloud enables high-fidelity reconstruction of complex traffic scenes via multi-view fusion from inputs from multiple moving vehicles.
    <br>
    The core challenge in RECAP lies in accurately and quickly fusing large volumes of 3D data from
    dynamic, sparsely overlapping views across space and time. Building upon prior work on 3D view fusion, RECAP introduces techniques that minimize reconstruction error and computational cost in these highly asynchronous observation scenarios.
</details>

<details open>
  <summary>Interpretation</summary>
    {% assign pub = site.data.pub | where: "ID", "cip" | first %}
    <a href="{{ pub.url }}">
        <strong><span style="color:#4281A4; font-size:1.2rem;">{{ pub.title }}</span></strong>
    </a>

    <div class="media-pair">
      <div class="media-item">
        <div class="media-wrapper">
          <img src="/assets/img_cip.png" alt="Description of image">
        </div>
        <!-- <p class="media-caption">Figure 1: Example image</p> -->
      </div>

      <div class="media-item">
        <div class="media-wrapper">
          <iframe src="https://www.youtube.com/embed/-g0ohldId3I?autoplay=1&mute=1" 
                  frameborder="0" 
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                  allowfullscreen>
          </iframe>
        </div>
        <!-- <p class="media-caption">Figure 2: Example video</p> -->
      </div>
    </div>

    CIP targets infrastructure-side sensing where 3D sensor-equipped roadside units stream 3D data to the cloud for large-scale traffic perception. It investigates how to extract semantic insights from traffic intersections in real-time.
    <br>
    To generate perception outputs fast enough for autonomous driving use cases, CIP must process large scale 3D scenes within 100 ms while achieving accuracy that match or exceed state-of-the-art vision algorithms. To meet this requirement, CIP introduces a novel alignment algorithm for accurate view fusion, along with efficient implementations of key perception tasks including dynamic object extraction, tracking, and motion estimation.
</details>

<details open>
  <summary>Delivery</summary>
    <!-- {% assign pub = site.data.pub | where: "ID", "mars" | first %}
    <a href="{{ pub.url }}">
        <strong><span style="color:#6a9fb5; font-size:1.2rem;">{{ pub.title }}</span></strong>
    </a> -->
    <strong><span style="color:#4281A4; font-size:1.2rem;">3D Video Delivery to in-vehicle AR Display (under submission)</span></strong>
    <br>
    While RECAP and CIP demonstrate how vehicles and infrastructure can collaboratively sense and interpret the traffic environment, this work extends this vision by exploring how 3D data can also serve human-facing applications like in-vehicle infotainment, navigation assistance, and spatially aware content delivery.
    <br>
    This work is motivated by growing availability of augmented rendering devices or augmented reality headup displays within modern vehicles. It opens the door for streaming 3D video as a spatially immersive medium that offers more expressive visual experiences to passengers in vehicles.
    <br>
    Delivering such content in a mobile vehicular context introduces new technical challenges:
    <ul style="margin-bottom: -0em; padding-left: 1.5em;">
        <li>Bandwidth constraints must be addressed to support the large size and complexity of 3D video streams especially under highly dynamic network conditions.</li>
        <li>Adaptation to vehicle motion is required to maintain spatial coherence and rendering accuracy during playback accounting for changes in position and speed.</li>
    </ul>
    This work aims to address these challenges by designing systems that treat 3D video not as a static asset, but as a context-aware and adaptive data stream responsive to vehicle dynamics and network conditions. This direction expands the scope of the thesis beyond machine understanding of 3D data (as explored in RECAP and CIP) to human-centered consumption of 3D content within vehicular environments.
</details>
