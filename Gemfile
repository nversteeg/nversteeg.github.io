source "https://rubygems.org"

# Requires Ruby 3.x (tested on 3.3.12, which is what GitHub Pages itself runs).
# It will NOT resolve on Ruby 4.x -- see README.md.

# Pins the exact gem versions GitHub Pages uses to build the site, so local
# previews match production. Do not add a `jekyll` line: github-pages pins it.
gem "github-pages", "~> 232", group: :jekyll_plugins

# Ruby 3.0 dropped webrick from the stdlib; `jekyll serve` needs it.
gem "webrick", "~> 1.8"

# Windows/JRuby ship no timezone database, and wdm gives Jekyll's file watcher
# a native backend so auto-rebuild isn't stuck polling.
gem "tzinfo-data", platforms: [:windows, :jruby]
gem "wdm", "~> 0.2", platforms: [:windows]
