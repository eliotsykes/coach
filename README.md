# Coach

> A (work in progress) coaching assistant for mentors who teach developers.

## Installation

On OSX, use Homebrew to install cmake and pkg-config (required by pronto gem):

```bash
brew install cmake pkg-config
```

Enable any pronto runners you want by uncommenting the relevant `pronto-*` gems
in `Gemfile`.

And then execute:

```bash
$ bundle
```

## Usage

```bash
bundle exec pronto run path/to/project-to-review
```

## Roadmap & Ideas

Build this to have sensible default configuration appropriate for newer Rails learners. This means only highlighting the most valuable lessons and treating the rest appropriately for an educational environment. 

For example, whitespace at the end of a line isn't as valuable a learning opportunity as a URL-tampering security vulnerability. By default, tools tend to be noisy about code formatting and documentation issues. The `coach` default ought to be tweaked to be suited to a learning environment to bring attention to the most essential points.

The goal of `coach` is to assist mentors. All of its warnings ought to be reviewed by a mentor manually before sharing with a student. `coach` is not recommended for students to use directly.

Borrowing from Inch's progressive grading of warnings may be useful: http://trivelop.de/inch/

## Guidelines & Tools to evaluate

- https://github.com/apiology/quality
- https://github.com/hakirisec/hakiri_toolbelt
- https://github.com/simplabs/excellent
- https://github.com/whitesmith/rubycritic
- https://github.com/square/cane
- https://github.com/eliotsykes/rails-code-review
- https://github.com/makaroni4/sandi_meter
- https://github.com/apiology/bigfiles
- https://github.com/metricfu/metric_fu
- https://github.com/roodi/roodi
- https://github.com/turboladen/tailor


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment. Run `bundle exec coach` to use the code located in this directory, ignoring other installed copies of this gem.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/[my-github-username]/coach/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
