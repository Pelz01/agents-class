# Agents Class Full Course Expansion Plan

> Goal: turn the current lightweight presentation into a broad beginner-friendly course that reads like a simple but detailed handbook.

## Objectives
- Expand the site from a short presentation into a full course.
- Cover AI, LLMs, agents, automation, tools, workflows, safety, business, and careers.
- Keep explanations plain-English first, technical second.
- Structure the material so it can reasonably print/export as a 100+ page course book.
- Preserve a separate slide-deck view for faster presentation mode.

## Implementation approach
1. Replace `index.html` with a full course-book experience.
2. Organize the course into 14 modules × 8 lessons = 112 lesson pages.
3. Give each lesson a consistent learning format:
   - plain-English explanation
   - technical translation
   - why it matters
   - real-world example
   - mini exercise
   - key terms
4. Add a syllabus overview, learning tracks, glossary, and capstone section.
5. Rebuild `slides.html` as a tighter presentation summary of the expanded course.
6. Verify locally with a static server and browser preview.
7. Commit, push to `main`, and verify the GitHub Pages site link.

## Files to modify
- `index.html`
- `slides.html`

## New supporting files
- `docs/plans/2026-04-26-full-course-expansion.md`

## Verification
- Open `index.html` through a local HTTP server.
- Open `slides.html` and test keyboard navigation.
- Confirm no JavaScript console errors.
- Push to GitHub and verify the live Pages URL.
