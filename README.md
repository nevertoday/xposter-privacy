# xPoster Privacy Policy

Effective date: May 21, 2026

xPoster is a Chrome extension for importing user-provided Markdown drafts into X Articles. The extension runs in the browser and is designed to help users preview, validate, and publish structured article content from a side panel.

## Data xPoster Handles

xPoster may handle the following data when the user chooses to use the extension:

- User-provided Markdown drafts, including text, links, tables, tweet URLs, code blocks, and image references.
- The active X or Twitter tab URL, page title, article route, editor readiness, and article identifier needed to confirm the import target.
- Local folder handles selected by the user for resolving relative image paths in Markdown drafts.
- Remote image URLs included by the user in Markdown drafts, when the user grants optional access to those image origins for import.
- Import readiness checks and saved run records generated locally in the side panel, such as block counts, readiness checks, and import results.

## How Data Is Used

xPoster uses this data only to provide its single purpose: importing Markdown drafts into the active X Article editor and verifying the publishing workflow.

The extension parses Markdown locally, prepares images and tables locally, communicates with the active X Article tab, and uses X page APIs only for user-requested article actions such as setting article title or cover media. xPoster does not operate a backend service and does not send user content to any xPoster-owned server.

xPoster's use of user data complies with the Chrome Web Store User Data Policy, including the Limited Use requirements. xPoster uses user data only to provide or improve its single purpose, does not transfer user data except as necessary for the user-requested publishing workflow, does not use user data for advertising, and does not allow humans to read user data.

## Storage

xPoster may store the following data locally in the user's browser:

- The current side panel draft in Chrome extension storage.
- Live verification checklist state in Chrome extension storage.
- A user-selected local image folder handle in IndexedDB, when the user chooses a folder for relative images.

This local data stays on the user's device unless the user independently publishes content through X.

## Network Requests

xPoster makes network requests only as needed for its publishing workflow:

- Requests to `x.com`, `twitter.com`, and related X media endpoints are used to interact with the active X Article editor under the user's logged-in X session.
- Requests to remote image URLs are made only when those URLs are present in user-provided Markdown content, the user starts the import workflow, and the user grants the optional host permission for those image origins. Remote image requests omit credentials.

xPoster does not use analytics, advertising SDKs, tracking pixels, payment services, or third-party telemetry.

## Data Sharing

xPoster does not sell, rent, transfer, or share user data with third parties. Data is not used for advertising, creditworthiness, or any purpose unrelated to the extension's publishing workflow.

When the user imports or publishes content into X Articles, that content is handled by X according to X's own terms and privacy practices. xPoster does not control X's processing of content after the user sends it to X.

## Authentication Information

xPoster does not collect, store, or transmit passwords or X authentication tokens to xPoster-owned systems. Browser cookies for X may be included by Chrome in same-site requests to X when the user performs an X Article action, but xPoster does not store those cookies.

## Remote Code

xPoster does not load or execute remote JavaScript. Extension code is packaged with the submitted Chrome extension.

## User Control

Users can clear locally stored extension data through Chrome's extension storage controls or by removing the extension. Users can also clear the local image folder setting from the xPoster side panel.

## Contact

For privacy questions, open an issue at:

https://github.com/nevertoday/xposter-privacy/issues
