# Fly Duel — support & privacy

The two pages the App Store requires for Fly Duel, kept in their own public
repository so the game's source can stay private.

- `index.html` — support page (the App Store **Support URL**)
- `privacy.html` — privacy policy (the App Store **Privacy Policy URL**)

Served by GitHub Pages from the default branch. Both must stay reachable
without a login for as long as the app is on sale: Apple re-checks them on
every update, and a dead link fails review.

Fly Duel collects no data. The policy says so because it is true, not as a
formality — the app has no networking code at all.
