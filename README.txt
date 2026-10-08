ASIA GROUP OF EVENTS — GITHUB READY

This build is static and can be deployed directly to GitHub Pages.

NEW IN THIS VERSION
- Interactive accessible AGE history timeline with keyboard-friendly <details> controls and filters.
- Privacy-first cookie consent banner. No analytics, advertising cookies, or social SDKs are enabled.
- Booking/contact forms use mailto and include explicit privacy + age/guardian consent.
- Data Rights page for access, correction, and deletion requests.
- Blog email preference page for subscribe/unsubscribe requests.
- Refund/cancellation policy and transparent-pricing language.
- Media & Licenses audit page.
- Instagram is a direct link only; no Instagram SDK/embed is loaded.
- No remote images or font SDKs are embedded in this build.
- CSS uses local system font stacks and original CSS artwork.
- Accessibility improvements: skip link, keyboard focus states, semantic controls, reduced-motion support, labels, and stronger contrast.
- Demo payment page collects no card data and does not process money.

IMPORTANT
- The static forms open the visitor's email application. They do not store submissions.
- For production booking/payment, use a proper backend and a supported payment provider. Never put payment secret keys in GitHub Pages HTML/JS.
- Legal pages are general website drafts and should be reviewed by AGE's Pakistani legal adviser before production use.

MAIN FILES
index.html — Home
about.html — About + interactive timeline
brands.html — Brands
services.html — Services
portfolio.html — Portfolio
blog.html — Blog + email preferences link
booking.html — Booking enquiry + consent
contact.html — Contact enquiry + consent
payment-demo.html — Non-payment demo checkout
privacy.html — Privacy Policy
terms.html — Terms of Use
cookies.html — Cookie Policy
refund-policy.html — Booking/Cancellation/Refund Policy
data-rights.html — Data access/correction/deletion request
newsletter.html — Blog email subscribe/unsubscribe request
copyright.html — Media/font/third-party license notice
styles.css — Shared styles
script.js — Shared navigation, consent banner, timeline, and static form helpers
assets/logo.png — AGE logo supplied for the project


Third-party audit: third-party.html

Before deployment: edit config.js and replace G-REPLACE_ME and ca-pub-REPLACE_ME with AGE's actual Google Analytics and AdSense identifiers. Do not add secret keys to this repository.
