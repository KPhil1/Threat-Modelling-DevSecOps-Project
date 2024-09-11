# Attack 3 Summary: SQL Injection

## Stages of the Attack

### Origins
The attack is initiated by a threat actor leveraging a long history of cyber attack techniques. The attacker identifies the Medway Health 360 application as a target due to its sensitive health data and public-facing nature.

### Reconnaissance
The attacker conducts research to identify vulnerabilities in the Medway Health 360 application. This includes gathering information about the Medway Health application's web interface, analysing the application's structure and potential database backend, and identifying potential entry points for SQL injection, such as login forms, search fields, or URL parameters.  

### Weaponisation
The attacker creates malicious SQL queries designed to exploit vulnerabilities in the Medway Health 360 application. The attacker prepares payloads that can bypass input validation and sanitisation measures. They develop scripts or tools to automate the injection process. 

### Delivery
The attacker submits the malicious SQL queries through the identified entry points. This could involve entering crafted inputs into form fields or manipulating URL parameters, using techniques like URL encoding to bypass simple filters.

### Exploitation
The malicious SQL query is executed by the Medway Health 360 application's database. The attacker exploits vulnerabilities such as insufficient input validation or lack of parameterised queries, and manipulates the database query to return unintended results or execute unauthorised commands.

### Installation
Once access is gained, the attacker establishes a foothold within the Medway Health 360 application's infrastructure. This may involve creating backdoor accounts or implanting malware to maintain persistent access to the system. This could involve creating new database users with elevated privileges. The attacker might modify existing database structures to maintain persistent access.

### Command and Control
The attacker establishes a means of remote control over the compromised database. This might involve creating stored procedures or triggers that respond to specific inputs. The attacker sets up data exfiltration channels to retrieve sensitive information.

### Actions on Objectives
With access to the Medway Health 360 application, the attacker can exfiltrate sensitive health data stored within the application's database. Additionally, the attacker may manipulate patient records, tamper with medical information, disrupt the application's functionality for malicious purposes, or use the compromised database as a pivot point to attack other connected systems.
