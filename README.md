Symbiot – AI‑Powered B2B Sales Intelligence Dashboard
Symbiot is a modern, fully responsive web dashboard that simulates an AI‑driven B2B sales platform. It helps sales teams discover, engage, and convert high‑intent prospects across multiple online communities (LinkedIn, Reddit, Discord, etc.). The dashboard includes real‑time analytics, a searchable lead database, CRM sync simulation, user settings, and a help centre – all in one clean interface.

🚀 Live Demo
(Add your GitHub Pages or hosting link here once deployed)

✨ Key Features
Dashboard Overview – Key metrics (pipeline value, ROI, engagements, opportunities) + interactive funnel & platform performance charts.

Advanced Analytics – Engagement trends, conversion rates by platform, performance matrix, and AI‑powered insights.

Lead Database – Searchable, filterable table with lead scoring, status tracking, and action buttons.

CRM Sync Simulation – Bidirectional field mapping, sync logs, and manual force‑sync functionality.

Settings Panel – Toggle platform connectors, AI reply rules, notification preferences.

Help & Support – System status, knowledge base links, and a support ticket form.

Fully Responsive – Works on desktop, tablet, and mobile devices.

Client‑side Only – Uses mock data and local JavaScript – no backend required for testing/demo.

🛠️ Built With
HTML5 – Semantic structure

CSS3 – Custom properties, Flexbox, Grid, animations

JavaScript (ES6) – Dynamic page navigation, filtering, chart rendering

Chart.js – Interactive bar, line, and doughnut charts

Font Awesome 6 – Icons for modern UI

Pravatar – Placeholder user avatar

📁 Project Structure
text
symbiot-dashboard/
├── index.html          # Complete single‑page application
├── README.md           # Project documentation
Note: All styles, scripts, and mock data are contained within the HTML file for simplicity.

🧪 How to Run Locally
Clone the repository

bash
git clone https://github.com/your-username/symbiot-dashboard.git
cd symbiot-dashboard
Open the dashboard

Simply open index.html in any modern browser (Chrome, Firefox, Edge).

No build steps, dependencies, or server required.

Explore the features

Use the sidebar to switch between Dashboard, Analytics, Lead Database, CRM Sync, Settings, and Help.

Filter leads by score or search keywords.

Click “Force Sync Now” to simulate a CRM sync.

Submit a test support ticket.

📈 Mock Data & Limitations
All data (leads, analytics numbers, sync logs) is static and defined in JavaScript for demo purposes.

No actual API calls or database – perfect for UI/UX prototyping, portfolio pieces, or starting point for a real backend integration.

To make it production‑ready, replace mock data with real API endpoints (e.g., REST, WebSockets) and add authentication.

🔮 Future Improvements
Connect to live CRM APIs (HubSpot, Salesforce, Pipedrive)

Implement real‑time signal detection using Reddit/LinkedIn APIs

AI reply generation using OpenAI GPT

User authentication and role‑based access control

Export leads to CSV/PDF
