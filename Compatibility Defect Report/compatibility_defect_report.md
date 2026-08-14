# Compatibility Defect Report

**Prepared by:** Ruknuddin Asrari

| ID | Defect | Browser(s) | Severity | Priority | Status |
|---|---|---|---|---|---|
| CB-001 | Mobile CTA overflows/wraps at narrow viewport | Chrome / Edge / Firefox | High | P1 | Open |
| CB-002 | Form select height differs from text input in Firefox compatibility scenario | Firefox | Medium | P2 | Open |
| CB-003 | Service card text wrapping causes uneven card heights at tablet width | Firefox / Tablet | Medium | P2 | Open |
| CB-004 | Secondary button focus outline appears clipped in Edge compatibility review | Edge | Low | P3 | Open |

## Detailed Observations
### CB-001 - Mobile CTA overflows/wraps at narrow viewport
- **Area:** Responsive Behavior
- **Browser(s):** Chrome / Edge / Firefox
- **Severity / Priority:** High / P1
- **Observation:** At 390px the primary CTA wraps and reduces usable spacing.
- **Recommended Fix:** Use flexible width, min-height, and responsive typography; retest 320/375/390/430px.

### CB-002 - Form select height differs from text input in Firefox compatibility scenario
- **Area:** Forms & Buttons
- **Browser(s):** Firefox
- **Severity / Priority:** Medium / P2
- **Observation:** Native/select rendering creates visible control-height mismatch.
- **Recommended Fix:** Normalize appearance, line-height, padding, and min-height across controls.

### CB-003 - Service card text wrapping causes uneven card heights at tablet width
- **Area:** Page Layout
- **Browser(s):** Firefox / Tablet
- **Severity / Priority:** Medium / P2
- **Observation:** One card becomes taller and disrupts row alignment.
- **Recommended Fix:** Use grid auto-rows, consistent card min-height, and content wrapping rules.

### CB-004 - Secondary button focus outline appears clipped in Edge compatibility review
- **Area:** Buttons / Accessibility
- **Browser(s):** Edge
- **Severity / Priority:** Low / P3
- **Observation:** Focus ring is visible but too close to container boundary.
- **Recommended Fix:** Add outline-offset and avoid overflow:hidden on focusable control containers.
