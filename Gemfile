# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

# TODO: remove when JRuby 9.4.10.0 will be released and available on CI
# Ref: https://github.com/jruby/jruby/issues/7262
if RUBY_PLATFORM.include?('java') && Gem::Version.new(JRUBY_VERSION) <= '9.4.9'
  gem 'jar-dependencies', '0.4.1'
end
