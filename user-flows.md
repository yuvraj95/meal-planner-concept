# User Flows — Meal Planner Concept

All flows are static and frontend-only in Phase 1. Data is pre-filled mock content across approximately 12 meals for 3 personas.

**Live Prototype:** [meal-flow-validator.lovable.app](https://meal-flow-validator.lovable.app)

---

## Flow 1 — Onboarding

**Goal:** Capture user preferences with minimal friction while establishing consent and trust.

1. User opens app for the first time
2. Enters name
3. Selects diet goal (High Protein / Low Carb / Diabetic-Friendly / Vegan / No Preference)
4. Selects allergens from checklist (Gluten, Dairy, Nuts, Soy, Shellfish, Eggs)
5. Sets budget preference (rupees per meal: under Rs 150 / Rs 150-250 / Rs 250+)
6. Sees consent microcopy: "We'll use this to personalize your feed. We never share your preferences without permission."
7. Lands on Home / Discovery screen personalized to their selections

**Assumption being tested:** Minimal onboarding steps with clear consent framing increases completion rate.

---

## Flow 2 — Home / Discovery Screen

**Goal:** Surface relevant meals quickly and establish trust before the user browses.

1. User sees two hero carousels:
   - "High-Protein under Rs 199" (personalized based on onboarding goal)
   - "Lunch Near Your Office" (mock GPS-based location)
2. Trust panel widget visible below fold:
   - FSSAI license number
   - Kitchen audit date
   - Hygiene badge
3. User scrolls and sees meal cards with macro chips and allergen icons
4. User taps a filter or carousel item to go to Meal List View

**Assumption being tested:** Visible trust signals (FSSAI, audit date) on the home screen increase confidence before the user has even viewed a meal.

---

## Flow 3 — Meal List View

**Goal:** Enable fast filtering to the right meals without overwhelming the user.

1. User sees meal cards in a grid or list layout
2. Each card shows:
   - Dish image
   - Macro chips: P / C / F values
   - Calories
   - Allergen icons
   - Price per gram of protein
3. Quick filter bar at top: High-Protein / Low-Carb / Diabetic-Friendly / Vegan / Allergen-Safe
4. User taps a filter — list updates to show matching meals only
5. User taps a meal card to go to Meal Detail Page

**Assumption being tested:** Price-per-macro as a visible metric on the card increases engagement from gym-goers and value-conscious users.

---

## Flow 4 — Meal Detail Page (PDP)

**Goal:** Give users enough information to trust the meal and commit to ordering.

1. User sees full meal detail:
   - Portion photo with hand-scale reference for size context
   - Full macro breakdown (protein, carbs, fat, calories)
   - Full ingredient list
   - Allergen callout in a highlighted block
2. Kitchen provenance block: "Prepared at KitchenX, audited 3 days ago"
3. Swap dropdowns:
   - Protein base swap (e.g., Chicken / Paneer / Tofu)
   - Carb base swap (e.g., Rice / Quinoa / Roti)
   - Macro chips update dynamically on frontend to reflect swap selection
4. User taps "Add to Cart"

**Assumption being tested:** Kitchen provenance block and portion photo with scale reference are the key trust drivers that convert hesitant health-conscious users.

---

## Flow 5 — Cart and Checkout

**Goal:** Confirm order details with value reinforcement and schedule delivery.

1. User sees cart with selected meal(s)
2. Price-per-macro line item shown alongside total price
3. "Schedule delivery" selector with static time slots (simulating office-area batching)
4. Privacy confirmation line: "Use my diet preferences to pre-fill my next order"
5. User taps "Place Order" (static — no real transaction)
6. Order confirmation screen shown

**Assumption being tested:** Showing price-per-macro at checkout reinforces value perception at the point of highest intent.

---

## Flow 6 — Post-Meal Feedback

**Goal:** Capture lightweight feedback to validate portion and taste expectations.

1. After "order" confirmation, a static post-meal survey screen appears
2. Two-tap survey:
   - "Did the taste meet your expectations?" (Yes / No)
   - "Did the portion match the photo?" (Yes / No)
3. Optional free-text field for additional comments
4. Thank you screen with a streak badge mock ("3 healthy meals this week!")

**Assumption being tested:** A 2-tap post-meal survey has high completion rates and surfaces the most critical expectation gaps (taste vs reality, portion vs photo).
