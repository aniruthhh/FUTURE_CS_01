# References

The following official resources were consulted while defining the assessment scope, interpreting findings and preparing remediation recommendations.

Accessed: 31 August 2026

## Assessment Target

### HCL Altoro Mutual

- Application: Altoro Mutual / AltoroJ
- Purpose: Demonstration application for testing web-application security products
- URL: https://demo.testfire.net/

### HCL Software Support

- Resource: Demo websites for testing AppScan products
- URL: https://support.hcl-software.com/csm?id=kb_article&sysparm_article=KB0010981

## OWASP ZAP

### OWASP ZAP Passive Scanner

- Purpose: Explanation of passive scanning and its safety characteristics
- URL: https://www.zaproxy.org/docs/desktop/addons/passive-scanner/

### OWASP ZAP Getting Started

- Purpose: Guidance for proxying browser traffic and using passive analysis
- URL: https://www.zaproxy.org/getting-started/

### OWASP ZAP Alert Details

- Purpose: Descriptions of passive and active alert rules
- URL: https://www.zaproxy.org/docs/alerts/

### OWASP ZAP Report Generation

- Purpose: Generation and filtering of ZAP assessment reports
- URL: https://www.zaproxy.org/docs/desktop/addons/report-generation/

## Nmap

### Nmap Legal Issues

- Purpose: Authorisation, scope and responsible-use guidance
- URL: https://nmap.org/book/legal-issues.html

### Nmap Reference Guide

- Purpose: Nmap options and output interpretation
- URL: https://nmap.org/book/man.html

## Transport Security

### OWASP Transport Layer Security Cheat Sheet

- Purpose: HTTPS and TLS deployment recommendations
- URL: https://cheatsheetseries.owasp.org/cheatsheets/Transport_Layer_Security_Cheat_Sheet.html

### CWE-319: Cleartext Transmission of Sensitive Information

- Purpose: Classification of sensitive information transmitted without encryption
- URL: https://cwe.mitre.org/data/definitions/319.html

### Mozilla HTTP Strict Transport Security

- Purpose: Guidance on enforcing HTTPS through HSTS
- URL: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Strict-Transport-Security

## Browser Security Headers

### Mozilla Content Security Policy

- Purpose: CSP syntax, behaviour and deployment guidance
- URL: https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP

### Mozilla X-Frame-Options

- Purpose: Browser protection against framing and clickjacking
- URL: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options

### Mozilla X-Content-Type-Options

- Purpose: Prevention of browser MIME-type sniffing
- URL: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Content-Type-Options

## Cookie Security

### Mozilla Set-Cookie

- Purpose: `Secure`, `HttpOnly` and `SameSite` cookie attributes
- URL: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie

### OWASP Session Management Cheat Sheet

- Purpose: Secure creation, transport and protection of session cookies
- URL: https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html

## CSRF Protection

### OWASP Cross-Site Request Forgery Prevention Cheat Sheet

- Purpose: Anti-CSRF tokens, SameSite cookies and server-side request validation
- URL: https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html

### CWE-352: Cross-Site Request Forgery

- Purpose: CSRF weakness classification
- URL: https://cwe.mitre.org/data/definitions/352.html

## Tools

### curl

- Purpose: Retrieval and inspection of HTTP response headers
- URL: https://curl.se/docs/manpage.html

### OpenSSL

- Purpose: TLS certificate inspection
- URL: https://docs.openssl.org/

## Ethical Measures

- Testing was limited to an intentionally vulnerable demonstration application.
- Only ports 80 and 443 were checked using Nmap.
- OWASP ZAP was operated in Safe Mode.
- Only passive ZAP alerts were collected.
- No credentials were entered or submitted.
- No vulnerability payloads were used.
- No exploitation, brute force, active scanning or denial-of-service activity was performed.
- Temporary session-cookie values were excluded or redacted from public evidence.
