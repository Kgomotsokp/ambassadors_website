# Christ Ambassadors Church — local reconstruction

A local React recreation based on the Base44 code excerpts provided. The public pages and a representative church-management experience run in the browser with demo data saved in local storage. No Base44 credentials or production services are used.

## Run locally

1. Install Node.js (18 or later) and npm.
2. In this folder, run `npm install`.
3. Run `npm run dev` and open the local URL Vite prints (usually `http://localhost:5173`).
4. Choose **Sign in (demo)** to open a demo dashboard. Choose a role to preview its navigation.

Use **Sign out** to return to the public experience. Demo changes are stored in this browser only; **Reset demo data** clears them.

## Scope and integration

The supplied excerpts did not include the full page set, Base44 entity/function definitions, or backend. This reconstruction provides the visual shell, representative public and management pages, and local-only sample interactions. It does not authenticate real users, send email, process donations, or connect to the published app's database. Those integrations require the original Base44 project or backend configuration and should be connected before real use.
