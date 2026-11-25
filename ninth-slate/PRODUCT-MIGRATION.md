# Ninth Slate — Product Migration Plan

Goal: move product identity under Ninth Slate without breaking development workflows or exposing private material.

## Migration rules

For every product:
1. Preserve working repository history
2. Do not transfer repositories blindly
3. Map CI, secrets, deploy providers and branch protections first
4. Update branding inside the product only when the product team is ready
5. Keep release status truthful
6. Separate public product name from private repository name when useful
7. Review screenshots before publication
8. Do not expose client or operational data
9. Add Ninth Slate attribution only after product-level review

---

## Academy Learning

**Target attribution:** A Ninth Slate product  
**Primary division:** Ninth Slate Software  
**Secondary division:** Ninth Slate AI

### Public identity
Keep "Academy Learning" as product brand unless a later commercial naming review changes it.

### Migration steps
- Replace founder-first attribution with Ninth Slate product attribution
- Add Ninth Slate brand to storefront/about/legal surfaces
- Keep commercial-preview status accurate
- Do not claim production availability before launch gates are green
- Keep AI provider/cost/privacy gates explicit internally
- Review domain, payments and privacy separately before launch

### Repository
Do not transfer until CI/deploy integrations are mapped.

---

## Remember

**Target attribution:** A Ninth Slate product  
**Division:** Ninth Slate Software

### Public identity
Current product name may remain, but founder identity should not be the product brand.

### Migration steps
- Replace personal attribution in product-facing surfaces
- Add Ninth Slate in About / legal / splash surfaces
- Review mobile package identifiers before any brand-level rename
- Preserve existing Supabase/Capacitor configuration unless intentionally migrated

### Repository
Private. Transfer only after mobile signing/deploy dependencies are understood.

---

## Fitness AI App

**Target attribution:** Ninth Slate AI / Ninth Slate Software

### Public identity
"Fitness AI App" should be treated as a working/internal name until a final commercial name is selected.

### Migration steps
- Run product naming exercise
- Define whether AI is the primary value proposition or supporting feature
- Keep hosting-offline status private unless relevant
- Rebrand only after product direction is fixed

---

## Valleverde

**Target attribution:** Ninth Slate Interactive

### Public identity
Keep "Valleverde" as the game identity.

### Migration steps
- Add "Ninth Slate Interactive" to splash/about/credits when appropriate
- Keep existing game/release workflow untouched during brand migration
- Do not transfer repository until Unity CI/build assumptions are mapped
- Prepare separate public game page later

---

## Business Management System

**Target attribution:** Private engineering by Ninth Slate Software

### Public identity
Do not expose client/internal operating details.

### Migration steps
- Use generic case-study language only
- Never publish sensitive business logic or personnel data
- Do not rename internal system merely for marketing
- Treat as proof of engineering capability, not a public consumer product

---

## I Rapaci di Eddy

**Target attribution:** Client work / public case study

### Public identity
Client brand remains primary.

### Migration steps
- Keep site ownership/client identity unchanged
- Ninth Slate may later list it as client work
- Do not over-brand the client's website
- Keep credit subtle and only if appropriate

---

## Repository-transfer gate

Before moving any repository to a future Ninth Slate GitHub Organization, document:
- default branch
- branch protections
- GitHub Actions
- secrets
- deploy hooks
- Supabase/Vercel/Netlify/Render integrations
- package identifiers
- release artifacts
- external webhooks
- issue/PR references
- local clone remotes

Transfer only after this checklist is complete.
