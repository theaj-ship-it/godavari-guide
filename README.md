# Godavari Guide — Website Prototype

A responsive, single-page prototype for the proposed Godavari Guide multilingual pilgrim assistance platform for Godavari Pushkaralu 2027.

## Run locally
1. Extract `godavari-guide-prototype.zip`.
2. Open `index.html` in Microsoft Edge, Chrome, or Firefox.
3. Try the language selector, search, service cards, and navigation.

No build tools or API keys are required.

## Deploy as a shareable prototype link with GitHub Pages
1. Create a new public GitHub repository, for example `godavari-guide`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. The URL will usually look like `https://YOUR-USERNAME.github.io/godavari-guide/`.

## Important prototype limitations
- This is a front-end demo; it does not connect to a live government database, map service, or AI backend.
- The route graphic is illustrative, not a navigable map.
- Pushkaralu dates, schedules, transport information, emergency contacts and official announcements are not presented as verified facts. Add them only after checking trusted official sources.
- The language selector translates the primary interface labels. Some descriptive notices remain in English and should be professionally reviewed before public use.
- Do not present this demo as an official government website.

## Suggested next milestones
1. Add a verified data source and source/last-updated fields.
2. Add real place records and a map using validated coordinates.
3. Add reviewed Telugu and Hindi translations for all content.
4. Add a multilingual search/chat endpoint that only retrieves from approved records.
5. Add accessible emergency and facility information after official validation.
