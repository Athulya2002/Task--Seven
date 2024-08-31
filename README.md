# Task--Seven
Metasploitable VM scanning and reporting

This directory contains the results of various scanning and banner-grabbing tasks performed on a Metasploitable VM. The tasks include an OpenVAS vulnerability scan, a Nikto web server scan, and a banner grab using Netcat.

CONTENTS 

metasploitable_nikto_report.html: An HTML report generated by Nikto, detailing the web server vulnerabilities on the Metasploitable VM.
metasploitable_openvas_report.pdf: A comprehensive vulnerability assessment report generated by OpenVAS.
nc_metasploitable.png: A screenshot capturing the banner information retrieved from one of the open ports on the Metasploitable VM using Netcat.

TASK DESCRIPTIONS

1. Nikto Web Server Scan and HTML Report
Description: Nikto was used to scan the web server running on the Metasploitable VM. This scan focused on identifying outdated software, misconfigurations, and other security issues. The results were saved in an HTML format.
File: metasploitable_nikto_report.html
2. OpenVAS Scan and Report
Description: An OpenVAS scan was conducted on the Metasploitable VM to identify vulnerabilities across various services and applications. The results were compiled into a PDF report.
File: metasploitable_openvas_report.pdf
3. Banner Grabbing Using Netcat
Description: Netcat was utilized to grab the banner information from a specific port on the Metasploitable VM, helping to identify the service running on that port. The output was captured and saved as a screenshot.
File: nc scan.png

NOTES

Ensure that all tools (OpenVAS, Nikto, Netcat) are properly installed and configured on your Kali Linux or equivalent penetration testing environment.
The Metasploitable VM should be used in a controlled, isolated environment to prevent unintended consequences.
