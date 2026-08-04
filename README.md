React Interview Prep

A single-file HTML flashcard app for React interview review. Click a question to expand its answer.

Usage

Open react-interview-prep.html in any browser. No build step, no dependencies.

Features
~30 questions across 7 categories: Fundamentals, Hooks, Performance & Rendering, State Management & Context, Component Patterns, Lifecycle, Debugging & Pitfalls
Click-to-expand answers with code examples
Search box (filters by keyword across questions and answers)
Difficulty filter: Easy / Medium / Hard
Expand all / Collapse all buttons
Live count of visible questions
Customizing

All content lives in the DATA array in the <script> block — each entry is { category, items: [{ q, level, a }] }. Add, edit, or reorder entries there; the UI renders automatically. a accepts HTML.
