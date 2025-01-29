Purpose

This POC scripts to demonstrate the risk of dependency confusion attacks. By mimicking these scenarios in authorized environments, security teams can identify and remediate such vulnerabilities in their systems.

What is Dependency Confusion?
Dependency confusion happens when a malicious package with a name matching an internal dependency is uploaded to a public repository (e.g. npm, PyPI). This can trick systems into downloading the malicious package instead of the private one, leading to potential compromise.
