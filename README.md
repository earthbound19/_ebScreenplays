# A collection of Public Domain screenplays

This is a collection of screenplays. Screenplays may be variously licensed, e.g. from the range of copyrighted ("All rights reserved), to open licenses (e.g. Creative Commons) or no license (Public Domain).

Contributions to this collection are welcome. Where some works in this collection are Public Domain, this is not intended as a general library of screenplays which happen to be in the Public Domain through copyright expiry or neglect. It is intended as a library of screenplays which are new at the time they are submitted to the library, and which are original. Adaptations of works in the Public Domain (which were not originally screenplays) are also welcome.

# Licenses

All screenplays express their license in the screenplay file itself.

# Contributions

I hope to add specific commands/steps to these instructions for people new to git, but in brief:

- Clone this repo and checkout the `drafts-submissions` branch.
- Create a new, original screenplay in it, in [fountain format](https://fountain.io/). Copy and use [screenplay_template.fountain](screenplay_template.fountain) as a template, rewriting and renaming it after the working title of your screenplay.
- Expressly dedicate the work you submit to the Public Domain in the copyright section of the fountain text source itself. If you do not do this your pull request will be rejected. Only dedicate it to the Public Domain if you actually had legal copyright control of the work before dedicating it to the Public Domain (for example, if it is an original work which you wrote yourself).
- Only create new files and avoid name conflicts. For works with the same title, avoid conflicts by adding random characters like `eDbJcR` or `uTY4T6` to the end of the file name (before the `.fountain` extension).
- Create a new branch named after your screenplay (also avoid branch name conflicts), and add, commit and push your screenplay to your branch.
- Open a pull request.

## Branching model

The main trunk is `master`. Branching from `master` is `published`. Branching from `published` is `drafts-submissions`. Branching from `drafts-submissions` is as many small branches for as many screenplays as I want to work on and which people want to submit.

`master` should only be merged into from `published`, and `published` should only be merged into from `drafts-submissions`, and `drafts-submissions` should only be merged into from branches off of it. `drafts-submissions` is merged into when a work is accepted in roughly final form for future publication. After merge into `drafts-submissions` any necessary final edits are done to the file and committed to the branch. After all final edits are committed to the branch, the file is renamed if necessary for clarifying, and that rename is committed. After a grouping of screenplays satisfactory for a release are merged into `drafts-submissions`, that branch is merged into `published`, and a release is cut from that. The `published` branch is then merged into `master` for final archiving.

## Conversion of fountain to pdf

See [fountain2pdf.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/fountain2pdf.sh).

Other conversions:

To join ventilated prose, see [fountain2fountain.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/fountain2fountain.sh).

To make a PNG 2nd-page preview from a screenplay see [pdfScreenplayPreviewPNG.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/imgAndVideo/pdfScreenplayPreviewPNG.sh).

## Creative writing?!

I claim to [know some stuff that I can pass along](https://github.com/earthbound19/screenplay_art_and_craft), which I learned from great teachers.