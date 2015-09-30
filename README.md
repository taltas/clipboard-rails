# clipboard-rails

clipboard-rails gem is the integration of clipboard.js javascript library for your Rails 4 application.

clipboard.js is a modern approach to copy text to clipboard No Flash. No dependencies. Just 2kb
source: https://github.com/zenorocha/clipboard.js

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'clipboard-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install clipboard-rails

Now you need to edit your `app/assets/javascripts/application.js` file and add the following line:
``` javascript
//= require clipboard
```

## Usage

Read the clipboard.js documentation here http://zenorocha.github.io/clipboard.js/

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake false` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/sadiqmmm/clipboard-rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

