# Tekservix OpenAPI definitions

Official OpenAPI 3.0 definitions for the public Tekservix messaging APIs. Use them to generate clients, import the APIs into Postman or Insomnia, or explore every endpoint before you write code.

| API | Definition | Docs |
| --- | --- | --- |
| **SMS Gora SMS Gateway**: send and receive SMS through your own Android phone and SIM, with bulk sends, scheduling, delivery reports and webhooks | [`smsgora.openapi.json`](smsgora.openapi.json) | [tekservix.com/smsgora/docs](https://tekservix.com/smsgora/docs/) |
| **WAservix WhatsApp API Gateway**: send WhatsApp messages, media, polls and locations from your own number, linked by QR code | [`waservix.openapi.json`](waservix.openapi.json) | [tekservix.com/waservix/docs](https://tekservix.com/waservix/docs/) |

Raw links for tools that import by URL:

- `https://raw.githubusercontent.com/TekservixHQ/openapi/main/smsgora.openapi.json`
- `https://raw.githubusercontent.com/TekservixHQ/openapi/main/waservix.openapi.json`

## You need an account and an API key

Both APIs need a Tekservix account and your own API key. Every request without a valid key gets `401`. Each product has a 3-day free trial, then a paid plan:

- SMS Gora: [tekservix.com/smsgora](https://tekservix.com/smsgora/). Plans include unlimited SMS; your mobile operator charges the SIM as usual.
- WAservix: [tekservix.com/waservix](https://tekservix.com/waservix/)

Keep keys on your server. Never put them in a website or a mobile app.

## Ready-made clients

Official client libraries are on npm, PyPI, Packagist, RubyGems, crates.io, NuGet, Maven Central and more: see [github.com/TekservixHQ](https://github.com/TekservixHQ).

## More from Tekservix

- **Tekservix AI Sales Agent**: an AI salesperson that answers customers on WhatsApp and SMS, 24/7
- **Website to App / App Studio**: turn a website into Android and iOS apps
- **Native App Builder** and custom app development
- **Takesuite**: plan, create and sell on social media
- **AI Studio**: AI tools for writing, images and business

All at [tekservix.com](https://tekservix.com).

## License

The definitions are provided under the MIT License so you can use them in your own tools. The Tekservix service itself is governed by the [Tekservix terms](https://tekservix.com/info/terms).
