# Project Summary



This project covers a distinct approach to Threat Modelling for an application for a healthcare organisation.

Threat modelling diagrams/models should reside within the repos of projects. This approach ensures teams understand the threats to the applications and continue to own it.



# Threat Modelling Workshop Summary



## Introduction

We held a 3-hour threat modelling workshop to detail the runbook scenario of multiple AI attacks against the web-facing health care application Medway Care Connect 360.



## Attendees

Medway Care Connect Engineering team, Product Managers, DevEx Engineers and the DevSecOps Team.



## Scope

We ran 4 scenarios covering: (1) AI Generated External phishing email utilising admin credentials, (2) Attack against Machine Processes and the data lake, (3) SQL Injection attack and (4) Insider attack taking Quant algorithms.



## Methodology

All scenarios were run against the cyber attack kill chain, utilising the Mitre Att&ack framework and STRIDE for control gap assessments, culminating in identified risks. 



## Conclusion

A total of 4 high risks and 1 medium risks were found during the threat modelling workshop.



## Controls Required



- Regular security audits using ASVS specifically targeting the Medway Health 360 application to detect vulnerabilities and weaknesses in its security measures.

- Patch management to ensure the Medway Health 360 application and its underlying technologies are up-to-date and protected against known vulnerabilities.

- Comprehensive employee training on phishing awareness to educate users of the Medway Health 360 application about the risks of phishing attacks, how to identify them and report suspicious emails.

- Implementation of a Web Application Firewall (WAF) tailored to the Medway Health 360 application's traffic to monitor and filter incoming requests for malicious activity.

- Deployment of Multi-factor Authentication (MFA) to enhance authentication security and prevent unauthorised access to the Medway Health 360 application.

- Continuous network traffic monitoring to detect and respond to suspicious activity within the Medway Health 360 application's infrastructure.

- Implementation of Role-Based Access Control (RBAC) within the Medway Health 360 application to limit access to sensitive health data and functionalities based on user roles and permissions.



# Threat Modelling Process Summary



![Threat Modelling Process Summary-2024-09-07-152103](https://github.com/user-attachments/assets/96f1e840-ccba-42e0-bf29-747c575273b0)
  
