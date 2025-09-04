Do This First Before Working in Godot!
======================================

Always update your local repository before you work In Godot
------------------------------------------------------------

Why this task matters
~~~~~~~~~~~~~~~~~~~~~

This will ensure sure you have the latest changes from your team before
you begin working on the game. You will be making changes to your game
quite a bit and pretty soon this will feel like second nature!

**Important concept**: Unlike Google Docs or other online tools, Git
does not automatically sync the latest updates from your GitHub
repository. You need to manually pull (download) the newest changes from
online into your local repository before you start working. This is a
key difference to remember when working with Git.

Steps
-----

1. **Open Git Bash**.
2. **Navigate to your project folder**. Use the ``cd`` command in Git to
   target the folder where you cloned the project.(this stands for
   "change directory"). Ex:
   ``cd C:/Users/YourName/Documents/MyGameProject``. You'll know you're
   in the right place when you see ``main`` next to your folder path -
   this tells you Git recognizes this as your main branch. You can also
   type ``git status`` to check if you're in the correct folder - Git
   will show you which branch you're on and confirm this is a Git
   repository.
3. **Pull the latest changes**. Before creating a new branch, always run
   this command on your main branch to get the newest updates from your
   team: ``git pull``

This is important because whenever you create a new branch, it just
copies your current main branch. If your main branch is outdated, your
new branch will be outdated too, causing conflicts later.

4. **Create and switch to a new branch**. Think of a branch like making
   a copy of your project to work on. You never work directly on your
   main branch - instead, you make a copy (branch) for each task. This
   way, your main branch stays exactly like the online version, so you
   can always get new updates from your team. Once the pull is complete,
   create your new branch:

   ::

      git switch -c your-new-branch-name

   The ``-c`` flag means "create and switch to" the new branch. Choose a
   branch name that describes what you're working on, like
   ``intro-outro-tilemap`` or ``add-character-spriteframes``.

5. **Verify you're on the new branch**: Git will show your new branch
   name next to the folder path, confirming you've switched
   successfully. You can also just use the ``git status`` command as
   well to double check that you have swapped to your new branch

6. **Open Godot**. Now you're ready to start working in Godot with your
   properly set up Git workflow. You can just leave Git open on your
   computer while you work in Godot. If you close it for any reason it's
   ok! Just open it up and navigate back to the correct folder and Git
   will remember that you were on your new branch.

Quick Recap
-----------

-  Always open Git on your computer first and navigate to your cloned
   game project folder.
-  Always do ``git pull`` on the main branch before creating a new
   branch
-  The ``git switch`` command lets you move between existing branches.
   (``git switch -c`` lets you create a new branch and switch to it)
-  Your new branch is a fresh copy of whatever branch you were on when
   you created it
-  This workflow prevents conflicts when you later merge your work back
   to the main project

Video
-----

.. youtube:: MsmyML4863E
