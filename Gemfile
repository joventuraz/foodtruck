source 'http://rubygems.org'

# Include everything needed to run rake, tests, features, etc.

gemspec

group :test do
  gem 'coveralls', require: false
end

local_gemfile = 'Gemfile.local'

if File.exist?(local_gemfile)
  eval(File.read(local_gemfile)) # rubocop:disable Lint/Eval
end