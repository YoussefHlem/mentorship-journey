# Mentorship Program · Block 1
## Study Plan

> Work through these topics in order. For each one, make sure you can honestly tick every box before moving on. How you get there — which courses, articles, or videos you use — is up to you.

---

## 01 Responsive Design
*Mobile-first thinking, modern layout primitives, and defensive CSS.*

- [ ] Understand mobile-first vs desktop-first and when each makes sense
- [ ] Can build any layout using CSS Grid and Flexbox without referencing docs
- [ ] Know how to define and apply a consistent breakpoint system across a project
- [ ] Understand responsive images: `srcset`, `sizes`, and the `picture` element
- [ ] Familiar with modern CSS units — `clamp()`, `min()`, `max()`, `svh`, `dvh`
- [ ] Know what container queries solve and when to use them over media queries

---

## 02 CSS Architecture
*Scalable style systems, naming conventions, and design tokens.*

- [ ] Understand BEM naming and can apply it consistently across a codebase
- [ ] Know how ITCSS layers are structured and why the order matters
- [ ] Can design a design token system covering colors, spacing, and typography
- [ ] Understand CSS specificity deeply and know how to keep it flat and predictable
- [ ] Know what CSS Modules and CSS-in-JS solve and the tradeoffs of each
- [ ] Can explain the cascade and work with it intentionally rather than against it

---

## 03 Testing
*Unit, component, and E2E — with a clear philosophy behind what to test and why.*

- [ ] Understand the Testing Trophy and can justify which layer to test at for a given case
- [ ] Can write unit tests for utility functions and custom hooks
- [ ] Can write component tests that assert on behaviour, not implementation details
- [ ] Can write E2E tests covering critical user flows end-to-end
- [ ] Know how to mock APIs, timers, and external dependencies cleanly
- [ ] Can configure a test suite to run in CI with a coverage threshold

---

## 04 Web Performance
*Core Web Vitals, bundle analysis, and runtime profiling.*

- [ ] Understand what LCP, CLS, and INP each measure and how to diagnose them
- [ ] Can audit and reduce bundle size using code splitting and dynamic imports
- [ ] Know how to lazy load images, routes, and components appropriately
- [ ] Can use Chrome DevTools Performance panel to identify rendering bottlenecks
- [ ] Understand the difference between render-blocking and non-blocking resources
- [ ] Know when a virtual list is necessary and how to implement one

---

## 05 Frontend Security
*XSS, CSRF, token storage, and Content Security Policy.*

- [ ] Understand what XSS is and how to prevent it — especially in user-generated content
- [ ] Know the difference between `httpOnly` cookies and `localStorage` for auth tokens and the risk of each
- [ ] Understand what CSRF is, how it works, and how to protect mutations against it
- [ ] Can write and apply a meaningful Content Security Policy header
- [ ] Familiar with the OWASP Top 10 vulnerabilities from a frontend perspective

---

## 06 SEO for Frontend
*Semantic HTML, meta tags, Open Graph, and rendering strategies.*

- [ ] Can write semantic HTML that is meaningful to both crawlers and screen readers
- [ ] Know how to add dynamic meta and Open Graph tags per route in a React app
- [ ] Understand SSR, SSG, and CSR from an indexability standpoint and their tradeoffs
- [ ] Know how JavaScript-heavy apps affect crawlers and how to verify indexing
- [ ] Can implement Twitter/X card and OG tags so link previews render correctly

---

## 07 Monitoring & Observability
*Error tracking, field performance data, and actionable dashboards.*

- [ ] Can integrate Sentry and configure it to capture meaningful, actionable errors
- [ ] Understand the difference between lab data and field data for performance metrics
- [ ] Know what Real User Monitoring is and how it differs from synthetic monitoring
- [ ] Can read a monitoring dashboard and identify what needs to be acted on
- [ ] Know how to set up alerts for critical error rate thresholds

---

## 08 Accessibility (a11y)
*ARIA, keyboard navigation, and screen reader compatibility.*

- [ ] Can navigate any UI using only a keyboard and identify where it breaks
- [ ] Understand semantic HTML and know when ARIA roles are and are not appropriate
- [ ] Familiar with WCAG 2.1 AA success criteria at a working level
- [ ] Can test a component with a screen reader and identify issues
- [ ] Know how to handle focus management in dynamic UIs — modals, drawers, toasts

---

## 09 State Management
*Local, global, and server state — knowing what to use and when.*

- [ ] Understand the distinction between local state, global state, and server state
- [ ] Can implement global state with at least one library (Zustand, Redux Toolkit, or Jotai)
- [ ] Know how to avoid prop drilling without reaching for a global store unnecessarily
- [ ] Understand when NOT to use a global state manager
- [ ] Can explain the tradeoffs between different state management approaches

---

## 10 Real-time Patterns
*WebSockets, SSE, and polling — for live feeds and notifications.*

- [ ] Understand the difference between WebSockets, Server-Sent Events, and polling
- [ ] Can choose the right pattern for a given use case (notifications vs chat vs live data)
- [ ] Can implement a basic WebSocket connection including reconnection logic
- [ ] Know how to handle connection drops, errors, and stale data gracefully

---

## 11 API Integration Patterns
*REST vs GraphQL, pagination, optimistic updates, and caching.*

- [ ] Understand REST vs GraphQL tradeoffs from a frontend implementation perspective
- [ ] Can implement both cursor-based and offset-based pagination
- [ ] Know what optimistic updates are and can implement them with rollback on error
- [ ] Understand stale-while-revalidate, cache invalidation, and when each applies
- [ ] Can handle loading, error, and empty states consistently across the app

---

## 12 Advanced Security
*Supply chain risk, subresource integrity, and OAuth best practices.*

- [ ] Understand what a supply chain attack is and how lockfiles and audits mitigate risk
- [ ] Know what Subresource Integrity (SRI) is and when to apply it
- [ ] Understand the OAuth 2.0 PKCE flow and why it is preferred for SPAs
- [ ] Understand CORS — how it works, why it exists, and how to configure it correctly

---

## 13 Advanced SEO & Structured Data
*JSON-LD, rich snippets, dynamic rendering, and i18n URLs.*

- [ ] Understand what JSON-LD is and can implement it for profiles and content pages
- [ ] Know what rich snippets are and how structured data enables them in search results
- [ ] Can generate a sitemap and configure `robots.txt` for a React app
- [ ] Understand when dynamic rendering is needed and how to implement it
