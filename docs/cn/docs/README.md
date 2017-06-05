#Following are notes for developing this website
## Setting up environment on new machine
The site is using jekyll and bundler to manage all version requirements
to make sure all dependencies are installed run
First, make sure jekyll and bunderler are installed, if not do
> $ gem install bundler
> $ bundle install
##To run locally
> $ jekyll serve
###To run locally from base url
> $ bundle exec jekyll serve --baseurl ''
##To build the site
> $ bundle exec jekyll build
## Using sass
### To run Sass from the command line, use
> $ sass _sass/main.scss css/main.css
### Tell Sass to watch the file and update the CSS every time the Sass file changes:
> $ sass --watch _sass/main.scss:css/main.css
