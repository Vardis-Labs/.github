# Security Policy

Security and privacy are core requirements for Vartari Labs projects, especially where software interacts with local AI models, MCP servers, credentials, tunnels, or private user data.

## Reporting a vulnerability

Please do not publish security vulnerabilities in a public issue.

Report suspected vulnerabilities privately to the maintainers through GitHub's private vulnerability reporting feature when it is enabled for the affected repository.

Include, when possible:

- the affected repository and version,
- a clear description of the issue,
- steps to reproduce it,
- the potential impact,
- suggested mitigation,
- relevant logs or screenshots with secrets removed.

## Sensitive information

Never include the following in an issue, pull request, log, or screenshot:

- API keys and access tokens,
- MCP authentication keys,
- Cloudflare credentials,
- private model or dataset URLs,
- passwords or session cookies,
- personal or customer data,
- unredacted environment files.

## Supported versions

Support policies are defined separately by each product repository. During early development, only the latest release or current `main` branch may receive security fixes.

## Response process

We will review valid reports, assess severity, prepare a fix, and coordinate disclosure where appropriate. Response times may vary while projects remain independently maintained.
