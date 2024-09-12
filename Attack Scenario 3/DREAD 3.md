# DREAD Threat Model

This Mermaid diagram illustrates the DREAD model applied to a SQL injection attack on the Medway health application. Here's a breakdown of the diagram:

The DREAD model components are shown: Damage Potential, Reproducibility, Exploitability, Affected Users, and Discoverability. Each component is linked to the SQL Injection attack on the Medway Health App.
Each DREAD component is assigned a score based on the severity of the SQL injection attack:

Damage Potential: High (9) due to potential access to sensitive patient data

Reproducibility: Easy (8) as SQL injection can often be reproduced consistently

Exploitability: Moderate (6) assuming some security measures are in place

Affected Users: Many (8) as it could affect a large number of patients

Discoverability: Easy (7) as SQL injection vulnerabilities are well-known

The Risk Calculation subgraph shows the final risk score, calculated as the average of the five DREAD components.
Different colours are used to distinguish between the DREAD components, the attack, the scores, and the final calculation.

This diagram provides a clear visual representation of how the DREAD model is applied to assess the risk of a SQL injection attack on the Medway health application.


![DREAD 3-2024-09-12-160311](https://github.com/user-attachments/assets/ad14adb7-457c-4f66-a903-9cb9fc5170a9)
