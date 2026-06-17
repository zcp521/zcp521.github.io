---
layout: default
title: "The sky is not the limit — it is only the beginning."
tagline: "&nbsp;"
---

<style>
  .research-page {
    max-width: 1000px;
    margin: 0 auto;
    padding: 0 1rem;
  }

  /* 章节标题 */
  .section-title {
    border-bottom: 3px solid #159957;
    padding-bottom: 0.4rem;
    margin-top: 2.5rem;
    font-size: 1.8rem;
    color: #159957;
  }

  .subsection-title {
    margin-top: 2rem;
    font-size: 1.3rem;
    color: #159957;
    padding-left: 0.2rem;
  }

  /* 引用文献 */
  .ref-list {
    padding-left: 1.8rem;
    text-indent: -1.8rem;
    margin-bottom: 0.25rem;
    font-size: 0.92rem;
    color: #444;
  }

  /* 亮点摘要卡片 */
  .highlight-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 1rem;
    margin: 1.2rem 0 0.8rem 0;
  }

  .highlight-card {
    background: #f0f7f3;
    border-radius: 8px;
    padding: 0.8rem 1rem;
    text-align: center;
    border: 1px solid #d4e8de;
  }

  .highlight-card .number {
    font-size: 1.6rem;
    font-weight: bold;
    color: #159957;
    display: block;
  }

  .highlight-card .label {
    font-size: 0.85rem;
    color: #555;
  }

  /* 参考列表悬停效果 */
  .ref-list:hover {
    color: #159957;
    transition: color 0.2s;
  }

  /* 响应式 */
  @media (max-width: 600px) {
    .highlight-grid {
      grid-template-columns: 1fr 1fr;
    }
    .section-title {
      font-size: 1.4rem;
    }
    .subsection-title {
      font-size: 1.1rem;
    }
  }

  @media (max-width: 400px) {
    .highlight-grid {
      grid-template-columns: 1fr;
    }
  }

  .pub-badge {
    display: inline-block;
    background: #159957;
    color: #fff;
    font-size: 0.65rem;
    font-weight: bold;
    padding: 0.1rem 0.5rem;
    border-radius: 12px;
    margin-left: 0.3rem;
    vertical-align: middle;
  }
</style>

<div class="research-page">

  <!-- ============================== -->
  <!-- 研究概述 -->
  <!-- ============================== -->
  <h2 class="section-title" style="margin-top: 0;">Research Overview</h2>

  <p style="font-size: 1.05rem; line-height: 1.8; color: #333;">
    My research centers on the <strong>baryon cycle</strong> across cosmic time—from the initial conditions of high-mass star formation within Milky Way molecular clouds to the large-scale neutral hydrogen (H&thinsp;i) content of galaxies in the nearby Universe. A unifying theme in my work is the use of observational data to understand how gas is accreted, converted, and regulated in galaxies. I have a particular focus on exploiting the unprecedented sensitivity of the <strong>Five-hundred-meter Aperture Spherical radio Telescope (FAST)</strong> to conduct wide-field H&thinsp;i surveys and to establish a statistical benchmark for galaxy evolution studies.
  </p>


  <!-- ============================== -->
  <!-- 1. FASHI -->
  <!-- ============================== -->
  <h2 class="section-title">1. The FASHI Survey: Building the Largest H&thinsp;i Galaxy Database</h2>

  <div class="highlight-grid">
    <div class="highlight-card">
      <span class="number">19,500</span>
      <span class="label">deg<sup>2</sup> mapped</span>
    </div>
    <div class="highlight-card">
      <span class="number">156,411</span>
      <span class="label">H&thinsp;i sources detected</span>
    </div>
    <div class="highlight-card">
      <span class="number">0.57</span>
      <span class="label">mJy beam<sup>−1</sup> median sensitivity</span>
    </div>
  </div>

  <p>
    I am a core leader of the <strong>FAST All-Sky H&thinsp;i Survey (FASHI)</strong>, the most sensitive wide-field H&thinsp;i survey ever conducted (<strong>Zhang et al. 2024b</strong>). The survey has mapped approximately 19,500 square degrees of the sky and detected over 156,000 extragalactic H&thinsp;i sources at redshifts <i>z</i> &lt; 0.09, with a median sensitivity of 0.57 mJy beam<sup>&minus;1</sup> (<strong>Zhang et al. 2026a</strong>).
  </p>

  <p>
    FASHI represents a significant advance in our ability to study the atomic gas content of the local Universe. Compared to previous surveys such as ALFALFA, it achieves a five-fold larger sample size and four times greater sensitivity, enabling the first robust measurement of the H&thinsp;i mass function down to 10<sup>6</sup> <i>M</i><sub>&#x2299;</sub> (<strong>Ma et al. 2025; Zhang et al. 2026a</strong>). This catalog provides a critical benchmark for studies of gas accretion, galaxy evolution, and large-scale structure. The data reduction is performed using the HiFAST pipeline (<strong>Jing et al. 2024</strong>), with dedicated RFI mitigation techniques developed for FAST's L-band observations (<strong>Zhang et al. 2022</strong>).
  </p>


  <!-- ============================== -->
  <!-- 2. Cosmic H I Density -->
  <!-- ============================== -->
  <h2 class="section-title">2. Cosmic H&thinsp;i Density and the Decline of Star Formation</h2>

  <p>
    A central question in galaxy evolution is why cosmic star formation has declined so dramatically over the past several billion years while the total H&thinsp;i reservoir remains relatively stable. Using the unique synergy between <strong>FASHI</strong> and the <strong>Dark Energy Spectroscopic Instrument (DESI)</strong>, I measured the cosmic H&thinsp;i density (&Omega;<sub>H&thinsp;i</sub>) over the past 4.5 Gyr with unprecedented precision (<strong>Zhang et al. 2026b</strong>). By stacking H&thinsp;i spectra from <strong>2.5 million</strong> DESI galaxies across 12,000 square degrees, I found that &Omega;<sub>H&thinsp;i</sub> declined by only a factor of <strong>1.35</strong> over this period, while the cosmic star formation rate density declined by a factor of <strong>2.46</strong>.
  </p>

  <p style="background: #f0f7f3; padding: 1rem 1.5rem; border-radius: 8px; border-left: 4px solid #159957;">
    <strong>Key Insight:</strong> This quantitative comparison demonstrates that the late-time decline in star formation is <strong>not</strong> driven by depletion of the H&thinsp;i reservoir. Instead, the results point to decreasing efficiency in converting H&thinsp;i into molecular hydrogen as the primary cause. This work provides a stringent observational benchmark for models of gas accretion, phase conversion, and star-formation regulation.
  </p>


  <!-- ============================== -->
  <!-- 3. H I in the Cosmic Web -->
  <!-- ============================== -->
  <h2 class="section-title">3. H&thinsp;i Content in the Cosmic Web and Galaxy Environments</h2>

  <p>
    The FASHI catalog also enables statistical studies of how H&thinsp;i traces large-scale structure. FASHI sources broadly follow the filamentary cosmic web seen in optical surveys, yet notable differences exist: optical voids are not devoid of H&thinsp;i galaxies, confirming that H&thinsp;i-selected systems preferentially reside in underdense environments (<strong>Zhang et al. 2026a</strong>).
  </p>

  <p>
    I have conducted detailed studies of H&thinsp;i gas in galaxy groups and clusters:
  </p>

  <ul style="line-height: 1.9; padding-left: 1.5rem;">
    <li>Our FAST observations of the <strong>NGC&nbsp;5055 group</strong> revealed a warped H&thinsp;i disk extending to 61.7 kpc, suggesting ongoing gas stripping (<strong>Liu et al. 2024</strong>).</li>
    <li>In the <strong>Ursa Major cluster</strong>, we found a shallower low-mass end slope of the H&thinsp;i mass function, consistent with gas stripping in dense environments (<strong>Yu et al. 2025</strong>).</li>
  </ul>

  <p>These results provide key observational constraints on environmental quenching mechanisms.</p>


  <!-- ============================== -->
  <!-- 4. H I–Stellar Mass Scaling -->
  <!-- ============================== -->
  <h2 class="section-title">4. H&thinsp;i&ndash;Stellar Mass Scaling Relations and Their Evolution</h2>

  <p>
    Using the cross-matched <strong>FASHI-DESI</strong> sample of over 64,000 galaxies, I established precise measurements of the H&thinsp;i gas fraction as a function of stellar mass across a broad mass range, from 10<sup>6</sup> to 10<sup>11</sup> <i>M</i><sub>&#x2299;</sub> (<strong>Zhang et al. 2026a; Zhang et al. 2026b</strong>). The relation exhibits remarkable invariance with redshift, evolving by less than 0.2 dex over the past 4.5 Gyr at fixed stellar mass. This population-wide trend implies that the weak evolution of H&thinsp;i is not the result of compensating changes among different galaxy populations, but rather a fundamental feature of the baryon cycle.
  </p>

  <p>
    In interacting systems:
  </p>

  <ul style="line-height: 1.9; padding-left: 1.5rem;">
    <li>In the <strong>NGC&nbsp;3395/3396 pair</strong>, we detected extended gas structures and ring-like tidal features (<strong>Yu et al. 2024</strong>).</li>
    <li>In the <strong>M101 group</strong>, we found a significantly extended and asymmetric H&thinsp;i disk (<strong>Xu et al. 2021</strong>).</li>
  </ul>

  <p>These observations highlight the role of interactions in shaping the gas content of galaxies.</p>


  <!-- ============================== -->
  <!-- 5. Exotic H I Sources -->
  <!-- ============================== -->
  <h2 class="section-title">5. Discovery of Exotic and Elusive H&thinsp;i Sources</h2>

  <p>
    The high sensitivity of FAST enables the detection of rare astrophysical objects. Using FASHI data, I have:
  </p>

  <ul style="line-height: 2.0; padding-left: 1.5rem; font-size: 0.98rem;">
    <li>🔭 Discovered isolated <strong>dark dwarf galaxy candidates</strong> (<strong>Xu et al. 2023a; Liu et al. 2025</strong>);</li>
    <li>📡 Detected over <strong>120 H&thinsp;i absorption line galaxies</strong>, with more than 80 being first detections (<strong>Zhang et al. 2025</strong>);</li>
    <li>💥 Identified over <strong>40 OH megamaser sources</strong>, with more than 20 being first detections (<strong>Zhang et al. 2024a</strong>).</li>
  </ul>

  <p>These discoveries provide unique laboratories for studying dark matter, cold gas dynamics, and galaxy mergers.</p>


  <!-- ============================== -->
  <!-- 6. Early Massive Star Formation -->
  <!-- ============================== -->
  <h2 class="section-title">6. Early Massive Star Formation in the Milky Way</h2>

  <p>
    Prior to my work on extragalactic H&thinsp;i, I studied the initial conditions of high-mass star formation within the Milky Way. This work provided the foundation for my later focus on the baryon cycle, connecting the earliest phases of star formation to the larger-scale evolution of galaxies. My contributions include:
  </p>

  <ul style="line-height: 1.9; padding-left: 1.5rem;">
    <li><strong>Fragmentation of dense cold cores:</strong> Using PdBI and VLA interferometric data, I revealed how massive clumps fragment into cores and condensations across different physical scales (<strong>Zhang et al. 2014; Zhang et al. 2016a</strong>).</li>
    <li><strong>Deuterium chemistry:</strong> Through NH<sub>2</sub>D and other deuterated molecules, I constrained the physical conditions and evolutionary timescales of pre-stellar and protostellar cores (<strong>Zhang et al. 2016a</strong>).</li>
    <li><strong>Triggered star formation:</strong> I investigated how ionizing radiation and stellar winds from massive stars compress molecular gas, triggering new generations of star formation in infrared dust bubbles (<strong>Zhang &amp; Wang 2012; Zhang et al. 2013; Zhang et al. 2017</strong>).</li>
    <li><strong>Large-scale surveys:</strong> I led a subproject of the TOP-SCOPE survey, studying the gas and dust properties of 64 Planck Galactic Cold Clumps (<strong>Zhang et al. 2017</strong>).</li>
  </ul>

  <p>
    Additional studies on Giant Molecular Clouds (<strong>Zhang et al. 2012</strong>) and Infrared Dark Clouds (<strong>Xu et al. 2016</strong>) further contributed to our understanding of the earliest phases of the star formation process.
  </p>


  <!-- ============================== -->
  <!-- References -->
  <!-- ============================== -->
  <h2 class="section-title" style="margin-top: 3rem;">References</h2>

  <div style="background: #f9f9f9; padding: 1.2rem 1.8rem; border-radius: 8px; margin-top: 0.5rem;">

    <div class="ref-list">Jing, Y., Wang, J., Xu, C., et al. 2024, SCPMA, 67, 259514</div>
    <div class="ref-list">Liu, X.-L., Zhu, M., Xu, J.-L., et al. 2024, RAA, 24, 075020</div>
    <div class="ref-list">Liu, X.-L., Xu, J.-L., Jiang, P., et al. 2025, Sci. Adv., 11, eads4057</div>
    <div class="ref-list">Ma, W., Guo, H., Xu, H., et al. 2025, A&A, 695, A241</div>
    <div class="ref-list">Xu, J.-L., Li, D., Zhang, C.-P., et al. 2016, ApJ, 819, 117</div>
    <div class="ref-list">Xu, J.-L., Zhang, C.-P., Yu, N., et al. 2021, ApJ, 922, 53</div>
    <div class="ref-list">Xu, J.-L., Zhu, M., Yu, N., et al. 2023a, ApJL, 944, L40</div>
    <div class="ref-list">Yu, N.-P., Zhu, M., Xu, J.-L., et al. 2024, MNRAS, 532, 1744</div>
    <div class="ref-list">Yu, H., Zhu, M., Zhang, C.-P., et al. 2025, ApJS, 278, 37</div>
    <div class="ref-list">Zhang, C.-P. &amp; Wang, J. J. 2012, A&A, 544, A11</div>
    <div class="ref-list">Zhang, C.-P., Esimbek, J., Zhou, J. J., et al. 2012, Ap&amp;SS, 337, 283</div>
    <div class="ref-list">Zhang, C.-P., Wang, J.-J., &amp; Xu, J.-L. 2013, A&A, 550, A117</div>
    <div class="ref-list">Zhang, C.-P., Wang, J.-J., Xu, J.-L., Wyrowski, F., &amp; Menten, K. M. 2014, ApJ, 784, 107</div>
    <div class="ref-list">Zhang, C.-P., Li, G.-X., Wyrowski, F., et al. 2016a, A&A, 585, A117</div>
    <div class="ref-list">Zhang, C.-P., Yuan, J.-H., Li, G.-X., Zhou, J.-J., &amp; Wang, J.-J. 2017, A&A, 598, A76</div>
    <div class="ref-list">Zhang, C.-P., Xu, J.-L., Wang, J., et al. 2022, RAA, 22, 025015</div>
    <div class="ref-list">Zhang, C.-P., Cheng, C., Zhu, M., &amp; Jiang, P. 2024a, ApJ, 971, 131</div>
    <div class="ref-list">Zhang, C.-P., Zhu, M., Jiang, P., et al. 2024b, SCPMA, 67, 219511</div>
    <div class="ref-list">Zhang, C.-P., Zhu, M., Jiang, P., et al. 2025, ApJS, 276, 6</div>
    <div class="ref-list">Zhang, C.-P., Zhu, M., Jiang, P., et al. 2026a, SCPMA, submitted</div>
    <div class="ref-list">Zhang, C.-P., Guo, H., Zhu, M., et al. 2026b, Nat. Astron., submitted</div>

  </div>

  <div style="text-align: right; font-size: 0.85rem; color: #999; margin-top: 0.5rem; border-top: 1px solid #eee; padding-top: 0.8rem;">
    <span>Last updated: June 2026</span>
  </div>

</div>
