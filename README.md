# MBNOG.ca website in jekyll

## to work on the site

*	fork the repo and make a branch for what you would like to commit
*	make your changes to that branch
*	use Github to make a pull request for your branch
	*	you may be requested to sync your branch (see github's [configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/) and [syncing a fork](https://help.github.com/articles/syncing-a-fork/) documentation for help with that)

## to build the site locally

	bundle install # only needed first time or after gem changes
	bundle exec jekyll build

the site will then be in the `_site` directory.

