# Lesson 9 Validation Report

## BEM
Blocks, elements and modifiers are used throughout the component stylesheet, including `.site-header__link--active`, `.feature-card__icon--green`, `.button--primary`, and `.token-card__body`.

## Design tokens
Centralized custom properties are defined in `css/01-settings.css` under `:root` and consumed with `var()` across the project.

## Specificity
Component selectors are kept flat and class-based where practical. The project avoids ID selectors, `!important`, tag+class combinations, and deep descendant chains in component styling.

## Organization
The CSS is organized in an ITCSS-inspired order: Settings → Generic → Elements → Objects → Components → Utilities.

## Validation limitation
This is a local/static implementation review, not a result from an external LMS-specific auditor.
