# Fatura-Takip-Uygulamas-Billing-Tracker-PWA-
This project is a modern, serverless Progressive Web App (PWA) designed to help users easily track their bills. Users can add one-time, regular monthly, or custom recurring bills, receive browser notifications as due dates approach, and securely store all their data within their own browser. his application serves as a portfolio piece demonstrating how an idea can be transformed into a product, how user-experience-focused features are developed, and how the limitations of web technologies can be overcome with smart algorithms.

✨ Features Multiple Bill Types:

One-Time: Bills that need to be paid only once.

Regular (Perpetual Monthly): Quick entry for standard recurring bills like electricity, water, or rent.

Custom Recurring: Bills that repeat on custom schedules set by the user (e.g., every 3 months, every 2 weeks).

Smart Auto-Update:

Overdue "Regular" or "Custom Recurring" bills are automatically updated to the next payment cycle the moment the app is opened. This ensures the billing cycle is never broken, even if the user forgets to mark a bill as "Paid".

Browser Notifications:

Sends a desktop or mobile browser notification one day before or on the due date.

Visual Status Indicators:

Provides visual cues by marking bills with a yellow border if the due date is within 3 days, and a red border for overdue bills.

Data Persistence:

All bill data is securely stored in the browser's Local Storage without needing a server. The user's data is preserved even if they close the browser.

Mobile-First & PWA:

Features a fully responsive design that works seamlessly across all devices (mobile, tablet, desktop).

Can be installed and used like a native mobile app thanks to the "Add to Home Screen" feature.

💻 Technologies Used Frontend:

HTML5

CSS3 (Styled with the Tailwind CSS framework)

Vanilla JavaScript (ES6+) (No JS frameworks were used)

Browser APIs:

Local Storage API: For persistent data storage.

Notifications API: For sending reminder notifications.

🚀 How to Run Deploying and using this project is extremely simple.

Deploy with GitHub Pages:

Navigate to the Settings > Pages section of this project's GitHub repository.

Select main (or master) as the branch and click Save.

Within a few minutes, your site will be live at https://your-username.github.io/repository-name/.

Install on Your Phone:

Open the deployed URL in your phone's browser.

Android (Chrome): Use the "Add to Home Screen" option from the menu.

iPhone (Safari): Use the "Add to Home Screen" option from the Share menu.

🧠 Technical Decisions & Architecture Serverless Architecture: This application is entirely client-side, requiring no backend or database. This eliminates maintenance costs and makes deployment incredibly easy.

Overcoming Web App Limitations: Web applications cannot run background code continuously like native mobile apps. To overcome this, the autoUpdateRecurringBills function was developed. It runs every time the app is opened or hourly (if the tab is open), instantly detects past-due recurring bills, and updates their dates, ensuring the system always stays current.

🗺️ Roadmap Here are some features planned for future versions of the project:

[ ] Bill Categorization: Allow users to categorize bills (e.g., "Home," "Work," "Subscriptions").

[ ] Statistics and Reporting: A dashboard to visualize data, such as total monthly expenses.

[ ] Data Backup & Restore: Enable users to export their bill data as a JSON or CSV file and import it back.

[ ] Native Mobile App Version: Develop a full-fledged mobile app using a technology like React Native or Flutter to enable features like background sync.
