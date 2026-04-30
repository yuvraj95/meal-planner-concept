# Feature Scope — Phase 1

## Approach

Phase 1 is a frontend-only validation prototype. The goal is to test assumptions about UX clarity, trust signals, and value framing with real users — without building any backend infrastructure. Every scope decision below is made to maximize learning speed and minimize build cost.

---

## In Scope

| Feature | Details |
|---|---|
| Interactive, tappable UI | Built in Lovable — fully navigable, no API calls, no backend persistence |
| Pre-filled static meal data | Approximately 12 meals across 3 personas (Gym-goer, Busy Professional, Diabetic-Friendly) |
| Onboarding flow | Name, diet goal, allergen checklist, budget preference, consent microcopy |
| Home / Discovery screen | Hero carousels, trust panel widget (FSSAI, audit date, hygiene badge) |
| Meal List View | Macro chips, allergen icons, price-per-macro, dietary filter bar |
| Meal Detail Page | Portion photo, macro breakdown, ingredient list, allergen callout, kitchen provenance block |
| Swap dropdowns | Protein base and carb base swaps with frontend macro simulation |
| Cart and Checkout | Schedule delivery selector, price-per-macro line item, privacy confirmation |
| Post-meal feedback | 2-tap survey, optional text field, streak badge mock |
| Trust signal UI | FSSAI license, kitchen audit date, hygiene badge |

---

## Out of Scope — Phase 1

| Feature | Reason Deferred |
|---|---|
| Real ordering and payment | Not needed to test UX and trust assumptions |
| Live kitchen inventory | Backend dependency — unnecessary for Phase 1 |
| Account creation and login persistence | Adds friction to prototype testing — not the assumption being tested |
| Actual delivery tracking | Post-validation feature |
| Real GPS location | Mock location sufficient for Phase 1 testing |
| Backend API calls | Static data covers all Phase 1 test scenarios |

---

## Phase 2 Considerations (Post-Validation)

If Phase 1 success criteria are met, Phase 2 would introduce:
- Backend with real menu, inventory, and ordering
- User accounts with preference persistence
- Real payment integration
- Live kitchen data and audit feed
- GPS-based delivery slot optimization
- Personalization engine based on order history and feedback data
