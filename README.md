# Prompt Generators

A single-page, no-dependency web app with three guided prompt builders — **Claude**, **Gemini**, and **ChatGPT** — each shaped around that model's own prompting best practices. Pick a tab, fill in the fields, watch your prompt assemble live, and copy it out.

## The three builders

- **Claude** — Anthropic's official prompt structure: a clear role, XML-tagged background and documents, detailed instructions, multishot examples, optional chain-of-thought, explicit output formatting, and response prefill.
- **Gemini** — Google's recommended **Persona · Task · Context · Format** framework, written conversationally, plus reference material and few-shot examples.
- **ChatGPT** — OpenAI's guidance: clear instructions, grounding **reference text**, step-by-step breakdown, few-shot examples, and a specified output format.

## Usage

Open `index.html` in any browser. No build step, no install, no server.

- **Tabs** switch between the landing page and each builder (also reflected in the URL hash, so links like `#gemini` work).
- **Upload files** to attach them by name. Browsers only expose the file name (not the full path), so the path field stays editable and the generated prompt instructs the model to locate uploaded files by searching for them.
- **Copy prompt** copies the assembled text to your clipboard.
- **Reset** clears the current builder.

## Privacy & cost

Everything runs entirely in your browser. It makes no API calls, requires no accounts, and sends nothing anywhere — it just assembles text. Free to use and share.

## License

MIT
