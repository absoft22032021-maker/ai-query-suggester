# AI Query Suggester — Privacy Policy

**Last updated:** 2025-09-28

AI Query Suggester is a Chrome extension that converts short user inputs into Jira JQL, Stack Overflow search strings, and RingCentral bug reports.

## Data We Collect
We do **not** collect, store, or transmit personal data to our own servers. We do not operate any backend.
The extension stores only minimal settings locally via Chrome storage:
- **chrome.storage.sync**: LLM provider, model, API key, custom model IDs.
- **chrome.storage.local**: last selected text and the active UI mode.

## How Your Data Is Used
When you click **Generate**, your input (and only your input) is sent to the model provider you selected (OpenAI or Google Gemini) strictly to produce the requested output. No other parties receive the data from the extension.

## Permissions & Why We Need Them
- **storage** – Save extension settings and small UI state.
- **tabs** – Open Jira Issue Navigator or Stack Overflow results in a new tab when you click a button.
- **contextMenus** – Provide a single menu item to use the currently selected text.
- **activeTab** – Access tab metadata for user‑initiated actions (no content is read or scraped).
- *(No content scripts are injected; no page scraping.)*
- *(No remote code, no eval, no runtime-fetched scripts or Wasm.)*

## Sharing & Selling
We do **not** sell user data. We do **not** share user data except with the chosen model provider (OpenAI or Google Gemini) solely to provide the requested feature.

## Security
API keys are stored via Chrome’s extension storage. You control these keys; revoke them if compromised. We recommend using separate API keys with usage limits.

## Children
This extension is not directed at children under 13 and does not knowingly collect information from them.

## Changes
We may update this policy as the product evolves. Changes will be committed to this file with a new “Last updated” date.

## Contact
For privacy questions or requests, please open an issue in the repository or contact the developer.
