# frozen_string_literal: true

source "https://rubygems.org"

gemspec

# Whitelisted plugins not included in runtime dependencies.
gem "jekyll-octicons"
gem "jekyll", "3.9.0", :git => "https://github.com/boris-badenov/jekyll.git" # 4.2.0 as 3.9.0

group :test do
  gem "rubocop", "~> 0.79"
  gem "rubocop-performance"
  gem "webmock"
end
