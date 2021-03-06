source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", "~> 5.1.4"
gem "mysql2", ">= 0.3.18", "< 0.5"
gem "puma", "~> 3.7"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.2"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
gem "faker"
gem "activerecord-import"
gem "devise"
gem "config"
gem "carrierwave"
gem "kaminari"
gem "i18n-js"
gem "jquery-rails"
gem "bootstrap-sass", "~> 3.3.7"
gem "jquery-datatables-rails", "~> 3.4.0"
gem "momentjs-rails"
gem "pnotify-rails"
gem "fullcalendar-rails"
gem "font-awesome-sass", "~> 4.7.0"
gem "bootstrap3-datetimepicker-rails", "~> 4.17.47"
gem "icheck-rails"
gem "select2-rails"
gem "mini_magick"
gem "material_icons"
gem "material_kit", "~> 1.0", ">= 1.0.0.2"

group :development, :test do
  gem "rspec"
  gem "rspec-rails"
  gem "rspec-collection_matchers"
  gem "factory_bot_rails"
  gem "better_errors"
  gem "guard-rspec", require: false
  gem "database_cleaner"
  gem "brakeman", require: false
  gem "jshint"
  gem "bundler-audit"
  gem "rubocop", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "eslint-rails", git: "https://github.com/octoberstorm/eslint-rails", require: false
  gem "scss_lint", require: false
  gem "scss_lint_reporter_checkstyle", require: false
  gem "rails_best_practices"
  gem "reek"
  gem "railroady"
  gem "autoprefixer-rails"
  gem "pry", platforms: [:mri, :mingw, :x64_mingw]
  gem "capybara", "~> 2.13"
  gem "selenium-webdriver"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  gem "simplecov", require: false
  gem "simplecov-rcov", require: false
  gem "simplecov-json"
  gem "shoulda-matchers"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
