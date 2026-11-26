# GRPS Team Workboard

A workboard that helps building teams run the GRPS monthly data review cycle in one place: run the 90-minute Rolling Agenda, work through the Data Conversation Process (Focus → Observe → Explain → Plan), and finish the Monthly Data Review Cycle Form without writing anything twice.

**Live site:** https://melatkins2-ops.github.io/grps-team-workspace/

## What teams can do

- **Home:** see where this month's cycle stands (Prepare → Meet → Submit → Follow through), open next steps, the parking lot, and this month's data.
- **Meeting:** a guided Rolling Agenda with segment timers: Open (roles, norms, objectives), Look back (update last month's next steps), Data conversation (2–3 data sets, each with sentence starters for the four protocol steps), and Close (next steps, what to bring, support needed, Plus/Delta).
- **Monthly form:** the meeting notes are rewritten as answers to the 18 questions on the Monthly Data Review Cycle Form, in the form's order. Copy them one at a time or all at once, open the form, and mark it submitted.
- **Priorities:** questions the team works on across months. Each one keeps its stage, data conversations, next steps, open questions, and history.
- **Parking lot:** questions, data needs, and wonderings, with owners, next steps, and answers.
- **Data calendar:** month-by-month data to discuss, where it lives, who can help, and when assessment results are released.
- **Resources:** links to the original documents in the shared Data Review Cycles folder.

## Good to know

- Work is saved in the browser on each device (local storage). Use **Settings → Download a copy** to keep it, share it, or open it on another device.
- Work saved by the earlier version (`grpsWorkboard6`) is brought forward automatically the first time the new version opens.
- New teams start with an empty board. They can load **sample work** to explore and then clear it.

## Files

- `index.html`: the whole workboard (HTML, CSS, and JavaScript in one file)
- `images/`: GRPS logo
- `.github/`: automated site check

## Updating the site

Edit on a branch and open a pull request. GitHub Pages publishes `main` automatically, usually within a minute or two of a merge.

## Automated site check

Every pull request and every push to `main` runs **Site check** (`.github/workflows/site-check.yml`). It opens the site in a headless browser at desktop (1366px) and phone (390px) widths. The check fails if the page throws a JavaScript error, a local file is missing, or the page scrolls sideways.

Maintained by GRPS Community & Student Affairs.
