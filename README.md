# Veggies First review

The review dashboard for [Veggies First](https://github.com/matthewsb419/veggies-before-dessert): bug reports, feature ideas, creator attribution. One static page, served by GitHub Pages; it signs in with Supabase Auth and the database policies decide what a signed-in reviewer can see. The key in the page is the publishable one.

The source of truth is `dashboard/index.html` in the app repo; copy it here to update.

## On the phone

The page is installable: in Safari on the iPhone, Share → **Add to Home Screen** puts it there as an app (standalone, no browser bars; the page shows a one-time hint). `manifest.webmanifest` and `icons/` (made from the app's icon) are what make it installable; the bar has a ↻ since a home-screen app has no reload. Sign-in persists between opens.
