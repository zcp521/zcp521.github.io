---
layout: default
title: "Every galaxy tells a story; we are just learning to read."
tagline: "&nbsp;"
---
<style>
  /* ===== 全局容器 ===== */
  .fashi-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
  }

  /* ===== 页眉 ===== */
  .fashi-header {
    text-align: center;
    padding: 1.5rem 0 1rem 0;
    border-bottom: 3px solid #159957;
    margin-bottom: 2.5rem;
  }

  .fashi-header h1 {
    font-size: 3rem;
    margin-bottom: 0.2rem;
    color: #159957;
    letter-spacing: 2px;
  }

  .fashi-header .subtitle {
    font-size: 1.3rem;
    color: #555;
    margin-top: 0;
  }

  .fashi-header .pronounce {
    font-size: 1.0rem;
    color: #777;
    font-style: italic;
  }

  /* ===== 通用章节 ===== */
  .fashi-section {
    margin-bottom: 3rem;
    padding: 0 0.5rem;
  }

  .fashi-section h2 {
    border-bottom: 2px solid #159957;
    padding-bottom: 0.4rem;
    font-size: 1.7rem;
    color: #159957;
    margin-top: 0;
  }

  .fashi-section h3 {
    color: #159957;
    margin-top: 1.8rem;
    border-bottom: 1px solid #d4e8de;
    padding-bottom: 0.2rem;
    font-size: 1.25rem;
  }

  /* ===== 正文 ===== */
  .fashi-body {
    font-size: 1rem;
    line-height: 1.9;
    color: #333;
  }

  .fashi-body p {
    margin-bottom: 1.2rem;
  }

  /* ===== 图片 ===== */
  .fashi-img-right {
    float: right;
    width: 35%;
    max-width: 320px;
    margin-left: 2rem;
    margin-bottom: 0.8rem;
    border-radius: 10px;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.12);
  }

  .fashi-img-center {
    display: block;
    margin: 1.5rem auto;
    max-width: 90%;
    border-radius: 10px;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.10);
  }

  .fashi-img-wide {
    display: block;
    margin: 1.5rem auto;
    max-width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.10);
  }

  /* ===== 摘要框 ===== */
  .fashi-abstract {
    background: #f8faf9;
    padding: 1.2rem 2rem;
    border-radius: 10px;
    border-left: 5px solid #159957;
    margin: 0.8rem 0 1.5rem 0;
    font-size: 0.95rem;
    line-height: 1.8;
  }

  /* ===== 数据政策框 ===== */
  .fashi-policy {
    background: #f8faf9;
    padding: 1.2rem 2rem;
    border-radius: 10px;
    border-left: 5px solid #159957;
    margin: 1rem 0;
    font-size: 0.95rem;
    line-height: 1.8;
  }

  .fashi-policy ul {
    padding-left: 1.5rem;
    margin-top: 0.3rem;
  }

  .fashi-policy ul li {
    margin-bottom: 0.2rem;
  }

  /* ===== 表格 ===== */
  .fashi-table-wrap {
    overflow-x: auto;
    margin: 1.2rem 0;
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.06);
  }

  .fashi-table-wrap table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.95rem;
    background: #fff;
    border-radius: 10px;
    overflow: hidden;
    border-bottom: 2px solid #159957;  /* ← 表格底部边框 */
  }

  .fashi-table-wrap thead tr {
    background-color: #e8f5e9;
    border-bottom: 2px solid #159957;
  }

  .fashi-table-wrap th {
    padding: 12px 18px;
    text-align: left;
    font-weight: bold;
  }

  .fashi-table-wrap td {
    padding: 10px 18px;
    border-bottom: 1px solid #eee;
  }

  .fashi-table-wrap tbody tr:last-child td {
    border-bottom: none;
    font-weight: bold;
    background: #f9f9f9;
  }

  .fashi-table-wrap tbody tr:hover {
    background: #f5faf7;
    transition: background 0.15s;
  }

  /* ===== 列表 ===== */
  .fashi-list {
    line-height: 2.0;
    padding-left: 1.5rem;
    font-size: 0.95rem;
  }

  .fashi-list li {
    margin-bottom: 0.1rem;
  }

  /* ===== 链接 ===== */
  .fashi-link {
    color: #1e6bb8;
    text-decoration: none;
  }

  .fashi-link:hover {
    text-decoration: underline;
  }

  /* ===== 页脚 ===== */
  .fashi-footer {
    text-align: center;
    padding: 1.5rem 0 0.5rem 0;
    border-top: 2px solid #eee;
    margin-top: 2.5rem;
    color: #aaa;
    font-size: 0.85rem;
  }

  /* ===== 响应式 ===== */
  @media (max-width: 768px) {
    .fashi-container {
      padding: 0 1rem;
    }

    .fashi-header h1 {
      font-size: 2.2rem;
    }

    .fashi-header .subtitle {
      font-size: 1.0rem;
    }

    .fashi-img-right {
      float: none;
      width: 100%;
      max-width: 100%;
      margin: 0 0 1rem 0;
    }

    .fashi-section h2 {
      font-size: 1.4rem;
    }

    .fashi-section h3 {
      font-size: 1.1rem;
    }

    .fashi-abstract,
    .fashi-policy {
      padding: 1rem 1.2rem;
    }

    .fashi-table-wrap table {
      font-size: 0.85rem;
    }

    .fashi-table-wrap th,
    .fashi-table-wrap td {
      padding: 8px 10px;
    }
  }

  @media (max-width: 480px) {
    .fashi-container {
      padding: 0 0.6rem;
    }

    .fashi-header h1 {
      font-size: 1.8rem;
    }

    .fashi-body {
      font-size: 0.92rem;
    }

    .fashi-img-center,
    .fashi-img-wide {
      max-width: 100%;
    }
  }
</style>

<!-- ============================================================ -->
<!-- 页面内容 -->
<!-- ============================================================ -->

<div class="fashi-container">

  <!-- ============ 页眉 ============ -->
  <header class="fashi-header">
    <h1>FASHI</h1>
    <p class="subtitle">The FAST All-Sky H I Survey</p>
    <p class="pronounce">读作 /fɑːʃ/ 或 “法师”</p>
  </header>

  <!-- ============ OVERVIEW ============ -->
  <section class="fashi-section">
    <h2>Overview</h2>

    <div class="fashi-body">
      <img src="{{ site.baseurl }}/img/fast_telescope.png" alt="FAST Telescope" class="fashi-img-right">

      <p>
        The <strong>FAST All-Sky H I Survey (FASHI)</strong> is a pioneering neutral hydrogen (H I) survey conducted using the <strong>Five-hundred-meter Aperture Spherical radio Telescope (FAST)</strong>, the world's most sensitive single-dish radio telescope. FASHI represents the first all-sky H I survey undertaken with FAST, leveraging the telescope's unprecedented sensitivity and wide field of view to conduct a comprehensive census of neutral atomic hydrogen in the local Universe.
      </p>

      <p>
        Neutral hydrogen is the fundamental building block of galaxies, serving as the primary reservoir of fuel for star formation. Mapping the distribution and content of H I across the sky is essential for understanding the formation and evolution of galaxies, the growth of large-scale structure, and the cycling of baryonic matter in the cosmos. FASHI is designed to detect H I emission from galaxies out to redshifts <em>z</em> &lt; 0.09, probing the local Universe with a sensitivity and source density that far surpasses previous surveys.
      </p>

      <p>
        The survey is designed to map the entire sky accessible to FAST, covering declinations from −14° to +66° (~22,000 deg²) in the frequency range 1.0–1.5 GHz. As of the second data release (DR2), FASHI has mapped approximately 19,500 deg² of the sky, detecting over 156,000 extragalactic H I sources — making it the largest and most sensitive H I survey ever conducted.
      </p>
    </div>
  </section>

  <!-- ============ SURVEY STRATEGY ============ -->
  <section class="fashi-section">
    <h2>Survey Strategy and Observations</h2>

    <div class="fashi-body">
      <p>
        FASHI adopts a flexible drift-scan observing strategy, optimized for FAST's schedule-filler observing mode. Observations are carried out at fixed declinations, enabling an efficient blind search for H I emission while maximizing the utilization of available telescope time. This strategy naturally leads to non-uniform sky coverage, with some regions observed multiple times and thus reaching greater sensitivity.
      </p>

      <p>
        The survey utilizes FAST's <strong>19-beam receiver array</strong>, with a half-power beamwidth of 2.9 arcmin at 1.4 GHz and pointing accuracy better than 15 arcsec. The spectral backend provides 500 MHz bandwidth with 64k channels, yielding a native resolution of 7.63 kHz (~1.6 km s<sup>−1</sup> at 1.4 GHz). Data are recorded at 1-second integrations. Intensity calibration employs periodic noise-diode injections, with a beam-dependent gain of 13–17 K Jy<sup>−1</sup> at 1400 MHz.
      </p>
    </div>
  </section>

  <!-- ============ DATA RELEASES ============ -->
  <section class="fashi-section">
    <h2>Data Releases</h2>

    <div class="fashi-body">
      <p>
        FASHI has released two major data releases, each representing significant milestones in the survey's progress and scientific impact.
      </p>
    </div>

    <!-- DR1 -->
    <h3>
      <a href="https://ui.adsabs.harvard.edu/abs/2024SCPMA..6719511Z/abstract" target="_blank" class="fashi-link">
        FASHI DR1 (2024): The First Release of Catalog
      </a>
    </h3>

    <div class="fashi-abstract">
      <strong>Abstract:</strong> The <strong>F</strong>AST <strong>A</strong>ll <strong>S</strong>ky <strong>H <small>I</small></strong> survey (FASHI) was designed to cover the entire sky observable by the Five-hundred-meter Aperture Spherical radio Telescope (FAST), spanning approximately 22,000 square degrees of declination between −14° and +66°, and in the frequency range of 1050–1450 MHz, with the expectation of eventually detecting more than 100,000 H I sources. Between August 2020 and June 2023, FASHI covered more than 7,600 square degrees, approximately 35% of the total sky observable by FAST. It has a median detection sensitivity of around 0.76 mJy beam<sup>−1</sup> and a spectral line velocity resolution of ∼6.4 km s<sup>−1</sup> at a frequency of ∼1.4 GHz. As of now, a total of 41,741 extragalactic H I sources have been detected in the frequency range 1305.5–1419.5 MHz, corresponding to a redshift limit of <em>z</em> ≲ 0.09. By cross-matching FASHI sources with the Siena Galaxy Atlas (SGA) and the Sloan Digital Sky Survey (SDSS) catalogs, we found that 16,972 (40.7%) sources have spectroscopic redshifts and 10,975 (26.3%) sources have only photometric redshifts. Most of the remaining 13,794 (33.0%) H I sources are located in the direction of the Galactic plane, making their optical counterparts difficult to identify due to high extinction or high contamination of Galactic stellar sources. Based on current survey results, the FASHI survey is an unprecedented blind extragalactic H I survey. It has higher spectral and spatial resolution and broader coverage than the Arecibo Legacy Fast ALFA Survey (ALFALFA). When completed, FASHI will provide the largest extragalactic H I catalog and an objective view of H I content and large-scale structure in the local universe.
    </div>

    <img src="{{ site.baseurl }}/img/fashi_dr1_sky.png" alt="FASHI DR1 sky coverage" class="fashi-img-center" style="max-width: 80%;">

    <!-- DR2 -->
    <h3 style="margin-top: 2.5rem;">
      <a href="https://ui.adsabs.harvard.edu/abs/2024SCPMA..6719511Z/abstract" target="_blank" class="fashi-link">
        FASHI DR2 (2026): The FASHI Catalog and the H I Mass Function
      </a>
    </h3>

    <div class="fashi-abstract">
      <strong>Abstract:</strong> The FAST All Sky H I survey (FASHI, read as /fɑːʃ/ or 法师 in Chinese) 
      conducted with the Five-hundred-meter Aperture Spherical radio Telescope (FAST) has 
      mapped ∼19 500 deg<sup>2</sup> of the sky north of DEC = −14°, detecting 156 411 extragalactic H I sources at 
      <em>z</em> &lt; 0.09 with a median sensitivity of 0.57 mJy beam<sup>−1</sup> at a velocity resolution of 6.4 km s<sup>−1</sup>. 
      The survey achieves unprecedented depth and area coverage, significantly improving upon previous single-dish 
      surveys. Through a detailed completeness analysis that accounts for the survey's non-uniform sensitivity 
      and line-width dependence, we construct a robust H I mass function (HIMF) using a completeness‑corrected 
      sample of over 109 000 sources. The HIMF is robustly constrained down to <em>M</em><sub>HI</sub> ∼ 
      10<sup>6.2</sup> <em>M</em><sub>⊙</sub>. When systematic uncertainties are included, the HIMF is well 
      described by a single-Schechter function with a characteristic mass 
      log(<em>M</em><sub>s</sub>/<em>h</em><sub>70</sub><sup>−2</sup> <em>M</em><sub>⊙</sub>) = 9.89 ± 0.02, 
      low-mass end slope α = −1.31 ± 0.02 and amplitude φ<sub>s</sub> = 
      (6.38 ± 0.49) × 10<sup>−3</sup> <em>h</em><sub>70</sub><sup>3</sup> Mpc<sup>−3</sup> dex<sup>−1</sup>. 
      The derived cosmic H I density is Ω<sub>HI</sub> = (4.71 ± 0.03<sub>stat</sub> ± 0.40<sub>sys</sub>) × 
      10<sup>−4</sup> <em>h</em><sub>70</sub><sup>−1</sup>. FASHI provides the most extensive and sensitive H I 
      catalog to date, establishing an important benchmark for studies of gas accretion, galaxy evolution, 
      and large-scale structure in the local universe.
    </div>

    <img src="{{ site.baseurl }}/img/fashi_dr2_sky.png" alt="FASHI DR2 sky coverage" class="fashi-img-wide">
  </section>

  <!-- ============ ACCESSING FASHI DATA ============ -->
  <section class="fashi-section">
    <h2>Accessing FASHI Data</h2>

    <div class="fashi-body">
      <p>
        In addition to the catalog listed in the DR2 Technical Details table, integrated one-dimensional H I line spectra for all cataloged sources have been extracted from the reduced three-dimensional FITS data cubes. The full FASHI H I source catalog will be made publicly available upon publication of this paper.
      </p>

      <p>
        The reduced one-dimensional spectral cubelets associated with individual sources are available upon request from the corresponding authors. Access to the reduced three-dimensional data cubes is currently restricted to internal collaboration use; however, a limited subset of these data may be provided upon reasonable request for specific scientific purposes.
      </p>

      <p>
        All raw observational data from the FASHI project will be released to the public following a <strong>twelve-month proprietary period</strong>, in accordance with the FAST data release policy. The twelve-month proprietary period applies to each individual scan observation, rather than to the completion of the full survey.
      </p>

      <div class="fashi-policy">
        <p style="margin-top: 0; font-weight: bold;">FAST Data Policy Summary:</p>
        <ul>
          <li><strong>Proprietary Period:</strong> 12 months from the date of data collection for PI-time projects and priority/key science projects.</li>
          <li><strong>Data Access During Proprietary Period:</strong> External researchers may apply to the project PI or the FAST Scientific Committee for access to data during the proprietary period for collaborative or independent research.</li>
          <li><strong>Data Release After Proprietary Period:</strong> Data are publicly released by the FAST Operation and Development Center after the proprietary period and can be used without restriction.</li>
          <li><strong>Data Transfer:</strong> Due to bandwidth limitations, it is encouraged to make direct copies of released FAST data using hard disks at the FAST Data Center.</li>
          <li><strong>Acknowledgment:</strong> Publications using FAST data must include the proper acknowledgment: <em>"This work has used the data from the Five-hundred-meter Aperture Spherical radio Telescope (FAST). FAST is a Chinese national mega-science facility, operated by the National Astronomical Observatories of Chinese Academy of Sciences (NAOC)."</em></li>
        </ul>
      </div>

      <p>
        Further details regarding FAST data access and release policies are available at <a href="https://fast.bao.ac.cn/cms/article/129/" target="_blank" class="fashi-link">FAST Data Policy</a>.
      </p>
    </div>
  </section>

  <!-- ============ DR2 TECHNICAL TABLE ============ -->
  <section class="fashi-section">
    <h3 style="border-bottom: 2px solid #159957; padding-bottom: 0.3rem; font-size: 1.4rem; color: #159957;">FASHI DR2 Technical Details</h3>

    <div class="fashi-table-wrap">
      <table>
        <thead>
          <tr>
            <th style="width: 40%;">Parameters</th>
            <th>Values</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>RA range</td><td>0<sup>h</sup> ≤ RA ≤ 24<sup>h</sup></td></tr>
          <tr><td>DEC range</td><td>−14° ≲ DEC ≲ +66°</td></tr>
          <tr><td>Receiver</td><td>19-beam array</td></tr>
          <tr><td>Polarizations per beam</td><td>2 linear (XX, YY)</td></tr>
          <tr><td>Beam size (FWHM)</td><td>2.9 arcmin at 1420 MHz</td></tr>
          <tr><td>Gain</td><td>13–17 K Jy<sup>−1</sup></td></tr>
          <tr><td>T<sub>sys</sub></td><td>16–19 K</td></tr>
          <tr><td>Total frequency coverage</td><td>1050–1450 MHz</td></tr>
          <tr><td>Released frequency range</td><td>1305.7–1422.8 MHz</td></tr>
          <tr><td>cz<sub>⊙</sub> range</td><td>−510.0 to 26320.6 km s<sup>−1</sup></td></tr>
          <tr><td>Redshift <em>z</em> range</td><td><em>z</em> &lt; 0.0878</td></tr>
          <tr><td>Spectral channels</td><td>65,536 (before smoothing)</td></tr>
          <tr><td>Channel spacing</td><td>7.629 kHz or 1.6 km s<sup>−1</sup> at 1420 MHz</td></tr>
          <tr><td>Spectral resolution</td><td>6.4 km s<sup>−1</sup> (after smoothing)</td></tr>
          <tr><td>Median rms σ<sub>rms</sub></td><td>~1.04 mJy at 6.4 km s<sup>−1</sup> resolution</td></tr>
          <tr><td>Median sensitivity f<sub>σ</sub></td><td>~0.57 mJy beam<sup>−1</sup> at 6.4 km s<sup>−1</sup> resolution</td></tr>
          <tr><td>Coverage area</td><td>19,500 deg<sup>2</sup></td></tr>
          <tr><td style="font-weight: bold;">Source number</td><td style="font-weight: bold;">156,411</td></tr>
        </tbody>
      </table>
    </div>

    <p style="font-size: 0.9rem; color: #666; margin-top: 0.2rem;">
      <strong>Notes:</strong> The definitions of the spectral rms σ<sub>rms</sub> and the per-source detection sensitivity f<sub>σ</sub> are provided in Column 9 of Section 2.4.
    </p>
  </section>

  <!-- ============ SOURCE EXTRACTION ============ -->
  <section class="fashi-section">
    <h2>Source Extraction</h2>

    <div class="fashi-body">
      <p>
        Source extraction for FASHI employs a two-step approach combining automated detection with visual validation:
      </p>
      <ol class="fashi-list">
        <li>
          <strong>Blind detection:</strong> Initial candidates are identified using SoFiA (Serra et al. 2015; Westmeier et al. 2021) with a 4.5σ detection threshold, which was empirically chosen to provide the optimal trade-off between completeness and reliability.
        </li>
        <li>
          <strong>Optically guided extraction:</strong> Given the substantial sky overlap (&gt;12,000 deg²) between FASHI and DESI/SDSS spectroscopic surveys, optical data are leveraged to complement source extraction and improve sample completeness. For each optical counterpart, an emission signal exceeding 3σ is required for detection.
        </li>
        <li>
          <strong>Visual validation:</strong> All candidates are inspected interactively using moment maps and integrated profiles to reject false detections and refine source boundaries.
        </li>
      </ol>
    </div>
  </section>

  <!-- ============ SUPPLEMENTARY MATERIALS ============ -->
  <section class="fashi-section">
    <h3 style="border-bottom: 2px solid #159957; padding-bottom: 0.3rem; font-size: 1.4rem; color: #159957;">FASHI DR1 Supplementary Materials</h3>

    <ol class="fashi-list">
      <li>The full paper can be downloaded in <a href="{{ site.baseurl }}/pub/fashi.pdf" target="_blank" class="fashi-link">The FAST All Sky HI Survey (FASHI): The First Release of Catalog</a></li>
      <li>The complete Table 2 containing 41,741 sources can be accessed in <a href="{{ site.baseurl }}/img/Table2-FASHI_extragalactic_HI_source_catalog.csv" target="_blank" class="fashi-link">FASHI Extragalactic H I Source Catalog</a></li>
      <li>The complete Table 3 containing 3,620 sources can be accessed in <a href="{{ site.baseurl }}/img/Table3-FASHI_and_ALFALFA_cross-matching_catalog.csv" target="_blank" class="fashi-link">FASHI and ALFALFA Cross-Matching Catalog</a></li>
      <li>The complete Table 4 containing 14,072 sources can be accessed in <a href="{{ site.baseurl }}/img/Table4-The_identified_optical_counterparts_from_the_SGA_catalog.csv" target="_blank" class="fashi-link">Identified Optical Counterparts from the SGA Catalog</a></li>
      <li>The complete Table 5 containing 2,900 sources can be accessed in <a href="{{ site.baseurl }}/img/Table5-The_identified_optical_counterparts_from_the_SDSS_spectroscopic_catalog.csv" target="_blank" class="fashi-link">Identified Optical Counterparts from the SDSS Spectroscopic Catalog</a></li>
      <li>The complete Table 6 containing 10,975 sources can be accessed in <a href="{{ site.baseurl }}/img/Table6-The_identified_optical_counterparts_from_the_SDSS_photometric_catalog.csv" target="_blank" class="fashi-link">Identified Optical Counterparts from the SDSS Photometric Catalog</a></li>
    </ol>
  </section>

  <!-- ============ RELATED PUBLICATIONS ============ -->
  <section class="fashi-section">
    <h3 style="border-bottom: 2px solid #159957; padding-bottom: 0.3rem; font-size: 1.4rem; color: #159957;">Important Publications Related to FASHI</h3>

    <ol reversed class="fashi-list">
      <li>Ma, Wenlin; Guo, Hong; Xu, Haojie; Jones, Michael G.; <strong>Zhang, Chuan-Peng</strong>; Zhu, Ming; Wang, Jing; Wang, Jie; Jiang, Peng<br>
        <em>"The H I Mass Function of the Local Universe: Combining Measurements from HIPASS, ALFALFA, and FASHI"</em><br>
        <a href="https://ui.adsabs.harvard.edu/abs/2025A%26A...695A.241M/abstract" target="_blank" class="fashi-link">2025A&A...695A.241M</a>
      </li>
      <li><strong>Zhang, Chuan-Peng</strong>; Zhu, Ming; Jiang, Peng; Cheng, Cheng; Xu, Jin-Long; Yu, Nai-Ping; Liu, Xiao-Lan; Zhang, Bo<br>
        <em>"FASHI: An Untargeted Survey of the 21 cm H I Absorption Galaxies with FAST"</em><br>
        <a href="https://ui.adsabs.harvard.edu/abs/2025ApJS..276....6Z/abstract" target="_blank" class="fashi-link">2025ApJS..276....6Z</a>
      </li>
      <li><strong>Zhang, Chuan-Peng</strong>; Cheng, Cheng; Zhu, Ming; Jiang, Peng<br>
        <em>"FASHI: A Search for Extragalactic OH Megamasers with FAST"</em><br>
        <a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...971..131Z/abstract" target="_blank" class="fashi-link">2024ApJ...971..131Z</a>
      </li>
      <li><strong>Zhang, Chuan-Peng</strong>; Zhu, M.; Jiang, P.; Cheng, C.; Wang, J.; Wang, J.; Xu, J.-L.; Liu, X.-L.; Yu, N.-P.; Qian, L.; Yu, H.; Ai, M.; Jing, Y.; Xu, C.; Liu, Z.; Guan, X.; Sun, C.; Yang, Q.; Huang, M.; Hao, Q.; FAST Collaboration<br>
        <em>"The FAST All Sky H I Survey (FASHI): The First Release of Catalog"</em><br>
        <a href="https://ui.adsabs.harvard.edu/abs/2024SCPMA..6719511Z/abstract" target="_blank" class="fashi-link">2024SCPMA..6719511Z</a>
      </li>
    </ol>
  </section>

  <!-- ============ NEWS ============ -->
  <section class="fashi-section">
    <h3 style="border-bottom: 2px solid #159957; padding-bottom: 0.3rem; font-size: 1.4rem; color: #159957;">News Related to FASHI</h3>

    <ul class="fashi-list">
      <li><a href="https://blog.sciencenet.cn/blog-528739-1413561.html" target="_blank" class="fashi-link">【科学网】中国天眼探测并构建世界最大的中性氢星系样本</a></li>
      <li><a href="http://news.gzu.edu.cn/2023/1211/c11069a210339/page.htm" target="_blank" class="fashi-link">【贵大新闻网讯】贵州射电天文台参与中国天眼探测 构建世界最大的中性氢星系样本</a></li>
      <li><a href="https://tv.cctv.com/2023/12/13/VIDEQFOsBrEMP1RpItMx6eG6231213.shtml" target="_blank" class="fashi-link">【CCTV】中国天眼最新巡天成果发布 探测并构建世界最大中性氢星系样本</a></li>
      <li><a href="https://english.news.cn/20231213/99a9ce6bcf1b461bb1b319157ab250f2/c.html" target="_blank" class="fashi-link">【Xinhua】Chinese Scientists Build Largest-Ever Neutral Hydrogen Catalog in Deep Space</a></li>
      <li><a href="https://www.zhihu.com/question/634798604" target="_blank" class="fashi-link">【知乎】中国天眼探测并构建世界最大的中性氢星系样本，这一巡天成果有哪些意义？</a></li>
      <li><a href="https://mp.weixin.qq.com/s/J7i9y-Bz1x353xkEI67zUw" target="_blank" class="fashi-link">【虚拟天文台】中国天眼（FAST）中性氢巡天源表：首次发布</a></li>
      <li><a href="http://news.china.com.cn/2023-12/26/content_116904209.shtml" target="_blank" class="fashi-link">【新华网】点赞科技“热词”丨2023那些振奋人心的科技成果</a></li>
      <li><a href="https://www.eurekalert.org/news-releases/1029943" target="_blank" class="fashi-link">【EurekAlert】FASHI Releases the Largest Extragalactic H I Catalog with FAST</a></li>
    </ul>
  </section>

  <!-- ============ 底部 ============ -->
  <div class="fashi-footer">
    <img src="{{ site.baseurl }}/img/fashi_pic.png" alt="FASHI" style="max-width: 100%; border-radius: 10px; box-shadow: 0 2px 12px rgba(0,0,0,0.08);">
    <p style="margin-top: 1rem; color: #aaa; font-size: 0.85rem;">&copy; FASHI Collaboration &middot; FAST Operation and Development Center, NAOC</p>
  </div>

</div>
