---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Nan DENG a Ph.D. student in the [Department of Mechanical Engineering](https://www.polyu.edu.hk/me/) at [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/), supervised by Prof. [Li Mengying](https://www.li-realab.info/authors/limengying/).  My PhD research focuses on quantifying the effects of clouds on the angular and spectral Plane of Array (POA) irradiance using a 3D shortwave Monte Carlo Radiative Transfer Model (MC-RTM) and advanced deep learning techniques. In addition to my primary research, I also participated in the project of retrieving cloud properties from Fengyun-4A satellite data. My role in this project involved simulating the upwelling radiance at the top of the atmosphere (TOA) using shortwave MC-RTM.

I got my BSc degree in [Nanjing University of Information Science & Technology](https://en.nuist.edu.cn/main.htm), where I embarked on my initial research project: analyzing the impact of various cloud particles on brightness temperature using the CRTM model. I obtained my Master Degree in [NSSC/UCAS](http://english.nssc.cas.cn/) where I researched the Feiyun-3 Series Satellite's GNSS data processing, advised by [Prof. BAI Weihua](https://people.ucas.edu.cn/~bwh), where I studied the grid optimization algirithm to control the quality of precessing.

For my PhD program, I am studying the angular-spectral characteristics of radiation propagation in atmosphere and water, via a 3D Monte Carlo shortwave radiative transfer model and deep learning approach. I have completed my research on radiative transfer in water body. Currently, I am studying how different cloud particle types affect upwelling and downwelling radiation, as well as plane of array (POA) irradiance.



# 📖 Education

- MS in Earth and Space Detection Technology, 2022

  National Space Science Center, University of Chinese Academy of Sciences (NSSC/UCAS)

- BSc in Atmosphere Science, 2017

  Nanjing University of Information Science and Technology (NUIST)



# 📝 Publication
- [Quantifying the effects of spectral and directional distribution of radiation on its
  propagation in saline water](https://www.sciencedirect.com/science/article/pii/S135943112402204X).  *Applied Thermal Engineering* (2024): 124536.

  **Nan Deng**, Peixin Dong, Zhe Wang, Mengying Li*.

- [Evaluation of Forward Models for GNSS Radio Occultation Data Processing and Assimilation](https://www.mdpi.com/2072-4292/14/5/1081). *Remote Sensing* (2022): 14 (5), 1081.

  **Nan Deng**, Weihua Bai*, Yueqiang Sun, Qifei Du, Junming Xia, Xianyi Wang, Congliang Liu, Yuerong Cai, Xiangguang Meng, Cong Yin et al. 

- [Applications of <strong>GNSS</strong>-RO to numerical weather prediction and tropical cyclone forecast](https://www.mdpi.com/2073-4433/11/11/1204). *Atmosphere* (2020): 11 (11), 1204. 

  Weihua Bai, **Nan Deng***, Yueqiang Sun, Qifei Du, Junming Xia, Xianyi Wang, Xiangguang Meng, Danyang Zhao, Congliang Liu, Guangyuan Tan et al.  

- [Simulations and analysis of GNSS multipath observables for frozen and thawed soil under complex surface conditions](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=_oiltS8AAAAJ&citation_for_view=_oiltS8AAAAJ:j3f4tGmQtD8C). *Water* 13 (14), 1986.
  C Gao, W Bai, Z Wang, X Wu, L Liu, **Nan Deng**, J Xia. 



# 💻 Skills
- Programming Language: Python (⭐️⭐️⭐️⭐️⭐️) , MATLAB (⭐️⭐️⭐️), C (⭐️⭐️), Fortran (⭐️)
- Programming Environment: Windows (⭐️⭐️⭐️⭐️⭐️), Linux (⭐️⭐️⭐️⭐️⭐️)
- Atmospheric Numerical Simulation Software: WRF (⭐️), LICOM (⭐️)
- GNSS data pre-processing softwave : ROPP (⭐️⭐️⭐️⭐️)
- RTM softwares : LibRadTran (⭐️⭐️),  mcarats (⭐️)
- Tools: Photoshop, Xmind, Visio, Drawio

<span class='anchor' id='research'></span>

# 📝 Research 

- The **water radiative transfer model**. This study provides essential guidance for the design and performance evaluation of applications such as air–water interface, radiation-driven underwater vapor generation, and underwater photovoltaic systems.

<img src="https://github.com/andy1smith/andy1smith.github.io/blob/main/images/Graph_abstract.png?raw=true" width="600" height="250">

- Study the angular distribution of POA while considering solar in different relative location with a cumulus cloud, via a 3D shortwave RTM model. The python RTM model is developed by Prof. Li, Mengying. I keep on going to update this model: (1) from 2D to 3D; (2) accelerating by correlated-K method (3) from homogeneous to inhomogeneous cloud layers. 

<img src="https://github.com/andy1smith/andy1smith.github.io/blob/main/images/cloud_locations.png?raw=true" width="900" height="300">
