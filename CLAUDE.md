# CLAUDE.md — MySkincare Stack

## Project
Single-file HTML skincare ingredient checker and pairing recommendation tool.
Stack: HTML/JS. Personal and potentially public use.
Status: In active development.

## Core Features
- Shelf management: current shelf + unopened shelf
- Daily routine builder: user selects products they intend to use that day
- Ingredient conflict detection: flags bad combinations
- Pairing suggestions: recommends good combos from current shelf
- Opportunity suggestions: recommends better combos by opening unopened products
- Product management: add, edit, remove products from shelf

## Product Data Structure
Each product should have: name, brand, key ingredients, shelf status (current/unopened).

## Edit Rules
- NEVER regenerate full file. Edit only the section requested.
- Ingredient conflict logic is core — do not modify without explicit instruction.
- Shelf state should persist (localStorage or equivalent).
- New features = discuss approach first before writing code.
