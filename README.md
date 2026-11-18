# DormNamo

Open `index.html` in a browser (no build step). For GitHub Pages, upload the whole folder.

## Pages
- `index.html`    Rooms: hero + search pill, filters, compare, owners section
- `discover.html` Discover: TikTok-style swipe feed (dark page, like/pass/bookmark/undo)

## CSS (`css/`)
base.css (design system) · home.css (navbar, hero, motion, dark Discover page) · discover.css (swipe cards) · ui.css (login/questionnaire, menus, toast) · chat.css (Namo)

## JS (`js/`, loaded in the order listed in each HTML file)
- data.js listings (replace with your database) · utils.js helpers · details.js listing dialog · browse.js Rooms list/filters
- matching.js facts, must-have filters, weighted score, explanations · twotower.js Two-Tower model · state.js per-user state
- discover.js swipe deck · accounts.js sign up/log in (localStorage; swap for a real backend)
- auth.js login screen · onboarding.js questionnaire (edit `STEPS`) · nav.js navbar (edit `TABS`) · fx.js animations
- chat.js Namo, the preference chatbot (edit the `WORDS` lists to teach it new words)
- main.js start-up: login -> questionnaire -> page
