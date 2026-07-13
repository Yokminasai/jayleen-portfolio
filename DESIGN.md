# Contact

## Mission
Create implementation-ready, token-driven UI guidance for Contact that is optimized for consistency, accessibility, and fast delivery across documentation site.

## Brand
- Product/brand: Contact
- URL: https://1haum3c.atoms.world/?fbclid=IwY2xjawTBe4RleHRuA2FlbQIxMABicmlkETFvV1pyeTJhRGFFdUtqcG5mc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHrYgf6b_zWXOgMNa3EHpdVYlyqCAlxArRsS6xVfQU3GchYXV7yeIe2WRhsFn_aem_gzZt5BrYcEf_4iygJp0nWQ
- Audience: developers and technical teams
- Product surface: documentation site

## Style Foundations
- Visual style: clean, functional, implementation-oriented
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
Concise, confident, implementation-focused.

## Rules: Do
- Use semantic tokens, not raw hex values, in component guidance.
- Every component must define states for default, hover, focus-visible, active, disabled, loading, and error.
- Component behavior should specify responsive and edge-case handling.
- Interactive components must document keyboard, pointer, and touch behavior.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.
- Do not ship component guidance without explicit state rules.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and semantic tokens.
3. Define component anatomy, variants, interactions, and state behavior.
4. Add accessibility acceptance criteria with pass/fail checks.
5. Add anti-patterns, migration notes, and edge-case handling.
6. End with a QA checklist.

## Required Output Structure
- Context and goals.
- Design tokens and foundations.
- Component-level rules (anatomy, variants, states, responsive behavior).
- Accessibility requirements and testable acceptance criteria.
- Content and tone standards with examples.
- Anti-patterns and prohibited implementations.
- QA checklist.

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.
- Include known page component density: links (3), cards (1).

- Extraction diagnostics: Low sample size: fewer than 30 visible elements were extracted. Limited typography variety detected; size scale may need manual refinement. Audience and product surface inference confidence is low; verify generated brand context.

## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Teams should prefer system consistency over local visual exceptions.
