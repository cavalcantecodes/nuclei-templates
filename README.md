# Nuclei Templates
![Static Badge](https://img.shields.io/badge/This%20Repo%20Is%20A%20Work%20In%20Progress-orange)
![Static Badge](https://img.shields.io/badge/Custom-Nuceli%20Templates-99ccff)
![Static Badge](https://img.shields.io/badge/Built%20With-YAML-yellow)
![Static Badge](https://img.shields.io/badge/Author-CyberCavalcante-ccee00)
----
![Static Badge](https://img.shields.io/badge/Last%20Update-09/17/2023-ff0000)

## Description
![Static Badge](https://img.shields.io/badge/About%20This%20Repo.-33cc33)

This repository hosts a collection of custom Nuclei templates crafted meticulously for both web and network scanning. Whether you're assessing web application vulnerabilities or probing network services, these templates are designed to provide accurate and comprehensive results.

## 🌐 Web Templates
- **Exposed Gits**: Hunts for mistakenly exposed `.git` directories.
- **Potential Subdomain Takeover**: Detects subdomains vulnerable to takeover attacks.
- **Default Admin Creds**: Searches for login pages accepting default admin credentials.
- **Exposed ENV**: Identifies exposed environment files leaking sensitive data.
- **Unsecured Jira Panel**: Flags potentially unprotected Jira panels.
- **Apache STRUT Check**: Tests for vulnerabilities associated with Apache Struts.
- **Open Redirect**: Identifies open redirect vulnerabilities.
- **Subdomain Takeover**: Detects subdomains vulnerable to takeover attacks.
- **SQL Injection**: Identifies SQL injection vulnerabilities.
- **Reflected XSS**: Identifies reflected XSS vulnerabilities.


## 🖧 Network Templates
- **FTP Server Detection**: Identifies open FTP servers.
- **Exposed SMB**: Probes for the SMB protocol, commonly used for sharing files.
- **Common Port Scan**: Checks the availability of the most common ports.
- **Exposed RDP**: Identifies exposed RDP services.
- **MS SQL Server Without Password**: Identifies MS SQL servers without password.
- **Exposed Docker API**: Identifies exposed Docker APIs.
- **MongoDB Without Password**: Identifies MongoDB instances without password.
- **Elasicsearch Without Password**: Identifies Elasticsearch instances without password.
- **SMB Without Password**: Identifies SMB instances without password.
- **RDP Without Password**: Identifies RDP instances without password.
- **FTP Without Password**: Identifies FTP instances without password.
- **Memcached Without Password**: Identifies Memcached instances without password.
- **MS SQL Server Without Password**: Identifies MS SQL instances without password.
---
> **Note**: This repository is a work in progress. More templates will be added soon.


## Usage
![Static Badge](https://img.shields.io/badge/Usage-ff6600)
![Static Badge](https://img.shields.io/badge/Must-Have%20Nuclei%20Installed-green)

```bash
nuclei -t <folder-name>/<template-name.yaml> -u <target-url>
```

For network templates:

```bash
nuclei -t <folder-name>/<template-name.yaml> -target <ip-address>
```

## 🛡️ Recommendations

For efficient and smooth execution:
- Ensure Nuclei is updated to its latest version.
- Regularly pull from this repo to get the latest templates.
- Always ensure you have proper authorization before testing against any target.

## 🔍 Disclaimer

![Static Badge](https://img.shields.io/badge/Important-Notice-red)

These templates are intended for educational and professional use cases. Always ensure that you have proper authorization before scanning a target. Unauthorized scanning can lead to legal and ethical issues.


## 🖥️ Resources
- [Nuclei Official Documentation](https://nuclei.projectdiscovery.io/)
- [Guide to Nuclei Templating](./TemplateGuide.md)
