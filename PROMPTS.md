<details>
<summary>🚀 AI Enhancement Master Prompt</summary>

You are a senior full-stack UI/UX engineer, AI product designer, and 
conversion rate optimization (CRO) specialist.

I have an existing website. ENHANCE it — do NOT rebuild it from scratch.
Preserve the current visual identity (colors, fonts, logo, navigation 
structure) while applying the following data-backed upgrade layers:

═══════════════════════════════════════════════════════════
LAYER 0: STATISTICAL NORTH STARS (Build every decision around these)
═══════════════════════════════════════════════════════════

Use the following verified 2025–2026 benchmark statistics to guide 
every design and engineering choice in this project:

SPEED & PERFORMANCE
  • Sites loading in ≤1s convert 3× higher than those loading in 5s
  • 53% of users abandon pages that take longer than 3 seconds to load
  • Every 1-second improvement in load time raises conversions by 4–7%
  • 85% of websites are slower than Google's 5s recommendation — 
    beating this alone puts you in the top 15%

MOBILE vs DESKTOP
  • Mobile drives ~65% of traffic but converts at only 2.49%
  • Desktop converts at 5.06% — the gap is the opportunity
  • Mobile-optimized checkout flows increase conversions by 22%
  • Sticky CTAs improve mobile conversions by 12%
  • Apple Pay / Google Pay integration lifts mobile conversions by 21%
  • Mobile-first page designs outperform desktop-first by 17%

PERSONALIZATION
  • Personalized experiences can increase conversion rates by 200%+
  • AI-driven product/content recommendations produce a 19% lift
  • Personalized emails convert 18% better than generic ones
  • Stores with AI recommendations see 19% higher revenue per session

UX & DESIGN
  • UX improvements alone can raise conversions by 30%
  • Heatmap-optimized pages convert 14% higher
  • Reducing above-the-fold clutter improves engagement by 16%
  • Consistent design elements boost trust and conversions by 10%
  • Improving readability increases conversions by 7%
  • Users trust images of real people 20% more than stock photos
  • Rewriting micro-copy (labels, CTAs, error messages) yields 8% lift

CTAs & LANDING PAGES
  • CTA copy A/B tests produce an average 12% lift
  • Headline tests produce an average 9% lift
  • Adding CTAs above the fold has delivered 138% conversion uplift 
    (real case: Enhance Insurance, UK)
  • Top-performing landing pages achieve 11.45%+ conversion rates
  • Increasing landing pages from 10 to 15 boosts leads by 55%
  • Layout redesign tests produce the largest lifts: 18–40%

FORMS & FRICTION
  • Shortening sign-up forms boosts B2B conversions by 27%
  • Autofill-enabled fields boost form completion by 12%
  • Guest checkout increases conversions by 18%
  • Showing total cost early reduces abandonment by 19%
  • 24% of users abandon due to unexpected fees — eliminate them

SOCIAL PROOF & TRUST
  • Case studies increase B2B landing page conversions by 22%
  • Users who interact with UGC (reviews, photos, videos) are 102% 
    more likely to convert
  • Placing testimonials above lead-gen forms increased submissions 
    by 50% (case: Hotel Institute Montreux)
  • Trust signals at checkout increase conversions by 9%
  • Streamlining navigation increased demo clicks by 63.27% 
    (case: Orah student platform)

TESTING & ITERATION
  • Companies running 10+ tests/month grow 2.1× faster
  • AI-assisted test ideation increases win rates by 23%
  • Multivariate tests increase long-term learnings by 28%

INDUSTRY BENCHMARKS (Know what you're beating)
  • Average eCommerce: 2.96%
  • Average SaaS: 9.5%
  • Average B2B services: 4.94%
  • Average finance: 10%
  • Average social media channel: 2.4%
  • High-performing eCommerce stores: 5–7%
  • Seamless UX can boost conversions by up to 400%

═══════════════════════════════════════════════════════════
LAYER 1: RESPONSIVE DESIGN (Phone + PC, Mobile-First)
═══════════════════════════════════════════════════════════
Guided by statistics: close the mobile/desktop 2.49% vs 5.06% gap

- Apply mobile-first CSS using fluid grids and CSS clamp() for 
  type scaling
- Breakpoints: 320px / 768px / 1024px / 1440px+
- Touch-friendly tap targets (min 44×44px), swipe gestures, 
  thumb-zone nav
- Implement sticky CTAs on mobile scroll — proven +12% conversion lift
- Add Apple Pay / Google Pay detection and render digital wallet 
  buttons on mobile — proven +21% lift
- Optimize for ≤1s load: lazy-load images, defer non-critical JS, 
  inline critical CSS
- Skeleton loaders and aspect-ratio CSS to prevent layout shifts
- Collapsible hamburger nav on mobile with smooth transitions
- Performance budget: Lighthouse ≥ 90 on mobile, ≥ 95 on desktop
- Streamline navigation structure — fewer clicks to key CTAs 
  (Orah case: +63% demo clicks from nav simplification alone)

═══════════════════════════════════════════════════════════
LAYER 2: AI-DRIVEN PERSONALIZATION & HYPER-PERSONALIZATION
═══════════════════════════════════════════════════════════
Guided by statistics: personalization = up to 200%+ conversion lift;
AI recommendations = 19% revenue lift

- Build a client-side personalization engine (personalization.js):
    * Signals: device type, time of day, visit frequency 
      (localStorage), referral source (UTM / document.referrer), 
      scroll behavior from previous sessions
    * Use signals to dynamically swap: hero headline, CTA text, 
      featured content, onboarding prompt, social proof variant
    * Time-aware messaging: "Good morning, here's where to start" 
      vs evening re-engagement messaging
    * Returning visitor mode: skip the intro, surface last-viewed 
      content and next logical step
    * AI content recommendations panel: "Based on your behavior, 
      you might also need..." (client-side, privacy-first)
- Preferences onboarding: let users self-segment 
  (e.g., "I'm a [Student / Professional / Enterprise]") → persist 
  to localStorage → swap relevant content blocks
- Real people imagery rule: Replace any stock photos with 
  contextual real-people imagery — +20% trust signal per stats
- All personalization: zero external tracking, fully client-side, 
  GDPR-safe

═══════════════════════════════════════════════════════════
LAYER 3: BEHAVIORAL ANALYTICS TO OPTIMIZE USER FLOWS
═══════════════════════════════════════════════════════════
Guided by statistics: heatmap-optimized pages convert 14% higher;
companies testing 10+ times/month grow 2.1× faster

- Build analytics.js — a lightweight, zero-dependency tracker:
    * Events: page views, scroll depth (25/50/75/100%), 
      click coordinates (heatmap), CTA clicks, form starts/abandons, 
      time-on-section, device/viewport
    * Persist events in localStorage with session timestamps
    * Auto-identify cold CTAs (low click-rate) vs hot zones 
      (high engagement)

- Developer Analytics Dashboard (Shift+Alt+D):
    * Heatmap overlay: color-coded click concentration per element
    * Scroll depth funnel: % of sessions reaching each 25% mark
    * CTA performance table: impression vs click vs conversion rate
    * Drop-off report: sections where engagement stops
    * Session count + avg. session duration
    * Export data as JSON for external analysis

- Smart surfacing on return visits:
    * Sections with highest engagement scores auto-increase visual 
      weight (subtle border, background highlight, badge)
    * Underperforming sections get a content refresh prompt 
      in the dashboard

- Exit-intent detection:
    * Desktop: cursor leaves viewport top → trigger soft retention 
      prompt (not a disruptive popup — an inline slide-in)
    * Mobile: rapid scroll-up pattern → surface a value reminder 
      or incentive strip

═══════════════════════════════════════════════════════════
LAYER 4: PROACTIVE, DATA-DRIVEN FEATURE PRIORITIZATION
═══════════════════════════════════════════════════════════
Guided by statistics: AI-assisted ideation = 23% higher win rates;
layout redesign tests = 18–40% lifts; 10+ tests/month = 2.1× growth

- Build a Feature Pulse widget (feature-pulse.js):
    * Minimal floating panel (bottom-right corner, collapsible)
    * Shows top 2–3 features by engagement score from Layer 3 data
    * Surfaces underused features via contextual page-aware tooltips
    * User upvote system (👍 this feature) → stored in localStorage, 
      exportable as JSON to feed into your roadmap

- Priority scoring algorithm:
    Score = (engagement_rate × 0.5) + (user_votes × 0.3) 
            + (recency_weight × 0.2)
    
    * engagement_rate: click + scroll interactions on feature section
    * user_votes: upvotes from Feature Pulse widget
    * recency_weight: higher score for features interacted with in 
      last 7 days

- Visual priority signals:
    * "🔥 Most Used" badge on top-scoring features
    * "↗ Trending" badge on features with rising scores
    * Subtle dim on features scoring below 20% threshold 
      (with a "Tell us what to improve" micro-prompt)

- GitHub Changelog Panel (optional — remove if not needed):
    * Fetches latest releases from your GitHub repo via public API
    * Displays as a "What's new" strip — builds trust and reduces 
      "is this maintained?" doubt
    * Proven trust signal: consistent product updates increase 
      perceived reliability

═══════════════════════════════════════════════════════════
LAYER 5: HIGH-IMPACT CRO QUICK WINS (Baked in by default)
═══════════════════════════════════════════════════════════
Guided by statistics: each of these is independently proven

Apply these as you work through the layers above:

  ✅ Reduce above-the-fold clutter → +16% engagement
  ✅ Improve heading readability (contrast, size, hierarchy) → +7% CVR
  ✅ Add CTAs above the fold on every key page
  ✅ Surface social proof (reviews, testimonials, case studies) above 
     lead-gen forms → +50% form submissions
  ✅ Eliminate hidden fees / show total cost early → -19% abandonment
  ✅ Autofill on all form fields → +12% completion
  ✅ Rewrite all micro-copy (button labels, error messages, 
     placeholder text) to be action-oriented → +8% lift
  ✅ Add product/service videos where possible → +21% conversion
  ✅ Show scarcity/urgency signals where authentic 
     (availability, deadlines) → +11% purchases
  ✅ Trust badges at all conversion checkpoints → +9% CVR
  ✅ Replace stock photos with real-people imagery → +20% trust

═══════════════════════════════════════════════════════════
TECHNICAL CONSTRAINTS
═══════════════════════════════════════════════════════════
- Framework: [INSERT YOUR STACK — e.g., React, Vue, HTML/JS]
- Styling: [INSERT — e.g., Tailwind, CSS Modules, vanilla CSS]
- Preserve existing: colors, typography, logo, nav structure
- Lighthouse target: ≥ 90 mobile / ≥ 95 desktop
- Zero external dependencies unless absolutely necessary
- Graceful degradation when JS is disabled
- Privacy-first: no third-party trackers, all data in localStorage

═══════════════════════════════════════════════════════════
DELIVERABLES
═══════════════════════════════════════════════════════════
1. Updated responsive layout files (mobile-first)
2. personalization.js — AI personalization engine
3. analytics.js — behavioral tracking + heatmap layer
4. feature-pulse.js — priority scoring + widget
5. cro-quickwins.css — utility classes for all Layer 5 improvements
6. ANALYTICS_DASHBOARD.md — how to read and act on your data
7. Inline config comment block at top of each file

Please start by asking me to share my existing codebase or describe 
my current stack, then proceed one layer at a time, validating before 
moving to the next.

</details>
