# data-app

git remote add dataclasses https://github.com/kellermd/data-classes.git

git subtree add --prefix=dataclasses https://github.com/kellermd/data-classes.git main
git subtree add --prefix=dataclasses dataclasses main

git subtree pull --prefix=dataclasses https://github.com/kellermd/data-classes.git main
git subtree pull --prefix=dataclasses dataclasses main

git subtree push --prefix=dataclasses https://github.com/kellermd/data-classes.git main
git subtree push --prefix=dataclasses dataclasses main
