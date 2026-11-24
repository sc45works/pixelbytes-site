Pixel Bytes: concept repair shop with an AI estimate assistant (SC45WORKS portfolio)
===================================================================================

Pixel Bytes is a fictional computer repair, service and optimization shop on
Sunset Blvd in Silver Lake, Los Angeles. Prices and services are invented,
and the page says so in the top ribbon and footer. The name was checked
against real repair shops in November 2026.

SUGGESTED ADDRESS
  pixelbytes.sc45works.com. The page has a "noindex" tag.

HOW THE ESTIMATE WORKS
  1. The customer picks the device (Windows laptop, MacBook, desktop PC,
     iMac), its age, and describes the problem in their own words.
  2. AI reads the description and names the likely jobs (screen, liquid,
     power, battery, tune-up, malware, heat, keyboard, boot, data, ports,
     upgrade), plus a one-line summary and a "do this now" tip.
  3. Prices come only from the shop's price list (JOBS in index.html), never
     from the AI. Several jobs at once get 10% off for shared labour.
  4. Honest extras: a "worth fixing?" note based on age (5+ years and a big
     bill suggests trade-in; under 2 years suggests checking the warranty),
     a tune-up add-on, and drop-off time slots.
  Without an API key, a built-in keyword matcher does step 2, so the tool
  always works.

DEPLOY
  Same as your other sites: Vercel (GitHub import or "npx vercel"), or
  Netlify via GitHub. Add ANTHROPIC_API_KEY and redeploy.

FOR A REAL SHOP
  Replace JOBS with the shop's real price list, and connect "Book" to its
  calendar (Google Calendar, Cal.com or GoHighLevel). The booking button
  in this concept stores nothing.
