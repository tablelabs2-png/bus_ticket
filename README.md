# RoadLine — Bus Ticket Booking Website

A responsive front-end demo built with **HTML, CSS, Bootstrap 5, and vanilla JavaScript**.

## Pages
- `index.html` — Home: route search, dynamic bus results, seat-map selection modal, booking confirmation
- `about.html` — About the (fictional) company
- `login.html` — Login form with validation
- `register.html` — Registration form with password-strength meter + validation

## Notes
- This is a **front-end only** demo — there is no real backend/database, so login, register and payment are simulated in the browser (no data is actually saved or charged).
- All bus operators, prices, and seat availability are sample data generated in `js/script.js` for demonstration.
- To add a real backend later (accounts, payments, live seat inventory), you'd connect the forms in `login.html`/`register.html` and the booking flow in `script.js` to an API (e.g. Node/Express + a database, or a service like Supabase/Firebase).

## How to run it locally
Just open `index.html` in a browser — no build step needed. For best results (so relative paths always work), serve it with a simple local server:

```bash
# Python
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Free hosting + a free domain
I can't create a live hosted URL for you directly, but you can deploy these exact files yourself in a few minutes, for free, with any of the options below:

### Option 1 — GitHub Pages (free subdomain: yourname.github.io)
1. Create a free GitHub account and a new repository.
2. Upload all these files (keep the `css/` and `js/` folders intact).
3. Go to **Settings → Pages**, set the source branch to `main` and folder to `/root`, then save.
4. Your site goes live at `https://yourusername.github.io/repo-name/`.

### Option 2 — Netlify (free subdomain: yourname.netlify.app)
1. Go to netlify.com and sign up free.
2. Drag-and-drop this whole folder onto the "Deploy" area (no git needed).
3. Netlify gives you an instant live URL immediately.

### Option 3 — Vercel (free subdomain: yourname.vercel.app)
1. Go to vercel.com, sign up free.
2. Import the folder/repo and deploy — static sites deploy instantly.

### A truly free custom domain (optional)
Registrars almost never give `.com`/`.in` domains for free, but you can get a **free subdomain** with no cost at all through:
- Freenom-style free TLDs (availability varies by country) — search "free domain name" providers and check current terms, as availability changes.
- Or simplest: use the free subdomain that GitHub Pages / Netlify / Vercel already gives you (e.g. `roadline.netlify.app`) — that's genuinely free and reliable long-term, unlike many "free domain" registrars.

If you'd like, I can also generate step-by-step screenshots-style instructions for whichever of these you pick.
