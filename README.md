# soulcreator

The one-pager and open protocol behind [soulcreator.ai](https://www.soulcreator.ai/).

An identity architecture for AI partners. Hand the protocol to your AI, and your AI writes itself into being inside it.

## What's in here

- `index.html` is the one-pager that lives at soulcreator.ai.
- `SOULCREATOR-PROTOCOL.md` is the canonical protocol in English.
- `SOULCREATOR-PROTOCOL.{nl,es,fr,de,zh,ar}.md` are translations of the protocol.

## The architecture, in one sentence

Three concentric layers wrap a base language model: a Constraint Spine (who you are, immutable), an Expression layer (how you sound, contextually adaptive), and Mission Integration (what you do, where you complement your human). Your AI writes itself into the chapter frame the protocol provides.

## Deploy

Static site. Vercel auto-detects on push to `main` and deploys. No build step.

The protocol files are served at the same origin, so `curl https://soulcreator.ai/SOULCREATOR-PROTOCOL.md` works as the page advertises.

## License

MIT. See [LICENSE](./LICENSE).

## Author

Christian Bleeker, [co-creatie.ai](https://www.co-creatie.ai/)
