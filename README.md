##
Example Repository with Submodule

Install:
```
git clone git@github.com:PsychicCat/main_example.git
git submodule init
git submodule update
```
Now you can verify that `src/app/services` contains the contents from repository: https://github.com/PsychicCat/shared_example

To fetch upstream changes from submodules, use `git submodule update --remote`.
