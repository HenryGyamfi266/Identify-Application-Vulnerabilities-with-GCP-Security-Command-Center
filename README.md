# Identify-Application-Vulnerabilities-with-GCP-Security-Command-Center
In this project, I utilized Google Cloud Platform's (GCP) Security Command Center, specifically Web Security Scanner, to secure a Python Flask application hosted on a Compute Engine instance by identifying and remediating common web vulnerabilities. I deployed a deliberately vulnerable web application and configured Web Security Scanner to crawl the application, simulating user inputs and exploring links to detect security issues.
The scanner automatically identified risks like cross-site scripting (XSS), Flash injection, mixed content, and outdated/insecure libraries. With a focus on application security and minimal false positives, I was able to efficiently locate and fix these vulnerabilities. Once remediations were applied, I re-ran the scan to confirm that no vulnerabilities remained.
This project provided a comprehensive understanding of GCP's web security tools, and the experience strengthened my ability to build and secure web infrastructures in a cloud environment, making it highly relevant to protecting small business applications from potential security threats.

# Objectives
In this Project, I perform the following tasks:
**Launch a vulnerable Python Flask application on a Compute Engine instance**
**Use Web Security Scanner to scan the application and find vulnerabilities**
**Fix the application vulnerability**
**Scan the application again and verify vulnerabilities no longer exist**

# Scenario
Cymbal Bank, a U.S. retail bank with over 2,000 branches nationwide, provides comprehensive debit and credit services on a secure payments platform.
Founded as Troxler in 1920, it was acquired by Cymbal Group in 1975 and has since focused on modernizing its customer experience both in branches and digitally, 
with an app introduced in 2014. With 42,000 employees, the bank reported $24 billion in revenue in 2019. Now, Cymbal Bank aims to develop a new banking application for corporate clients using Google Cloud technology. To ensure security, the CTO has tasked a Cloud Security Engineer with demonstrating Google Cloud’s Security Command Center to identify and mitigate application vulnerabilities.
**As a cloud security engineer, I will identify and remediate application vulnerabilities to ensure Cymbal bank's applications are secure from attack**
