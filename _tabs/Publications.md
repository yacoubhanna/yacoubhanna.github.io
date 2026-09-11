---
layout: page
title: Publications
permalink: /publications/
icon: fas fa-stream
order: 3
---

<style>

/* ==========================================
   Publication Category Cards
   ========================================== */

.publication-card {
  border: 1px solid var(--main-border-color, #e5e5e5);
  border-radius: 14px;
  margin-bottom: 20px;
  background: var(--main-bg, #ffffff);
  overflow: hidden;

  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease,
    border-color 0.2s ease;
}

.publication-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
}

.publication-card[open] {
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
}


/* ==========================================
   Category Header
   ========================================== */

.publication-card > summary {
  list-style: none;
  cursor: pointer;

  padding: 22px 24px;

  display: flex;
  align-items: center;
  justify-content: space-between;

  gap: 18px;
}

.publication-card > summary::-webkit-details-marker {
  display: none;
}

.publication-card > summary::marker {
  content: "";
}

.publication-summary {
  display: flex;
  align-items: center;
  gap: 16px;
  min-width: 0;
}

.publication-icon {
  width: 48px;
  height: 48px;
  min-width: 48px;

  border-radius: 12px;

  display: flex;
  align-items: center;
  justify-content: center;

  font-size: 1.3rem;

  background: rgba(13, 110, 253, 0.10);
  color: var(--link-color, #0d6efd);
}

.publication-title {
  display: block;

  font-size: 1.08rem;
  font-weight: 700;

  color: var(--heading-color, inherit);
}

.publication-subtitle {
  display: block;

  margin-top: 4px;

  font-size: 0.90rem;
  font-weight: 400;

  color: var(--text-muted-color, #6c757d);
}


/* ==========================================
   Arrow
   ========================================== */

.publication-card > summary::after {
  content: "›";

  font-size: 1.9rem;
  font-weight: 300;

  color: var(--text-muted-color, #777);

  transition: transform 0.2s ease;
}

.publication-card[open] > summary::after {
  transform: rotate(90deg);
}


/* ==========================================
   Expanded Area
   ========================================== */

.publication-body {
  padding: 22px 24px 26px 24px;

  border-top: 1px solid var(--main-border-color, #e5e5e5);
}


/* ==========================================
   Individual Publication
   ========================================== */

.pub-item {
  position: relative;

  padding: 18px 20px;
  margin-bottom: 14px;

  border: 1px solid var(--main-border-color, #e5e5e5);
  border-radius: 10px;

  background: var(--card-bg, var(--main-bg, #ffffff));

  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.pub-item:last-child {
  margin-bottom: 0;
}

.pub-item:hover {
  transform: translateY(-1px);
  box-shadow: 0 5px 16px rgba(0, 0, 0, 0.06);
}

.pub-title {
  font-weight: 600;
  line-height: 1.55;
}

.pub-venue {
  margin-top: 8px;

  font-size: 0.92rem;

  color: var(--text-muted-color, #6c757d);
}

.pub-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  margin-top: 12px;
  padding: 8px 15px;

  border: 1px solid var(--link-color, #0d6efd);
  border-radius: 10px;

  font-size: 0.85rem;
  font-weight: 600;
  line-height: 1.2;

  color: var(--link-color, #0d6efd);
  background: rgba(13, 110, 253, 0.03);

  text-decoration: none !important;
  box-sizing: border-box;
}

.pub-link:hover {
  background: var(--link-color, #0d6efd);
  color: white !important;
}


/* ==========================================
   Year Badge
   ========================================== */

.pub-year {
  display: inline-block;

  margin-bottom: 8px;
  padding: 3px 9px;

  border-radius: 20px;

  font-size: 0.76rem;
  font-weight: 600;

  background: rgba(13, 110, 253, 0.10);
  color: var(--link-color, #0d6efd);
}


/* ==========================================
   Mobile
   ========================================== */

@media (max-width: 700px) {

  .publication-card > summary {
    padding: 18px;
  }

  .publication-body {
    padding: 18px;
  }

  .publication-icon {
    width: 42px;
    height: 42px;
    min-width: 42px;

    font-size: 1.1rem;
  }

  .publication-title {
    font-size: 1rem;
  }

  .publication-subtitle {
    font-size: 0.82rem;
  }

  .pub-item {
    padding: 16px;
  }

}

</style>


<!-- =========================================================
     BOOK CHAPTER
     ========================================================= -->

<details class="publication-card">

<summary>

  <span class="publication-summary">

    <span class="publication-icon">
      <i class="fa-solid fa-book"></i>
    </span>

    <span>

      <span class="publication-title">
        Book Chapters
      </span>

      <span class="publication-subtitle">
        Published chapters and contributed books
      </span>

    </span>

  </span>

</summary>


<div class="publication-body">

  <div class="pub-item">

    <span class="pub-year">2026</span>

    <div class="pub-title">
      <strong>Y. Hanna</strong>, S. Tonyali, R. Harrilal-Parchment, and K. Akkaya,
      "Rethinking IoT Security in the Era of Quantum Computing: Literature Reviews."
    </div>

    <div class="pub-venue">
      <em>Quantum Computing, Sensing and Communications for IoT</em>,
      Springer Nature Singapore, 2026.
    </div>

    <a class="pub-link"
       href="https://link.springer.com/chapter/10.1007/978-981-95-6276-3_5"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>

</div>

</details>



<!-- =========================================================
     JOURNAL PAPERS
     ========================================================= -->

<details class="publication-card">

<summary>

  <span class="publication-summary">

    <span class="publication-icon">
      <i class="fa-solid fa-newspaper"></i>
    </span>

    <span>

      <span class="publication-title">
        Journal Papers
      </span>

      <span class="publication-subtitle">
        Elsevier Internet of Things, IEEE Transactions on Control Systems Technology
      </span>

    </span>

  </span>

</summary>


<div class="publication-body">


  <div class="pub-item">

    <span class="pub-year">2025</span>

    <div class="pub-title">
      <strong>Y. Hanna</strong>, J. Bozhko, S. Tonyali,
      R. Harrilal-Parchment, M. Cebe, and K. Akkaya,
      "A Comprehensive and Realistic Performance Evaluation of
      Post-Quantum Security for Consumer IoT Devices."
    </div>

    <div class="pub-venue">
      <em>Elsevier Internet of Things</em>, 2025.
    </div>

    <a class="pub-link"
       href="https://www.sciencedirect.com/science/article/abs/pii/S2542660525001647?via%3Dihub"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


  <div class="pub-item">

    <span class="pub-year">2024</span>

    <div class="pub-title">
      <strong>Y. Hanna</strong>, M. Cebe, J. Leon, and K. Akkaya,
      "Efficient Group Key Management for Resilient Operation of
      LoRaWAN-Based Smart Grid Applications."
    </div>

    <div class="pub-venue">
      <em>IEEE Transactions on Control Systems Technology</em>, 2024.
    </div>

    <a class="pub-link"
       href="https://ieeexplore.ieee.org/document/10490239"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


  <div class="pub-item">

    <span class="pub-year">2022</span>

    <div class="pub-title">
      J. Leon, <strong>Y. Hanna</strong>, and K. Akkaya,
      "Development and Evaluation of a Publish/Subscribe IoT Data
      Sharing Model with LoRaWAN."
    </div>

    <div class="pub-venue">
      <em>Open Journal of Internet of Things (OJIOT)</em>, 2022.
    </div>

    <a class="pub-link"
       href="https://www.researchgate.net/profile/Yacoub-Hanna/publication/403996119_Development_and_Evaluation_of_a_PublishSubscribe_IoT_Data_Sharing_Model_with_LoRaWAN/links/69e66cfab1056332819dc8c3/Development-and-Evaluation-of-a-Publish-Subscribe-IoT-Data-Sharing-Model-with-LoRaWAN.pdf"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


</div>

</details>



<!-- =========================================================
     CONFERENCE PAPERS
     ========================================================= -->

<details class="publication-card">

<summary>

  <span class="publication-summary">

    <span class="publication-icon">
      <i class="fa-solid fa-users"></i>
    </span>

    <span>

      <span class="publication-title">
        Conference Papers
      </span>

      <span class="publication-subtitle">
        IEEE, ACM, and other conference publications
      </span>

    </span>

  </span>

</summary>


<div class="publication-body">


  <div class="pub-item">

    <span class="pub-year">2026</span>

    <div class="pub-title">
      <strong>Y. Hanna</strong>, M. Veksler, and K. Akkaya,
      "PQ-CKEM: Efficient Quantum-Resistant Group Key Creation for
      Large-Scale LEO Satellite Networks."
    </div>


    <div class="pub-venue">
      <em>IEEE International Symposium on Local and Metropolitan
      Area Networks (LANMAN)</em>, 2026.
      <br>
      <strong>Best Paper Award</strong>
    </div>

    <a class="pub-link"
       href="https://ieeexplore.ieee.org/abstract/document/11623619"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  

  </div>


  <div class="pub-item">

    <span class="pub-year">2024</span>

    <div class="pub-title">
      <strong>Y. Hanna</strong>, D. Pineda, M. Veksler, M. Paudel,
      K. Akkaya, M. Anastasova, and R. Azarderakhsh,
      "Integrating Post-Quantum TLS into the Control Plane of 5G Networks."
    </div>

    <div class="pub-venue">
      <em>IEEE International Performance, Computing, and Communications
      Conference (IPCCC)</em>, 2024.
    </div>

    <a class="pub-link"
       href="https://ieeexplore.ieee.org/document/10850437"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


  <div class="pub-item">

    <div class="pub-title">
      M. Paudel, <strong>Y. Hanna</strong>, M. Veksler, K. Akkaya,
      D. Pineda, M. Anastasova, and R. Azarderakhsh,
      "Practical and Efficient Post-Quantum Security Framework
      for IoT-Based 5G Networks."
    </div>

    <div class="pub-venue">
      Available at SSRN 6714859.
    </div>

    <a class="pub-link"
       href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6714859"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


  <div class="pub-item">

    <span class="pub-year">2024</span>

    <div class="pub-title">
      A. Mutlugun, <strong>Y. Hanna</strong>, and K. Akkaya,
      "Performance Evaluation of Quantum-Resistant IKEv2 Protocol
      for Satellite Networking Environments."
    </div>

    <div class="pub-venue">
      <em>IEEE Virtual Conference on Communications (VCC)</em>, 2024.
    </div>

    <a class="pub-link"
       href="https://ieeexplore.ieee.org/document/10914395"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


  <div class="pub-item">

    <span class="pub-year">2023</span>

    <div class="pub-title">
      <strong>Y. Hanna</strong>, D. Pineda, K. Akkaya, A. Aydeger,
      R. Harrilal-Parchment, and H. Albalawi,
      "Performance Evaluation of Secure and Privacy-Preserving DNS
      at the 5G Edge."
    </div>

    <div class="pub-venue">
      <em>IEEE 20th International Conference on Mobile Ad Hoc and
      Smart Systems (MASS)</em>, 2023.
    </div>

    <a class="pub-link"
       href="https://ieeexplore.ieee.org/abstract/document/10298330"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


  <div class="pub-item">

    <span class="pub-year">2023</span>

    <div class="pub-title">
      J. Bozhko, <strong>Y. Hanna</strong>, R. Harrilal-Parchment,
      S. Tonyali, and K. Akkaya,
      "Performance Evaluation of Quantum-Resistant TLS for
      Consumer IoT Devices."
    </div>

    <div class="pub-venue">
      <em>IEEE 20th Consumer Communications & Networking Conference
      (CCNC)</em>, 2023.
    </div>

    <a class="pub-link"
       href="https://ieeexplore.ieee.org/abstract/document/10060762"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


  <div class="pub-item">

    <span class="pub-year">2022</span>

    <div class="pub-title">
      J. Leon, <strong>Y. Hanna</strong>, and K. Akkaya,
      "Integration of WAVE and OpenFlow for Realization of
      SDN-Based VANETs in ns-3."
    </div>

    <div class="pub-venue">
      <em>Workshop on ns-3 (WNS3)</em>, 2022.
    </div>

    <a class="pub-link"
       href="https://dl.acm.org/doi/10.1145/3532577.3532608"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


  <div class="pub-item">

    <span class="pub-year">2021</span>

    <div class="pub-title">
      <strong>Y. Hanna</strong>, M. Cebe, S. Mercan, and K. Akkaya,
      "Efficient Group-Key Management for Low-Bandwidth Smart Grid Networks."
    </div>

    <div class="pub-venue">
      <em>IEEE International Conference on Communications, Control,
      and Computing Technologies for Smart Grids (SmartGridComm)</em>, 2021.
    </div>

    <a class="pub-link"
       href="https://ieeexplore.ieee.org/abstract/document/9631988"
       target="_blank"
       rel="noopener noreferrer">
       View Publication
    </a>

  </div>


</div>

</details>



<!-- =========================================================
     DISSERTATION
     ========================================================= -->

<details class="publication-card">

<summary>

  <span class="publication-summary">

    <span class="publication-icon">
      <i class="fa-solid fa-graduation-cap"></i>
    </span>

    <span>

      <span class="publication-title">
        Dissertation
      </span>

      <span class="publication-subtitle">
        Ph.D. Dissertation · Florida International University
      </span>

    </span>

  </span>

</summary>


<div class="publication-body">

  <div class="pub-item">

    <span class="pub-year">2026</span>

    <div class="pub-title">
      <strong>Y. Hanna</strong>,
      "Emerging Key Management Strategies for Constrained Wireless Networks."
    </div>

    <div class="pub-venue">
      Ph.D. Dissertation, Florida International University, 2026.
    </div>

  </div>

</div>

</details>