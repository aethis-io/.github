# Aethis

Govern AI agents before they act.

Aethis is an AI-agent governance platform for policy checks, human approvals, and Action Records on supported model and tool calls.

## How it works

Point your MCP-compatible agent at an Aethis MCP server URL on mcp.aethis.io. Aethis governs each call and forwards it to your existing MCP server. No SDK is required.

For each call, your policy returns one of three decisions: Allow, Require Approval, or Block. A call that needs approval waits in the Approval Queue, where a reviewer can Approve Once or Deny.

Every governed call gets an Action Record. It connects the request, the policy decision, any approval, and the outcome.

Aethis only governs calls that are routed through it.

Aethis is in early access.

## Read more

- [Website](https://aethis.io)
- [Docs](https://aethis.io/docs)
- [Quickstart](https://aethis.io/docs/quickstart)
- [What an MCP gateway is, and when you need one](https://aethis.io/blog/what-is-an-mcp-gateway)
- [Security](https://aethis.io/security)
- [Join the waitlist](https://aethis.io/waitlist)

## Contact

[hello@aethis.io](mailto:hello@aethis.io) or [LinkedIn](https://www.linkedin.com/company/aethis-io/)
