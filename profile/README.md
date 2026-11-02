# LightsOut Factory

Self-hosted automation kits: the code, configuration and runbooks of the automation that runs our own servers, made to
install on yours and run on your own local AI. **[lightsoutfactory.ai](https://lightsoutfactory.ai)**

Free and open source here, from the kits:

| Repository | What it does | From the kit |
|---|---|---|
| [cloudflare-free-shield](https://github.com/lightsoutfactory/cloudflare-free-shield) | Three Cloudflare Free-plan WAF rules that stop most scraper floods at the edge | [Night Watch](https://lightsoutfactory.ai/kits/night-watch/) |
| [bot-gate](https://github.com/lightsoutfactory/bot-gate) | One-file ASGI/WSGI middleware that keeps pages up for people during a flood | [Night Watch](https://lightsoutfactory.ai/kits/night-watch/) |
| [translation-checks](https://github.com/lightsoutfactory/translation-checks) | Catch translations that would break your app, in 43 languages | [Polyglot](https://lightsoutfactory.ai/kits/polyglot/) |
| [vllm-health](https://github.com/lightsoutfactory/vllm-health) | A vLLM health check that never waits in the queue: a busy server is left alone, a stuck one fails | [Factory Floor](https://lightsoutfactory.ai/kits/factory-floor/) |

What we learn running all of this goes into the [field notes](https://lightsoutfactory.ai/field-notes/).

Recent field notes:

- [In 14 of our 42 languages, the plural form called "one" is not just for 1](https://lightsoutfactory.ai/field-notes/plural-one-is-not-one/)
- [1,082 translations had a word in the wrong alphabet. Our checks passed every one.](https://lightsoutfactory.ai/field-notes/letters-of-another-script/)
- [Our health check restarted a healthy model server eight times in one day](https://lightsoutfactory.ai/field-notes/health-check-restarted-healthy-model/)
- [A scraper flood on Cloudflare's Free plan: what stopped it, and what we left switched off](https://lightsoutfactory.ai/field-notes/scraper-flood-cloudflare-free-plan/)
