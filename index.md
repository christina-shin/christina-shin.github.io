---
layout: default
title: Home
---

## Bio Sketch

I am a Ph.D. candidate in [Department of Computer Science](https://www.cs.usc.edu) at [University of Southern California](http://www.usc.edu), where I am advised by [Prof. Ramesh Govindan](https://govindan.usc.edu) in the [Networked Systems Lab (NSL)](https://nsl.usc.edu). My research interests include computer networking, mobile computing, autonomous & connected vehicles, AR/VR systems, volumetric video streaming, 3D data processing, and 3D mapping.

Before joining USC, I received my B.S. and M.S. degree in Computer Science and Engineering from [Ewha Womans University](https://www.ewha.ac.kr).

**I am currently on job market!**

---

## Experience

> **[Networked Systems Lab](https://nsl.usc.edu)**, University of Southern California (Aug 2019 - Present)<br>
> Research Assistant (Advisor: [Prof. Ramesh Govindan](https://govindan.usc.edu))

> **[General Motors](https://www.gm.com/research)**, Warren, Michigan (Summer 2021 & Summer 2024)<br>
> Research Intern (Mentor: Fan Bai and Chuan Li)

> **[Intelligent Networked Systems Lab](https://inslab-ewha.weebly.com)**, Ewha Womans University (Jan 2017 - May 2019)<br>
> Research Assistant (Advisor: [Prof. HyungJune Lee](https://home.ewha.ac.kr/hyungjunelee))

---

## Publication
### Conference
<div>
{% for pub in site.data.pub %}
    {% if pub.ENTRYTYPE == "inproceedings" %}
        {% if pub.img %}
            {% include pubentry.html %}
        {% endif %}
    {% endif %}
{% endfor %}
</div>

### Journal
<div>
{% for pub in site.data.pub %}
    {% if pub.ENTRYTYPE == "article" %}
        {% if pub.img %}
            {% include pubentry.html %}
        {% endif %}
    {% endif %}
{% endfor %}
</div>
<p>* Equal contribution</p>

<!-- ### Conference

- **[RECAP: 3D Traffic Reconstruction](https://dl.acm.org/doi/10.1145/3636534.3690691)**<br>
**Christina Suyong Shin**, Weiwu Pang, Chuan Li, Fan Bai, Fawad Ahmad, Jeongyeup Paek, and Ramesh Govindan<br>
*Proceedings of the ACM on Mobile Computing and Networking (MobiCom)*, 2024.

- **[Cooperative Infrastructure Perception](https://doi.ieeecomputersociety.org/10.1109/IoTDI61053.2024.00010)**<br>
**Christina Suyong Shin\***, Fawad Ahmad\*, Weiwu Pang\*, Branden Leong, Pradipta Ghosh, and Ramesh Govindan (\* equal contributions)<br>
*IEEE/ACM Conference on Internet-of-Things Design and Implementation (IoTDI)*, 2024.

- **[AeroTraj: Trajectory Planning for Fast and Accurate 3D Reconstruction Using a Drone-based LiDAR](https://dl.acm.org/doi/abs/10.1145/3610911)**<br>
Fawad Ahmad, **Christina Suyong Shin**, Rajrup Ghosh, John D’Ambrosio, Eugene Chai, Karthikeyan Sundaresan, and Ramesh Govindan<br>
*Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (Ubicomp/IMWUT)*, 2023.

- **[Progressive ad-hoc route reconstruction using distributed UAV relays after a large-scale failure](https://ieeexplore.ieee.org/abstract/document/8377012)**<br>
**Christina Suyong Shin**, So-Yeon Park, JinYi Yoon, and HyungJune Lee<br>
*IEEE Wireless Communications and Networking Conference (WCNC)*, 2018.

- **[DroneNet+: Adaptive Route Recovery Using Path Stitching of UAVs in Ad-Hoc Networks](https://ieeexplore.ieee.org/abstract/document/8253970)**<br>
So-Yeon Park, Dahee Jeong, **Christina Suyong Shin**, and HyungJune Lee<br>
*IEEE Global Communications Conference (GLOBECOM)*, 2017.

### Journal

- **[Infrastructure-less Vehicle Traffic Density Estimation via Distributed Packet Probing in V2V Network](https://ieeexplore.ieee.org/abstract/document/9178450)**<br>
**Christina Suyong Shin**, JiHo Lee, and HyungJune Lee<br>
*IEEE Transactions on Vehicular Technology (TVT)*, vol. 69, no. 10, Oct 2020.

- **[DroneNetX: Network Reconstruction through Connectivity Probing and Relay Deployment by Multiple UAVs in Ad-Hoc Networks](https://ieeexplore.ieee.org/abstract/document/8466046)**<br>
So-Yeon Park, **Christina Suyong Shin**, Dahee Jeong, and HyungJune Lee<br>
*IEEE Transactions on Vehicular Technology (TVT)*, vol. 67, no. 11, Nov 2018. -->

---

## Contact
- Email: [cshin956@usc.edu](mailto:cshin956@usc.edu)<br>
- LinkedIn: [https://www.linkedin.com/in/christina-sy-shin](https://www.linkedin.com/in/christina-sy-shin)<br>
- Homepage: [https://christina-shin.github.io/](https://christina-shin.github.io/)
