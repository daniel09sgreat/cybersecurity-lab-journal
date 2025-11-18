# Lab 2: Web Application Security with Burp Suite

## Objective
Learn how to intercept and analyze HTTP requests using Burp Suite to identify vulnerabilities in web applications.

## Tools Used
- Kali Linux
- Burp Suite
- Firefox (configured with Burp proxy)

## Steps
1. Launch Burp Suite on Kali Linux.
2. Configure Firefox to use Burp as a proxy:
   - Proxy settings: 127.0.0.1:8080
3. Visit a vulnerable web application (e.g., DVWA or Juice Shop).
4. Intercept HTTP requests and analyze parameters.
5. Test for common vulnerabilities:
   - SQL Injection
   - Cross-Site Scripting (XSS)

## Findings
- Discovered input fields vulnerable to XSS.
- Observed insecure cookies without `HttpOnly` flag.

## Screenshot
../screenshots/lab2-burp-intercept.png

## References
- https://portswigger.net/burp/documentation
- https://owasp.org/www-project-top-ten/
