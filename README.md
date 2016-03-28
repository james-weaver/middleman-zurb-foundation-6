# Middleman Foundation 6 Template

A basic template for Middleman 4 including [Foundation 6](http://foundation.zurb.com/)

## Getting Started

####Install Middleman

Install Xcode Command Line Tools (for OS X users)

`$ xcode-select --install`

Install Middleman 4

`$ gem install middleman`

####Start a New Project

Start a new project with the middleman-foundation-6 template

`$ middleman init -T james-weaver/middleman-foundation-6 PROJECT_NAME`

You'll be asked if you want to enable [livereload](https://github.com/middleman/middleman-livereload) and if you want a `rack.ru` file


##Configuration

####CSS Modules
middleman-foundation-6 inclues all of the Foundation 6 CSS modules. You can comment out the modules you don't need in `source/stylesheets/foundation/app.css.sass`

####CSS Settings
You can change Foundation 6 settings, such as grid size, by editing `source/stylesheets/foundation/_foundation-sites/_settings.scss`

####JavaScript
middleman-foundation-6 includes the Foundation 6 Javascript Modules and [jQuery 2.2.2](https://jquery.com/download/)

Only some of the CSS modules require Javascript (see the [Foundation 6 documentation](http://foundation.zurb.com/sites/docs/javascript.html)). So you may choose not to include the files in `source/layouts/layout.erb`
