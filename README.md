<br/>
<div align="center">

A curated list of awesome .NET Security related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

_List inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing._

Supported by: [GuardRails.io](https://www.guardrails.io)

</div>
<br/>

# Contents
- [Tools](#tools)
- [Educational](#educational)
- [Companies](#companies)
- [Other](#other)

# Tools

## Libraries

- [.NET Core Security Headers](https://github.com/juunas11/aspnetcore-security-headers) - Middleware for adding security headers to an ASP.NET Core application.
- [NetEscapades.AspNetCore.SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) - Small package to allow adding security headers to ASP.NET Core websites.
- [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - Cleans HTML to avoid XSS attacks.
- [JWT .NET](https://github.com/jwt-dotnet/jwt) - Jwt.Net, a JWT (JSON Web Token) implementation for .NET.
- [NWebsec](https://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET.
- [AspNetSaml](https://github.com/jitbit/AspNetSaml) - SAML client library, allows adding SAML single-sign-on to your ASP.NET app.

## Static Code Analysis

- [Security Code Scan](https://github.com/security-code-scan/security-code-scan) - Vulnerability Patterns Detector for C# and VB.NET.
- [Puma Scan](https://github.com/pumasecurity/puma-scan) - Puma Scan is a .NET software secure code analysis tool providing real time, continuous source code analysis.
- [DevSkim](https://github.com/Microsoft/DevSkim) - DevSkim is a set of IDE plugins and rules that provide security "linting" capabilities.
- [SonarQube](https://github.com/SonarSource/sonar-dotnet) - SonarC# and SonarVB are static code analyser for C# and VB.​NET languages used as an extension for the SonarQube and SonarCloud platforms. It will allow you to produce stable and easily supported code by helping you to find and to correct bugs, vulnerabilities and smells in your code.

## Vulnerabilities and Security Advisories

- [RetireNET](https://github.com/RetireNet/dotnet-retire) - CLI extension to check your project for known vulnerabilities.
- [OWASP Dependency Check](https://github.com/jeremylong/DependencyCheck) - Detects publicly disclosed vulnerabilities in application dependencies.
  - [NuGet tool package](https://www.nuget.org/packages/DependencyCheck.Runner.Tool/) - Nuget tool package for OWASP Dependency Check
- [Audit.NET](https://github.com/OSSIndex/audit.net) - Identify known vulnerabilities in .net NuGet dependencies.
- [Snyk](https://github.com/snyk/snyk) - CLI and build-time tool to find & fix known vulnerabilities in open-source dependencies.
- [.NET Security Announcements](https://github.com/dotnet/announcements/issues?q=is%3Aopen+is%3Aissue+label%3ASecurity) - Watch this repo to receive security announcements in .NET Core
- [Snyk Vulnerability DB](https://snyk.io/vuln?type=nuget) - Commercial but free listing of known vulnerabilities in NuGet libraries.
- [Common Vulnerabilities and Exposures](https://www.cvedetails.com/product/42998/Microsoft-Asp.net-Core.html?vendor_id=26) - Vulnerabilities in .NET Core that were assigned a CVE.
- [National Vulnerability Database](https://nvd.nist.gov/vuln/search/results?form_type=Basic&results_type=overview&query=ASP.NET&queryType=phrase&search_type=all) - .NET related known vulnerabilities in the National Vulnerability Database.

# Educational

## Hacking Playgrounds

- [WebGoat.NET](https://github.com/jerryhoff/WebGoat.NET) - OWASP WebGoat.NET
- [Damn Vulnerable Thick Client App](https://github.com/secvulture/dvta) - DVTA is a Vulnerable Thick Client Application developed in C# .NET
- [ASP.NET Vulnerable Site](http://aspnet.testsparker.com) - Online .NET application that can be used to practice hacking.

## Articles, Guides & Talks

- [Anti-Request Forgery](https://docs.microsoft.com/en-us/aspnet/core/security/anti-request-forgery?view=aspnetcore-2.2) - Prevent Cross-Site Request Forgery (XSRF/CSRF) attacks.
- [Prevent Cross-Site Scripting](https://docs.microsoft.com/en-us/aspnet/core/security/cross-site-scripting?view=aspnetcore-2.2) - Prevent Cross-Site Scripting (XSS).
- [Protect Secrets in Development](https://docs.microsoft.com/en-us/aspnet/core/security/app-secrets?view=aspnetcore-2.2) - Safe storage of app secrets in development
- [.NET Security Cheat Sheet](https://www.owasp.org/index.php/.NET_Security_Cheat_Sheet) - Quick, basic .NET security tips for developers.
- [Hardening the security of your ASP.NET core apps](https://geeklearning.io/hardening-the-security-of-your-asp-net-core-apps/) - Lessons learned after a third-party penetration test.
- [Secure Coding Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/security/secure-coding-guidelines) - Microsoft's take on secure coding guidelines.
- [Security Headers](https://andrewlock.net/adding-default-security-headers-in-asp-net-core/) - Adding Default Security Headers in .NET Core.

# Other

## Reporting Bugs

- [Report a Security Issue](https://www.microsoft.com/en-us/msrc/faqs-report-an-issue)

## Contributing

Found an awesome project, package, article, or another type of resources related to .NET Security? Submit a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
