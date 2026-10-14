# VaultFilter AI

A sleek, lightweight, developer-centric data sanitization utility designed to prevent accidental data leaks into commercial LLM histories (like ChatGPT or Claude) while significantly optimizing your prompt token overhead.

## 🛡️ Data Sovereignty Guarantee
**100% Private & Local-First.** VaultFilter AI processes all inputs completely client-side within your browser's local sandbox using vanilla JavaScript arrays and optimized regex routines.
* **Zero Server Requests:** Absolutely no text inputs, logs, keys, or analytical telemetry data are ever transmitted to a remote server or external API.
* **Your Data Stays Yours:** You can safely run this tool entirely offline.

## ✨ Core Features
* **Advanced PII Redaction:** Instantly sweeps and redacts regional identity profiles (like Aadhaar and SIN numbers), phone numbers, email strings, and both IPv4/IPv6 network gateway addresses.
* **Credential & Secret Scrubbing:** Robust, case-insensitive detection for OpenAI/Anthropic API keys (`sk-proj-...`, `sk-ant-...`), database interconnect metrics (`DATABASE_URL`), Bearer tokens, and local `.env` file variables.
* **Context Line Compression:** Streamlined line-by-line filtering array that strips multi-line corporate legal boilerplates, disclaimers, and casual email signatures to lower prompt token footprints.
* **Live Token Calculator:** A real-time analytical widget tracking character metrics to display your precise prompt token savings dynamically.

## 🚀 1-Minute GitHub Pages Deploy
Because this utility runs purely on client-side frontend files, you can host your own private instance for free instantly:
1. Navigate to your repository **Settings** tab on GitHub.
2. Scroll down to the **Pages** menu on the sidebar.
3. Under "Build and deployment", set the source Branch to **`main`** and click **Save**.
4. Your application will be live globally at `https://github.io`.
