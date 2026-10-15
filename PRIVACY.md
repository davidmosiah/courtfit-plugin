# Privacy boundaries

CourtFit's remote MCP endpoint is `https://plugin.courtfit.app/mcp`. It accepts bounded, structured exercise searches and session constraints; it is not an account, history, Apple Health or iPhone synchronization service. The server uses these fields in memory and does not save training history. Do not send medical histories, personal identifiers or unrelated conversation text in tool fields.

Grok/xAI and Cursor are separate hosts. Their services handle conversations, model requests, tool execution and related information under the policies and settings applicable to that host. The CourtFit server and its hosting infrastructure receive network requests and associated operational metadata. No claim is made that host conversations stay on-device or that host logs are disabled.

When you request a video, a host with native attachment support may fetch the exact original anatomical MP4 returned by CourtFit and attach a small number of demonstrations to the conversation. The host may process, copy and retain those attachments under its own policies and settings. This on-demand display does not create a connection to iPhone records or authorize a bulk media export. If attachments are unavailable, the assistant can provide the original video link and text instructions instead.

The [CourtFit plugin privacy policy](https://plugin.courtfit.app/privacy) was updated on 15 October 2026 for ChatGPT/OpenAI and Grok Bot/Cursor, including requested native attachments. The complete policy is available in [English](https://plugin.courtfit.app/privacy), [Portuguese](https://plugin.courtfit.app/privacy/pt) and [Spanish](https://plugin.courtfit.app/privacy/es). Those hosted pages describe the service's current practices; this package file is a concise boundary summary.

Support email is forwarded through Forward Email to a Zoho Mail support mailbox. Voluntarily supplied correspondence and saved sent replies remain until manual deletion; no support-specific automatic Inbox/Sent deletion deadline is confirmed. The observed 30-day Spam/Trash setting does not define Inbox/Sent retention. The server's approximately one-minute temporary rate-identifier expiry does not delete support mail, host conversations or attachments. Access, correction or deletion requests can use the public support address; no guaranteed response deadline or immediate provider-backup purge is promised.

Support: [support@courtfit.app](mailto:support@courtfit.app). Do not send sensitive training or medical records to support for using this plugin.
