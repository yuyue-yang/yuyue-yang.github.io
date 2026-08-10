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
    <a href="/images/SZU.jpg"><img src="/images/SZU.jpg" style="width: 100%; border-radius: 10px; aspect-ratio: 4/3; object-fit: cover; box-shadow: 0 2px 6px rgba(0,0,0,0.1);"></a>
    <span style="display: block; font-size: 1.5em; color: #00369f; margin-top: 8px;">Shenzhen University</span>
  </div>
  <div style="flex: 1; min-width: 160px; text-align: center;">
    <a href="/images/SCNU.jpg"><img src="/images/SCNU.jpg" style="width: 100%; border-radius: 10px; aspect-ratio: 4/3; object-fit: cover; box-shadow: 0 2px 6px rgba(0,0,0,0.1);"></a>
    <span style="display: block; font-size: 1.5em; color: #00369f; margin-top: 8px;">South China Normal University</span>
  </div>
  <div style="flex: 1; min-width: 160px; text-align: center;">
    <a href="/images/GBU.jpg"><img src="/images/GBU.jpg" style="width: 100%; border-radius: 10px; aspect-ratio: 4/3; object-fit: cover; box-shadow: 0 2px 6px rgba(0,0,0,0.1);"></a>
    <span style="display: block; font-size: 1.5em; color: #00369f; margin-top: 8px;">Great Bay University</span>
  </div>
</div>


<div style="display: flex; flex-wrap: wrap; gap: 1em; justify-content: center; margin: 1.8em 0;">
  <div class="info-card" style="flex: 1; min-width: 160px; text-align: center; padding: 1.4em 1em; background: #f8f9fa; border-radius: 10px; box-shadow: 0 1px 3px rgba(0,0,0,0.06);">
    <i class="fas fa-map-marker-alt" style="font-size: 1.8em; color: #00369f; margin-bottom: 0.3em; display: block;"></i>
    <strong>Location</strong>
    <p style="margin: 0.3em 0 0 0; font-size: 1em; color: #333;">Shenzhen / Foshan / Dongguan , China</p>
  </div>
  <div class="info-card" style="flex: 1; min-width: 160px; text-align: center; padding: 1.4em 1em; background: #f8f9fa; border-radius: 10px; box-shadow: 0 1px 3px rgba(0,0,0,0.06);">
    <i class="fas fa-microscope" style="font-size: 1.8em; color: #00369f; margin-bottom: 0.3em; display: block;"></i>
    <strong>Research</strong>
    <p style="margin: 0.3em 0 0 0; font-size: 1em; color: #333;">Computational Optics &amp; Deep Optics</p>
  </div>
  <div class="info-card" style="flex: 1; min-width: 160px; text-align: center; padding: 1.4em 1em; background: #f8f9fa; border-radius: 10px; box-shadow: 0 1px 3px rgba(0,0,0,0.06);">
    <i class="fas fa-graduation-cap" style="font-size: 1.8em; color: #00369f; margin-bottom: 0.3em; display: block;"></i>
    <strong>Education</strong>
    <p style="margin: 0.3em 0 0 0; font-size: 1em; color: #333;">M.S. at SCNU (2024–2027)</p>
  </div>
</div>

I received my B.S. degree in Optoelectronic Information Science and Engineering from [**Shenzhen University**](https://en.szu.edu.cn/) in 2022. 

Currently, I am an M.S. student in Integrated Circuit Engineering at [**South China Normal University (SCNU)**](https://english.scnu.edu.cn/), supervised by [Prof. Shichen Su (宿世臣)](http://semi.scnu.edu.cn/a/20150917/14.html) starting from 2024.

From Aug. 2025 to Aug. 2026, I was a visiting student at [**Great Bay University**], under the guidance of [Prof. Shuming Jiao (焦述铭)](https://scholar.google.com/citations?hl=zh-CN&user=jh7YHO4AAAAJ).

Currently, I am an optical intern at [**Shenzhen Ledarobot**], working on LiDAR development.

> <i class="fas fa-lightbulb" style="color: #00369f;"></i> My research focuses on **computational imaging, deep optics, optical design, and machine vision**.


<span class='anchor' id='publications'></span>

# 📝 First-Author Publications & Patents

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><a href='images/depth_estimation.png'><img src='images/depth_estimation.png' alt="Depth Estimation" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Physics-Informed Deep Optics: Chromatic Aberrations for Monocular Depth Estimation](https://opg.optica.org/oe/abstract.cfm?doi=10.1364/OE.608898)

**Yuyue Yang**, et al.

*Optics Express / Under Review*, 2026
- Developed a differentiable ray-tracing engine using PyTorch to optimize spherical lens groups by introducing axial chromatic aberration loss.
- Achieved 0.182m RMSE on the NYU v2 dataset with extremely low parameters (25M), surpassing mainstream large visual models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Optics Comms</div><a href='images/Optics_Communications2025.jpg'><img src='images/Optics_Communications2025.jpg' alt="Metasurfaces" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Asymmetric double-layer compact metasurfaces based on phase-progressive diffractive networks](https://www.sciencedirect.com/science/article/pii/S0030401825009046)

**Yuyue Yang**, Azad, F., Huang, Z., Shen, M., Su, S.

*Optics Communications* , 2025
- Improved traditional optical neural network algorithms, designing a compact asymmetric double-layer metasurface with 62.5% network degrees of freedom.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Patent</div><a href='images/patent.png'><img src='images/patent.png' alt="Patent" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[A monocular laser rangefinder telescope, measurement method and rangefinder (CN118642263A)](https://www.qcc.com/zhuanliDetail/7c1c584b5dc3d72aa4ed131fe65ccf72.html)

**Yuyue Yang**, et al.

*Invention Patent*, 2024
</div>
</div>


<span class='anchor' id='other-publications'></span>

<hr class="section-divider">

<div class="section-light" markdown="1">

# 📚 Other Publications

<div class="pub-card" markdown="1">
Huang, Z., Wang, W., **Yang, Y.**, Zhang, H., Wang, Y., Zhao, T., ... & Su, S. (2024). Controllable and reversible photoresponses in graphene-gated WSe<sub>2</sub> field-effect transistors for communication, logic gate operations and image pre-processing. *Nano Res.*, 18(6), 94907460.
</div>

<div class="pub-card" markdown="1">
Shen, M., Guo, S., Wang, Z., **Yang, Y.**, Li, C., Ding, M., & Wang, B. (2026). A Physics-Informed Residual Learning Method for Real-Time 5-DoF Magnetic Localization in Capsule Endoscopy. *IEEE Transactions on Industrial Informatics*.
</div>

<div class="pub-card" markdown="1">
Jiao, S., Liu, H., Zhang, S., Zhou, C., Liu, Y., Chen, W., ... & Pengh, Y. (2026). Single-pixel imaging: principles, methods, algorithms, and applications. *Advanced Imaging*, 2, 1.
</div>



<hr class="section-divider">

# 🎖 Honors and Awards

<div class="honor-card">
  <span class="honor-year">2025</span>
  <span>BYD Scholarship</span>
</div>
<div class="honor-card">
  <span class="honor-year">2021</span>
  <span>Shenzhen University "Niu Hanben" Scholarship</span>
</div>
<div class="honor-card">
  <span class="honor-year">2021</span>
  <span>Shenzhen University "Innovation and Entrepreneurship Star" 2nd Prize (Team)</span>
</div>
<div class="honor-card">
  <span class="honor-year">2021</span>
  <span><strong>2nd Prize (Southeast Region)</strong>, 9th National College Students Optoelectronic Design Competition (Captain)</span>
</div>
<div class="honor-card">
  <span class="honor-year">2020</span>
  <span><strong>2nd Prize (National Finals)</strong>, 8th National College Students Optoelectronic Design Competition (Captain)</span>
</div>

</div>

<hr class="section-divider">

# 📖 Educations

<div style="border-left: 3px solid #00369f; padding-left: 1.5em; margin-left: 0.5em;">
  <div class="timeline-item" style="position: relative; margin-bottom: 1.4em;">
    <div style="position: absolute; left: -2.05em; top: 0.2em; width: 12px; height: 12px; background: #00369f; border-radius: 50%; border: 2px solid #fff; box-shadow: 0 0 0 2px #00369f;"></div>
    <span style="font-size: 1em; color: #00369f; font-weight: bold;">Sep. 2024 – Jun. 2027 (Expected)</span><br>
    <strong>Master of Engineering in Integrated Circuit Engineering</strong><br>
    South China Normal University (SCNU), Foshan
  </div>
  <div class="timeline-item" style="position: relative; margin-bottom: 0.5em;">
    <div style="position: absolute; left: -2.05em; top: 0.2em; width: 12px; height: 12px; background: #00369f; border-radius: 50%; border: 2px solid #fff; box-shadow: 0 0 0 2px #00369f;"></div>
    <span style="font-size: 1em; color: #00369f; font-weight: bold;">Sep. 2018 – Jun. 2022</span><br>
    <strong>Bachelor of Engineering in Optoelectronic Information Science and Engineering</strong><br>
    Shenzhen University, Shenzhen
  </div>
</div>

# 💻 Professional Experience

<div style="border-left: 3px solid #00369f; padding-left: 1.5em; margin-left: 0.5em;">

  <div class="timeline-item" style="position: relative; margin-bottom: 1.6em;">
    <div style="position: absolute; left: -2.05em; top: 0.25em; width: 12px; height: 12px; background: #00369f; border-radius: 50%; border: 2px solid #fff; box-shadow: 0 0 0 2px #00369f;"></div>
    <span style="font-size: 1em; color: #00369f; font-weight: bold;">Aug. 2023 – Aug. 2024</span><br>
    <strong>Optical Engineer</strong>, Shenzhen Hengtian Weiyan Technology Co., Ltd.
    <ul style="margin-top: 0.3em; font-size: 1em;">
      <li>Responsible for the optical design and system-level evaluation of laser rangefinders.</li>
      <li>Assisted in locating and resolving optical calibration issues during mass production, optimizing optical component selection.</li>
    </ul>
  </div>

  <div class="timeline-item" style="position: relative; margin-bottom: 1.6em;">
    <div style="position: absolute; left: -2.05em; top: 0.25em; width: 12px; height: 12px; background: #00369f; border-radius: 50%; border: 2px solid #fff; box-shadow: 0 0 0 2px #00369f;"></div>
    <span style="font-size: 1em; color: #00369f; font-weight: bold;">Feb. 2023 – Aug. 2023</span><br>
    <strong>Optical Engineer</strong>, Laison Optics (Shenzhen) Co., Ltd.
    <ul style="margin-top: 0.3em; font-size: 1em;">
      <li>Developed and debugged core optical algorithms for machine vision projects.</li>
    </ul>
  </div>




</div>



<hr class="section-divider">

<div class="section-light" markdown="1">

<span class='anchor' id='skills'></span>

# 🛠️ Skills

<div style="margin-bottom: 1em;">
  <i class="fas fa-code" style="color: #00369f; width: 24px;"></i> <strong>Programming:</strong>
  <span style="display: inline-flex; flex-wrap: wrap; gap: 6px; vertical-align: middle; margin-left: 4px;">
    <span class="skill-tag" style="background: #00369f; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">Python</span>
    <span class="skill-tag" style="background: #00369f; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">MATLAB</span>
    <span class="skill-tag" style="background: #00369f; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">C/C++</span>
  </span>
</div>

<div style="margin-bottom: 1em;">
  <i class="fas fa-tools" style="color: #00369f; width: 24px;"></i> <strong>Tools &amp; Software:</strong>
  <span style="display: inline-flex; flex-wrap: wrap; gap: 6px; vertical-align: middle; margin-left: 4px;">
    <span class="skill-tag" style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">Zemax</span>
    <span class="skill-tag" style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">FDTD</span>
    <span class="skill-tag" style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">SolidWorks</span>
    <span class="skill-tag" style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">OpenCV</span>
    <span class="skill-tag" style="background: #4a6fa5; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">PyTorch</span>
  </span>
</div>

<div style="margin-bottom: 1em;">
  <i class="fas fa-globe" style="color: #00369f; width: 24px;"></i> <strong>Languages:</strong>
  <span style="display: inline-flex; flex-wrap: wrap; gap: 6px; vertical-align: middle; margin-left: 4px;">
    <span class="skill-tag" style="background: #2e7d32; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">English (CET-6)</span>
  </span>
</div>

<div style="margin-bottom: 1em;">
  <i class="fas fa-certificate" style="color: #00369f; width: 24px;"></i> <strong>Certifications:</strong>
  <span style="display: inline-flex; flex-wrap: wrap; gap: 6px; vertical-align: middle; margin-left: 4px;">
    <span class="skill-tag" style="background: #6c757d; color: white; padding: 3px 14px; border-radius: 16px; font-size: 1em;">Assistant Engineer (Shenzhen)</span>
  </span>
</div>

</div>

<hr class="section-divider">

<span class='anchor' id='projects'></span>

# 🚀 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Enterprise</div><a href='images/LaserRangefinder.png'><img src='images/LaserRangefinder.png' alt="Laser Rangefinder" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Coaxial Laser Rangefinder Project** | *Core Developer* | *2024*
- Participated in the development of a coaxial laser rangefinder based on the 905nm ToF method.
- Formulated system specifications and integrated the laser transceiver module using lens splicing and beam-splitting systems.
- Conducted optical path design and non-sequential simulation using **Zemax** to evaluate and verify optical component performance.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Enterprise</div><a href='images/CornealDefectDetection.png'><img src='images/CornealDefectDetection.png' alt="Corneal Defect Detection" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Corneal Defect Detection System** | *Project Leader* | *2023*
- Led the design of an automated defect detection system for production lines.
- Independently selected core hardware (LED light sources, industrial cameras, lenses) and optimized algorithms for various defect types.
- Deployed **YOLO** deep learning models for real-time inference and data statistics.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Competition</div><a href='images/AppleSugarMeasurement.png'><img src='images/AppleSugarMeasurement.png' alt="Apple Sugar Measurement" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Smartphone-based Non-destructive Apple Sugar Measurement** | *Captain* | *2021*
- Designed an Android APP-linked non-destructive measurement device based on the diffuse reflection energy ratio of characteristic wavelengths.
- Led the selection of LED light sources and photodiodes, built the diffuse reflection light path, and constructed the sugar prediction algorithm model.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Competition</div><a href='images/AI5G_Smart_Glasses.jpg'><img src='images/AI5G_Smart_Glasses.jpg' alt="Smart Glasses" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**AI+5G Smart Glasses for the Blind** | *Captain* | *2020*
- Designed smart glasses integrating binocular ranging, object recognition, and voice broadcast functions.
- Led the implementation of binocular ranging algorithms and successfully deployed the **YOLO** model on a development board.

</div>
</div>

<hr class="section-divider">

# 📸 Team Gallery {#gallery}

<div style="display: flex; flex-wrap: wrap; gap: 12px; justify-content: center; margin-bottom: 2em;">
  <a href="images/TeamGallery/SZU_2022_young.jpg"><img class="gallery-img" src="images/TeamGallery/SZU_2022_young.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></a>
  <a href="images/TeamGallery/SZU_2025.jpg"><img class="gallery-img" src="images/TeamGallery/SZU_2025.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></a>
  <a href="images/TeamGallery/SCNU.jpg"><img class="gallery-img" src="images/TeamGallery/SCNU.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></a>
  <a href="images/TeamGallery/GBU.jpg"><img class="gallery-img" src="images/TeamGallery/GBU.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></a>
  <a href="images/TeamGallery/CIT.jpg"><img class="gallery-img" src="images/TeamGallery/CIT.jpg" style="width: 180px; height: 135px; object-fit: cover; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></a>
</div>

---

<div style="text-align: center; margin: 2.5em 0 1em 0;">
  <h2 style="border-bottom: none; margin-bottom: 0.5em;">Let's Connect</h2>
  <p style="color: #444; font-size: 1em;">Feel free to reach out for collaboration, discussion, or just a chat!</p>
  <p style="font-size: 1.5em; margin-top: 0.8em;">
    <a href="mailto:2024023860@m.scnu.edu.cn" title="Email" style="margin: 0 10px; color: #00369f;"><i class="fas fa-envelope"></i></a>
    <a href="https://scholar.google.com/citations?user=Lz_VWw4AAAAJ&hl" title="Google Scholar" style="margin: 0 10px; color: #00369f;"><i class="fas fa-graduation-cap"></i></a>
    <a href="https://github.com/yuyue-yang" title="GitHub" style="margin: 0 10px; color: #00369f;"><i class="fab fa-github"></i></a>
  </p>
</div>