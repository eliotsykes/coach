source 'https://rubygems.org'

# Specify your gem's dependencies in coach.gemspec
gemspec

gem 'pronto'

# Pronto needs to be configured with runners. Available runners list:
# https://github.com/mmozuras/pronto#runners

# Pronto runner for JSHint, JavaScript code quality tool
# https://github.com/mmozuras/pronto-jshint
# http://jshint.com/
gem 'pronto-jshint', require: false

# Pronto runner for Brakeman, security vulnerability scanner for RoR
# https://github.com/mmozuras/pronto-brakeman
# -
# Brakeman is a static analysis tool which checks Ruby on Rails applications for
# security vulnerabilities.
# https://github.com/presidentbeef/brakeman
# TODO/BUG: confirm pronto-brakeman is ignoring path CLI option
# gem 'pronto-brakeman', require: false

# Pronto runner for Flay, structural similarities analyzer.
# https://github.com/mmozuras/pronto-flay
# -
# Flay analyzes code for structural similarities. Differences in literal values,
# variable, class, method names, whitespace, programming style, braces vs
# do/end, etc are all ignored. Making this totally rad.
# https://github.com/seattlerb/flay
# -
# TODO: Experiment with https://github.com/UncleGene/flay-actionpack
gem 'pronto-flay', require: false

# Pronto runner for Rubocop, ruby code analyzer
# https://github.com/mmozuras/pronto-rubocop
# -
# A Ruby static code analyzer, based on the community Ruby style guide.
# https://github.com/bbatsov/rubocop
gem 'pronto-rubocop', require: false

# Pronto runner for Rails Best Practices, code metric tool for Rails projects
# https://github.com/mmozuras/pronto-rails_best_practices
# -
# rails_best_practices is a code metric tool to check the quality of rails code.
# https://github.com/railsbp/rails_best_practices
gem 'pronto-rails_best_practices', require: false

# Pronto runner for Reek, code smell detector for Ruby
# https://github.com/mmozuras/pronto-reek
# -
# Reek - code smell detection for Ruby
# https://github.com/troessner/reek
gem 'pronto-reek', require: false

# Pronto runner for Poper, git commit message analyzer
# https://github.com/mmozuras/pronto-poper
# -
# Make sure git commit messages are well-formed
# https://github.com/mmozuras/poper
# gem 'pronto-poper', require: false

# gem 'pronto-coffeelint', require: false
# gem 'pronto-haml', require: false
# gem 'pronto-scss', require: false
# gem 'pronto-spell', require: false