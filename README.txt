WEALTHTRACKER AI — STARTER VERSION

Features:
- Responsive interface for phone and computer
- Income and expense tracking in CAD
- Cash balance, investment value, simple net-worth estimate
- Manual investment cost/current value comparison
- Educational stock research checklist and locally saved notes
- CSV export
- Basic offline cache when hosted on localhost/HTTPS

Limitations:
- No bank or brokerage connection
- No live stock quotes or live AI analysis yet
- Data stays in this browser/device and does not sync across devices
- Clearing browser storage can erase entries; export CSV backups
- Educational tool, not financial advice

Run on a computer:
1. Extract the ZIP.
2. Open index.html for basic testing.
3. For install/offline support, open a terminal in the folder and run: python -m http.server 8000
4. Visit http://localhost:8000

Phone:
Open the folder in a code-editor preview or serve it with a local web server. Installable PWA features require localhost/HTTPS. Cross-device sync can be added later using a secure backend.

Next: test adding income/expenses, adding/deleting an investment, researching a ticker, and exporting CSV. Never put private AI API keys in app.js.
