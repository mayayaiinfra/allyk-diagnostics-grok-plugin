# ALLYK Diagnostics for Grok

ALLYK Diagnostics gives founders and entrepreneurs a focused next customer check before they build, price, or change an offer.

The plugin connects Grok to ALLYK's public Diagnostics MCP service. It can:

- preview an advisory diagnostic from the business context you provide;
- save a review to a task you choose in ALLYK Roadmap;
- show bounded history for the task you selected.

The service exposes only Diagnostics operations. It does not expose ALLYK conversations, files, credentials, private calculations, internal agents, billing data, or arbitrary actions. Results are advisory and do not verify evidence or execute work.

## Access and privacy

Sign in through ALLYK's OAuth consent screen when Grok asks. Do not paste passwords, API keys, workspace tokens, cookies, or private credentials into chat. The host sends the diagnostic context and receives the returned review; ALLYK stores saved reviews under the account and task you select.

Diagnostics assessments use no ALLYK credits and do not require a model key. An eligible ALLYK trial or paid plan and normal service limits still apply. Host usage charges, if any, are controlled by Grok or your provider.

You can revoke a connection from [ALLYK plugin connections](https://allyk.app/plugins/connections). Read the [privacy policy](https://allyk.app/privacy) and [terms](https://allyk.app/terms) before installing.

## Distribution

This repository is the source package for Grok marketplace review. Marketplace availability is subject to xAI review. For controlled testing, add this repository as a Grok marketplace and install `allyk-diagnostics` only after reviewing its files and trusting the source.

## License

This package is proprietary to MAYAYAI. See [LICENSE](LICENSE).
