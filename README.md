# Frontend Toolchain

Tools and references for common frontend tasks.

Each entry helps with a specific task. The list favors useful recommendations over volume.

## Contents

- [Audit a website](#audit-a-website)
- [Performance](#performance)
- [Testing](#testing)
- [Accessibility](#accessibility)
- [Security](#security)
- [SEO and metadata](#seo-and-metadata)
- [HTML and CSS](#html-and-css)
- [Cheatsheets](#cheatsheets)
- [Development tools](#development-tools)
- [AI-assisted development](#ai-assisted-development)
- [Images, fonts, and icons](#images-fonts-and-icons)
- [UI and visual assets](#ui-and-visual-assets)
- [APIs and test data](#apis-and-test-data)
- [Learning and references](#learning-and-references)
- [Contributing](#contributing)

## Audit a website

- [Lighthouse](https://developer.chrome.com/docs/lighthouse/) — Audit performance, accessibility, SEO, and best practices in Chrome or from the command line.
- [PageSpeed Insights](https://pagespeed.web.dev/) — Compare lab diagnostics with real-user Core Web Vitals when field data is available.
- [WebPageTest](https://www.webpagetest.org/) — Inspect loading behavior across browsers, locations, and network conditions.
- [Nu HTML Checker](https://validator.w3.org/nu/) — Find markup conformance errors in HTML documents.

## Performance

- [web.dev: Learn Performance](https://web.dev/learn/performance/) — Practical guidance on loading, rendering, and Core Web Vitals.
- [Chrome DevTools Performance](https://developer.chrome.com/docs/devtools/performance/) — Record and investigate runtime performance in the browser.
- [Core Web Vitals](https://web.dev/articles/vitals) — Learn the user-centered metrics used to assess loading, interactivity, and visual stability.
- [HAR Analyzer](https://toolbox.googleapps.com/apps/har_analyzer/) — Inspect HTTP Archive files to investigate network requests.

## Testing

- [Playwright](https://playwright.dev/) — Run end-to-end tests in Chromium, Firefox, and WebKit.
- [Vitest](https://vitest.dev/) — Run unit and component tests with a Vite-compatible test runner.
- [Testing Library](https://testing-library.com/) — Test UI through the same interactions users rely on.

## Accessibility

- [W3C WAI: Evaluation Tools](https://www.w3.org/WAI/test-evaluate/tools/) — Browse accessibility evaluation tools and their capabilities.
- [axe DevTools](https://www.deque.com/axe/devtools/) — Find common accessibility issues with axe-powered browser tooling.
- [WAVE](https://wave.webaim.org/) — Get visual feedback about accessibility issues on a public page.
- [A11Y Project Checklist](https://www.a11yproject.com/checklist/) — Use a practical checklist while building and reviewing websites.
- [WCAG 2.2](https://www.w3.org/TR/WCAG22/) — Read the W3C Web Content Accessibility Guidelines.

Automated checks can catch only some accessibility issues. Include keyboard and assistive technology review in a real audit.

## Security

- [HTTP Observatory](https://developer.mozilla.org/en-US/observatory/) — Scan a site for security headers and related configuration issues.
- [SSL Labs Server Test](https://www.ssllabs.com/ssltest/) — Review a public server's TLS configuration.

## SEO and metadata

- [Google Rich Results Test](https://search.google.com/test/rich-results) — Check structured data that may enable Google rich results.
- [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/) — Inspect and refresh the information used for Facebook link previews.
- [Open Graph Protocol](https://ogp.me/) — Reference for Open Graph metadata used by social platforms.
- [Open Graph Generator](https://webcode.tools/generators/open-graph) — Generate Open Graph metadata for a page.

## HTML and CSS

- [Can I use](https://caniuse.com/) — Check browser support for web platform features.
- [Baseline](https://web.dev/baseline/) — Check whether web platform features are supported across browsers.
- [Browser Default Styles](https://browserdefaultstyles.com/) — Compare built-in browser styles for HTML elements.
- [MDN Box-shadow Generator](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Backgrounds_and_borders/Box-shadow_generator) — Build and preview CSS box shadows.
- [Cubic Bezier](https://cubic-bezier.com/) — Create and preview cubic-bezier timing functions.
- [Easings](https://easings.net/) — Explore common easing functions with visual examples.
- [CSS Gradient](https://cssgradient.io/) — Build and preview CSS gradients.

## Cheatsheets

- [Devhints](https://devhints.io/) — Search concise guides for JavaScript, CSS, React, TypeScript, and developer tools.
- [Flexbox Cheatsheet](https://flexbox.malven.co/) — Look up Flexbox properties and see how they affect layout.
- [Grid Cheatsheet](https://grid.malven.co/) — Look up CSS Grid properties with visual examples.
- [MDN Regular Expressions Cheat Sheet](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions/Cheatsheet) — Find JavaScript regular expression syntax and examples.

## Development tools

- [Biome](https://biomejs.dev/) — Format and lint JavaScript, TypeScript, and related files with one tool.
- [Chrome DevTools Local Overrides](https://developer.chrome.com/docs/devtools/overrides/) — Mock or edit network resources locally to test frontend changes without changing the server.
- [Bundlephobia](https://bundlephobia.com/) — Check an npm package's impact on bundle size before adding it to a project.

## AI-assisted development

- [Figma Make](https://www.figma.com/make/) — Turn prompts and designs into interactive, editable frontend prototypes.
- [Playwright Test Agents](https://playwright.dev/docs/test-agents) — Explore an app, plan test coverage, and generate or repair Playwright tests.

## Images, fonts, and icons

- [Squoosh](https://squoosh.app/) — Compare image formats and compression settings in the browser.
- [TinyPNG](https://tinypng.com/) — Compress PNG, JPEG, WebP, and AVIF images online.
- [RealFaviconGenerator](https://realfavicongenerator.net/) — Generate favicon assets and markup for common platforms.
- [Google Fonts](https://fonts.google.com/) — Browse and use open font families.
- [Fontsource](https://fontsource.org/) — Self-host open-source fonts through packages.
- [Tabler Icons](https://tabler.io/icons) — Browse open-source icons available as SVGs and packages.
- [Lucide](https://lucide.dev/) — Browse a consistent set of open-source icons.
- [Simple Icons](https://simpleicons.org/) — Find SVG icons for popular brands.

## UI and visual assets

- [Storybook](https://storybook.js.org/) — Develop and document UI components in isolation.
- [shadcn/ui](https://ui.shadcn.com/) — Copy-ready UI components and patterns for React projects.
- [Open Props](https://open-props.style/) — Copy-ready CSS custom properties for design tokens and common styles.
- [Unsplash](https://unsplash.com/) — Find photography for prototypes and visual assets.
- [DiceBear](https://www.dicebear.com/) — Generate customizable avatar illustrations.
- [GLTF Viewer](https://gltf.pmnd.rs/) — Preview glTF and GLB 3D assets in a browser.

## APIs and test data

- [Hoppscotch](https://hoppscotch.io/) — Send and inspect HTTP requests from a browser-based API client.
- [Mock Service Worker](https://mswjs.io/) — Mock network requests in development and tests.
- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) — Use a fake REST API for quick prototypes.
- [Random User Generator](https://randomuser.me/) — Generate sample user data for demos and prototypes.
- [Stripe Test Cards](https://docs.stripe.com/testing) — Use documented test payment methods in Stripe integrations.
- [PayPal Sandbox](https://developer.paypal.com/tools/sandbox/) — Test PayPal integrations in a sandbox environment.

## Learning and references

- [MDN Learn Web Development](https://developer.mozilla.org/en-US/docs/Learn_web_development) — Learn core web technologies with structured guides.
- [web.dev](https://web.dev/) — Read guidance and tutorials on building for the modern web.
- [Frontend Checklist](https://github.com/thedaviddias/Front-End-Checklist) — Review a broad checklist of quality considerations for websites.
- [Frontend Awesome](https://github.com/felipefialho/frontend-awesome) — Browse a larger community-curated collection of frontend tools and resources.
- [Frontend Dev Bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) — Explore a comprehensive, manually curated frontend reference collection.

## Contributing

To suggest a resource, open a pull request and follow [CONTRIBUTING.md](CONTRIBUTING.md).
