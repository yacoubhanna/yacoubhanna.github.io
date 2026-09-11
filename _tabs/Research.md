---
layout: page
title: Research
permalink: /research/
icon: fas fa-archive
order: 2
---

<style>

/* ================================
   Research Project Cards
   ================================ */

.research-card {
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

/* Card hover */
.research-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
}

/* Expanded card */
.research-card[open] {
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
}


/* ================================
   Card Header
   ================================ */

.research-card > summary {
  list-style: none;
  cursor: pointer;

  padding: 22px 24px;

  display: flex;
  align-items: center;
  justify-content: space-between;

  gap: 18px;
}

.research-card > summary::-webkit-details-marker {
  display: none;
}

.research-card > summary::marker {
  content: "";
}


/* ================================
   Header Content
   ================================ */

.research-summary {
  display: flex;
  align-items: center;
  gap: 16px;
  min-width: 0;
}

.research-icon {
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

.research-title {
  display: block;

  font-size: 1.08rem;
  font-weight: 700;

  color: var(--heading-color, inherit);
}

.research-subtitle {
  display: block;

  margin-top: 4px;

  font-size: 0.90rem;
  font-weight: 400;

  color: var(--text-muted-color, #6c757d);
}


/* ================================
   Arrow
   ================================ */

.research-card > summary::after {
  content: "›";

  font-size: 1.9rem;
  font-weight: 300;

  color: var(--text-muted-color, #777);

  transition: transform 0.2s ease;
}

.research-card[open] > summary::after {
  transform: rotate(90deg);
}


/* ================================
   Expanded Content
   ================================ */

.research-body {
  padding: 5px 24px 26px 24px;

  border-top: 1px solid var(--main-border-color, #e5e5e5);
}

.research-body > :first-child {
  margin-top: 22px;
}

.research-body h4 {
  margin-bottom: 20px;
}

.research-body p {
  line-height: 1.75;
}


/* ================================
   Images
   ================================ */

.research-single-image {
  text-align: center;
  width: 100%;
  margin: 28px 0;
}

.research-single-image img {
  width: 70%;
  max-width: 800px;
  height: auto;

  display: block;
  margin: 0 auto;
}

.research-two-images {
  display: grid;

  grid-template-columns: 1.2fr 1fr;

  gap: 20px;

  width: 100%;

  align-items: center;

  margin: 28px 0;
}

.research-two-images img {
  width: 100%;
  max-width: none;
  height: auto;
}


/* ================================
   Publications
   ================================ */

.research-publication {
  margin-bottom: 14px;
}


/* ================================
   Mobile
   ================================ */

@media (max-width: 700px) {

  .research-card > summary {
    padding: 18px;
  }

  .research-body {
    padding: 5px 18px 22px 18px;
  }

  .research-icon {
    width: 42px;
    height: 42px;
    min-width: 42px;

    font-size: 1.1rem;
  }

  .research-title {
    font-size: 1rem;
  }

  .research-subtitle {
    font-size: 0.82rem;
  }

  .research-two-images {
    grid-template-columns: 1fr;
  }

  .research-single-image img {
    width: 100%;
  }

}

</style>


<!-- =========================================================
     PROJECT 1 — PQ-CKEM / LEO SATELLITE NETWORKS
     ========================================================= -->

<details class="research-card" markdown="1">

<summary>

  <span class="research-summary">

    <span class="research-icon">
      <i class="fa-solid fa-satellite"></i>
    </span>

    <span>

      <span class="research-title">
        Post-Quantum Security for Large-Scale LEO Satellite Networks
      </span>

      <span class="research-subtitle">
        PQ-CKEM · Satellite Security · Post-Quantum Group Key Management
      </span>

    </span>

  </span>

</summary>


<div class="research-body" markdown="1">

<h4>
PQ-CKEM: Post-Quantum Group Key Management for LEO Satellite Networks
</h4>

<p>
Low Earth Orbit (LEO) satellite constellations are rapidly expanding to provide global broadband connectivity and support future integrated 5G/6G networks. As the number of satellites increases, secure and efficient handover between neighboring satellites becomes essential to maintain continuous communication. Existing group key management solutions rely on traditional cryptographic techniques that are vulnerable to future quantum computing attacks and are not optimized for the highly dynamic topology of satellite networks.
</p>

<p>
This project introduces Post-Quantum Clustered Key Encapsulation Mechanism (PQ-CKEM), a lightweight and scalable group key management framework designed specifically for large-scale LEO satellite constellations. The proposed approach combines Post-Quantum Cryptography (PQC) based on ML-KEM (Kyber) with a hierarchical clustering architecture inspired by TreeKEM and Connected Dominating Set (CDS) graph theory. Satellites are organized into localized clusters, where cluster leaders coordinate secure group key establishment and maintenance while minimizing communication overhead.
</p>

<p>
PQ-CKEM enables efficient group key creation, renewal, join, and leave operations while providing quantum-resistant security, forward secrecy, and backward secrecy. The framework also supports establishing a global network-wide key through cooperation among cluster leaders, enabling secure and scalable handover operations across the constellation. This research contributes a practical and future-proof security solution for next-generation satellite communication systems by combining scalable group key management with PQC, ensuring the secure and efficient operation of large LEO constellations in the quantum computing era.
</p>


<div class="research-two-images">

  <img src="/assets/img/PQC.png"
       alt="PQ-CKEM Architecture">

  <img src="/assets/img/PQC2.png"
       alt="LEO Satellite Network">

</div>


<p>
<strong>Highlight:</strong> Best Paper Award, IEEE LANMAN 2026.
</p>

<p>
<strong>People:</strong> Yacoub Hanna, Maryna Veksler, Kemal Akkaya.
</p>

<p>
<strong>Publications:</strong>
</p>

<p class="research-publication">
Y. Hanna, M. Veksler, and K. Akkaya, (2026). "PQ-CKEM: Efficient Quantum-Resistant Group Key Creation for Large-Scale LEO Satellite Networks." Proceedings of the IEEE International Symposium on Local and Metropolitan Area Networks (LANMAN).
</p>

<p class="research-publication">
A. Mutlugun, Y. Hanna, and K. Akkaya, "Performance Evaluation of Quantum-Resistant IKEv2 Protocol for Satellite Networking Environments." 2024 IEEE Virtual Conference on Communications (VCC), NY, USA, pp. 1-7, 2024, doi: 10.1109/VCC63113.2024.10914395.
</p>

</div>

</details>



<!-- =========================================================
     PROJECT 2 — POST-QUANTUM IoT
     ========================================================= -->

<details class="research-card" markdown="1">

<summary>

  <span class="research-summary">

    <span class="research-icon">
      <i class="fa-solid fa-microchip"></i>
    </span>

    <span>

      <span class="research-title">
        Post-Quantum Security for Consumer IoT Devices
      </span>

      <span class="research-subtitle">
        Post-Quantum TLS · BLE · Wi-Fi · Embedded and IoT Security
      </span>

    </span>

  </span>

</summary>


<div class="research-body" markdown="1">

<h4>
A Comprehensive and Realistic Performance Evaluation of Post-Quantum Security for Consumer IoT Devices
</h4>

<p>
The computational capacity envisaged for quantum computers poses a significant threat to today’s traditional cryptographic algorithms. Although they are not yet large enough to compromise current cryptographic protocols, retrospective decryption remains a concern because encrypted network traffic can be captured today and decrypted in the future. This threat extends to wireless communication security within consumer IoT devices that use lightweight cryptography due to limited computational power. Thus, countermeasures against potential quantum attacks should be preemptively adopted. In response, the National Institute of Standards and Technology (NIST) published its first Post-Quantum Cryptography (PQC) standards in August 2024, including standards for Key Encapsulation Mechanisms (KEMs) and digital signatures.
</p>

<p>
This project investigates the viability of these PQ algorithms in Transport Layer Security (TLS) for power-constrained IoT devices. Specifically, it focuses on two widely used IoT network protocol stacks: Bluetooth Low Energy (BLE) and Wi-Fi. We built a realistic IoT testbed running IP over BLE. Our evaluation considers several realistic factors, including a chain of certificates on the server side and certificate validation methods such as Online Certificate Status Protocol (OCSP) and Certificate Revocation Lists (CRLs). We also evaluated the impact of mutual authentication between the server and the client.
</p>

<p>
Using the outcomes of this evaluation, we proposed a novel approach that enables IoT devices to dynamically choose suitable post-quantum KEM and digital signature algorithms for TLS based on the device’s physical network interface. The performance results provide insights into TLS latency, communication overhead, and energy consumption in consumer IoT environments.
</p>


<div class="research-single-image">

  <img src="/assets/img/PQ-IoT.png"
       alt="Post-Quantum IoT Testbed">

</div>


<p>
<strong>People:</strong> Yacoub Hanna, Jessica Bozhko, Samet Tonyali, Ricardo Harrilal-Parchment, Mumin Cebe, Kemal Akkaya.
</p>

<p>
<strong>Publications:</strong>
</p>

<p class="research-publication">
Y. Hanna, J. Bozhko, S. Tonyali, R. Harrilal-Parchment, M. Cebe, and K. Akkaya, "A Comprehensive and Realistic Performance Evaluation of Post-Quantum Security for Consumer IoT Devices." Elsevier Internet of Things Journal, 2025, 101650, doi:
<a href="https://doi.org/10.1016/j.iot.2025.101650"
   target="_blank"
   rel="noopener noreferrer">
10.1016/j.iot.2025.101650
</a>.
</p>

<p class="research-publication">
Y. Hanna, S. Tonyali, R. Harrilal-Parchment, and K. Akkaya, (2026). "Rethinking IoT Security in the Era of Quantum Computing: Literature Reviews." In <em>Quantum Computing, Sensing and Communications for IoT</em>, pp. 169-226. Singapore: Springer Nature Singapore.
</p>

<p class="research-publication">
J. Bozhko, Y. Hanna, R. Harrilal-Parchment, S. Tonyali, and K. Akkaya, "Performance Evaluation of Quantum-Resistant TLS for Consumer IoT Devices." 2023 IEEE 20th Consumer Communications & Networking Conference (CCNC), Las Vegas, NV, USA, pp. 230-235, 2023, doi:
<a href="https://doi.org/10.1109/CCNC51644.2023.10060762"
   target="_blank"
   rel="noopener noreferrer">
10.1109/CCNC51644.2023.10060762
</a>.
</p>

</div>

</details>



<!-- =========================================================
     PROJECT 3 — RINGS / PQ 5G
     ========================================================= -->

<details class="research-card" markdown="1">

<summary>

  <span class="research-summary">

    <span class="research-icon">
      <i class="fa-solid fa-network-wired"></i>
    </span>

    <span>

      <span class="research-title">
        RINGS: Bringing Post-Quantum Cryptography to Large-Scale NextG Systems
      </span>

      <span class="research-subtitle">
        5G · Post-Quantum TLS · Next-Generation Network Security
      </span>

    </span>

  </span>

</summary>


<div class="research-body" markdown="1">

<h4>
Integrating Post-Quantum TLS into the Control Plane of 5G Networks
</h4>

<p>
Significant performance improvements in bandwidth and latency make 5G a suitable candidate for a wide range of applications, particularly those requiring real-time communication, such as Industrial Control Systems (ICS) and autonomous vehicles. However, today’s security, including modern cryptographic systems, is prone to attacks enabled by the high computational power expected from quantum computing, emphasizing the need for quantum-resistant security measures.
</p>

<p>
To accommodate attacks targeted at 5G networks, there are efforts to move toward TLS-based security, which is widely accepted in other network environments. However, integrating post-quantum algorithms must also be considered as part of such a transition. This project is the first to perform the integration of PQ-TLS protocols into 5G networks and provide a realistic performance evaluation. Our approach focused on bringing PQ-TLS into the 5G control plane without requiring a major architectural overhaul, thereby preserving interoperability with legacy 5G components that may not support TLS.
</p>

<p>
Specifically, we transitioned the registration and authentication protocols for the core network functions and User Equipment (UE) by following a TLS tunneling approach using virtualization. We then evaluated the performance and feasibility of PQ-TLS in enhancing the security of 5G communications on an actual testbed. Our results demonstrated that while PQ algorithms introduce additional overhead, they remain viable for 5G applications, particularly for protocols operating within the core network.
</p>


<div class="research-single-image">

  <img src="/assets/img/PQ-5G.png"
       alt="Post-Quantum 5G Testbed">

</div>


<p>
<strong>People:</strong> Yacoub Hanna, Diana Pineda, Maryna Veksler, Manish Paudel, Kemal Akkaya, Mila Anastasova, Reza Azarderakhsh.
</p>

<p>
<strong>Publications:</strong>
</p>

<p class="research-publication">
Y. Hanna, D. Pineda, M. Veksler, M. Paudel, K. Akkaya, M. Anastasova, and R. Azarderakhsh, "Integrating Post-Quantum TLS into the Control Plane of 5G Networks." 2024 IEEE International Performance, Computing, and Communications Conference (IPCCC), Orlando, FL, USA, 2024, pp. 1-8, doi:
<a href="https://doi.org/10.1109/IPCCC59868.2024.10850437"
   target="_blank"
   rel="noopener noreferrer">
10.1109/IPCCC59868.2024.10850437
</a>.
</p>

</div>

</details>



<!-- =========================================================
     PROJECT 4 — LoRaWAN / SMART GRID
     ========================================================= -->

<details class="research-card" markdown="1">

<summary>

  <span class="research-summary">

    <span class="research-icon">
      <i class="fa-solid fa-key"></i>
    </span>

    <span>

      <span class="research-title">
        Efficient Key Management for Low-Bandwidth Networks
      </span>

      <span class="research-subtitle">
        LoRaWAN · Smart Grid Security · Group Key Management
      </span>

    </span>

  </span>

</summary>


<div class="research-body" markdown="1">

<h4>
Efficient Group Key Management for Resilient Operation of LoRaWAN-Based Smart Grid Applications
</h4>

<p>
The underlying legacy communication infrastructures, which may have severely constrained bandwidth, are under increasing strain as new smart devices are added and more data is collected to support better control decisions in Smart Grid infrastructures. Therefore, publish-subscribe architectures are becoming increasingly common because they provide flexible communication options while also taking advantage of multicast and broadcast capabilities to minimize the amount of transmitted data.
</p>

<p>
To enable secure multicast and broadcast data exchange, underlying mechanisms are required to generate and manage cryptographic keys. A group key can be used to protect the authenticity, integrity, and confidentiality of broadcast messages. Although session-key generation for unicast communications has been extensively studied, these mechanisms do not directly address the requirements of group communications, including key generation, distribution, and renewal in Smart Grid environments.
</p>

<p>
In addition, efficient mechanisms are needed to minimize disruption to data traffic when keys are updated. This project focuses on achieving efficient key management for securing both unicast and broadcast communications in publish-subscribe Smart Grid applications. One component of the project explores a secure key management scheme that integrates dynamic key generation with Shamir’s Secret Sharing to achieve efficient group key management. Another component investigates more efficient broadcast mechanisms for the DDS protocol.
</p>


<div class="research-single-image">

  <img src="/assets/img/LoRaWAN.png"
       alt="LoRaWAN Testbed">

</div>


<p>
<strong>People:</strong> Yacoub Hanna, Juan Leon, Mumin Cebe, Suat Mercan, Kemal Akkaya.
</p>

<p>
<strong>Publications:</strong>
</p>

<p class="research-publication">
Y. Hanna, M. Cebe, J. Leon, and K. Akkaya, "Efficient Group Key Management for Resilient Operation of LoRaWAN-Based Smart Grid Applications." IEEE Transactions on Control Systems Technology, vol. 32, no. 5, 2024, pp. 1706-1717, doi:
<a href="https://doi.org/10.1109/TCST.2024.3378988"
   target="_blank"
   rel="noopener noreferrer">
10.1109/TCST.2024.3378988
</a>.
</p>

<p class="research-publication">
Y. Hanna, M. Cebe, S. Mercan, and K. Akkaya, "Efficient Group-Key Management for Low-Bandwidth Smart Grid Networks." 2021 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm), Aachen, Germany, 2021, pp. 188-193, doi:
<a href="https://doi.org/10.1109/SmartGridComm51999.2021.9631988"
   target="_blank"
   rel="noopener noreferrer">
10.1109/SmartGridComm51999.2021.9631988
</a>.
</p>

<p class="research-publication">
J. Leon, Y. Hanna, and K. Akkaya, "Development and Evaluation of a Publish/Subscribe IoT Data Sharing Model with LoRaWAN." Open Journal of Internet of Things (OJIOT), vol. 8, no. 1, 2022, pp. 7-19.
</p>

</div>

</details>