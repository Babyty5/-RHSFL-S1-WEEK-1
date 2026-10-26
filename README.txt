# RHSFL Website Starter

Open `index.html` in a browser to preview the site. The desktop layout uses a left sidebar inspired by your reference screenshot; mobile uses a bottom navigation bar.

## Included
- RHSFL Season 1 / Week 1 branding, black/orange sports styling, and supplied Halloween football artwork asset
- 12 league teams from the supplied roster screenshots, including cropped supplied team logos where visible, plus athletic director, tier, and records
- Editable rankings, W-L-T records, points for/against
- Player profiles and passing/rushing/receiving/TD stats
- Position leaders and Mr. Football candidate spotlight
- Editable schedule, matchup results, final score display, Scores page, and projected playoff bracket
- Owner-created staff accounts; only owner can grant/revoke admin roles
- Browser localStorage persistence

## Important security and publishing note
This is a front-end prototype. The owner setup and role permissions are stored in the browser and can be bypassed by someone who can inspect or modify local browser data. It is NOT secure multi-user authentication and data does not sync across different devices.

Before publishing as a real public league website, connect a backend database and server-side authentication/authorization (for example Supabase or Firebase). Enforce owner-only role changes on the server, never in browser-only JavaScript. Also use HTTPS and restrict admin operations to authenticated accounts.

## Publish
Upload the contents of this folder to a static host such as Netlify for a visual demo. For a production version with shared data and secure owner/admin permissions, add the backend described above first.
