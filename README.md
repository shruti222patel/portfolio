# Portfolio

This is Shruti's porfolio static generator.


### Dependencies
- Based on the `Hugo Agency Theme` forked https://github.com/shruti222patel/hugo-agency-theme. (Note: now, the theme has been modified directly in the code and it isn't a submodule)

### Set Up
- `git clone` the repo
- `cd` into the repo
- for local testing: run `hugo server -D`
- to generate the static site: run `hugo`


### Deploy (to Github Pages)
- `chmod +x deploy.sh` (only need to run the first time)
- `./deploy.sh "Your optional commit message"` -- this commits changes to https://github.com/shruti222patel/shruti222patel.github.io; you'll have to commit your changes to this repo as you normally would
