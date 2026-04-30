# Testing Plan — Phase 1

## Objective

Validate core product assumptions with real users using the frontend prototype before committing to backend development. Focus areas: UX comprehension, trust signal effectiveness, value metric clarity, and navigation behavior.

---

## Research Method

### Qualitative Interviews (Primary)
- Sample size: 8-12 users
- Format: In-person or remote screen-share sessions
- Duration: 30-45 minutes per session
- Recruitment: Across all 4 target personas (Busy Professional, Gym-goer, Diabetic/Health-conscious, Allergen-sensitive)

**Session structure:**
1. Brief intro — no product context given upfront (avoid bias)
2. User given prototype link and asked to think aloud while navigating
3. Specific task prompts given at key flows (e.g., "Find a meal that fits your goals and add it to cart")
4. Post-session debrief questions

### Click and Behavior Tracking (Secondary)
- Heatmaps and click tracking via Lovable preview
- Metrics to observe:
  - Filter bar usage rate (do users filter or browse all?)
  - PDP scroll depth (do users read nutrition info or stop at the image?)
  - Swap option engagement (do users interact with protein/carb swaps?)
  - Price-per-macro click-through (do users notice and engage with it?)
  - Trust panel visibility (do users scroll to see kitchen provenance?)

---

## Key Questions to Answer

| Question | How It Is Tested |
|---|---|
| Do users understand what they will receive in terms of portion and nutrition? | Comprehension check post-PDP viewing |
| Do trust signals (FSSAI, audit date, kitchen name) increase confidence? | Direct question + observed hesitation during session |
| Does price-per-macro resonate as a value metric? | Reaction observation + direct question |
| Do preset filters reduce choice overload vs browsing all meals? | Click tracking + observed behavior |
| Is the onboarding flow low enough friction to complete? | Completion rate + dropout point tracking |
| Does the swap feature add value or create confusion? | Observed usage + comprehension check |

---

## Comprehension Check Questions

Asked verbally after the user views the Meal Detail Page:

- "If you ordered this meal, what portion size would you expect to receive?"
- "What does the nutrition information tell you about this meal?"
- "How confident are you that this meal matches your dietary goal?"
- "What does the kitchen information on this page mean to you?"

---

## Bias Prevention

- No product description or framing given before session starts
- Moderator avoids leading questions
- Users recruited across personas — not just health enthusiasts
- Sessions conducted independently — participants do not see each other's responses
