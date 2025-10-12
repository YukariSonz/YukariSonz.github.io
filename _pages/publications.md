---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}



### Publications

- Efficient Model Compression Techniques with FishLeg (Compression Workshop@NeurIPS 2024, Jamie McGowan, Wei Sheng Lai, Weibin Chen, Henry Aldridge, Jools Clarke, Jezabel R Garcia, Rui Xia, Yilei Liang, Guillaume Hennequin, Alberto Bernacchia) .  -- Work done@MediaTek Research


-  A Novel Framework of Horizontal-Vertical Hybrid Federated Learning for EdgeIoT (IEEE Networking Letters, vol. 7, no. 2, pp. 83-87, June 2025, Kai Li, Yilei Liang, Xin Yuan, Wei Ni, Jon Crowcroft, Chau Yuen, Ozgur B Akan) 

- FedCOM: Efficient Personalized Federated Learning by Finding Your Best Peers (FedEdge 2023, Xintong Lu, Yuchao Zhang, Huan Zou, Yilei Liang, Wendong Wang, Jon Crowcroft) ---  In conjunction with ACM Mobicom 2022. 


- Federated Split GANs for collaborative training with heterogeneous devices (Software Impact, Invited Paper, Yilei Liang, Pranvera Kortoçi Pengyuan Zhou, Lik-Hang Lee, Abbas Mehrabi, Pan Hui, Sasu Tarkoma, Jon Crowcroft)

- Efficient Federated Learning Under Non-IID Conditions With Attackers (FedEdge 2022, Huan Zou, Yuchao Zhang, Xirong Que, Yilei Liang, Jon Crowcroft) ---  In conjunction with ACM Mobicom 2022. 

- Federated Split GANs (FedEdge 2022, Pranvera Kortoçi, Yilei Liang, Pengyuan Zhou, Lik-Hang Lee, Abbas Mehrabi, Pan Hui, Sasu Tarkoma, Jon Crowcroft) ---  In conjunction with ACM Mobicom 2022.

- PAIGE: Towards a Hybrid-Edge Design for Privacy-Preserving Intelligent Personal Assistants: The 3rd International Workshop on Edge Systems, Analytics and Networking (EdgeSys 2020, Yilei Liang, Dan O’Keeffe, Nishanth Sastry)  ---  In conjunction with ACM EuroSys 2020.



### Under Review




{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
