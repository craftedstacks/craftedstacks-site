# Crafted Stacks website

Static product and support website for Crafted Stacks and Measured.

## Local preview

```bash
python3 -m http.server 5180
```

Open `http://127.0.0.1:5180/`.

## Public routes

- `/` — Crafted Stacks home
- `/measured/` — Measured product page
- `/measured/privacy/` — App Store privacy policy
- `/measured/support/` — App Store support page
- `/measured/terms/` — Terms of use

## Before publishing

1. Point `craftedstacks.net` and `www.craftedstacks.net` to the selected host.
2. Configure `support@craftedstacks.net` or replace it with a working support address.
3. Confirm Azure telemetry retention is no more than 90 days.
4. Replace the App Store launch status and add the final App Store URL after approval.
5. Review the privacy policy and terms with qualified counsel before launch.
