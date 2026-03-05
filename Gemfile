source "https://rubygems.org"

# This gem handles almost everything for you
gem "github-pages", "~> 232", group: :jekyll_plugins

# Only load Windows-specific gems if we are actually on Windows
install_if -> { Gem.win_platform? } do
  gem "wdm", ">= 0.1.0"
end

# Required for Ruby 3+
gem "webrick", "~> 1.8"
