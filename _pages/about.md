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

<!-- <h1 style="text-align: center; font-size: 2em;">Hi! 👋 I am yuyue yang</h1> -->

<span class='anchor' id='about-me'></span>

<div style="display: flex; flex-wrap: wrap; gap: 1em; justify-content: center; margin: 1.8em 0;">
  <div style="flex: 1; min-width: 160px; text-align: center;">
    <img src="/images/SZU.jpg" style="width: 100%; border-radius: 10px; aspect-ratio: 4/3; object-fit: cover; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
    <span style="display: block; font-size: 1.5em; color: #777; margin-top: 6px;">SZU</span>
  </div>
  <div style="flex: 1; min-width: 160px; text-align: center;">
    <img src="/images/SCNU.jpg" style="width: 100%; border-radius: 10px; aspect-ratio: 4/3; object-fit: cover; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
    <span style="display: block; font-size: 1.5em; color: #777; margin-top: 6px;">SCNU</span>
  </div>
  <div style="flex: 1; min-width: 160px; text-align: center;">
    <img src="/images/GBU.jpg" style="width: 100%; border-radius: 10px; aspect-ratio: 4/3; object-fit: cover; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
    <span style="display: block; font-size: 1.5em; color: #777; margin-top: 6px;">GBU</span>
  </div>
</div>


<div style="display: flex; flex-wrap: wrap; gap: 1em; justify-content: center; margin: 1.8em 0;">
  <div style="flex: 1; min-width: 160px; text-align: center; padding: 1.4em 1em; background: #f8f9fa; border-radius: 10px; box-shadow: 0 1px 3px rgba(0,0,0,0.06);">
    <i class="fas fa-map-marker-alt" style="font-size: 1.8em; color: #00369f; margin-bottom: 0.3em; display: block;"></i>
    <strong>Location</strong>
    <p style="margin: 0.3em 0 0 0; font-size: 0.9em; color: #555;">Shenzhen / Foshan / Dongguan , China</p>
  </div>
  <div style="flex: 1; min-width: 160px; text-align: center; padding: 1.4em 1em; background: #f8f9fa; border-radius: 10px; box-shadow: 0 1px 3px rgba(0,0,0,0.06);">
    <i class="fas fa-microscope" style="font-size: 1.8em; color: #00369f; margin-bottom: 0.3em; display: block;"></i>
    <strong>Research</strong>
    <p style="margin: 0.3em 0 0 0; font-size: 0.9em; color: #555;">Computational Optics &amp; Deep Optics</p>
  </div>
  <div style="flex: 1; min-width: 160px; text-align: center; padding: 1.4em 1em; background: #f8f9fa; border-radius: 10px; box-shadow: 0 1px 3px rgba(0,0,0,0.06);">
    <i class="fas fa-graduation-cap" style="font-size: 1.8em; color: #00369f; margin-bottom: 0.3em; display: block;"></i>
    <strong>Education</strong>
    <p style="margin: 0.3em 0 0 0; font-size: 0.9em; color: #555;">M.S. at SCNU (2024–2027)</p>
  </div>
</div>

I received my B.S. degree in Optoelectronic Information Science and Engineering from [**Shenzhen University**](https://en.szu.edu.cn/) in 2022. 

Currently, I am an M.S. student in Integrated Circuit Engineering at [**South China Normal University (SCNU)**](https://english.scnu.edu.cn/), supervised by [Prof. Shichen Su (宿世臣)](http://semi.scnu.edu.cn/a/20150917/14.html) starting from 2024.

Since August 2025, I have been a visiting student at Great Bay University, under the guidance of [Prof. Shuming Jiao (焦述铭)](https://scholar.google.com/citations?hl=zh-CN&user=jh7YHO4AAAAJ).

> <i class="fas fa-lightbulb" style="color: #00369f;"></i> My research focuses on **computational imaging, deep optics, optical design, and machine vision**.


<span class='anchor' id='publications'></span>

# 📝 First-Author Publications & Patents

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/depth_estimation.png' alt="Depth Estimation" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Physics-Informed Deep Optics: Chromatic Aberrations for Monocular Depth Estimation](#)

**Yuyue Yang**, et al.

*Optics Express / Under Review*, 2026
- Developed a differentiable ray-tracing engine using PyTorch to optimize spherical lens groups by introducing axial chromatic aberration loss.
- Achieved 0.182m RMSE on the NYU v2 dataset with extremely low parameters (25M), surpassing mainstream large visual models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Optics Comms</div><img src='images/Optics_Communications2025.jpg' alt="Metasurfaces" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asymmetric double-layer compact metasurfaces based on phase-progressive diffractive networks](#)

**Yuyue Yang**, Azad, F., Huang, Z., Shen, M., Su, S.

*Optics Communications* , 2025
- Improved traditional optical neural network algorithms, designing a compact asymmetric double-layer metasurface with 62.5% network degrees of freedom.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Patent</div><img src='images/patent.png' alt="Patent" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A monocular laser rangefinder telescope, measurement method and rangefinder (CN118642263A)](#)

**Yuyue Yang**, et al.

*Invention Patent*, 2024
</div>
</div>


<span class='anchor' id='other-publications'></span>

# 📚 Other Publications
- Huang, Z., Wang, W., **Yang, Y.**, Zhang, H., Wang, Y., Zhao, T., ... & Su, S. (2024). Controllable and reversible photoresponses in graphene-gated WSe2 field-effect transistors for communication, logic gate operations and image pre-processing. Nano Res., 18(6), 94907460.
- Shen, M., Guo, S., Wang, Z., **Yang, Y.**, Li, C., Ding, M., & Wang, B. (2026). A Physics-Informed Residual Learning Method for Real-Time 5-DoF Magnetic Localization in Capsule Endoscopy. IEEE Transactions on Industrial Informatics.
- Jiao, S., Liu, H., Zhang, S., Zhou, C., Liu, Y., Chen, W., ... & Pengh, Y. (2026). Single-pixel imaging: principles, methods, algorithms, and applications. Advanced Imaging, 2, 1.



# 🎖 Honors and Awards
- *2025* BYD Scholarship
- *2021* Shenzhen University "Niu Hanben" Scholarship
- *2021* Shenzhen University "Innovation and Entrepreneurship Star" 2nd Prize (Team)
- *2021* **2nd Prize (Southeast Region)**, 9th National College Students Optoelectronic Design Competition (Captain)
- *2020* **2nd Prize (National Finals)**, 8th National College Students Optoelectronic Design Competition (Captain)

# 📖 Educations

<div style="border-left: 3px solid #00369f; padding-left: 1.5em; margin-left: 0.5em;">
  <div style="position: relative; margin-bottom: 1.4em;">
    <div style="position: absolute; left: -2.05em; top: 0.2em; width: 12px; height: 12px; background: #00369f; border-radius: 50%; border: 2px solid #fff; box-shadow: 0 0 0 2px #00369f;"></div>
    <span style="font-size: 0.85em; color: #00369f; font-weight: bold;">Sep. 2024 – Jun. 2027 (Expected)</span><br>
    <strong>Master of Engineering in Integrated Circuit Engineering</strong><br>
    South China Normal University (SCNU), Foshan
  </div>
  <div style="position: relative; margin-bottom: 0.5em;">
    <div style="position: absolute; left: -2.05em; top: 0.2em; width: 12px; height: 12px; background: #00369f; border-radius: 50%; border: 2px solid #fff; box-shadow: 0 0 0 2px #00369f;"></div>
    <span style="font-size: 0.85em; color: #00369f; font-weight: bold;">Sep. 2018 – Jun. 2022</span><br>
    <strong>Bachelor of Engineering in Optoelectronic Information Science and Engineering</strong><br>
    Shenzhen University, Shenzhen
  </div>
</div>

# 💻 Professional Experience

<div style="border-left: 3px solid #00369f; padding-left: 1.5em; margin-left: 0.5em;">

  <div style="position: relative; margin-bottom: 1.6em;">
    <div style="position: absolute; left: -2.05em; top: 0.25em; width: 12px; height: 12px; background: #00369f; border-radius: 50%; border: 2px solid #fff; box-shadow: 0 0 0 2px #00369f;"></div>
    <span style="font-size: 0.85em; color: #00369f; font-weight: bold;">Aug. 2023 – Aug. 2024</span><br>
    <strong>Optical Engineer</strong>, Shenzhen Hengtian Weiyan Technology Co., Ltd.
    <ul style="margin-top: 0.3em; font-size: 0.95em;">
      <li>Responsible for the optical design and system-level evaluation of laser rangefinders.</li>
      <li>Assisted in locating and resolving optical calibration issues during mass production, optimizing optical component selection.</li>
    </ul>
  </div>

  <div style="position: relative; margin-bottom: 1.6em;">
    <div style="position: absolute; left: -2.05em; top: 0.25em; width: 12px; height: 12px; background: #00369f; border-radius: 50%; border: 2px solid #fff; box-shadow: 0 0 0 2px #00369f;"></div>
    <span style="font-size: 0.85em; color: #00369f; font-weight: bold;">Feb. 2023 – Aug. 2023</span><br>
    <strong>Optical Engineer</strong>, Laison Optics (Shenzhen) Co., Ltd.
    <ul style="margin-top: 0.3em; font-size: 0.95em;">
      <li>Developed and debugged core optical algorithms for machine vision projects.</li>
    </ul>
  </div>




</div>



# 🛠️ Skills {#skills}

<div style="margin-bottom: 1em;">
  <i class="fas fa-code" style="color: #00369f; width: 24px;"></i> <strong>Programming:</strong>
  <span style="display: inline-flex; flex-wrap: wrap; gap: 6px; vertical-align: middle; margin-left: 4px;">
    <span style="background: #00369f; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">Python</span>
    <span style="background: #00369f; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">MATLAB</span>
    <span style="background: #00369f; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">C/C++</span>
  </span>
</div>

<div style="margin-bottom: 1em;">
  <i class="fas fa-tools" style="color: #00369f; width: 24px;"></i> <strong>Tools &amp; Software:</strong>
  <span style="display: inline-flex; flex-wrap: wrap; gap: 6px; vertical-align: middle; margin-left: 4px;">
    <span style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">Zemax</span>
    <span style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">FDTD</span>
    <span style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">SolidWorks</span>
    <span style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">OpenCV</span>
    <span style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">PyTorch</span>
  </span>
</div>

<div style="margin-bottom: 1em;">
  <i class="fas fa-globe" style="color: #00369f; width: 24px;"></i> <strong>Languages:</strong>
  <span style="display: inline-flex; flex-wrap: wrap; gap: 6px; vertical-align: middle; margin-left: 4px;">
    <span style="background: #2e7d32; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">English (CET-6)</span>
  </span>
</div>

<div style="margin-bottom: 1em;">
  <i class="fas fa-certificate" style="color: #00369f; width: 24px;"></i> <strong>Certifications:</strong>
  <span style="display: inline-flex; flex-wrap: wrap; gap: 6px; vertical-align: middle; margin-left: 4px;">
    <span style="background: #6c757d; color: white; padding: 3px 14px; border-radius: 16px; font-size: 0.85em;">Assistant Engineer (Shenzhen)</span>
  </span>
</div>

# 🚀 Projects {#projects}

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Enterprise</div><img src='images/LaserRangefinder.png' alt="Laser Rangefinder" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Coaxial Laser Rangefinder Project** | *Core Developer* | *2024*
- Participated in the development of a coaxial laser rangefinder based on the 905nm ToF method.
- Formulated system specifications and integrated the laser transceiver module using lens splicing and beam-splitting systems.
- Conducted optical path design and non-sequential simulation using **Zemax** to evaluate and verify optical component performance.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Enterprise</div><img src='images/CornealDefectDetection.png' alt="Corneal Defect Detection" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Corneal Defect Detection System** | *Project Leader* | *2023*
- Led the design of an automated defect detection system for production lines.
- Independently selected core hardware (LED light sources, industrial cameras, lenses) and optimized algorithms for various defect types.
- Deployed **YOLO** deep learning models for real-time inference and data statistics.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Competition</div><img src='images/AppleSugarMeasurement.png' alt="Apple Sugar Measurement" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Smartphone-based Non-destructive Apple Sugar Measurement** | *Captain* | *2021*
- Designed an Android APP-linked non-destructive measurement device based on the diffuse reflection energy ratio of characteristic wavelengths.
- Led the selection of LED light sources and photodiodes, built the diffuse reflection light path, and constructed the sugar prediction algorithm model.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Competition</div><img src='images/AI5G_Smart_Glasses.jpg' alt="Smart Glasses" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AI+5G Smart Glasses for the Blind** | *Captain* | *2020*
- Designed smart glasses integrating binocular ranging, object recognition, and voice broadcast functions.
- Led the implementation of binocular ranging algorithms and successfully deployed the **YOLO** model on a development board.

</div>
</div>

# 📸 Team Gallery {#gallery}

<div style="display: flex; flex-wrap: wrap; gap: 12px; justify-content: center; margin-bottom: 2em;">
  <img src="images/TeamGallery/SCNU.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <img src="images/TeamGallery/SZU.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <img src="images/TeamGallery/GBU.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <img src="images/TeamGallery/CIO.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <img src="images/TeamGallery/CIT.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
</div>

---

<div style="text-align: center; margin: 2.5em 0 1em 0;">
  <h2 style="border-bottom: none; margin-bottom: 0.5em;">Let's Connect</h2>
  <p style="color: #777; font-size: 0.95em;">Feel free to reach out for collaboration, discussion, or just a chat!</p>
  <p style="font-size: 1.5em; margin-top: 0.8em;">
    <a href="mailto:2024023860@m.scnu.edu.cn" title="Email" style="margin: 0 10px; color: #00369f;"><i class="fas fa-envelope"></i></a>
    <a href="https://scholar.google.com/citations?user=Lz_VWw4AAAAJ&hl" title="Google Scholar" style="margin: 0 10px; color: #00369f;"><i class="fas fa-graduation-cap"></i></a>
    <a href="https://github.com/yuyue-yang" title="GitHub" style="margin: 0 10px; color: #00369f;"><i class="fab fa-github"></i></a>
  </p>
</div>