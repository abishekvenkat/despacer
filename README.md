# despacer

Cleans up text copied from the terminal.

Terminal output tends to land with trailing spaces, stray leading indentation, and lines broken wherever your terminal happened to wrap. Pasting that into a doc or ticket looks bad. despacer fixes it.

## What it does

- Strips leading and trailing whitespace from every line
- Rejoins soft-wrapped lines by detecting sentence continuations
- Leaves blank lines, list items, headings, and `---` separators alone

## How to use

1. Paste your terminal output into the box
2. Click **despace**
3. Copy

Hit **sample** to try it on an example. **clear** resets the box.

## Design

Follows the design language of [md-render](https://github.com/abishekvenkat/md-render).
