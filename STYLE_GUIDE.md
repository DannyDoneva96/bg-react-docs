# Bulgarian React Documentation – Style Guide

## Goals
The Bulgarian translation should be technically accurate, consistent, and natural for Bulgarian developers.
We preserve established React terminology and translate explanations in clear Bulgarian.

## Core Principles
- React API names and Hook names remain in English (e.g. `useEffect`, `useState`, `useMemo`).
- Established React technical terms stay in English where that’s the common developer usage (e.g. `props`, `state`, `key`, `ref`, `hook`).
- Explanatory text is translated into natural, technical Bulgarian.
- Avoid overly academic phrasing and avoid artificial “Bulgarian-izing” of React terms.

## Special Case: `state`
- When referring to the React API concept → use `state`.
- When referring to a general concept (app state, UI state, etc.) → use “състояние”.

## First Mention Rule (BG + EN)
On the first mention of an important programming concept or less common term in a file, use:

**Bulgarian translation (English term)**

Examples:
- чиста функция (pure function)

After the first mention in the same file, you may use only the Bulgarian term (without repeating the English in parentheses).

This rule does **not** apply to established React API names/terms like `useEffect`, `useState`, `props`, `state`, etc., which remain in English.

## Consistency
- One term → one chosen translation/usage across the project.
- If a term is missing or unclear, add it to `GLOSSARY.md` (or open a discussion) before using it inconsistently.
