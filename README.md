# SmartCampus AI

A responsive, self-contained campus life web app prototype. Built with HTML, CSS and vanilla JavaScript. No build tools, dependencies, accounts, or API keys are required.

## Run it

Open `index.html` in a modern browser. For a more realistic hosted-style preview, serve this folder with any static file server. All demo interactions work client-side. Submitted reports, reservations, and saved resources persist in that browser using local storage.

## Completed features

- Student overview with campus availability, issue, energy, and resource summaries.
- Space discovery with text search, quiet/group/power filters, sorting, availability, and reserving a space.
- Learning resource catalogue with course filters, search, and saved resources.
- Campus issue submission with category, location, description, and local persistence.
- Student issue list plus admin issue triage and resolve action.
- Energy overview with building breakdown and a labeled sample AI opportunity.
- Admin dashboard with sample operations metrics and issue triage.
- Responsive layout for desktop and mobile.

## Technology and implementation

- HTML5, CSS3, vanilla JavaScript; no third-party runtime libraries.
- Data is initialized from sample records and stored in browser `localStorage` for the demo.
- The analytics, occupancy, AI opportunity, schedule, campus, and feedback values are illustrative sample data. No live university systems or AI model are connected.

## Plan changes and limitations

The Round 1 concept described student space discovery, resources, campus issue reporting, and administrator energy insights. Those themes are all represented in the working prototype. To keep this first build easy to open, the implementation uses sample campus data and browser storage. Real availability, identity, AI analysis, energy-meter integrations, and cross-user synchronization need campus access and a backend, and are planned as future improvements.

## Three meaningful Round 3 improvements

1. Connect campus room schedules and occupancy sensors so space availability and reservations reflect real-time conditions and prevent conflicts.
2. Add an AI issue assistant that classifies reports, detects duplicates, routes them to the right facilities team, and summarizes recurring campus problems.
3. Integrate building energy meters and time-of-day baselines to detect likely waste, estimate savings, and track verified outcomes after an administrator acts.

## Round 2 submission checklist

- Working project link: publish the project folder as a static website, then add its URL.
- Source repository: create a repository and push these source files, then add its URL.
- Updated project PDF: `outputs/SmartCampus_AI_Round_2_Project.pdf`.
- Completed features and implementation details: see this README and the PDF.
- Original-plan changes and three Round 3 improvements: see above and the PDF.

## Project files

- `index.html` — application layout and dialogs.
- `styles.css` — responsive visual design.
- `app.js` — navigation, local interactions, sample data, and persistence.
