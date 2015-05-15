#New Options Project

##Created to test some options for the command `rails new`

Project created by running:
```bash
rails new new_options --skip-git --skip-bundle -T
```

`--skip-git` skips creating the .gitignore file in the project directory

`--skip-bundle` tells rails not to run the `bundle install` command after creating project files, so that an initial gem install does not happen.

`-T` is shorthand for `--skip-test-unit` which does not include standard unit tests with the project.