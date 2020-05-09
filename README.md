# A collection of original screenplays

This is a collection of original screenplays with their various licenses. My ideal is that any work submitted to this repository be dedicated to the Public Domain, but you may use any license you like, including traditional copyright with all rights reserved.

I prefer Public Domain so that anyone can use these for any (ethical) purpose.

Contributions to this collection are welcome.

I will probably not collect screenplays which happen to be in the Public Domain; only new original works which the authors licence or dedicate for whatever purpose. However, adaptations of works in the Public Domain (which were not originally screenplays) are also welcome.

# License

Whatever is declared in each `.fountain` file in this repository is the licence.

# Contributions

To contribute a new work, do this (you must have git installed) :

- From you GitHub account, fork this repository.
- Clone your fork to your local computer, e.g. `git clone https://github.com/YOUR_USERNAME/_ebScreenplays.git` 
- `cd` into or open a terminal into the newly cloned repo, e.g.: `cd _ebScreenplays`, then run these commands (adapting to your needs):
- `git checkout drafts-submissions`
- `git checkout -b branch-named-after-your-new-screenplay` (it doesn't matter if you later change your screenplay name. This branch can actually be named anything, like `i-dont-know-what-to-call-this-79FJ`)
- Create a new, original screenplay in it, in [fountain format](https://fountain.io/). You may copy the [screenplay_template.fountain](screenplay_template.fountain) template into the `drafts_submissions` folder and rename it to whatever your working title is.
- Expressly declare either your copyright or Public Domain dedication in the copyright section of the fountain file of your original work.
- To avoid file name conflicts where files would otherwise be named the same, it is good practice to append some random characters to your fountain file name, like `PJdbR`, `X8Ht7`, `8YC8U`, or `4sBCV`.
- As you write, periodically save, add and commit your work to your branch. Please look up and learn the git `add` and `commit` commands to do this, if you need to.
- _Finish writing your work_. Don't weasel out of it! Finish it! _Do it!_
- When your work is done, pat yourself on the back. Then git `push` it to your fork on GitHub, and open a pull request from your branch at your fork to the `drafts-submissions` branch of my "upstream" repository. Do a web search about how to do this, if you need to.

## Branching model

This is the development trunk and branch hierarchy:

- `master`
- `published` ->
- `drafts-submissions` ->
- As many branches as there are working drafts and work that people want to submit via pull request

All new screenplays and works should be created on new branches off `drafts-submissions`.

New works are received for processing and editing (and worked on to that end) via pull request from those new branches into `drafts-submissions`. 

When works are considered complete and all proofreading final, `drafts-submissions` is periodically merged into `published` (which would be a good time to make releases or pdf publications/updates). Finalization should also include appropriate renaming/moving of files. 

`published` is periodically merged into `master` for finalization/archiving.

## Conversion of fountain to pdf

This is for me, the repository manager, to periodically do upon publication, but others might be curious about how to create industry standard layout screenplays from their `.fountain` screenplays this way:

See [fountain2pdf.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/fountain2pdf.sh).

Other conversions:

To join ventilated prose, see [fountain2fountain.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/fountain2fountain.sh).

To make a PNG 2nd-page preview from a screenplay see [pdfScreenplayPreviewPNG.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/imgAndVideo/pdfScreenplayPreviewPNG.sh).

## Everything about screenwriting in three paragraphs

The only thing you need to know to write screenplays is a few technical things you can learn that are built into the fountain format, and a love of stories and storytelling, and to write in a way that can be immediately rendered sensible and/or literal to actors and cinematographers.

Do not let anybody fool you that you need to know anything more than that. Just follow your guts, wits, and heart. That is all.

Also, don't let anyone mislead you that there is any foolproof formula for creative writing. There absolutely positively _is not_. As William Goldman, the Oscar-winning writer of screenplays for “All the President's Men” and “Butch Cassidy and the Sundance Kid" said: "Nobody knows anything." Anyone who tells you otherwise is full of balogna. Cinema history is riddled with "structurally perfect" screenplays and "high concept" films that fell flat on their faces and deserved too. Cinema history is also full of gloriously imperfect things that succeeded and deserved to (and did not succeed but deserved to).