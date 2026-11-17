# GRPS Team Workspace

A team workboard that keeps work visible across meetings: today's meeting, priorities, the data the team can use now, and links to GRPS tools.

**Live site:** https://melatkins2-ops.github.io/grps-team-workspace/

## What's here

- `index.html`: the workboard
- `images/`: GRPS logo

## Good to know

- Changes are saved in the browser on the device (local storage). Use **Save a copy** to keep or share a version.

## Updating the site

Edit the files on a branch and open a pull request. GitHub Pages publishes `main` automatically, usually within a minute or two of a merge.

## Automated site check

Every pull request and every push to `main` runs **Site check** (`.github/workflows/site-check.yml`). It opens the site in a headless browser at desktop (1366px) and phone (390px) widths and fails if the page throws a JavaScript error, a local file or image is missing, or the page scrolls sideways. See the Actions tab for results.

Maintained by GRPS Community & Student Affairs.
