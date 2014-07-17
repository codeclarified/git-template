#Pre-commit PHP Lint

* Create directory `mkdir ~/.git_template/hooks`
* Place or symlink pre-commit in this directory
 * Make script executable `chmod +x pre-commit`
* Run `git config --global init.templatedir '~/.git_template'` to set this directory as a global git template, this will apply this template to any new repos
* Run `git init` on any existing repos to apply template to repo