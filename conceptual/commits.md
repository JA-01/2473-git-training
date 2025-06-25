# Commits - bundling your changes and sending them for others to see

Let's say you've made some changes. Instead of sending your files, git tracks what specific lines you changed and how, and then sends specifically that information

Pros:
- Easier for your computer to send it this way
- tracks your changes locally in well organized chunks
- commits can be manipulated with other git actions

Commits have an ID (which you mostly don't need to care about), a name, and the changes in the commit.

*THE NAME ABSOLUTELY MUST START WITH A CAPITALIZED 3RD PERSON PRESENT INDICATIVE TENSE VERB AND NOT END WITH PUNCTUATION, AND MUST DESCRIBE ALL THE CHANGES MADE IN THE COMMIT. IF YOU NAME YOUR COMMIT 'asdkjfhsadklfh' I WILL FIND YOU.*

When you commit, your changes are stored locally and ready to be pushed.

To send commits for other people to see, all you have to do is run 'git push'.

All you have to do to get other peoples' commits onto your machine is to run 'git fetch' to load the commits then 'git pull' to apply them to your files. 'git pull' also fetches on most versions of git, so you can just run 'git pull'.