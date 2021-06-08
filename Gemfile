source "https://rubygems.org"

ruby RUBY_VERSION

gem 'mimemagic', github: 'mimemagicrb/mimemagic', ref: '01f92d86d15d85cfd0f20dabd025dcbd36a8a60f'
gem "decidim", git: "https://github.com/decidim/decidim.git", branch: "release/0.22-stable"
gem "decidim-conferences", git: "https://github.com/decidim/decidim.git", branch: "release/0.22-stable"

gem "decidim-homepage_interactive_map", git: "https://github.com/OpenSourcePolitics/decidim-module-homepage_interactive_map.git", branch: "release/0.22-stable"
gem "decidim-navbar_links", git: "https://github.com/OpenSourcePolitics/decidim-module-navbar_links.git", branch: "0.22-stable"
gem "decidim-term_customizer", git: "https://github.com/OpenSourcePolitics/decidim-module-term_customizer.git", branch: "0.dev"

gem "bootsnap", "~> 1.3"
gem "dotenv-rails"
gem "puma", "~> 4.3"
gem "uglifier", "~> 4.1"
gem "faker", "~> 1.8"
gem "ruby-progressbar"
gem "sentry-raven"
gem "figaro"

gem "letter_opener_web", "~> 1.3"
gem "sprockets", "~> 3.7"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri
  gem "decidim-dev", git: "https://github.com/decidim/decidim.git", branch: "release/0.22-stable"
end

group :development do
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

group :production do
  gem "passenger"
  gem "fog-aws"
  gem "dalli"
  gem "sendgrid-ruby"
  gem "newrelic_rpm"
  gem "lograge"
  gem "sidekiq"
  gem "sidekiq-scheduler"
end
