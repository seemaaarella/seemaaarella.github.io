---
title: "Research Projects"
collection: projects
excerpt: 'Projects'
author_profile: true
redirect_from: 
  - /projects/
  - /projects.html
---

The research on “Fortified Edge” has promising prospects with huge opportunities for improving and  enhancing the model to its intended optimal application for security at the edge. The integration of ML and AI is a prime focus along with expanding the security model across edge IoT platforms and making the model scalable and interoperable. The scope of the future research is formulated in the following categories:

A Scalable and Interoperable Hybrid Mesh-Blockchain Framework for Edge:
======
<hr />
This research aims to integrate blockchain and Mesh IoT networks to develop a scalable and interoperable security system that addresses scalability issues with blockchain-based authentication systems, by offering dynamic and computationally less critical authentication to the mesh nodes and using blockchain for data-dependent and critical requests to the blockchain for global verification.

- Aim 1: Implement an off-chain storage model where the mesh network stores data locally using the blockchain for secure metadata tracking. This approach reduces the blockchain’s data load, improving network scalability and efficiency.

- Aim 2: Develop an architecture that integrates mesh networking with blockchain for secure, low-latency communication. The mesh network will handle local, rapid data exchanges, while the blockchain records key interactions for tamper-proof auditing and device tracking.

- Aim 3: Implement a hop-to-hop authentication mechanism within the mesh network using PUF-Based Secure Node Onboarding, allowing each node to verify the authenticity of its neighboring nodes. This hop-to-hop verification will enhance local network security and improve resilience against impersonation attacks

Targeted Applications: Supply chain management, smart homes, intelligent transportation systems, Agriculture IoT, environmental monitoring systems, and rural healthcare IoT networks.

Fortified Edge for Air-Ground Cross-Platform Networks:
======
<hr />
This research aims to develop a cross-platform "Fortified Edge" authentication system designed for air-ground coordination between airborne devices (such as UAVs and drones) and ground nodes.

- Aim 1: Develop a multi-layer authentication protocol combining PUFs and blockchain technology for secure interactions between airborne devices and ground nodes. This protocol dynamically adjusts security parameters based on environmental factors (e.g., altitude, speed) to ensure robust communication. 

- Aim 2: Design a session-based key exchange mechanism where UAVs and ground nodes generate unique encryption keys for each communication session. This approach provides end-toend encryption, reducing the risk of interception and data breaches.

- Aim 3: Introduce a time-sensitive authentication mechanism that adapts to the fast-changing dynamics of air-ground interactions, ensuring that communication links are secure without causing delays in mission-critical operations. 

Targeted Applications: Disaster management, smart agriculture, defense and surveillance systems, emergency response, and logistics involving UAVs, drones, and ground stations

PUF Behavior Monitoring and Adaptive Response System:
=====
<hr />
This research aims to enhance "Fortified Edge" by incorporating Generative Adversarial Networks (GANs) to detect glitch attacks on PUF circuits and propose a GAN-based software PUF to adapt the behavior of the PUF model.

- Aim 1: Create a database that stores the behavioral patterns of the PUFs, as monitored by the GAN model. This database will help in identifying potential anomalies and assist in threat intelligence.  

- Aim 2:  Use GANs to create a behavior model of the target PUF circuits under normal operating conditions. The generator network will simulate the legitimate responses of the PUF, while the discriminator distinguishes between genuine and manipulated (glitch-induced) responses.

- Aim 3: Propose a GAN-based framework to create a software PUF that simulates the behavior of a physical PUF. The generator in the GAN produces a virtual PUF response for a given challenge, while the discriminator ensures the generated responses exhibit the unpredictability and uniqueness typical
of hardware PUFs.

Targeted Applications: Secure IoT devices, hardware-based authentication systems, and environments requiring robust PUF integrity monitoring (e.g., smart cities, smart village, critical infrastructure security).


Fortified Edge with Post-Quantum Cryptography:
====
<hr />
This research plan aims to fortify edge networks against quantum computing threats by integrating post-quantum cryptographic algorithms with PUF-based authentication. By addressing key exchange, data privacy, and adaptive security, the proposed design seeks to provide a robust, quantum-resistant framework for securing edge devices in various high-risk IoT applications.

- Aim 1: Develop a hybrid authentication protocol that combines PUF-based mechanisms with post-quantum cryptographic algorithms (e.g., lattice-based, hash-based, and multivariate polynomial cryptosystems). This hybrid approach ensures resilience against quantum attacks while maintaining efficient authentication.
- Aim 2: Introduce a lightweight key exchange protocol using latticebased cryptography tailored for resource-constrained edge devices. This protocol will facilitate secure communication between edge devices without the computational overhead typically associated with quantumsafe algorithms.

- Aim 3: Modify the traditional PUF challenge-response mechanism to incorporate hash-based signatures for added protection. This aims to secure the PUF responses from quantum-powered brute-force attacks, enhancing the overall security of the edge network.  