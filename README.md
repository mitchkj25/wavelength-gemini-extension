# Wavelength extension for Gemini CLI

Turn calls, notes, and code into editable process flow diagrams with [Wavelength](https://wavelengthflow.com), from the Gemini CLI.

## Install

```bash
gemini extensions install https://github.com/mitchkj25/wavelength-gemini-extension
```

Start `gemini`. The first Wavelength tool call opens a browser to sign in with your Wavelength account (OAuth). A free account works. You can also run `/mcp auth wavelength`.

## What it adds

- The hosted Wavelength MCP server at `https://wavelengthflow.com/api/mcp`.
- `GEMINI.md` context that tells Gemini when to use each Wavelength tool.
- Commands: `/wavelength:map <file or process>` and `/wavelength:export <flow name>`.

## Try it

- "Map src/checkout.js as a Wavelength flow."
- "Turn these call notes into a process flow: ..."
- "Export my Order checkout flow as Mermaid and add it to README.md."

## Privacy

Wavelength does not read your code. Gemini CLI reads it on your machine and sends only the flow to Wavelength. Each tool acts only as the signed-in user.

- Privacy policy: https://wavelengthflow.com/privacy.html
- Support: support@wavelengthflow.com

## License

MIT
