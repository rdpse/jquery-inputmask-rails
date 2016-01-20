# Jquery::Inputmask::Rails


## Installation

Add this line to your application's Gemfile:
```
vim Gemfile
[...]
gem 'jquery-inputmask-rails', :git => 'https://github.com/douglas-dksh/jquery-inputmask-rails.git'
```

And then execute:
```
bundle install
````
Add the following to your `app/assets/javascripts/application.js`: needs to be after require jquery
```
//= require jquery.inputmask.bundle.min
```

A sample of this configuration file:
```
// This is a manifest file that'll be compiled into application.js, which will include all the files
// listed below.
//
// Any JavaScript/Coffee file within this directory, lib/assets/javascripts, vendor/assets/javascripts,
// or any plugin's vendor/assets/javascripts directory can be referenced here using a relative path.
//
// It's not advisable to add code directly here, but if you do, it'll appear at the bottom of the
// compiled file.
//
// Read Sprockets README (https://github.com/rails/sprockets#sprockets-directives) for details
// about supported directives.
//
//= require jquery
//= require jquery_ujs
//= require turbolinks
//= require bootstrap-sprockets
//= require jquery.inputmask.bundle.min
//= require_tree .
```

## Plugin Documentation

https://github.com/RobinHerbots/jquery.inputmask

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
