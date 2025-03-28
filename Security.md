#  Security and Secure Coding Practices

##  Introduction

Security isn't just a final step — it's a mindset. Writing secure code means actively defending against threats, protecting user data, and building trust. In a fast-paced development environment, it’s easy to prioritize speed over safety, but even small mistakes can lead to major vulnerabilities.

This section outlines how we build secure software from the start, and the most common security flaws developers should avoid.

---

##  Building Secure Software from Day One

To “build security in,” we focus on integrating security into every stage of the software development lifecycle — not just at the end.

Here’s how we do that:

- **Threat modeling early**: Understand what attackers could exploit and how your feature could be misused
- **Secure defaults**: Disable features unless explicitly needed (e.g. file uploads, APIs, open ports)
- **Static analysis tools**: Use automated scanners to detect security issues during development
- **Security-focused code reviews**: Review code with a security checklist in mind
- **Least privilege principle**: Limit access, permissions, and trust boundaries in the system
- **Use secure libraries and frameworks**: Favor well-maintained packages with good security track records
- **Fail securely**: Plan for what happens when things go wrong — handle exceptions, validate inputs, and never expose stack traces in production

---

##  Common Vulnerabilities to Avoid

These are some of the most common — and dangerous — security issues that developers must avoid. Most of them appear regularly in the [OWASP Top 10](https://owasp.org/www-project-top-ten/).

- ** SQL Injection (SQLi)**  
  Failing to properly sanitize user input can allow attackers to execute malicious database queries.

- ** Cross-Site Scripting (XSS)**  
  Allowing users to inject scripts (e.g., in forms, comments) which are then executed by other users.

- ** Broken Authentication**  
  Poorly implemented login systems, token handling, or session management that allows attackers to impersonate users.

- ** Insecure File Uploads**  
  Accepting uploaded files without checking type, size, and content — leading to remote code execution or malware.

- ** Hardcoded Secrets**  
  Including API keys, passwords, or tokens in source code or config files.

- ** Using Outdated or Vulnerable Dependencies**  
  Not updating packages or using libraries with known security issues.

- ** Insufficient Input Validation**  
  Trusting user input too much can lead to logic flaws, data leaks, or crashes.

- ** Excessive Error Details in Production**  
  Displaying full stack traces or error messages that reveal system details or paths.

Avoiding these flaws doesn't require perfection — it requires awareness, good habits, and a checklist-driven mindset.

