# Kamailio SIP Server - Security Policy

## Supported Versions

The latest two stable branches are supported. Older versions may get patches from time to time (e.g., 5.8/5.7),
but you have to maintain the installation from git repository, because packages are built only for last two stable branches.

| Version | Supported            |
| ------- | -------------------- |
| 6.1.x   | :white_check_mark:   |
| 6.0.x   | :white_check_mark:   |
| 5.8.x   | :question: (limited) |
| 5.7.x   | :question: (limited) |
| < 5.7   | :x:                  |

## Reporting A Vulnerability

If you believe there's a security vulnerability, please don't use the public forums. Submiting using the form 
`[Report a vulnerability](https://github.com/kamailio-security/reports/security/advisories/new)` linked on upper right corner at:

- https://github.com/kamailio-security/reports/security

The report will be reviewed by the Kamailio security team and appropriate actions will be taken.

The report should include the following information

- A summary
- If the issue was discovered by running Kamailio in production or by code analysis with AI or other tools
- A detailed explanation of how this issue can be exploited and/or reproduced

### After The Report

- A member of the Kamailio Security Team will respond
- The kamailio developer team will work to solve the issue.
- When there is a patch for the issue, it should NOT be committed directly without clarification with the security team. In many cases this should be coordinated with the release of a security release as well as the publication of a Kamailio project security vulnerability report.

## Publishing Security Vulnerabilities

Kamailio will publish security vulnerabilities, including an CVE ID, on the kamailio-business mailing list, sr-dev, sr-users as well as related lists. The advisories will also be published on the kamailio.org web site and the Kamailio github repository. This will be done for vulnerabilities that have a higher severity, that means having a big enough impact as decided from the Kamailio Security Team.

CVE entries should be created for critical vulnerabilities in the core and major modules, for rarely used modules this is not necessary. If there are several security issues together in one release, they should be announced together.

The Kamailio project release security fixed in the normal time based maintenance schedule, no immediate security releases are done. If possible a non-code workaround should be provided for the found security vulnerability.

## Timeline Of The Security Process

1. Initial acknowledge time to the reporting party for a report about a new security issue for a new report: 3 working days
2. Time for verification and bug fix from Kamailio development: 5 working days (could be extended e.g. in vacation period)
3. Waiting time for public announcement after the fix is in an official release: 90 days
4. Project preparation time for kamailio.org announcement: 3 working days

## Kamailio Security Team

A Kamailio Security team is appointed with core developers of the project. These individuals will be part of the security process and review patches and text for the vulnerability report. Persons of this group take the role of Kamailio Security Officers. One of these should manage each security incident - which does not mean solving the code issue, but managing the process from report to publication and patch release.

Members of Kamailio Security Team are volunteers, not paid for the work they do in this scope. Everyone should conduct decent conversations, keep the expectations and the demands within reasonable.

