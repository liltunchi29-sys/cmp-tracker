# Ownership & Edit Rules — READ BEFORE CHANGING ANYTHING

**`index.html` is owned and deployed exclusively by Claude Code** (the CLI tool with direct git access).

## Do NOT
- Do **not** edit, replace, or upload `index.html` via the GitHub web "Upload files" button.
- Do **not** push changes to `index.html` from any other tool, sandbox, or chat (e.g. Claude cowork).

## Why
On 2026-06-22 an out-of-date copy of `index.html` was uploaded here, which silently **reverted**:
- the CMP brand theme (green/copper → old navy), and
- the save-error fix (re-introduced the `mode:'no-cors'` silent-save-failure bug).

Any tool holding an older copy will revert live fixes every time it uploads.

## If a change is needed
Describe **what** should change and **why**, and hand it to Claude Code to implement and deploy.
Advisory tools (e.g. Claude cowork) are **read-only** on this tracker — discussion and guidance only.

_Source of truth = the live file in this repo, served at https://liltunchi29-sys.github.io/cmp-tracker/_
