# FUTURE_CS_01 - Vulnerability Assessment Report

## Task Overview
This repository contains my completed **Task 1** for the Future Interns Cyber Security program.

## Assignment
Perform a vulnerability assessment on a live website and create a professional report documenting findings, risks, and remediation recommendations.

## Target Website
`http://testphp.vulnweb.com` - A deliberately vulnerable test application by Acunetix

## Tools Used
- **OWASP ZAP** - Web application vulnerability scanning
- **Browser Developer Tools** - Manual testing and verification

## Key Findings

| Risk Level | Vulnerability | Location |
|------------|---------------|----------|
| HIGH | SQL Injection | `listproducts.php?cat=1` |
| HIGH | Default Admin Credentials | `/admin/` (test:test) |
| MEDIUM | Exposed CVS Directory | `/CVS/` |
| MEDIUM | Missing CSRF Tokens | Multiple forms |
| MEDIUM | CSP Header not set | HTTP Response Headers |

## Files Included
- `Vulnerability_Assessment_Report.pdf` - Complete professional report
- Screenshot images showing evidence of each finding

## Assessment Date
February 21, 2026

## Submitted By
Grace Wambui
Cyber Security Intern - Future Interns
