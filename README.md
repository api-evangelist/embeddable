# Embeddable (embeddable)
An index and topic collection covering embeddable widgets, JavaScript SDKs, iframe-able experiences, and embedded analytics. Embeddable platforms allow product teams to drop pre-built UI components, payment flows, chat widgets, media players, forms, maps, dashboards, and authentication experiences directly into a host site or application via a script tag, iframe, or JS SDK. This collection includes payment elements like Stripe Elements and Stripe Checkout, financial linking like Plaid Link, mapping like Mapbox GL JS and Google Maps Embed, media players from YouTube, Vimeo, and Wistia, chat widgets from Intercom, Drift, Crisp, and Tawk-style services, scheduling widgets like Calendly, forms from HubSpot, Typeform, JotForm and Gravity Forms, identity via Auth0 Lock, chat SDKs from Stream and Sendbird, and embedded analytics from Looker, Apache Superset, Sigma, Cube, Mode, Metabase, Qlik Mashups, SAP BI Tools, Power BI, and Tableau.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Embeddable, Widget, Embedded Analytics, JS SDK, iframe, Embed, Drop-in UI

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Embed Config Schema](https://raw.githubusercontent.com/api-evangelist/embeddable/refs/heads/main/json-schema/embeddable-embed-config-schema.json)
- [JSONSchema - Widget Instance Schema](https://raw.githubusercontent.com/api-evangelist/embeddable/refs/heads/main/json-schema/embeddable-widget-instance-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/embeddable/refs/heads/main/json-ld/embeddable-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/embeddable/refs/heads/main/vocabulary/embeddable-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Drop-in UI Components | Embeddable platforms ship pre-built, brandable UI components that drop into a host page via a script tag, web component, or framework binding. |
| Iframe and Script-Tag Distribution | Most embeddable widgets are delivered as either a hosted iframe or a small JavaScript bootstrap that injects an isolated DOM subtree into the host site. |
| Tokenized and Scoped Authentication | Embeds use short-lived, server-issued tokens (publishable keys, link tokens, JWTs, session tokens) so the host can render the widget without exposing long-lived credentials. |
| Theme and Style Customization | Embeds expose theming hooks - color tokens, fonts, CSS variables, layout options - so the embedded experience matches the host product's visual identity. |
| Postmessage and Callback Event Model | Embedded widgets communicate with the host page through postMessage events, callback functions, or SDK event listeners (ready, success, error, dismiss). |
| Embedded Analytics and Dashboards | BI vendors like Looker, Sigma, Cube, Mode, Apache Superset, Metabase, Power BI, and Tableau ship embed SDKs and signed iframe URLs for in-product dashboards. |
| PCI, KYC, and Compliance Offloading | Embeds for payments, identity, and financial data keep sensitive data inside the provider's frame so the host product stays out of PCI, KYC, and compliance scope. |
| Mobile SDK and Web Parity | Most embeddable platforms ship matching iOS, Android, and React Native SDKs alongside the JS widget so the same experience can be embedded across web and mobile. |

## Use Cases

| Name | Description |
|------|-------------|
| Accepting Payments Without PCI Scope | Drop Stripe Elements, Stripe Checkout, Braintree Drop-in, Adyen Components, or Square Web Payments SDK into a checkout flow without touching raw PAN data. |
| Linking Bank Accounts and Financial Data | Embed Plaid Link in a fintech onboarding flow so users can authenticate with their bank and grant data access without leaving the host application. |
| Embedding Maps and Location Pickers | Drop Mapbox GL JS or the Google Maps Embed into a marketplace, real estate, or logistics product to render interactive maps and place markers. |
| Adding Live Chat and Support Widgets | Embed Intercom Messenger, Drift, Crisp, Olark, LiveChat, Help Scout Beacon, Zendesk Web Widget, or Freshdesk Messaging through a single script tag. |
| Inline Scheduling and Booking | Embed Calendly or Cal.com inline widgets into marketing sites and SaaS dashboards so prospects and customers can book meetings without bouncing. |
| Embedded Forms and Lead Capture | Drop HubSpot Forms, Typeform, JotForm, Gravity Forms, or Formspree into landing pages and product surfaces to capture leads and feedback. |
| Embedded BI Dashboards in SaaS | SaaS vendors embed Looker, Sigma, Cube, Mode, Apache Superset, Metabase, Knowi, Qlik Mashups, Power BI, SAP BI Tools, or Tableau as in-app dashboards. |
| Login, Signup, and Identity as a Widget | Embed Auth0 Lock or hosted login pages to give the host product a full identity experience - email/password, social, MFA, passwordless. |

## Integrations

| Name | Description |
|------|-------------|
| Stripe Elements and Checkout | Pre-built UI components and a hosted checkout page that drop into any web or mobile app to accept cards, wallets, ACH, and BNPL. |
| Plaid Link | Drop-in flow that lets end users authenticate with their bank, link accounts, and grant data access in a few clicks. |
| Mapbox GL JS | WebGL-based JS SDK for embedding interactive vector maps, custom styles, 3D terrain, and geocoding into web applications. |
| Google Maps Embed | Iframe-based embed and JavaScript SDK for placing Google Maps, Street View, directions, and search into any host page. |
| Intercom Messenger | Embeddable customer messaging widget delivered via a single script tag, with conversation routing, tours, and inbox tooling. |
| Calendly Inline Widget | Embeddable scheduling experience that drops into a host page as an inline widget, popup, or popup text link. |
| Typeform Embed | Iframe and JS embed for Typeform conversational forms in inline, popup, drawer, side-tab, popover, and full-page modes. |
| Auth0 Lock and Universal Login | Embeddable login widget and hosted login pages that handle email/password, social, MFA, and passwordless flows. |
| Looker and Sigma Embedded Analytics | Embedded analytics SDKs and signed iframe URLs for dropping BI dashboards directly into customer-facing SaaS products. |
| Apache Superset and Cube Embedded | Open-source and headless embedded analytics platforms providing JWT-signed dashboards, charts, and semantic-layer-driven embeds. |

## Artifacts

Machine-readable specifications for embeddable widgets and embed sessions.

### JSON Schema

- [Embed Config Schema](json-schema/embeddable-embed-config-schema.json)
- [Widget Instance Schema](json-schema/embeddable-widget-instance-schema.json)

### JSON Structure

- [Embed Config Structure](json-structure/embeddable-embed-config-structure.json)
- [Widget Instance Structure](json-structure/embeddable-widget-instance-structure.json)

### JSON-LD

- [Embeddable Context](json-ld/embeddable-context.jsonld)

## Vocabulary

- [Embeddable Vocabulary](vocabulary/embeddable-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 7 actions, 4 workflows, and 4 personas across embeddable widgets, JS SDKs, iframe experiences, and embedded analytics.

## Network

This index references the following embeddable widget, JS SDK, iframe, and embedded analytics repositories:

- [Adyen](https://github.com/api-evangelist/adyen)
- [Amplitude](https://github.com/api-evangelist/amplitude)
- [Apache Superset](https://github.com/api-evangelist/apache-superset)
- [Auth0](https://github.com/api-evangelist/auth0)
- [Braintree](https://github.com/api-evangelist/braintree)
- [Bubble](https://github.com/api-evangelist/bubble)
- [Cal.com](https://github.com/api-evangelist/cal-com)
- [Calendly](https://github.com/api-evangelist/calendly)
- [Canva](https://github.com/api-evangelist/canva)
- [ChatGPT](https://github.com/api-evangelist/chatgpt)
- [Crisp](https://github.com/api-evangelist/crisp)
- [Disqus](https://github.com/api-evangelist/disqus)
- [DocuSign](https://github.com/api-evangelist/docusign)
- [Drift](https://github.com/api-evangelist/drift)
- [Formspree](https://github.com/api-evangelist/formspree)
- [Freshdesk](https://github.com/api-evangelist/freshdesk)
- [FullStory](https://github.com/api-evangelist/fullstory)
- [Google Maps](https://github.com/api-evangelist/google-maps)
- [Gravity Forms](https://github.com/api-evangelist/gravity-forms)
- [Heap](https://github.com/api-evangelist/heap)
- [Help Scout](https://github.com/api-evangelist/helpscout)
- [Hotjar](https://github.com/api-evangelist/hotjar)
- [HubSpot](https://github.com/api-evangelist/hubspot)
- [Intercom](https://github.com/api-evangelist/intercom)
- [JotForm](https://github.com/api-evangelist/jotform)
- [Knowi](https://github.com/api-evangelist/knowi)
- [LiveChat](https://github.com/api-evangelist/livechat)
- [Looker](https://github.com/api-evangelist/looker)
- [Mapbox](https://github.com/api-evangelist/mapbox)
- [Metabase](https://github.com/api-evangelist/metabase)
- [Mixpanel](https://github.com/api-evangelist/mixpanel)
- [Olark](https://github.com/api-evangelist/olark)
- [OpenAI](https://github.com/api-evangelist/openai)
- [Pendo](https://github.com/api-evangelist/pendo)
- [Plaid](https://github.com/api-evangelist/plaid)
- [Power BI](https://github.com/api-evangelist/power-bi)
- [Qlik Mashups](https://github.com/api-evangelist/qlik-mashups)
- [SAP BI Tools](https://github.com/api-evangelist/sap-bi-tools)
- [Segment](https://github.com/api-evangelist/segment)
- [Sendbird](https://github.com/api-evangelist/sendbird)
- [SoundCloud](https://github.com/api-evangelist/soundcloud)
- [Square](https://github.com/api-evangelist/square)
- [Stream](https://github.com/api-evangelist/stream-io)
- [Stripe](https://github.com/api-evangelist/stripe)
- [Tableau](https://github.com/api-evangelist/tableau)
- [Twilio](https://github.com/api-evangelist/twilio)
- [Typeform](https://github.com/api-evangelist/typeform)
- [Userpilot](https://github.com/api-evangelist/userpilot)
- [Vimeo](https://github.com/api-evangelist/vimeo)
- [Wistia](https://github.com/api-evangelist/wistia)
- [YouTube](https://github.com/api-evangelist/youtube)
- [Zendesk](https://github.com/api-evangelist/zendesk)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
