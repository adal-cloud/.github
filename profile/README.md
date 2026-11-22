# Adal Cloud — Webhook Delivery & HTTP Tunnels

Adal Cloud helps developers receive and inspect webhooks, deliver them to local applications or remote HTTP endpoints, send outgoing HTTP requests with retries, and expose local HTTP services through public HTTPS URLs.

[Website](https://adal.cloud) · [Documentation](https://adal.cloud/en/docs) · [Dashboard](https://dashboard.adal.cloud) · [Try Go without signing up](https://go.adal.cloud)

## What you can do

- **Inbound webhooks:** receive requests at a public URL, inspect captured HTTP data, and route deliveries to remote endpoints or local applications through Adal CLI.
- **Outgoing HTTP requests:** submit HTTP jobs through the API and inspect execution results and delivery attempts.
- **HTTP Tunnels:** connect a local HTTP service to a public HTTPS address through Adal CLI for integration testing and development.
- **MCP integration:** connect AI assistants through Model Context Protocol to inspect Inbound webhook history and saved HTTP data, and create, update, or delete Inbound Servers. See the [MCP quickstart](https://adal.cloud/en/docs/mcp/quickstart).
- **Adal Cloud Go:** get a temporary webhook URL and inspect incoming requests in your browser for free, without creating an account.

## Get started

1. **Inspect a webhook in your browser:** open [Adal Cloud Go](https://go.adal.cloud), select **Get URL**, and send a test request to the generated address.
2. **Build an integration:** follow the [developer documentation](https://adal.cloud/en/docs) for Inbound, Outbound, and HTTP Tunnels.
3. **Connect a local application:** download [Adal CLI](https://github.com/adal-cloud/adal-cli) for Windows, macOS, or Linux and follow the [CLI setup guide](https://adal.cloud/en/docs/inbound/adal-cli).
4. **Work from an AI assistant:** follow the [MCP connection guide](https://adal.cloud/en/docs/mcp/quickstart) to connect your Adal Cloud account.

## Open-source client

[**adal-cli**](https://github.com/adal-cloud/adal-cli) is the MIT-licensed command-line client for Inbound webhook delivery and HTTP Tunnels. It connects to the Adal Cloud service; the client repository is not a self-hosted distribution of the cloud platform.

## Contact

Questions about the service? Email [hello@adal.cloud](mailto:hello@adal.cloud).

Follow product updates on [X / Twitter](https://x.com/adalcloud).
