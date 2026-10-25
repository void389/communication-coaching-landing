# Speakwell landing page concept

An editable, responsive landing-page design for a human communication coaching marketplace. Open `docs/index.html` directly or serve the `docs` folder from any static host.

## Structure and final copy

1. **Hero:** “Say what you mean. When it matters.” Primary CTA: **Find your coach**.
2. **Goal chooser:** Interviews, negotiation, and debating framed around the learner’s next real conversation.
3. **How it works:** Choose a focus, find a human coach, and practice together.
4. **Coach discovery:** Three clearly labeled placeholder profiles and an Explore all coaches CTA.
5. **AI support:** AI assists coaches with lesson planning, class insights, progress notes, and paperwork; the coach still leads every session.
6. **Closing CTA:** “Ready to practice with someone in your corner?”

## Visual direction

- **Layout:** Editorial hero, circular conversation composition, generous spacing, three-up goal cards, human profiles before AI explanation, and a large closing CTA. Mobile collapses to a single column with a compact menu.
- **Typography:** Instrument Serif for warm, conversational headlines; DM Sans for clear interface copy. CSS includes sensible Georgia/Arial fallbacks.
- **Color:** Deep evergreen (#142d2a), warm paper (#f6f1e7), coral (#ee725a), ochre (#efbd53), and mint (#a7d6c7). The palette feels capable without becoming corporate or clinical.
- **Imagery:** Use candid, naturally lit moments between two people. Avoid futuristic AI imagery. Current coach portraits are deliberate labeled placeholders.
- **Interface:** Rounded CTAs, high-contrast focus states, restrained cards, short descriptive links, and a responsive mobile menu.

## Content safeguards

No credentials, testimonials, outcomes, ratings, prices, matching claims, or customer results are invented. Unknown coach/profile content and the working brand/legal details are explicitly marked as placeholders.

## Verification

Run `npm test` to validate the required sections, human-first language, placeholder labeling, responsive stylesheet, page metadata, and local asset links. Run `npm run capture` while `npm start` is active to export 1440px desktop and 390px mobile PNGs into `screenshots/`.
