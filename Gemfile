source "https://rubygems.org"

# Jekyll

## Ensure latest Jekyll version is used (change it and run "bundle update" in terminal)
gem "jekyll", "~> 4.0.0"

## Plugins

group :jekyll_plugins do
  gem "jemoji", ">= 0.11.0"
  gem "jekyll-redirect-from", ">= 0.15.0"
end

# Windows

## include zoneinfo files
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

## performance-booster for watching directories
gem "wdm", "~> 0.1.0" if Gem.win_platform?