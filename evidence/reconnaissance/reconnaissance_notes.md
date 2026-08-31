# Manual Reconnaissance Notes

## Target

- URL: https://demo.testfire.net/
- Application: Altoro Mutual
- Owner: HCL Software
- Assessment type: Read-only public-page review

## Initial Observations

- The website was reachable over HTTPS.
- Firefox displayed a certificate warning before access.
- The website presented itself as an online banking demonstration application.
- Public navigation and an online-banking login form were visible.
- No credentials were entered.
- No forms were submitted.
- No payloads or exploitation attempts were used.
- Normal navigation was limited to publicly linked pages.

## Publicly Visible Features

- Homepage
- Public navigation menu
- Online banking sign-in form
- Banking product information
- Contact or feedback functionality

## Items Requiring Later Verification

- TLS certificate validity
- HTTP-to-HTTPS behaviour
- Security response headers
- Cookie security attributes
- Server-information disclosure
- Passive OWASP ZAP alerts

## Evidence

- `02_target_homepage.png`
- `03_public_login_page.png`
