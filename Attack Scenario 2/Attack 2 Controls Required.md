# Controls Required:

Here are the key security controls required to prevent such a DDoS attack:

Network Segmentation: Separate and distribute assets within the network, placing web servers in a public subnet and database servers in a private subnet .

Geographical Restrictions: Limit traffic to specific countries where legitimate users are located .

Load Balancer Protection: Utilise load balancers to distribute incoming traffic evenly and protect against attacks targeting specific servers .

Clean Application/Website: Remove unnecessary services, features, or legacy systems to reduce the attack surface .

Traffic Filtering: Implement Web Application Firewalls (WAF) to identify and block malicious traffic .

Rate Limiting: Throttle traffic volume to prevent suspicious surges that may indicate a DDoS attack .

IP Filtering: Block traffic from known malicious IP addresses or network ranges .

Blackholing: Route attack traffic to a null address, effectively dropping it before it reaches the target .

Scrubbing Centers: Analyse traffic and filter out malicious elements before delivering legitimate traffic to the target server .

Bot Mitigation Techniques: Use challenges like CAPTCHAs or device fingerprinting to distinguish legitimate users from bots .

Content Delivery Networks (CDNs): Distribute traffic across geographically dispersed servers to make it harder for attackers to overwhelm a single location .

Continuous Monitoring and Analysis: Regularly monitor network traffic for suspicious activity to detect potential attacks early .

DDoS Prevention and Simulation Solutions: Employ various mitigation techniques and test the resilience of your infrastructure .

Managed Detection and Response (MDR) Services: Enable early detection of suspicious activity for swift response .

Plan for Scale: Ensure adequate bandwidth capacity and server capacity to absorb and mitigate large-scale attacks .

Know Normal and Abnormal Traffic: Understand the characteristics of legitimate traffic to better identify and mitigate malicious traffic .

Sinkholing: Divert traffic from identified malicious IP addresses .

Multi-Factor Authentication (MFA): Make it more difficult for attackers to use stolen credentials .

Email Filtering: Detect and filter out phishing emails that could lead to compromised systems used in DDoS attacks .

Security Awareness Training: Educate employees about the risks of phishing and other social engineering tactics that could lead to system compromises .


By implementing these security controls, the Medway health application can significantly improve its resilience against DDoS attacks and better protect its critical services and patient data.
