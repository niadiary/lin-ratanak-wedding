# Lin & Ratanak Wedding Invitation

Open `index.html` in a browser or upload the files to your website host.

## Guest blessings integration
The blessing form submits to the configured Google Form using its two prefilled field IDs, and the guestbook reads the published Google Sheets CSV response feed. The sheet must remain published for the website to retrieve messages. If the browser blocks cross-origin CSV access, the guestbook will keep its sample blessings visible; use a small server-side proxy or Apps Script endpoint to enable reliable retrieval.
