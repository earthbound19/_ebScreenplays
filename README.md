# A collection of original screenplays

This is a collection of original screenplays with their various licenses. My ideal is that any work submitted to this repository be dedicated to the Public Domain, but you may use any license you like, including traditional copyright with all rights reserved.

I prefer Public Domain so that anyone can use these for any (ethical) purpose.

Contributions to this collection are welcome.

I will probably not collect screenplays which happen to be in the Public Domain; only new original works which the authors license or dedicate for whatever purpose. However, adaptations of works in the Public Domain (which were not originally screenplays) are also welcome.

# License

Whatever is declared in each `.fountain` file in this repository is the licence. Works in the Cyber Bob universe (see the `cyber_bob`) folder are all dedicated to the Public Domain.   

# Contributions

To contribute a new work, do the following. You must know or learn `git` commands to `add`, `commit` and `push` your work to do so, and moreover how to [open a pull request](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/creating-an-issue-or-pull-request) after you have finished your work, and added, committed and pushed the completed work to your own fork. If you encounter problems you can't surmount after your own research and effort, [open an issue](https://github.com/earthbound19/_ebScreenplays/issues/new) or email `ansible1+eb_screenplays` (at) `earthbound.io`.

- From you GitHub account, fork this repository (see [this document](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) for how to do that).
- Clone your fork to your local computer, with this command:
	- `git clone https://github.com/YOUR_USERNAME/_ebScreenplays.git`
- `cd` into or open a terminal into the newly cloned repo (for example with the command `cd _ebScreenplays`), then run these commands (adapting to your needs):
- `git status`, then read whether it is on the `drafts-submissions` branch (which hopefully it is, as that is the default branch). If not, run this command: `checkout drafts-submissions`. Then create a new branch named after your screenplay, but before you create it, mind these naming rules:
	- Only letters, numbers, and dashes or underscores (`-` or `_`), no spaces (` `) or any other characters.
	- It may be best if you add a few [random characters](https://www.random.org/strings/?num=1&len=4&digits=on&loweralpha=on&unique=on&format=html&rnd=new) to the end of the name, to avoid any cases of branch name conflict where anyone else might have a branch of the same name.
	- Example branch names that follow these rules: `ascent_to_guru_peak__sps9`, `untitled_screenplay_by_RAH__e7v2`, and `2020-09-02__Sk8f`.
- An example command to create the branch: `git checkout -b branch-named-after-your-new-screenplay`
- Create a new, original screenplay file, in [fountain format](https://fountain.io/). You may copy the [screenplay_template.fountain](screenplay_template.fountain) template into the `drafts_submissions` folder and rename it to anything else. The file name does not have to be final (you can rename it later). You must follow the same naming rules for files, but in addition, since they are fountain format files, give them a `.fountain` extension. Examples:`ascent_to_guru_peak__sps9.fountain`, `untitled_screenplay_by_RAH__e7v2.fountain`, `2020-09-02__Sk8f.fountain` (not that these are the same as the branch name examples, only they add `.fountain`. You may want to name branches the same as files assocaited with them if you write multiple scripts, to help keep straight what branches have what files.
- In the copyright section of the fountain file, declare your license or lack thereof (copyrgight, or Creative Commons, or Public Domain dedication, etc.). Note that entries in the Cyber Bob universe (see the `cyber_bob` folder) _must_ be dedicated to the Public Domain, or they will not be accepted.
- As you write, periodically save your work. At intervals where you have substantially added to your work, add and commit your work to your branch. Here is [one of the better tutorials](https://www.earthdatascience.org/workshops/intro-version-control-git/basic-git-commands/) I've found involving those commands.
- _Finish writing your work_. Don't weasel out of it! Finish it! _Do it!_
- If you later decide to rename your screenplay file, please do so in a commit where the only change is renaming the file. That means no changes to the text of the file, only renaming it, and adding the delete and the new file to git, then committing both.
- When your work is done, pat yourself on the back. Then `git push` it to your fork on GitHub, and open a pull request from your branch at your fork to the `drafts-submissions` branch of my "upstream" repository. Do a web search about how to do this, if you need to.

# Everything essential about screenwriting in a few paragraphs

## The actual craft is simple

The only things you absolutely need to know to write screenplays are a few technical things you can learn that are built into the [fountain format](https://fountain.io/), and a love of stories and storytelling, and to write in a way that can be immediately rendered sensible or literal to directors, actors, and cinematographers. If what is written can be performed by actors and/or translated to the screen without too much difficulty of imagination, it works. If it's too nebulous or novelistic, it doesn't work.

## The only rule is that there are no rules

Do not let anybody fool you that you need to know anything more than that. Just follow your guts, and/or wits, heart, or sillies, or whatever. That is all.

Also, don't let anyone mislead you that there are any rules for creative writing that you should always follow. There are not. I would argue, even, that if your ideas are clear and confident, that you don't even need to pay attention to rules.

As William Goldman, the Oscar-winning writer of screenplays for "All the President's Men" and "Butch Cassidy and the Sundance Kid" said: "Nobody knows anything." My addendum to that: anyone who tells you otherwise has been fooled. Also, note that if what he asserts is true, he might not know what he's talking about, and you might not have to take his word for it (or my word for anything!) and there may actually be people who really do know things. The point, I think, is that nobody can prove that their belief that anything will succeed or not is true, until future events that bear on the belief might come true.

Every venture is a stab in the dark. Plenty of people have wildly succeeded in the film industry where few people or nobody predicted it would happen. Also, plenty of people have had wild flops in the film industry where many people predicted wild success. The same holds for people's assertions that _X won't ever work in a screenplay_ or _Y will always work in a screenplay_.

The only all-cases-true rule for writing is the nebulous and infinitely-definition-shifting "Great writing succeeds."

## Greatness is in the eye of the beholder

For any given book or screenplay, you may be able to find a random stranger who will love it and a random stranger who will hate it. This is because beauty (or greatness, or any desirable thing) is in the eye of the beholder, and telling people that they should or should not love this or that doesn't generally work. The fact is, they do or don't love it. Loves can change, but nobody is "wrong" for not loving any particular work of art.

_Ergo,_ nobody knows anything. They only know (if they are self-aware enough to know) what they love or don't love. So, everything is risk. Anything can succeed or fail with any audience, and only God knows whether it will, and he/she/they/it are notoriously mum on the question. Embrace it, make your own best calculation, and run with it. That is life.

# Repository administration

The remainder of this document is for administration of this repository; contributors don't necessarily need to read the rest of this.

## Branching model

This is the development trunk and branch hierarchy:

- `master`
	- `published`
		- `drafts-submissions`
			- As many branches as there are working drafts and work that people want to submit via pull request

All new screenplays and works should be created on new branches off `drafts-submissions`, which is set as the default branch.

New works are received for processing and editing (and worked on to that end) via pull request from those new branches into `drafts-submissions`. 

When works are considered complete and all proofreading final, `drafts-submissions` is periodically merged into `published` (which would be a good time to make releases or pdf publications/updates). Finalization should also include appropriate renaming/moving of files. 

`published` is periodically merged into `master` for finalization/archiving.

## Conversion of fountain to pdf

A way to create industry standard layout screenplays from `.fountain` screenplays in this repository is via the [fountain2pdf.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/fountain2pdf.sh) over at `_ebDev`.

Also, ventilated prose can be joined via [fountain2fountain.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/fountain2fountain.sh).

To make a PNG 2nd-page preview from a screenplay see [pdfScreenplayPreviewPNG.sh](https://github.com/earthbound19/_ebDev/blob/master/scripts/imgAndVideo/pdfScreenplayPreviewPNG.sh).