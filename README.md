# Twitter Bootstrap addons for Rails asset pipeline

Includes:

* [colorpicker](http://www.eyecon.ro/bootstrap-colorpicker/)
* [datepicker](http://www.eyecon.ro/bootstrap-datepicker/)
* [image gallery](https://github.com/blueimp/Bootstrap-Image-Gallery)

## Installation

in Gemfile

`gem 'bootstrap-addons-rails'`

then bundle it!

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
//= require bootstrap/colorpicker
//= require bootstrap/datepicker

//= require bootstrap/load-image.min
//= require bootstrap/image-gallery.min
```

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

