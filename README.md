# TimeAgo
A gem that integrates timeago.js in to a Rails application and provides a simple way to render relative timestamps in a view.

[![Gem Version](https://badge.fury.io/rb/jquery-timeago.svg)](https://badge.fury.io/rb/jquery-timeago)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jquery-timeago'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jquery-timeago

## Usage

Add the following to ```app/assets/javascripts/application.js``` :

```
//= require jquery-timeago
```

Tags using the ```timeago``` view helper get rendered to UI as:

```html
<time class="timeago" datetime="2016-01-08T14:55:58Z">
    2016-01-08 14:55:58 UTC
</time>
```
and are updated to:
```html
<time class="timeago" datetime="2016-01-08T15:04:10Z" title="2016-01-08 15:04:10 UTC">
    20 days ago
</time>
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/roshan92/jquery-timeago. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
