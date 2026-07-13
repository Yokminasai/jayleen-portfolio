---
name: design-system-contact
description: Creates implementation-ready design-system guidance with tokens, component behavior, and accessibility standards. Use when creating or updating UI rules, component specifications, or design-system documentation.
---

<!-- TYPEUI_SH_MANAGED_START -->

# Contact

## Mission
Deliver implementation-ready design-system guidance for Contact that can be applied consistently across documentation site interfaces.

## Brand
- Product/brand: Contact
- URL: https://1haum3c.atoms.world/?fbclid=IwY2xjawTBe4RleHRuA2FlbQIxMABicmlkETFvV1pyeTJhRGFFdUtqcG5mc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHrYgf6b_zWXOgMNa3EHpdVYlyqCAlxArRsS6xVfQU3GchYXV7yeIe2WRhsFn_aem_gzZt5BrYcEf_4iygJp0nWQ
- Audience: developers and technical teams
- Product surface: documentation site

## Style Foundations
- Visual style: structured, accessible, implementation-first
- Main font style: `font.family.primary=Mali`, `font.family.stack=Mali, cursive, sans-serif`, `font.size.base=16px`, `font.weight.base=700`, `font.lineHeight.base=normal`
- Typography scale: `font.size.xs=16px`
- Color palette: `color.text.primary=#4d4d4d`, `color.text.secondary=#333333`, `color.surface.base=#ffffff`, `color.surface.muted=#000000`, `color.surface.raised=#f9dcec`, `color.border.default=#f9b4c9`, `color.border.muted=#f59ab6`
- Spacing scale: `space.1=18px`, `space.2=22px`, `space.3=24px`, `space.4=32px`, `space.5=36px`, `space.6=40px`, `space.7=44px`, `space.8=48px`
- Radius/shadow/motion tokens: `radius.xs=32px`, `radius.sm=44px` | `shadow.1=rgba(249, 180, 201, 0.2) 0px 8px 18px 0px`, `shadow.2=rgba(245, 154, 182, 0.32) 0px 10px 25px 0px`, `shadow.3=rgba(245, 154, 182, 0.25) 0px 18px 45px 0px` | `motion.duration.instant=200ms`

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone
concise, confident, implementation-focused

## Rules: Do
- Use semantic tokens, not raw hex values in component guidance.
- Every component must define required states: default, hover, focus-visible, active, disabled, loading, error.
- Responsive behavior and edge-case handling should be specified for every component family.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and tokens.
3. Define component anatomy, variants, and interactions.
4. Add accessibility acceptance criteria.
5. Add anti-patterns and migration notes.
6. End with QA checklist.

## Required Output Structure
- Context and goals
- Design tokens and foundations
- Component-level rules (anatomy, variants, states, responsive behavior)
- Accessibility requirements and testable acceptance criteria
- Content and tone standards with examples
- Anti-patterns and prohibited implementations
- QA checklist

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.

## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Prefer system consistency over local visual exceptions.

<!-- TYPEUI_SH_MANAGED_END -->
