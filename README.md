# MellowFood — Recipe Studio 

## Project Summary

**MellowFood** is a responsive Recipe Studio website that presents recipes through a clean, story-driven “recipe book” experience. Users explore recipes by **seasoning / flavor profile** (e.g., Garlic, Herbs, Spice, Citrus) with strong visual hierarchy, readable layouts, and reusable components. As a bonus feature, the site includes a **Recommendation Engine UI** that shows “Suggested Next Recipe” cards with a confidence label and brief explainability hints — simulated using **HTML + CSS**.

---

## Pages

* **Home (`index.html`)**
  Introduces the recipe-book theme and guides users into the browsing experience.
* **Recipes List (`recipes.html`)**
  Displays recipe cards for visual browsing and selection.
* **Flavors List (`flavors.html`)**
  Displays a flavor profile and guide
* **Details List (`details.html`)**
  Gives a detailed list of everything needed for specific recipes 

---

## Key Features

* **Responsive design (mobile-first)**
* **Reusable components** (cards, badges/tags, layout sections)
* **Global navigation** across all pages
* **CSS transitions & hover effects**

  * Button background fade on hover
  * Card “lift” / elevation effect
  * Navigation underline / emphasis animation (as implemented)
* **Animations / transformations**

  * Subtle hero fade-in
  * Step instruction reveal / slide-in effects (as implemented)
  * Recommendation card entrance animation (as implemented)
* **Recommendation Engine UI (Bonus)**

  * “Suggested Next Recipe” card
  * Confidence label/bar
  * “Why this match?” explainability hints

---

## Screen-to-Screen Transitions 

* **Home → Recipes List** via CTA button
* **Recipes List → Recipe Detail** via recipe card click
* **Recipe Detail → Suggested Recipe** via recommendation UI card/action
* **Global navigation** allows jumping between all pages

---

## Accessibility Notes

* Semantic structure: `header`, `nav`, `main`, `section`, `footer`
* Logical heading order
* Keyboard navigation support with visible focus states (`:focus-visible`)
* Clear hover + active states
* Reduced motion support using `prefers-reduced-motion` (when included)

---

## Testing Plan

### Usability Testing (Peer Feedback)

* Can users navigate from Home → a Recipe without confusion?
* Are recipe steps easy to follow?
* Is the recommendation module easy to understand?

### Responsive Testing

* Verify layout on mobile and desktop screen sizes
* Confirm card grid adapts correctly

### Validation

* Validate HTML with **W3C HTML Validator**
* Check CSS for consistency and reuse

---

## Tech Stack

* **HTML5**
* **CSS3** (transitions, animations, responsive layout)
* No external frameworks required

---

## Team

* **Brock Freiberger**
* **Jay Patel**

---

