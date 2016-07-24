# FormattedGemUpdates

A script to print differences in Gem versions between the current commit and the previous. Perhaps useful for pasting into commit messages.

The output currently looks something like this:

```
UPDATED:
poltergeist         1.9.0   1.10.0
rspec-core          3.4.4   3.5.0
rspec-expectations  3.4.0   3.5.0
rspec-mocks         3.4.1   3.5.0
rspec-rails         3.4.2   3.5.0
rspec-support       3.4.1   3.5.0
sass-rails          5.0.4   5.0.5
selenium-webdriver  2.53.3  2.53.4
sprockets           3.6.2   3.6.3
sprockets-rails     3.0.4   3.1.1

REMOVED:
multi_json          1.12.1
```

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'formatted-gem-updates'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install formatted-gem-updates

## Usage

After making a commit that changes Gemfile and Gemfile.lock

    $ formatted-gem-updates

This will print out a table of changes with which you can do what you will.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/tjgrathwell/formatted-gem-updates. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

