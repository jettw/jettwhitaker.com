# jekyll-foundation-6-starter

Website for my personal portfolio [jettwhitaker.com](https://jettwhitaker.com)

### Tools used, and useful commands

If you don't have it, install [node.js](https://nodejs.org/en/). Easiest way it to use [Homebrew](http://brew.sh/) by
  `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
then 
  `brew install node`
and install npm and gulp globally by running 
  `sudo npm install npm bower gulp -g`

Run gulp to compile css from sass by simply run `gulp` or `npm start` from your terminal within your repo. 
It will launch watch by default. <code>control-c</code> to stop. If you only want the css compiled once, run `gulp sass`

To run jekyll locally to test your website while developing, run `bundle install` then `bundle exec jekyll serve --watch` (Requires ruby *) Your website should be viewable by going to [localhost:4000](http://localhost:4000/)

Github's doc on [how to use Jekyll on Github Pages](https://help.github.com/articles/using-jekyll-with-pages) is also helpful. 

* You may have to run `brew install ruby` and `sudo gem install bundler`. [Mac OS X 10.11 nokogiri trouble](http://stackoverflow.com/questions/23668684/failed-to-build-gem-native-extension-when-i-run-bundle-install)

You can update to the latest foundation by running `bower update foundation-sites --save`. Ping me and I will update this repo. Any questions, make an issue or ask on twitter @DaigoFuji
