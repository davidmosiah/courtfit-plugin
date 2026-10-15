# Privacy boundaries

CourtFit's remote MCP endpoint is `https://plugin.courtfit.app/mcp`. It accepts bounded, structured exercise searches and session constraints; it is not an account, history, Apple Health or iPhone synchronization service. The server uses these fields in memory and does not save training history. Do not send medical histories, personal identifiers or unrelated conversation text in tool fields.

Grok/xAI and Cursor are separate hosts. Their services handle conversations, model requests, tool execution and related information under the policies and settings applicable to that host. The CourtFit server and its hosting infrastructure receive network requests and associated operational metadata. No claim is made that host conversations stay on-device or that host logs are disabled.

When you request a video, a host with native attachment support may fetch the exact original anatomical MP4 returned by CourtFit and attach a small number of demonstrations to the conversation. The host may process, copy and retain those attachments under its own policies and settings. This on-demand display does not create a connection to iPhone records or authorize a bulk media export. If attachments are unavailable, the assistant can provide the original video link and text instructions instead.

The currently published [CourtFit plugin privacy policy](https://plugin.courtfit.app/privacy) must be reviewed for this distribution before publication. The existing policy's OpenAI-specific host language is not sufficient evidence of Grok/Cursor coverage. This file documents the proposed boundary; it does not replace or update the hosted policy.

Support: [support@courtfit.app](mailto:support@courtfit.app). Do not send sensitive training or medical records to support for using this plugin.
