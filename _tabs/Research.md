---
layout: page
title: Research
permalink: /research/
icon: fas fa-archive
order: 2
---

<details markdown="1">
<summary><strong>Post-Quantum Security for Large-Scale LEO Satellite Networks</strong></summary>

<h4>PQ-CKEM: Post-Quantum Group Key Management for LEO Satellite Networks</h4>

<p>
Low Earth Orbit (LEO) satellite constellations are rapidly expanding to provide global broadband connectivity and support future integrated 5G/6G networks. As the number of satellites increases, secure and efficient handover between neighboring satellites becomes essential to maintain continuous communication. Existing group key management solutions rely on traditional cryptographic techniques that are vulnerable to future quantum computing attacks and are not optimized for the highly dynamic topology of satellite networks.
</p>

<p>
This project introduces Post-Quantum Clustered Key Encapsulation Mechanism (PQ-CKEM), a lightweight and scalable group key management framework designed specifically for large-scale LEO satellite constellations. The proposed approach combines Post-Quantum Cryptography (PQC) based on ML-KEM (Kyber) with a hierarchical clustering architecture inspired by TreeKEM and Connected Dominating Set (CDS) graph theory. Satellites are organized into localized clusters, where cluster leaders coordinate secure group key establishment and maintenance while minimizing communication overhead.
</p>

<p>
PQ-CKEM enables efficient group key creation, renewal, join, and leave operations while providing quantum-resistant security, forward secrecy, and backward secrecy. The framework also supports establishing a global network-wide key through cooperation among cluster leaders, enabling secure and scalable handover operations across the constellation. This research contributes a practical and future-proof security solution for next-generation satellite communication systems by combining scalable group key management with PQC, ensuring the secure and efficient operation of large LEO constellations in the quantum computing era.
</p>

<div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 20px; width: 100%; align-items: center; margin: 25px 0;">

  <img src="/assets/img/PQC.png"
       alt="PQ-CKEM Architecture"
       style="width: 100%; max-width: none; height: auto;">

  <img src="/assets/img/PQC2.png"
       alt="LEO Satellite Network"
       style="width: 100%; max-width: none; height: auto;">

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

<p style="margin-bottom: 12px;">
Y. Hanna, M. Veksler, and K. Akkaya, (2026). "PQ-CKEM: Efficient Quantum-Resistant Group Key Creation for Large-Scale LEO Satellite Networks." Proceedings of the IEEE International Symposium on Local and Metropolitan Area Networks (LANMAN).
</p>

<p style="margin-bottom: 12px;">
A. Mutlugun, Y. Hanna, and K. Akkaya, "Performance Evaluation of Quantum-Resistant IKEv2 Protocol for Satellite Networking Environments." 2024 IEEE Virtual Conference on Communications (VCC), NY, USA, pp. 1-7, 2024, doi: 10.1109/VCC63113.2024.10914395.
</p>

</details>


<details markdown="1">
<summary><strong>Post-Quantum Security for Consumer IoT Devices</strong></summary>

<h4>A Comprehensive and Realistic Performance Evaluation of Post-Quantum Security for Consumer IoT Devices</h4>

<p>
The computational capacity envisaged for quantum computers poses a significant threat to today’s traditional cryptographic algorithms. Although they are not yet large enough to compromise current cryptographic protocols, retrospective decryption remains a concern because encrypted network traffic can be captured today and decrypted in the future. This threat extends to wireless communication security within consumer IoT devices that use lightweight cryptography due to limited computational power. Thus, countermeasures against potential quantum attacks should be preemptively adopted. In response, the National Institute of Standards and Technology (NIST) published its first Post-Quantum Cryptography (PQC) standards in August 2024, including standards for Key Encapsulation Mechanisms (KEMs) and digital signatures.
</p>

<p>
This project investigates the viability of these PQ algorithms in Transport Layer Security (TLS) for power-constrained IoT devices. Specifically, it focuses on two widely used IoT network protocol stacks: Bluetooth Low Energy (BLE) and Wi-Fi. We built a realistic IoT testbed running IP over BLE. Our evaluation considers several realistic factors, including a chain of certificates on the server side and certificate validation methods such as Online Certificate Status Protocol (OCSP) and Certificate Revocation Lists (CRLs). We also evaluated the impact of mutual authentication between the server and the client.
</p>

<p>
Using the outcomes of this evaluation, we proposed a novel approach that enables IoT devices to dynamically choose suitable post-quantum KEM and digital signature algorithms for TLS based on the device’s physical network interface. The performance results provide insights into TLS latency, communication overhead, and energy consumption in consumer IoT environments.
</p>

<div style="text-align: center; width: 100%; margin: 25px 0;">

  <img src="/assets/img/PQ-IoT.png"
       alt="Post-Quantum IoT Testbed"
       style="width: 65%; max-width: 750px; height: auto; display: block; margin: 0 auto;">

</div>

<p>
<strong>People:</strong> Yacoub Hanna, Jessica Bozhko, Samet Tonyali, Ricardo Harrilal-Parchment, Mumin Cebe, Kemal Akkaya.
</p>

<p>
<strong>Publications:</strong>
</p>

<p style="margin-bottom: 12px;">
Y. Hanna, J. Bozhko, S. Tonyali, R. Harrilal-Parchment, M. Cebe, and K. Akkaya, "A Comprehensive and Realistic Performance Evaluation of Post-Quantum Security for Consumer IoT Devices." Elsevier Internet of Things Journal, 2025, 101650, doi: <a href="https://doi.org/10.1016/j.iot.2025.101650" target="_blank" rel="noopener noreferrer">10.1016/j.iot.2025.101650</a>.
</p>

<p style="margin-bottom: 12px;">
Y. Hanna, S. Tonyali, R. Harrilal-Parchment, and K. Akkaya, (2026). "Rethinking IoT Security in the Era of Quantum Computing: Literature Reviews." In <em>Quantum Computing, Sensing and Communications for IoT</em>, pp. 169-226. Singapore: Springer Nature Singapore.
</p>

<p style="margin-bottom: 12px;">
J. Bozhko, Y. Hanna, R. Harrilal-Parchment, S. Tonyali, and K. Akkaya, "Performance Evaluation of Quantum-Resistant TLS for Consumer IoT Devices." 2023 IEEE 20th Consumer Communications & Networking Conference (CCNC), Las Vegas, NV, USA, pp. 230-235, 2023, doi: <a href="https://doi.org/10.1109/CCNC51644.2023.10060762" target="_blank" rel="noopener noreferrer">10.1109/CCNC51644.2023.10060762</a>.
</p>

</details>


<details markdown="1">
<summary><strong>RINGS: Bringing Post-Quantum Cryptography to Large-Scale NextG Systems</strong></summary>

<h4>Integrating Post-Quantum TLS into the Control Plane of 5G Networks</h4>

<p>
Significant performance improvements in bandwidth and latency make 5G a suitable candidate for a wide range of applications, particularly those requiring real-time communication, such as Industrial Control Systems (ICS) and autonomous vehicles. However, today’s security, including modern cryptographic systems, is prone to attacks enabled by the high computational power expected from quantum computing, emphasizing the need for quantum-resistant security measures.
</p>

<p>
To accommodate attacks targeted at 5G networks, there are efforts to move toward TLS-based security, which is widely accepted in other network environments. However, integrating post-quantum algorithms must also be considered as part of such a transition.
</p>

<p>
This project is the first to perform the integration of PQ-TLS protocols into 5G networks and provide a realistic performance evaluation. Our approach focused on bringing PQ-TLS into the 5G control plane without requiring a major architectural overhaul, thereby preserving interoperability with legacy 5G components that may not support TLS.
</p>

<p>
Specifically, we transitioned the registration and authentication protocols for the core network functions and User Equipment (UE) by following a TLS tunneling approach using virtualization. We then evaluated the performance and feasibility of PQ-TLS in enhancing the security of 5G communications on an actual testbed. Our results demonstrated that while PQ algorithms introduce additional overhead, they remain viable for 5G applications, particularly for protocols operating within the core network.
</p>

<div style="text-align: center; width: 100%; margin: 25px 0;">

  <img src="/assets/img/PQ-5G.png"
       alt="Post-Quantum 5G Testbed"
       style="width: 65%; max-width: 750px; height: auto; display: block; margin: 0 auto;">

</div>

<p>
<strong>People:</strong> Yacoub Hanna, Diana Pineda, Maryna Veksler, Manish Paudel, Kemal Akkaya, Mila Anastasova, Reza Azarderakhsh.
</p>

<p>
<strong>Publications:</strong>
</p>

<p style="margin-bottom: 12px;">
Y. Hanna, D. Pineda, M. Veksler, M. Paudel, K. Akkaya, M. Anastasova, and R. Azarderakhsh, "Integrating Post-Quantum TLS into the Control Plane of 5G Networks." 2024 IEEE International Performance, Computing, and Communications Conference (IPCCC), Orlando, FL, USA, 2024, pp. 1-8, doi: <a href="https://doi.org/10.1109/IPCCC59868.2024.10850437" target="_blank" rel="noopener noreferrer">10.1109/IPCCC59868.2024.10850437</a>.
</p>

</details>


<details markdown="1">
<summary><strong>Efficient Key Management for Low-Bandwidth Networks</strong></summary>

<h4>Efficient Group Key Management for Resilient Operation of LoRaWAN-Based Smart Grid Applications</h4>

<p>
The underlying legacy communication infrastructures, which may have severely constrained bandwidth, are under increasing strain as new smart devices are added and more data is collected to support better control decisions in Smart Grid infrastructures. Therefore, publish-subscribe architectures are becoming increasingly common because they provide flexible communication options while also taking advantage of multicast and broadcast capabilities to minimize the amount of transmitted data.
</p>

<p>
To enable secure multicast and broadcast data exchange, underlying mechanisms are required to generate and manage cryptographic keys. A group key can be used to protect the authenticity, integrity, and confidentiality of broadcast messages. Although session-key generation for unicast communications has been extensively studied, these mechanisms do not directly address the requirements of group communications, including key generation, distribution, and renewal in Smart Grid environments.
</p>

<p>
In addition, efficient mechanisms are needed to minimize disruption to data traffic when keys are updated. This project focuses on achieving efficient key management for securing both unicast and broadcast communications in publish-subscribe Smart Grid applications. One component of the project explores a secure key management scheme that integrates dynamic key generation with Shamir’s Secret Sharing to achieve efficient group key management. Another component investigates more efficient broadcast mechanisms for the DDS protocol.
</p>

<div style="text-align: center; width: 100%; margin: 25px 0;">

  <img src="/assets/img/LoRaWAN.png"
       alt="LoRaWAN Testbed"
       style="width: 65%; max-width: 750px; height: auto; display: block; margin: 0 auto;">

</div>

<p>
<strong>People:</strong> Yacoub Hanna, Juan Leon, Mumin Cebe, Suat Mercan, Kemal Akkaya.
</p>

<p>
<strong>Publications:</strong>
</p>

<p style="margin-bottom: 12px;">
Y. Hanna, M. Cebe, J. Leon, and K. Akkaya, "Efficient Group Key Management for Resilient Operation of LoRaWAN-Based Smart Grid Applications." IEEE Transactions on Control Systems Technology, vol. 32, no. 5, 2024, pp. 1706-1717, doi: <a href="https://doi.org/10.1109/TCST.2024.3378988" target="_blank" rel="noopener noreferrer">10.1109/TCST.2024.3378988</a>.
</p>

<p style="margin-bottom: 12px;">
Y. Hanna, M. Cebe, S. Mercan, and K. Akkaya, "Efficient Group-Key Management for Low-Bandwidth Smart Grid Networks." 2021 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm), Aachen, Germany, 2021, pp. 188-193, doi: <a href="https://doi.org/10.1109/SmartGridComm51999.2021.9631988" target="_blank" rel="noopener noreferrer">10.1109/SmartGridComm51999.2021.9631988</a>.
</p>

<p style="margin-bottom: 12px;">
J. Leon, Y. Hanna, and K. Akkaya, "Development and Evaluation of a Publish/Subscribe IoT Data Sharing Model with LoRaWAN." Open Journal of Internet of Things (OJIOT), vol. 8, no. 1, 2022, pp. 7-19.
</p>

</details>



<!-->
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


<div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 20px; width: 100%; align-items: center;">

  <img src="/assets/img/PQC.png"
       alt="PQ-CKEM Architecture"
       style="width: 100%; max-width: none; height: auto;">

  <img src="/assets/img/PQC2.png"
       alt="LEO Satellite Network"
       style="width: 100%; max-width: none; height: auto;">

</div>


Highlight: Best Paper Award, IEEE LANMAN 2026.

People: Yacoub Hanna, Maryna Veksler, Kemal Akkaya.

Publications: 

Y. Hanna, M. Veksler, and K. Akkaya, (2026). PQ-CKEM: Efficient Quantum resistant Group Key Creation for Large-Scale LEO Satellite Networks. Proceedings of the IEEE International Symposium on Local and Metropolitan Area Networks (LANMAN).

A. Mutlugun, Y. Hanna, and K. Akkaya, "Performance Evaluation of Quantum-Resistant IKEv2 Protocol for Satellite Networking Environments." 2024 IEEE Virtual Conference on Communications (VCC), NY, USA, pp. 1-7, 2024, doi: 10.1109/VCC63113.2024.10914395.

</details>



<details markdown="2"> <summary><strong>Post-Quantum Security for Consumer IoT Devices</strong></summary>

A comprehensive and realistic performance evaluation of post-quantum security for consumer IoT devices

The computational capacity envisaged for quantum computers poses a significant threat to today’s traditional cryptographic algorithms. Although they are not yet large enough to compromise current cryptographic protocols, one can practice retrospective decryption since
data packets traveling through the Internet can be easily sniffed. This threat extends to wireless communication security within consumer IoT devices that use lightweight cryptography due to limited computational power. Thus, countermeasures against potential quantum attacks should be preemptively adopted. In response, the National Institute of Standards and Technology (NIST) published its first Post-Quantum Cryptography (PQC) standards in August 2024, including the Key-Encapsulation Mechanism (KEM) and Digital Signature Algorithm. 

This project investigate the viability of these PQ algorithms in the Transport Layer Security (TLS) of powerconstrained IoT devices. Specifically, it focuses on two widely used IoT network protocol stacks, i.e., Bluetooth Low Energy (BLE) and Wi-Fi. We built a realistic IoT testbed running IP over BLE. Our evaluation considers the impact of several realistic factors for the first time, such as using a chain of certificates on the server side and incorporating certificate validation methods such as Online Certificate Status Protocol (OCSP) and Certificate Revocation Lists (CRL). We also evaluated the impact of mutual authentication between the server and the client. Utilizing the outcomes of this evaluation, we also proposed a novel approach for IoT devices to dynamically choose the most efficient KEM algorithm for TLS based on the device’s physical network interface. The performance results provide valuable insights with respect to the TLS latency and energy consumption of consumer IoT devices.



<div style="text-align: center; width: 100%; margin: 25px 0;">

  <img src="/assets/img/PQ-IoT.png"
       alt="Post-Quantum IoT Testbed"
       style="width: 65%; max-width: 750px; height: auto; display: block; margin: 0 auto;">

</div>


People: Yacoub Hanna, Jessica Bozhko, Samet Tonyali, Ricardo Harrilal-Parchment, Mumin Cebe, Kemal Akkaya.

Publications: 

Y. Hanna, J. Bozhko, S. Tonyali, R. Harrilal-Parchment, M. Cebe, and K. Akkaya, "A comprehensive and realistic performance evaluation of post-quantum security for consumer IoT devices." Elsevier Internet of Things Journal 2025, 101650, doi: https://doi.org/10.1016/j.iot.2025.101650.

Y. Hanna, S. Tonyali, R. Harrilal-Parchment, and K. Akkaya, (2026). Rethinking IoT Security in the Era of Quantum Computing: Literature Reviews. In Quantum Computing, Sensing and Communications for IoT (pp. 169-226). Singapore: Springer Nature Singapore.

J. Bozhko, Y. Hanna, R. Harrilal-Parchment, S. Tonyali, and K. Akkaya. "Performance evaluation of quantum-resistant TLS for consumer IoT devices." 2023 IEEE 20th Consumer Communications & Networking Conference (CCNC), Las Vegas, NV, USA, pp. 230-235, 2023, doi: 10.1109/CCNC51644.2023.10060762

</details>



<details markdown="3"> <summary><strong>RINGS: Bringing Post-Quantum Cryptography to Large-Scale NextG Systems</strong></summary>

Integrating post-quantum tls into the control plane of 5g networks

Significant performance improvements in bandwidth and latency make 5G a suitable candidate for a wide range of applications, particularly those requiring real-time communication, such as Industrial Control Systems (ICS) and autonomous vehicles. However, today’s security, including modern cryptographic systems, is prone to different attacks caused by the high computational power of quantum computing, emphasizing the requirements for including quantum-resistant security measures. To accommodate attacks targeted at 5G networks, there are efforts to move towards TLS-based security, which is the widely accepted standard on other networks. However, integrating PQ algorithms must also be considered in such a transition.

This project is the first to perform the integration of PQ TLS (PQTLS) protocols into 5G networks and offer a realistic performance evaluation. Our approach focused on bringing PQ-TLS within the 5G control plane (CP) without needing a major overhaul, thus ensuring communications’ interoperability even with legacy components of 5G, which may not support TLS. Specifically, we have transitioned the registration and authentication protocols for the core network functions and the user equipment (UE) by following a TLS tunneling approach using virtualization. We then evaluated the performance and feasibility of PQ-TLS in enhancing the security of 5G communications on an actual testbed. Our results demonstrated that while PQ algorithms introduce some overhead, they remain viable for 5G applications, particularly for protocols that can run on the core network.



<div style="text-align: center; width: 100%; margin: 25px 0;">

  <img src="/assets/img/PQ-5G.png"
       alt="Post-Quantum 5G Testbed"
       style="width: 65%; max-width: 750px; height: auto; display: block; margin: 0 auto;">

</div>


People: Yacoub Hanna, Diana Pineda, Maryna Veksler, Manish Paudel, Kemal Akkaya, Mila Anastasova, Reza Azarderakhsh.

Publications: 

Y. Hanna, D. Pineda, M. Veksler, M. Paudel, K. Akkaya, M. Anastasova, and R. Azarderakhsh, "Integrating Post-Quantum TLS into the Control Plane of 5G Networks," 2024 IEEE International Performance, Computing, and Communications Conference (IPCCC), Orlando, FL, USA, 2024, pp. 1-8, doi: 10.1109/IPCCC59868.2024.10850437.

</details>



<details markdown="4"> <summary><strong>Efficient Key Management for Low-bandwidth Networks</strong></summary>

Efficient group key management for resilient operation of LoRaWAN-based smart grid applications

The underlying legacy communication infrastructures, which may have severely constrained bandwidth, are under a lot of strain as a result of adding new smart devices and increased data collection for better control decisions in the Smart Grid infrastructure. Therefore, publish-subscribe architectures are becoming common, which not only enable flexible communication options but also take advantage of the multicast/broadcast abilities to minimize the amount of data messages transmitted.

To enable secure multicast/broadcast data exchange, there must be underlying mechanisms to generate keys due to the importance of security in any of these scenarios. A group key is employed for protecting the authenticity, integrity, and confidentiality of broadcast messages. Although the generation of session keys for unicast communications has been the subject of extensive research, this does not entirely apply to group communications (i.e., key generation, distribution, and renewal in Smart Grid environments). In addition, there need to be efficient mechanisms for any type of key generation to minimize the disruption to data traffic when keys are being updated. 

This project focuses on achieving an efficient key management scheme to secure both unicast and broadcast communications in publish-subscribe (i.e., OPC UA) based Smart Grid applications.  For instance, one component of the project explores a secure key management scheme that integrates dynamic key generation with Shamir’s secret sharing to achieve efficient group key management. The other component investigates more efficient broadcasts for DDS protocol.

<div style="text-align: center; width: 100%; margin: 25px 0;">

  <img src="/assets/img/LoRaWAN.png"
       alt="LoRaWAN Testbed"
       style="width: 65%; max-width: 750px; height: auto; display: block; margin: 0 auto;">

</div>


People: Yacoub Hanna, Juan Leon, Dr. Mumin Cebe, Dr. Suat Mercan, and Dr. Kemal Akkaya. 

Publications: 

Y. Hanna, M. Cebe, J. Leon, and K. Akkaya, "Efficient Group Key Management for Resilient Operation of LoRaWAN-Based Smart Grid Applications." IEEE Transactions on Control Systems Technology 32, no. 5, 2024, pp. 1706-1717, doi: 10.1109/TCST.2024.3378988.

Y. Hanna, M. Cebe, S. Mercan, and K. Akkaya, "Efficient group-key management for low-bandwidth smart grid networks." 2021 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm), Aachen, Germany, 2021, pp. 188-193, doi: 10.1109/SmartGridComm51999.2021.9631988.

J. Leon, Y. Hanna, and K. Akkaya. "Development and evaluation of a publish/subscribe IoT data sharing model with LoRaWAN." 2022 Open Journal of Internet of Things (OJIOT) 8, no. 1, 2022, pp. 7-19, urn: urn:nbn:de:101:1-2022090515501014226277.

</details>



