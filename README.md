# SocialFind — HTML / CSS / JavaScript edition

A responsive front-end starter for SocialFind. It includes:
- Search by name, username, profession and bio
- Category filters
- Public profile cards and detail view
- Add profile form
- English / বাংলা language toggle
- Dark / light theme toggle
- Demo login/logout
- Local browser storage for demo profiles and preferences
- Privacy-first copy: profiles are opt-in and phone-number lookup is not supported

## Run locally
Open `index.html` in a modern browser. For best results, use VS Code with the Live Server extension.

## Publish on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `styles.css`, `app.js`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for the published URL shown in the Pages section.

## Important limitations
This is a static front-end demo, not a production backend:
- Login is a local demo only; it does not securely authenticate users.
- Profiles are stored in the current browser's localStorage and are not shared with other visitors.
- There is no real admin panel, email verification, password reset, database, server-side moderation, or cross-device sync.
- Do not collect real passwords or sensitive personal information with this demo.
- For a real public directory, connect a secure backend such as Supabase, implement authentication and row-level security, server-side validation, abuse prevention, verification, and deletion workflows.

Only list social links that profile owners voluntarily submit and are authorized to share. Do not use phone-number reverse lookup or scrape private social accounts.
