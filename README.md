# StripEmoji

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/strip_emoji`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem
## Alert

随着手机系统升级,emoji表情也会更新,此gem包不保证能过滤所有表情符号...

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'strip_emoji'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install strip_emoji

## Usage
```ruby
class Zone < ActiveRecord::Base
  strip_emoji_characters :name
end
```
![使用示例](./assets/strip_emoji.png?raw=true)


After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/strip_emoji. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

