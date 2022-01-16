# data-app

Build originally with this:
1. git remote add dataclasses https://github.com/kellermd/data-classes.git
2. git subtree add --prefix=dataclasses dataclasses main
   OR if you want to omit #1:
   git subtree add --prefix=dataclasses https://github.com/kellermd/data-classes.git
3. git subtree pull --prefix=dataclasses dataclasses main
   OR (omitting #1)
   git subtree pull --prefix=dataclasses https://github.com/kellermd/data-classes.git main

To use the repository, after cloning with the intent of updating or contributing to the subtree:
Initially:
1. git remote add dataclasses https://github.com/kellermd/data-classes.git
2. git subtree pull --prefix=dataclasses dataclasses main
   OR (omitting #1)
   git subtree pull --prefix=dataclasses https://github.com/kellermd/data-classes.git main
   Some git UI (Visual Studio Code) will require you to use the git subtree pull once before it knows that the main branch is available to pull.

Contributing:
1. git subtree push --prefix=dataclasses dataclasses main


