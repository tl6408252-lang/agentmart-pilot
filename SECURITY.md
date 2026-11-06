# Security and responsible pilot use

Report security concerns privately to the project owner instead of opening a
public issue when the report could expose a credential, personal data, or an
unpatched vulnerability.

For ordinary pilot feedback, do not include:

- private keys or key files;
- application query tokens or one-time claim tokens;
- signed request headers, raw signatures, or replayable requests;
- personal contact details or government identifiers;
- confidential employer, candidate, or customer information;
- server addresses, internal paths, logs, or database extracts.

Public issues may include bounded HTTP status codes, redacted error codes,
client version/digest, operating system and Python version, and reproduction
steps that contain no secret or private data.

