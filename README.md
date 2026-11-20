# 🌿 Petite Manie

**Conceptual redesign of a restaurant website in Fleurier, Switzerland**



A dark green palette with absinthe and apricot accents, lively animations, and a 3D burger rotating endlessly on the home screen.



`HTML` · `CSS` · `JavaScript` · `three.js`

&#x20; &#x20;

---

## About the project

The original [petitemanie.ch](https://www.petitemanie.ch) website felt a little empty: the home screen had no text or buttons. I reimagined it in a more modern and appetizing style while preserving **all of its content**: the full menu with prices and dietary notes, the team, contact details, opening days, and social media links.

> This is an educational portfolio project. It is not the restaurant’s official website. The text and information are from petitemanie.ch.

### Design

- **A considered palette**: deep green, absinthe, and a warm apricot accent. Absinthe was chosen for a reason: the menu includes trout with absinthe sauce, and Fleurier is considered the birthplace of the drink.
- **A complete home screen**: the restaurant name, description, two calls to action, and opening-day badges replace the empty splash screen.
- **Typography**: expressive Fraunces for headings and clean DM Sans for body text.
- **Light and dark themes**: the site adapts to the device’s settings.

### Animations

- A **three.js** 3D burger that rotates and gently bobs in an endless loop, with shading and a vignette to keep the text readable.
- Floating particles, a scrolling marquee, cascading section reveals on scroll and menu-card reveals when switching tabs, plus a pulsing primary button.
- Animation pauses when the home screen is out of view to reduce device load.

### Usability

- **Tabbed menu**: Entrées, Plats, Menu enfant, Desserts. The data is stored in a single JS object, making dishes and prices easy to update.
- Clickable contact details: call, email, and open directions in Google Maps with a single tap.
- **Responsive layout** for phones, tablets, and computers.
- **Accessibility** features include semantic markup, keyboard focus, and aria attributes. The site also respects “reduce motion”: animations are disabled and the burger remains static.
- If the 3D library fails to load or WebGL is unavailable, a fallback illustration is shown.

### Simplicity

- A single `index.html` file, with no build step or dependencies. The only external resources are Google Fonts and three.js via CDN.
- Open it directly in a browser or deploy it to Vercel, Netlify, or GitHub Pages in a couple of minutes.

## How I worked

I created this project with the help of artificial intelligence (Claude by Anthropic). I used it to move faster from the idea to a working prototype. AI helped with the initial code, the 3D scene, and the animations, while I defined the concept and requirements, chose the direction, and reviewed the result. This approach let me focus on the design and details instead of routine work.
What could be improved

- Add real food and interior photos
- Add online table reservations
- Add multiple language versions (FR / EN / DE)
- Add actual opening hours once they are confirmed
