# Vansh Traders Website

React + Vite website for Vansh Traders, Katni, Madhya Pradesh.

## Run locally
1. Install Node.js (LTS).
2. Open this repository folder in VS Code.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL shown by Vite.

## Features
- Responsive business homepage, product catalogue and current-rate display.
- WhatsApp enquiry links default to **919131724142**.
- Admin screen for editing current rates and business contact settings.
- No Supabase, backend, database or environment variables.

## Admin access
Open **Admin access** in the footer.
- Username: `admin`
- Password: `vanshtraders@katni`

## Important limitations
- Admin login is frontend-only and is not secure authentication for a public production website.
- Rates and business settings are saved in localStorage on the current browser/device only. They do not sync to other devices or customers.
- Product prices are intentionally blank until the business enters verified rates.
- WhatsApp settings can be changed in the admin settings screen.
