<Why: one line. The problem and where it came from (issue, finding, request).>

**What changes for you**
- <2-5 plain bullets: what a user or Ollie can now do or will see, naming the commands or screens.>

## Risk
<!-- A No needs a `> [!CAUTION]` alert above the first heading saying what a revert would not undo. -->
**Can a revert undo it?** Yes -- <why, or `No -- <what a revert can't bring back>`>
**If it's wrong, who notices?** <who sees it first, and what they see>

**Look hardest at:**
- [<file> L<a>-L<b>](<blob link at the head sha>#L<a>-L<b>) -- <what goes wrong if this code is wrong>
<!-- 1 to 3 bullets, riskiest first. No code changed: `**Look hardest at:** N/A -- <reason>`. -->

## Summary
<!--
At least one visual, each next to the line of text it supports. Pick the smallest that makes the point:
pseudocode or call tree (logic/flow, ```text), component or file tree (structure, ```text),
Mermaid (interaction, data flow, state), diff sketch (```diff), code (new shape, CLI call, API, type).
-->
<1-2 visuals, each with one line of text. Describe the final behaviour, not a log of review rounds.>

## Read in this order
| # | File | What it does |
|---|---|---|
| 1 | <file> | <what it does> |

## Evidence
- Before: <the test that failed, named, or the bug as seen>
- After: <same test passing, or the fix as seen>
- Gates at HEAD: <lint / typecheck / tests command> -> <result>

<UI changed: before and after screenshots or a GIF.>

## Left undone
- <real debt only, each linking an issue (#n)> or `None`

Closes #<n>
