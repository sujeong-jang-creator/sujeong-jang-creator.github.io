source "https://rubygems.org"

gem "github-pages", "~> 226"

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

# HTTP server for local tests
gem "webrick", "~> 1.7"
