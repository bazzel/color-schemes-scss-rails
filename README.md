# color-schemes-scss

Rails version of [color-schemes-scss](https://github.com/bazzel/color-schemes-scss).

Please refer to its [README](https://github.com/bazzel/color-schemes-scss/blob/master/README.md) for further info.

Some significant changes and remarks:

* The files located in source/css/ can now be found in app/assets/stylesheets.
* The file `source/css/site.css.scss` is renamed to `app/assets/stylesheets/application.css.scss`
* The [susy](http://rubygems.org/gems/susy/versions/1.0.9) gem might be a bit outdated, but this made porting to Rails a bit easier.

## Installation

    bundle install
    rails s

Open a browser and navigate to [http://localhost:3000](http://localhost:3000).
