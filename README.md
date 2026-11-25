# Fonno for Gemini CLI

[Fonno](https://fonno.no) is bookkeeping for Norwegian companies. With this extension Gemini CLI can read and post to your
books, send invoices and get the aksjonærregisteroppgave ready for Skatteetaten.

```sh
gemini extensions install https://github.com/NordserEng/fonno-gemini
```

The first time Gemini uses Fonno, your browser opens Fonno's sign-in. Sign in, choose the company, and approve. Then ask:

- "What does Fonno say is due this month?"
- "Book yesterday's 250 kr parking, paid from the bank account."
- "Get last year's aksjonærregisteroppgave ready and show me what changed."

The extension connects to `https://fonno.no/mcp`. Every tool is described at [fonno.no/claude](https://fonno.no/claude),
and the server is `no.fonno/fonno` in the [MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers?search=no.fonno/fonno).
Stuck? Write to kontakt@fonno.no.
