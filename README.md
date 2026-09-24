# Atlas of Westfalia — final review, 24 September 2026

## Upload to GitHub
Unzip this package. Upload its contents to your repository with index.html at the root, alongside assets/, terms.html, privacy.html and the two assistant JavaScript files. In Settings → Pages select Deploy from a branch, main, /(root). GitHub will supply the public website address. This package has not been deployed for you. No build command is needed.

## Current behaviour
Stories and edits are saved in the visitor’s browser. Photos last only in the current page. #FoundAnotherWestfalia is included in saved story tags and generated share captions/cards. Search, filters, local saves, map/list switching, book previews and the bag work locally. The detailed street map needs an internet connection.

Payments, deferred PayPal authorisations, email registration and remote story delivery are NOT connected. No order, email, reservation or subscription is created. Book reservations and farm/launch registrations are marked as opening soon. Workshop RSVP previews only save a local plan.

## Services to connect before accepting orders or submissions
- Create and verify hi@atlasofwestfalia.com.
- Add a server-backed story submission/moderation service with delivery errors and notifications if stories should reach the team.
- Connect an opt-in email list with unsubscribe and test delivery.
- Confirm USD prices, stock, shipping, tax, seller details and return/cancellation policies. Intended PayPal account: shannonrbarnett@gmail.com. No Stripe checkout is offered.
- Deferred book payment needs PayPal vaulting, explicit amount/timing consent, secure server-side tokens, release reminders, cancellation links and duplicate-charge protection. Keep payments closed until verified.
- Confirm workshop, farm and launch arrangements. No public private-address listing is included.
- Review policy pages for the actual operator and services before launch.

## Visitor ChatGPT assistant
See docs/CHATGPT-SETUP.md and docs/ATLAS-ASSISTANT.md. No assistant has been published from this package. Once you have its public GPT link, paste it into assistant-config.js. A footer link then appears automatically. Empty or invalid URLs show no link. ChatGPT access is subject to the visitor’s account, region and service limits; this is not a guarantee of anonymous unlimited chat.

## Checks and limitations
48 automated syntax and interaction checks passed in a simulated document. The packaged edition is checked separately using docs/check.cjs. Desktop/mobile layout and native camera/file/share features have not been verified in a real browser here. Live payment, email and external-link delivery are untested. Test on a real phone and desktop before public launch.

All image assets are local and below GitHub’s per-file upload limit. Preserve the photo credits and MAPLIBRE-LICENSE.txt. Copyright remains with respective creators; there is no blanket Creative Commons licence for the whole site.
