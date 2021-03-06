# PasswordPolice

The idea behind this gem is that users' passwords must match a password strength respective to the sensitivity of the information on their account or the privileges available to the user. The strength of a password is determined using Dropbox's [zxcvbn](https://github.com/dropbox/zxcvbn). The hope is that this idea would be an decent balance between usability and security.

i.e. Users should be required to register with a "higher" strength password if they are "administrators" compared to the "lower" password strength requirement for a "normal" user.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'password_police'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install password_police

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/edwardqiu/password_police. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the PasswordPolice project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/edwardqiu/password_police/blob/master/CODE_OF_CONDUCT.md).
