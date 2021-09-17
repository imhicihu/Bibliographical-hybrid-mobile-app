* Merge staging into `master` - Don't "Squash & Merge", just do a regular merge
* Check out `master`
* If submodules are out of date `git submodule update --init --recursive`
* Remove node modules `rm -rf node_modules`
* Install fresh packages `yarn install`
* Compile assets `yarn compile`
* Run the test suite `yarn test`
* Change the version in `package.json`
* Commit and push
* Tag the repository `git tag 'vX.x.XX'` and `git push --tags`
* Package the app `yarn package`
* Run the packaged version
* Make sure it runs
* Deploy the new version `yarn deploy`
* Merge `master` back into staging