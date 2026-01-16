---
layout: default
title: Home
---

## Bio Sketch

I am a Ph.D. candidate in [Department of Computer Science](https://www.cs.usc.edu) at [University of Southern California](http://www.usc.edu), where I am advised by [Prof. Ramesh Govindan](https://govindan.usc.edu) in the [Networked Systems Lab (NSL)](https://nsl.usc.edu). My research interests include computer networking, mobile computing, autonomous & connected vehicles, AR/VR systems, volumetric video streaming, 3D data processing, and 3D mapping.

Before joining USC, I received my B.S. and M.S. degree in Computer Science and Engineering from [Ewha Womans University](https://www.ewha.ac.kr).

---

<!-- ## Industry Experience

> **[Google]()**, Sunnyvale, California (Jan 2026 - Present) <br>
> Software Engineer

> **[General Motors](https://www.gm.com/research)**, Warren, Michigan (Summer 2021 & Summer 2024)<br>
> Research Intern (Mentor: Fan Bai and Chuan Li) -->

## Research Experience

> **[Networked Systems Lab](https://nsl.usc.edu)**, University of Southern California (Aug 2019 - Jan 2026)<br>
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

---

## Contact

- Email: [christina.suyong.shin@gmail.com](mailto:christina.suyong.shin@gmail.com)<br>
- Homepage: [https://christina-shin.github.io/](https://christina-shin.github.io/)<br>
- LinkedIn: [https://www.linkedin.com/in/christina-sy-shin](https://www.linkedin.com/in/christina-sy-shin)
