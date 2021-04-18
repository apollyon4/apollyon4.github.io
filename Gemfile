source "https://rubygems.org"
gemspec

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]

# avoid warning message "Please add the following to your Gemfile to avoid polling for changes:"
# if it doesn't work? try cmd "gem install wdm"
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

# manage for post by jekyll-admin
gem 'jekyll-admin', group: :jekyll_plugins