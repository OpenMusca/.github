# Security policy (OpenMusca organisation default)

OpenMusca firmware controls a device that dispenses food and sits on your home network, so security problems matter
beyond the usual. Thank you for reporting them responsibly.

Do **not** open a public issue for a security problem. In the affected repository, open the "Security" tab and use
"Report a vulnerability" (GitHub private vulnerability reporting). Include what you found, the version, how to
reproduce it and the impact. Do not include Wi-Fi credentials, MQTT passwords, flash dumps or device identifiers;
redact them.

What to expect: an acknowledgement within a week, a fix or a mitigation plan as soon as it is understood, and credit in
the release notes if you want it. Please give us reasonable time to fix before you disclose. There is no bug bounty.
Only the latest release is supported; the project is pre-1.0.

The threat model (trusted home network only, never expose to the internet) and a hardening checklist for users are in
the project documentation: https://openmusca.github.io/security/
