# Improvement Recommendations

**Prepared by:** Ruknuddin Asrari

## Priority 1 - Responsive CTA
Use flexible sizing, `min-height`, responsive font sizing, and spacing rules so the primary CTA does not wrap or overflow at 320-430px widths.

## Priority 2 - Normalize Form Controls
Apply consistent `min-height`, padding, font inheritance, and line-height to inputs, selects, and buttons. Avoid relying solely on browser-native dimensions.

## Priority 2 - Stabilize Card Layout
Use CSS Grid/Flexbox alignment rules and a consistent card minimum height so text wrapping does not produce uneven rows at tablet widths.

## Priority 3 - Improve Focus Styling
Use a visible focus ring with `outline-offset` and ensure parent containers do not clip keyboard focus indicators.

## Regression Recommendation
Retest Chrome, Edge, and Firefox at desktop, tablet, and mobile widths after fixes. Confirm buttons, links, forms, images, text wrapping, keyboard focus, and responsive navigation.
