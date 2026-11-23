# Sequence Board

Interactive classroom games for a Promethean board or any touch screen, in a single HTML file.

- **Sentence order:** drag shuffled sentences and sentence parts into a paragraph in the right order.
- **Word builder:** attach prefixes and suffixes to four root words.
- **Word family:** build words from one root and match them to definitions.

Large, high-contrast text, a highlighter, sequence-word highlighting, celebration sounds, and a teacher editor that accepts rows pasted straight from a spreadsheet.

## Auto-generate with any AI

The editor can write passages and word lists for you. Choose a service in the **AI service** menu:

| Service | What you need | Cost |
|---|---|---|
| Copy and paste with any chatbot (ChatGPT, Gemini, Grok, Claude, Copilot) | Nothing: copy the request into the chatbot's website and paste its answer back | Free |
| Gemini (Google) | API key from [Google AI Studio](https://aistudio.google.com/apikey) | Free tier with daily limits |
| Groq | API key from [Groq](https://console.groq.com/keys) | Free tier with limits |
| OpenRouter | API key from [OpenRouter](https://openrouter.ai/keys) | Models ending in `:free` cost nothing |
| Claude (Anthropic), ChatGPT (OpenAI), Grok (xAI), Mistral, DeepSeek | That company's API key | Paid per use |
| Custom or local (Ollama, LM Studio) | Server address, e.g. `http://localhost:11434/v1` | Free |
| Claude, built in | Open the page inside Claude | Uses your Claude account |

API keys stay in your browser and are sent only to the service you chose. They're saved on the computer only if you tick **Remember on this computer**. OpenAI sometimes blocks requests from web pages; if it won't connect, use copy and paste with ChatGPT or OpenRouter with an OpenAI model.

**Play it:** open `index.html` in a browser, or use the GitHub Pages link for this repository.

Activities you add or change on the public page are saved in that browser only. Use **Download app file** on the Activities tab to keep a copy with your activities built in.
