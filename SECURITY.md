# Security Policy

GeoSolutions maintainers take security vulnerabilities seriously.
Please do not report suspected security vulnerabilities through public GitHub issues, public pull requests, public discussions, mailing lists, or other public channels.

This is the default security policy for public repositories in the [geosolutions-it](https://github.com/geosolutions-it) organization.
If a repository has its own `SECURITY.md` (for example [MapStore](https://github.com/geosolutions-it/MapStore2/blob/master/SECURITY.md)), that policy takes precedence.

If the repository is a fork of an upstream open source project (for example GeoServer, GeoTools, or GeoNode), vulnerabilities in the upstream code should be reported to the upstream project, following its own security policy.

## Supported versions

Unless the repository states otherwise, security fixes are prepared only for the latest release, or for the default branch when the repository has no releases.

Users running older versions are encouraged to upgrade. If your organization requires security fixes for an older version, please contact GeoSolutions or your support provider to discuss feasibility.

## Reporting a vulnerability

Please report suspected vulnerabilities privately using one of the following channels.

### GitHub private vulnerability reporting

When enabled on the repository, open the repository's "Security" tab and select "Report a vulnerability".

This is the preferred channel when available, because it allows maintainers and the reporter to coordinate privately, prepare a fix, request or associate a CVE where appropriate, and publish a GitHub Security Advisory after release.

### Email

If GitHub private vulnerability reporting is not available, or if email is more appropriate, contact:

[infosec@geosolutionsgroup.com](mailto:infosec@geosolutionsgroup.com)

Please include as much of the following information as possible:

* affected repository, version, release, commit, or deployment profile;
* affected component, endpoint, or configuration;
* steps to reproduce the issue;
* proof-of-concept details, preferably against a local or test instance;
* expected and actual behavior;
* potential impact;
* whether the issue has already been disclosed to anyone else;
* whether you would like public credit in the advisory.

Please do not test against third-party systems or production deployments unless you have explicit authorization.

## Coordinated vulnerability disclosure

GeoSolutions follows a coordinated vulnerability disclosure process.

1. The report is received through a private channel.
2. The maintainers acknowledge receipt, normally within 5 business days.
3. The maintainers privately verify the vulnerability and assess severity, impact, affected versions, and exploitability.
4. If the report is valid, the maintainers prepare a fix and mitigation guidance where applicable.
5. A GitHub Security Advisory may be used to coordinate the fix, request or associate a CVE, credit the reporter, and prepare public advisory text.
6. Fixed releases are published before exploit details are disclosed publicly, unless the vulnerability is already public or actively exploited.
7. The advisory is published with affected versions, fixed versions, severity, mitigation or workaround instructions, and upgrade guidance.

We ask reporters to keep vulnerability details private until a fixed release and advisory are available. If public disclosure is required for external reasons, please coordinate the timing with the maintainers whenever possible.

## Scope

This policy covers vulnerabilities in the source code, default configurations, official build artifacts, and official documentation of the repository, where the documentation causes an insecure deployment pattern.

Issues in third-party dependencies may be reported if they materially affect users of the repository, but they may also need to be coordinated with the upstream dependency maintainers.

Deployments operated by third parties are out of scope for this policy. GeoSolutions support customers should report issues affecting their own installations to [infosec@geosolutionsgroup.com](mailto:infosec@geosolutionsgroup.com).

## Safe harbor

We will not pursue legal action against security researchers who make a good-faith effort to comply with this policy, avoid privacy violations, avoid service disruption, avoid data destruction, and report vulnerabilities privately.
