# INVU-TC-001 — Language switch: typography and layout consistency (EN / KA)

**Test Type:** UI/UX  
**Priority:** Medium  

---

## Pre-Conditions

- Open a browser and navigate to https://invu.ge
- Ensure the website loads successfully before test execution
- Verify that the language switcher (EN / KA) is visible and functional

---

## Description

Verify that switching the website language from English (EN) to Georgian (KA) does not break or change text styling, layout, or spacing. Font size, font weight, line height, button label alignment, and heading formatting must look identical in both languages.

---

## Test Steps

| Step No. | Action                                             | Expected Result                                                 |
| -------- | -------------------------------------------------- | --------------------------------------------------------------- |
| 1        | Select **EN** from the language switcher           | Website content is displayed in English                         |
| 2        | Verify the main heading styling and formatting     | Heading is displayed correctly with consistent styling          |
| 3        | Verify body text styling and readability           | Body text is properly formatted and readable                    |
| 4        | Verify button text appearance and alignment        | Button labels are displayed correctly without UI issues         |
| 5        | Select **KA** from the language switcher           | Website content changes to Georgian successfully                |
| 6        | Verify heading styling in Georgian language        | Font size and formatting remain consistent with English version |
| 7        | Verify body text styling in Georgian language      | Text remains readable without unexpected scaling                |
| 8        | Verify button text appearance in Georgian language | Button text remains aligned without overflow or wrapping issues |
| 9        | Switch back to English and verify UI consistency   | All elements remain visually stable and unchanged               |

---

## Post-Conditions

- Text styling and formatting remain consistent in both English and Georgian languages
- No text overflow, truncation, alignment issues, or unexpected font size changes are observed
- UI elements remain visually stable after language switching
