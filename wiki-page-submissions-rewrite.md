# Screenplay submission process

This project encourages you to submit original screenplays under any license, with the Public Domain Dedication (permanent forfeit of all copyright and license claims) preferred.

Prerequisites: [git](https://gist.github.com/derhuerst/1b15ff4652a867391f03), creative smarts, any computing device with a plain text editor

# To submit entries--expert summary

The brief version of this if you are familiar with git and GitHub already is:
- [Fork this repo](https://help.github.com/articles/fork-a-repo/)
- Clone your fork locally
- Copy `screenplay_template.fountain` to a new file named after your screenplay and [some random characters](https://www.random.org/strings/?num=1&len=8&digits=on&upperalpha=on&loweralpha=on&unique=on&format=plain&rnd=new)
- Open that new file and adapt it to write your new screenplay in [fountain format](https://fountain.io/syntax)
- Off the `entries` branch, create a new branch named after your screenplay
- Add and commit your new screenplay to the new branch
- Push your new branch to your remote
- From your remote open a pull request to merge your new branch into `entries` on my remote.

# To submit entires--noob details

For the following, commands which you must execute in your terminal `are formatted like this`. Technical information may be _emphasized with italics_. You must also know how to save, rename, and open files on your computer.

If you don't know how to use a terminal, you must research how to open a terminal, how to execute various commands from it, and how to navigate to a working directory where you want to keep your files. Example web searches to help you with this are "Windows command prompt basics," "Mac terminal basics," or "Linux terminal basics," etc.--depending on what operating system you use. *

- [Fork this repo](https://help.github.com/articles/fork-a-repo/) (that's an instructive link)
- Clone your fork: `git clone https://github.com/your-user-name/eb_screenplays.git` (where `your-user-name` is your GitHub username)
- Move into the cloned directory: `cd eb_screenplays`
- Grab a random string from [this URL](https://www.random.org/strings/?num=1&len=8&digits=on&upperalpha=on&loweralpha=on&unique=on&format=plain&rnd=new)
- Copy the fountain screenplay template to a new file with that random string, e.g. `cp screenplay_template.fountain eb32984f.fountain`
- Open _eb32984f.fountain_ in a plain text editor, and adapt it to a new screenplay in [fountain format](https://fountain.io/syntax). Save often as you write.
- Rename _eb32984f.fountain_ (for example) to something better suited, and if applicable move it into one of the subfolders for a given series of scripts. For example you could move it into the _cyber_bob_ folder and rename it _cyber_bob_kisses_a_squirrel__eb32984f.fountain._ The random string is to avoid duplicate file names on merges. Use only letters, numbers, underscores, and `.fountain` in the file name--no spaces or other terminal-unfriendly characters. **
- Run `git status` from the terminal to ensure you are on the `entries` branch. If you are not, run `git checkout entries`.
- From the `entries` branch, create a new branch named after the submitted screenplay; e.g.: `git checkout -b cyber_bob_kisses_a_squirrel__eb32984f`
- Add the new screenplay to git tracking; e.g.: `git add cyber_bob_kisses_a_squirrel__eb32984f.fountain` (you can also get away with a command that adds all new files if it is the only addition: `git add .`
	- Commit the new screenplay to the branch with an appropriate message between quote marks; e.g. `git commit -m "Submit: Cyber Bob Kisses a Squirrel, by RAH"`

- Push the branch to your remote fork.
- Open a pull request to merge your branch from your remote fork into the `publication_queue` branch of my repo. 

https://www.random.org/strings/?num=1&len=14&digits=on&loweralpha=on&unique=on&format=html&rnd=new





- Push your new local branch to a new remote branch: `git push --set-upstream origin cyber_bob_kisses_a_squirrel__eb32984f` (what you type after `origin` must be the exact name of your new branch)
- Find the web view of your newly pushed branch at GitHub via a web browser; it may be e.g. via `https://github.com/your-user-name/eb_screenplays/tree/cyber_bob_kisses_a_squirrel__eb32984f`
- From that web view, click the "New pull request" button, select `earthbound19/eb_screenplays` + `entries` as the base fork (and base) and `your-user-name/eb_screenplays/` + `cyber_bob_kisses_a_squirrel__eb32984f` as the head fork (and base), click the "Create pull request" button, and follow instructions to open the pull request.
- Wait for my code review and (hopefully) merge. If in my code review I ask you to do anything, please do so.
- When your work appears in the `published` branch in my repository after code review and any necessary editing, it is published. Hopefully anyone who loves it will produce a film from it!

Tip: if you leave a comment near the start of your fountain script which is an ETH cryptocurrency address, this will tell others where to send you (a better kind of) a tip. Your comment could look like this:

`[[ETH 0xb0b4155bd54dd52b23bcf9f2dec760a90f8e26fc]]`

You can create a vanity address that stars with b0b via [vanity-eth online](https://vanity-eth.tk/) or a similar [offline terminal tool](https://github.com/MyEtherWallet/VanityEth).

# Submission agreement

# Git branching model
`published`: is the master branch. Branched off it is `publication_queue`, the editorial collection branch. Everything on `publication_queue` is published on merge into `published`. Branched off `publication_queue` is the `entries` branch.

*_For the love of all that is holy and pure, once you get the terminal basics down, find a utility (or operating system configuration) that opens a terminal from your current path in your Explorer window (on Windows), or Finder window (on Mac), or whatever window (on Linux), or whatever whatever (on whatever). Don't fritter away your life navigating a thousand paths and typing a thousand `cd` commands to get where you need to go in the terminal._

** For local computer scripts and network operating systems to handle file names that include spaces, silly things must be done like 'quote marks around a path/and file name.jpg' or awful%20fugly%20beastly%20percent%20and/mixed%20path%20encoding.jpg or stupid+what+the+fragglenaut+plus+marks+for+spaces.jpg.