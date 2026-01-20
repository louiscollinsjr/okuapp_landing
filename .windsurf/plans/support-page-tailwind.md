# Support Page Tailwind Refresh
Bring support.html in line with the Tailwind-styled home page, mirroring the Claude support layout while keeping ATWH? branding and typography.

## Plan
1. **Audit existing support content**: Inventory current sections (nav, search, article blocks, footer) and align needed structure with the Claude example: breadcrumb, hero title, search bar, article body, right-side quick links.
2. **Build Tailwind shell**: Swap legacy CSS for Tailwind CDN + inline utilities matching index.html palette/typography (Manrope + Source Serif 4, background #faf9f6/#f1e9dc, text #151514/#64635f, accent #c35b3d). Recreate nav/footer to mirror index patterns and reuse app icon.
3. **Layout main content**: Add breadcrumb row, serif H1, updated copy blocks for paid plans, note callout, and ordered/ul lists matching the reference layout; add a minimal right rail list for key links.
4. **Search + CTA details**: Implement a faux search bar (non-functional) styled like the reference; include contact CTA blocks (email support, press) matching brand buttons.
5. **Terms/Privacy placeholders**: Add routed links/sections or stub pages and propose generic writing-app-appropriate ToS/Privacy stubs for future fill.

## Open Questions
- Should we include the app icon in nav/footer (like index) or keep text-only brand?
- Do you want stub pages for Terms/Privacy now, and should we link them in both nav and footer?
- Any specific support tiers or contact channels beyond email to call out?
