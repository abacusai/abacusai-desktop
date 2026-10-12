<div align="center">

<a href="https://desktop.abacus.ai/"><img src="assets/logo.png" alt="Abacus AI logo" width="88" height="88"></a>

# Abacus AI Agent

**A coding agent that works with any model, in VS Code, your terminal and the desktop app.**

<a href="https://marketplace.visualstudio.com/items?itemName=abacusai.abacusai-agent"><img src="https://vsmarketplacebadges.dev/version-short/abacusai.abacusai-agent.svg?label=VS%20Marketplace&color=2488FF" alt="VS Marketplace version"></a> <a href="https://open-vsx.org/extension/abacusai/abacusai-agent"><img src="https://img.shields.io/open-vsx/v/abacusai/abacusai-agent?label=Open%20VSX&color=2488FF" alt="Open VSX version"></a> <a href="https://www.npmjs.com/package/@abacus-ai/cli"><img src="https://img.shields.io/npm/v/@abacus-ai/cli?label=npm&color=2488FF" alt="npm version"></a>

<a href="https://abacus.ai/help/abacusai-desktop/introduction"><b>Docs</b></a> &nbsp;·&nbsp; <a href="#get-started"><b>Install</b></a> &nbsp;·&nbsp; <a href="https://abacus.ai/pricing"><b>Pricing</b></a> &nbsp;·&nbsp; <a href="mailto:support@abacus.ai"><b>Support</b></a>

</div>

<br>

<p align="center">
  <img src="assets/extension-agent.png" alt="Abacus AI Agent in the VS Code sidebar adding input validation to a TypeScript file, with the edit shown as a diff in the chat" width="820">
</p>

Abacus AI Agent is a coding agent that works with any model. Hand it a task and it reads your project, plans, edits files and runs commands, and you decide how much it does on its own. Use it in VS Code, in your terminal with the `abacusai` CLI, or in the Abacus AI Desktop app, with the same account and conversation history.

## Get started

<table>
  <tr>
    <td width="50%" valign="top">
      <b>VS Code</b><br>
      Install <a href="https://marketplace.visualstudio.com/items?itemName=abacusai.abacusai-agent">Abacus AI Agent</a> from the Marketplace. It is also on <a href="https://open-vsx.org/extension/abacusai/abacusai-agent">Open VSX</a> for VS Code-compatible editors. Open the <b>Abacus AI</b> view and sign in.
    </td>
    <td width="50%" valign="top">
      <b>Desktop</b><br>
      Download the app from <a href="https://desktop.abacus.ai/">desktop.abacus.ai</a>.
    </td>
  </tr>
</table>

**CLI.** On macOS, Linux and WSL:

```sh
curl -fsSL https://static.abacus.ai/cli/install.sh | bash
```

On Windows (PowerShell):

```powershell
irm https://static.abacus.ai/cli/install.ps1 | iex
```

Or with npm (Node 18 or later):

```sh
npm install -g @abacus-ai/cli
```

Then run `abacusai` in your project and sign in with `/login`.

## Use any model

<table>
  <tr>
    <td width="50%" valign="top">
      <b>One Abacus.AI plan</b><br>
      Claude, GPT and Gemini families plus open models such as Kimi, Qwen, DeepSeek and GLM. RouteLLM can pick a model for each turn.
    </td>
    <td width="50%" valign="top">
      <b>Your ChatGPT subscription</b><br>
      If Codex is signed in with ChatGPT, the agent detects it and offers those models.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>Your API keys</b><br>
      OpenAI, Anthropic and Google keys, stored in your OS keychain.
    </td>
    <td width="50%" valign="top">
      <b>Local and OpenAI-compatible models</b><br>
      Ollama, LM Studio, vLLM, Groq, Together, OpenRouter, DeepSeek or any OpenAI-compatible endpoint.
    </td>
  </tr>
</table>

Switch models mid-conversation, even across providers.

## Reporting bugs

Run `/feedback` in the CLI, or [open an issue](https://github.com/abacusai/abacusai-desktop/issues/new/choose) here. Please include:

- the product and version (`abacusai --version`, or the extension version in VS Code's Extensions view)
- your OS
- steps to reproduce, and what you expected to happen

## Data and privacy

Your code is not used for training. Abacus.AI has zero data retention agreements with model providers, and data is encrypted in transit. With a local provider, nothing about the turn reaches Abacus.AI. See the [privacy policy](https://abacus.ai/privacy) and [terms of service](https://abacus.ai/terms).

---

<p align="center"><a href="https://abacus.ai/help/abacusai-desktop/introduction">Documentation</a> &nbsp;·&nbsp; <a href="https://desktop.abacus.ai/desktop_faq">FAQ</a> &nbsp;·&nbsp; <a href="mailto:support@abacus.ai">support@abacus.ai</a> &nbsp;·&nbsp; <a href="https://abacus.ai/privacy">Privacy</a> &nbsp;·&nbsp; <a href="https://abacus.ai/terms">Terms</a></p>

<p align="center"><sub>The source code is not public. This repository tracks issues and feedback.</sub></p>
