# NewGPI API and SDK Examples

Status: Interface examples pending public API release

NewGPI has not documented a public production API or SDK in this repository. To avoid encouraging integrations against an unstable or unofficial interface, endpoint URLs, credentials and install commands will be added only after a versioned developer release.

## Planned example structure

When the public interface is released, this directory is expected to include:

```text
examples/
├── javascript/
│   ├── quickstart/
│   └── agent-workflow/
├── python/
│   ├── quickstart/
│   └── agent-workflow/
└── webhooks/
    └── verify-event/
```

## Release requirements

Every official example should include:

- A versioned SDK or API reference
- Environment-variable based credential handling
- Timeouts and error handling
- Input validation
- A minimal-permission example
- Clear test and production environment separation
- A link to the applicable privacy and security documentation

## Security warning

Never publish API keys, access tokens, private keys or production user data in a repository. NewGPI will not ask developers to commit credentials to source control.

