---
layout: page
title: Research
permalink: /research/
icon: fas fa-archive
order: 2
---

<details markdown="1"> <summary><strong>Post-Quantum Security for Large-Scale LEO Satellite Networks</strong></summary>

PQ-CKEM: Post-Quantum Group Key Management for LEO Satellite Networks

Low Earth Orbit (LEO) satellite constellations are rapidly expanding to provide global broadband connectivity and support future integrated 5G/6G networks. As the number of satellites increases, secure and efficient handover between neighboring satellites becomes essential to maintain continuous communication. Existing group key management solutions rely on traditional cryptographic techniques that are vulnerable to future quantum computing attacks and are not optimized for the highly dynamic topology of satellite networks.

This project introduces Post-Quantum Clustered Key Encapsulation Mechanism (PQ-CKEM), a lightweight and scalable group key management framework designed specifically for large-scale LEO satellite constellations. The proposed approach combines Post-Quantum Cryptography (PQC) based on ML-KEM (Kyber) with a hierarchical clustering architecture inspired by TreeKEM and Connected Dominating Set (CDS) graph theory. Satellites are organized into localized clusters, where cluster leaders coordinate secure group key establishment and maintenance while minimizing communication overhead.

PQ-CKEM enables efficient group key creation, renewal, join, and leave operations while providing quantum-resistant security, forward secrecy, and backward secrecy. The framework also supports establishing a global network-wide key through cooperation among cluster leaders, enabling secure and scalable handover operations across the constellation. This research contributes a practical and future-proof security solution for next-generation satellite communication systems by combining scalable group key management with PQC, ensuring the secure and efficient operation of large LEO constellations in the quantum computing era.


<div style="display: flex; gap: 2%; justify-content: center; align-items: flex-start;">
  <img src="/assets/img/PQC.png"
       alt="Research Figure 1"
       style="width: 48%; height: auto;">

  <img src="/assets/img/PQC2.png"
       alt="Research Figure 2"
       style="width: 48%; height: auto;">
</div>


Highlight: Best Paper Award, IEEE LANMAN 2026.

People: Yacoub Hanna, Maryna Veksler, Kemal Akkaya

Publications: 

Yacoub Hanna, Maryna Veksler, and Kemal Akkaya. "PQ-CKEM: Efficient Quantum-Resistant Group Key Creation for Large-Scale LEO Satellite Networks." 2026 IEEE 32nd International Symposium on Local and Metropolitan Area Networks (LANMAN). IEEE, 2026.

</details>
