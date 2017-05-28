#Following are notes for developing this website
## To run on a new machine
The site is using jekyll and bundler to manage all version requirements
to make sure all dependencies are installed run
> $ bundle install
## Using sass
### To run Sass from the command line, use
> $ sass _sass/main.scss css/main.css
### Tell Sass to watch the file and update the CSS every time the Sass file changes:
> $ sass --watch _sass/main.scss:css/main.css
