[Originally sourced from the 🏎 `downshift` contributing guide](https://github.com/downshift-js/downshift/edit/master/CONTRIBUTING.md)

# Contributing

Thanks for being willing to contribute!

**Working on your first Pull Request?** You can learn how from this _free_
series [How to Contribute to an Open Source Project on GitHub][egghead]

## Project setup

1.  Fork and clone the repo
2.  Create a branch for your PR

> Tip: Keep your `master` branch pointing at the original repository and make
> pull requests from branches on your fork. To do this, run:
>
> ```
> git remote add upstream https://github.com/godaddy/eslint-plugin-i18n-json.git
> git fetch upstream
> git branch --set-upstream-to=upstream/master master
> ```
>
> This will add the original repository as a "remote" called "upstream," Then
> fetch the git information from that remote, then set your local `master`
> branch to use the upstream master branch whenever you run `git pull`. Then you
> can make all of your pull request branches based on this `master` branch.
> Whenever you want to update your version of `master`, do a regular `git pull`.

## Committing and Pushing changes

Please make sure to run the tests before you commit your changes. You can run
`npm run test -u` which will update any snapshots that need updating. Make
sure to include those changes (if they exist) in your commit.

## Help needed

Please feel free to create an issue to discuss.

Thanks!!! :smile: