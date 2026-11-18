ROGERS RESPITE MILEAGE & VEHICLE EXPENSES — INSTALLATION

This is a static progressive web app (PWA). It needs an HTTPS URL for installation and offline caching. Simply opening index.html from Files does not install an offline PWA.

1. Create a NEW public GitHub repository (for example, rogers-mileage-app). Do NOT upload any exported client or financial data.
2. Upload index.html, app.js, sw.js, manifest.webmanifest and icon.png to the repository root.
3. In repository Settings > Pages, choose Deploy from a branch, main, / (root), and save.
4. Wait for GitHub Pages to publish the HTTPS site, then open its URL in Safari on your iPhone.
5. Safari > Share > Add to Home Screen > Add.
6. Open the app once while online, then test with Airplane Mode enabled. After first successful load, its interface can work offline.

All trip and expense entries stay in the browser's local storage on the iPhone. GitHub Pages hosts only the app code, not your entered data. Export JSON backups regularly; iOS may remove site data and local storage is not a guaranteed long-term archive. Do not enter client names or identifying information.

CSV: The Trips CSV and Expenses CSV can be imported into Google Sheets. The complete JSON backup can be restored through the app's Data tab.

NOTE: Vehicle expenses and business-use percentages are tracking figures, not CRA tax deductions. Maintain comprehensive odometer logs and consult your accountant about eligibility and allocations. No automatic GPS or background tracking.
