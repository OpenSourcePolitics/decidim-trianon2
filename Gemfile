# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "f-moderation"

gem "decidim-export", git: "https://github.com/OpenSourcePolitics/decidim-user-export.git"
gem 'webpacker', '~> 3.0'

# Uncomment the following line if you want to use decidim-assemblies plugin
# gem "decidim-assemblies", path: ".."

gem "puma", "~> 3.0"
gem "uglifier", ">= 1.3.0"

gem "faker", "~> 1.8.4"

group :development, :test do
  gem "byebug", platform: :mri

  gem "decidim-dev", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "f-moderation"
end

group :development do
  gem "letter_opener_web", "~> 1.3.0"
  gem "listen", "~> 3.1.0"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console"
end
