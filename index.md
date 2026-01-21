---
layout: default
title: Home
---

## Bio Sketch

I am a Ph.D. candidate in [Department of Computer Science](https://www.cs.usc.edu) at [University of Southern California](http://www.usc.edu), where I am advised by [Prof. Ramesh Govindan](https://govindan.usc.edu) in the [Networked Systems Lab (NSL)](https://nsl.usc.edu). I have successfully defended my dissertation and expect to receive my Ph.D. degree in May 2026. My research interests include computer networking, mobile computing, telemetry systemns, cloud computing, autonomous & connected vehicles, AR/VR systems.

Before joining USC, I received my B.S. and M.S. degrees in [Computer Science and Engineering](https://myr.ewha.ac.kr/cse/index.do) from [Ewha Womans University](https://www.ewha.ac.kr). I will be joining Google as a Software Engineer.

---

## Industry Experience

> **[Google]()**, Sunnyvale, California (Jan 2026 - Present) <br>
> Software Engineer

> **[General Motors](https://www.gm.com/research)**, Warren, Michigan (Summer 2021 & Summer 2024)<br>
> Research Intern (Mentor: Fan Bai and Chuan Li)

## Research Experience

> **[Networked Systems Lab](https://nsl.usc.edu)**, University of Southern California (Aug 2019 - Jan 2026)<br>
> Research Assistant (Advisor: [Prof. Ramesh Govindan](https://govindan.usc.edu))

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
