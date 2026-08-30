# Canvas Hub — Feature List

Master list of everything discussed for the app. Organized by subsystem so it's easier to scope into milestones later. Nothing here is locked in — this is a working doc, edit freely.

## 1. Canvas Sync (multi-account)
- Connect to multiple Canvas instances (different domains, e.g. NUAMES + CE school accounts) via personal API access tokens
- Merge assignments, grades, announcements, and messages from all connected accounts into one unified data set
- Custom class names and custom colors per class (like Canvas allows)
- Hide/show individual classes (fixes the Canvas bug/annoyance where old-year classes still clutter tabs like Grades)
- Sync notification settings (email/push) across all connected accounts from one place, with the ability to override per-school if wanted

## 2. Unified Todo List / Dashboard
- One combined list showing: due soon, past due, and due today — not split across separate pages/widgets like new Canvas
- Manually add custom todo items not tied to any Canvas account
- **"Currently In Progress" section** — separate from the daily todo list, for long-term projects/assignments you should be chipping away at but that aren't due imminently, so they don't get forgotten
- Ability to break a long-term task into smaller pieces and assign each piece to a specific day — either auto-populating it on your list each day until done, or as a lightweight sub-task breakdown, without needing to manually create a bunch of separate todo entries
- Time estimate field per assignment/task
- Sorting: by due date, by time estimate (ascending/descending), by class — combinable when compatible (e.g. sort by due date *and* time estimate, without grouping by class)
- **Lock/"until" dates** — flag and visually mark (e.g. an exclamation icon) items that will become fully unsubmittable after a certain date, distinct from the due date and its late-penalty window, so you never miss the actual point of no return

## 3. Notes
- Built-in notes app — each note can be freeform text (doc-style) or a checklist (Keep-style), chosen per note
- Unlimited number of notes

## 4. Calendar
- Fully user-editable calendar (not just a mirror of Canvas's)
- Custom notifications/reminders (push and/or email) per event
- Deliberately does *not* auto-list every single assignment (that's what the todo list is for) — reserved for bigger-picture planning, e.g. surfacing something due in a month that you should start now
- Some mechanism to actually encourage checking it, since Canvas's calendar tends to get ignored entirely

## 5. Syllabus / Class Rules Center
- Per-class syllabus link or file
- Manually add specific extracted rules per class (late work policy, food/phone policy, etc.)
- "What we're doing in class today" section, from a teacher-provided schedule or entered manually
- Related "what you need before class today" section (reading due, test to study for, etc.)
- *Stretch goal:* automated weekly email to teachers asking for the week's plan, ideally parsed into a custom file format for full automation — depends on teacher buy-in, treat as phase 3+

## 6. Grades
- Dashboard shows each class as a large letter grade, with the percent shown smaller or on hover
- Improved "what-if" grade simulator that correctly recalculates the total possible points (including for assignments not yet posted), instead of treating hypothetical points as extra credit
- Ability to exclude specific assignments — even already-graded ones — from a what-if calculation
- Goal-based solver: "I want a B in this class — what do I need on the remaining assignments, assuming I skip this one?"
- Late/skip impact calculator — shows projected grade if something is turned in late or not at all, to reduce anxiety around taking a break

## 7. Customization
- Add, remove, and rearrange widgets/features
- Custom color themes
- Custom fonts, including a dyslexia-friendly font option
- Custom decorative pictures/themes
- General accessibility options

## 8. Links Center
- Bookmark-style hub for saved/important links, built into the app
