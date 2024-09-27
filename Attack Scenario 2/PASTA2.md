# PASTA Threat Model


This Mermaid diagram illustrates the PASTA (Process for Attack Simulation and Threat Analysis) model applied to a DDoS attack on the Medway health application. It follows the seven stages of the PASTA methodology:

Define Objectives: The primary objective is to ensure the availability of health services.

Define Technical Scope: This includes Web Application Servers, Network Infrastructure, and Database Servers.

Decompose Application: The application is broken down into Load Balancers, Application Servers, Database Clusters, and Network Firewalls.

Analyse Threats: The main threats identified are Volumetric DDoS, Application Layer DDoS, and Protocol DDoS.

Vulnerability Analysis: Potential vulnerabilities include Insufficient Network Capacity, Lack of DDoS Mitigation, and Unpatched Systems.

Attack Modelling: Possible attack vectors include Botnet Traffic Flood, Slowloris Attack, SYN Flood, and DNS Amplification.

Risk Impact Analysis: The potential impacts are Service Unavailability, Patient Care Disruption, Reputational Damage, and Financial Loss.

The diagram shows the flow from objectives to technical scope, application decomposition, threats, vulnerabilities, attack modelling, and finally to risk and impact analysis. This structured approach helps in systematically identifying and addressing potential security issues related to DDoS attacks on the Medway health application.


![PASTA 2-2024-09-27-132431](https://github.com/user-attachments/assets/22b94aaa-de97-43ac-9f00-c91bb66b436f)
