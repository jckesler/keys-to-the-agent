# Keys to the Agent

A 10 to 12 minute browser game about deploying an AI agent safely.

A business team wants an AI agent, and you're the security reviewer deciding what it can read, do and reach. Then it goes live, and you find out what those decisions meant. Lock it down too far and the team may find its own workaround.

**Play it:** https://jckesler.github.io/keys-to-the-agent/

## What it covers

- Prompt injection, direct and indirect
- Excessive agency and least privilege for AI agents
- The "lethal trifecta": private data, untrusted content, and a way to send data out (a term introduced by Simon Willison)
- AI agents as non-human identities: whose access, what limits, who owns them
- The AI supply chain, AI vendors as third parties, and runaway costs
- Shadow AI as the cost of saying no

Each play draws one of three invented companies (a health system, a retailer and a software vendor). The scenarios are modeled on real incidents, which the debrief describes. The debrief can be saved as a PDF.

## Running it

It's a single self-contained HTML file. Open `index.html` in any modern browser, or host it anywhere that serves static files. No build step, no server, no data collected.

## About

Created by Chuck Kesler. Companion to *The 2AM Page* (https://github.com/jckesler/the-2am-page), an incident response tabletop game, and *Ship It?* (https://github.com/jckesler/ship-it-ai-review), an AI launch review game.

## License

[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Free to use and adapt for non-commercial purposes, with credit.
