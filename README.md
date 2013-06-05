# Twitter Bootstrap addons for Rails asset pipeline

Includes:

* [colorpicker](http://www.eyecon.ro/bootstrap-colorpicker/)
* [datepicker](http://www.eyecon.ro/bootstrap-datepicker/)
* [image gallery](https://github.com/blueimp/Bootstrap-Image-Gallery)

## Installation

in Gemfile

`gem 'bootstrap-addons-rails'`

then bundle it!

## Gotchas!

https://github.com/twitter/bootstrap/issues/2543

https://github.com/the-teacher/the_role/issues/4

http://www.rqgg.net/topic/mrrkx-compiling-less-twitter-bootstrap-files-in-ubuntu.html

http://railscasts.com/episodes/329-more-on-twitter-bootstrap?view=comments

```
To fix the issue put this in your application.rb

config.assets.initialize_on_precompile = false

then run again...
```

## Configuration

Stylesheets:

```css
 *= require bootstrap/colorpicker
 *= require bootstrap/datepicker
 *= require bootstrap/image-gallery
```

Or using Compass/SASS:

`@import "bootstrap/image-gallery";`

Javascripts:

```javascript
//= require bootstrap

//= require bootstrap/colorpicker
//= require bootstrap/datepicker

//= require bootstrap/load-image.min
//= require bootstrap/image-gallery.min
```

Pleas note that `bootstrap` needs to be imported before `image_gallery`

For convenience, a `gallery` script is included that loads everything needed for gallery in the correct order, so the above can be simplified to this:

```javascript
//= require bootstrap/gallery
//= require bootstrap/colorpicker
//= require bootstrap/datepicker
```

Gotcha: The `gallery` script assumes that bootstrap (js) can be loaded simply as `bootstrap`. 

## Extras

To customize Bootstrap, check out: 

* http://charliepark.org/bootstrap_buttons/
* http://bootswatch.com/

## Contributing to bootstrap-addons-rails
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (c) 2012 Kristian Mandrup. See LICENSE.txt for
further details.

