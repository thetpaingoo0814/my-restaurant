How the QR system works
Step 1 — Generate QR codes (tables.html → QR Codes panel)

Select a table from the dropdown, a QR code appears instantly
Click Print This QR Code for one table, or Print All 8 QR Codes for a full sheet
Each QR encodes the string UMAMI-TABLE:Table 1 (and so on)

Step 2 — Place QR codes on tables
Print and laminate one per table. Customers scan with their phone camera.
Step 3 — Customer scans

The camera opens automatically on index.html
When a valid QR is detected, it auto-fills the table and dismisses the gate — no typing needed
The 📋 My Orders tab then only shows orders from that table's session — Table 1 customers cannot see Table 3's orders
If camera isn't available, there's a manual fallback input and a Take Out shortcut


Your complete 4-page system
FileWho uses itWhat it doesindex.htmlCustomerQR scan → order → view own orderskitchen.htmlChefLive orders + table map on the righttables.htmlStaff/HostTable availability map + QR generatorcashier.htmlCashierLookup by table → collect cash → print receipt
Table statuses flow automatically:

Customer scans QR → table turns Occupied in Firebase
All orders served → staff tap ✓ Free → table turns Available
After customer leaves → tap 🧹 Needs Clean → then ✓ Free when ready
