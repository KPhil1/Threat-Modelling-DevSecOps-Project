# DREAD Threat Model

This Mermaid diagram illustrates the DREAD model applied to a DDoS attack on the Medway health application. Here's a breakdown of the diagram:

The central node represents the DDoS attack on the Medway health application.

The DREAD model components are shown: Damage Potential, Reproducibility, Exploitability, Affected Users, and Discoverability.

Each DREAD component is assigned a score based on the severity of the DDoS attack:

Damage Potential: High (9) due to potential service disruption

Reproducibility: High (10) as DDoS attacks are easily reproducible

Exploitability: Medium (6) as it requires some resources and coordination

Affected Users: High (10) as it impacts all users of the application

Discoverability: High (8) as DDoS vulnerabilities are well-known

The Risk Calculation subgraph shows the final risk score, calculated as the average of the five DREAD components.

The Attack Details subgraph provides additional information about the nature of the DDoS attack.

Different colours are used to distinguish between the DREAD components, the attack, the scores, the final calculation, and the attack details.

This diagram provides a clear visual representation of how the DREAD model is applied to assess the risk of a DDoS attack targeting the Medway health application. 



![DREAD2-2024-09-27-131622](https://github.com/user-attachments/assets/20c71ec7-0ed2-4512-8df4-e034e9eb40ff)
