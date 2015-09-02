Git Guide
=========

Git is a version control system that allows dvelopers to collaborate on projects.
Version control keeps track of project changes and allows the developer
to revert to previous versions, which saves a lot of headache
when things stop working. Collabration is achieved by keeping a "master" version
of the project on a server or service like Github_, and project members would have
a copy of it on their local machines; any changes they make would be added to
the "master" after they commit their changes and push them.

A typical git workflow is::

  git add "changedFile or * for all changed files. Don't add files."
  git pull
  git commit -m "Your message here; a description of what you did "
  git push


GAI projects should be hosted on github, and the team leader should add members
as collaboraters so they can push their changes.

To learn more about git, take TeamTreeHouse's `git basics course`_ and look at
these resources:

- `Try Git`_: A short interactive tutorial that will get you acquainted with git
  that we highly recommend you start with.
- `Practical Guide to Git`_: A stackoverflow post that has answers to the most
  common questions in git, and a few guides.
- `Think Like a Git`_: If you want a deeper understanding of how git works.

.. _`Try Git`: https://try.github.io/
.. _`git basics course`: http://teamtreehouse.com/library/git-basics
.. _`Practical Guide to Git`: http://stackoverflow.com/questions/315911/git-for-beginners-the-definitive-practical-guide
.. _`Think Like a Git`: http://think-like-a-git.net/
.. _Github: https://github.com/



Cheat Sheets
^^^^^^^^^^^^

- `Github's Git Cheat Sheet`_
- `Git - The Simple Guide`_
- `Interactive Git Cheat Sheet`_

.. _`Github's Git Cheat Sheet`: https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf
.. _`Git - The Simple Guide`: http://rogerdudler.github.io/git-guide/
.. _`Interactive Git Cheat Sheet`: http://www.ndpsoftware.com/git-cheatsheet.html
