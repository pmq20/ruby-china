if ENV['USE_OFFICIAL_GEM_SOURCE']
  source 'https://rubygems.org'
else
  source 'https://ruby.taobao.org'
end

ruby '2.3.0'

gem 'rails', '5.0.0'
gem 'sprockets', '>= 3.5.2'
gem 'sass-rails', '>= 5.0.5'
gem 'coffee-rails', '>= 4.1.1'
gem 'uglifier', '>= 2.7.2'
gem 'jquery-rails', '>= 4.1.1'
gem 'jbuilder', '>= 2.4.0'
gem 'turbolinks', github: 'rails/turbolinks'
gem 'jquery-turbolinks', '>= 2.1.0'
gem 'dropzonejs-rails', '>= 0.7.2'

gem 'rails-i18n', '>= 5.0.0'
gem 'http_accept_language'
gem 'rails_autolink', '>= 1.1.6'
gem 'md_emoji', '>= 1.0.2'
gem 'exception_notification', '>= 4.1.1'

gem 'doorkeeper', github: 'doorkeeper-gem/doorkeeper'
gem 'doorkeeper-i18n'

# gem 'rails-perftest'
# gem 'ruby-prof'

# 上传组件
gem 'carrierwave', '>= 0.10.0'
gem 'carrierwave-upyun', '>= 0.2.1'
gem 'mini_magick'

gem 'rucaptcha'
gem 'letter_avatar'

gem 'pg'

# remove this after migrate MongoDB into PostgreSQL
gem 'mongo', require: false

# 用户系统
gem 'devise', '~> 4.0.0.0'
gem 'devise-encryptable', '>= 0.2.0'

# 分页
gem 'will_paginate'

# 搜索
gem 'elasticsearch-model', '>= 0.1.8'
gem 'elasticsearch-rails'

# 三方平台 OAuth 验证登陆
gem 'omniauth', '>= 1.3.1'
gem 'omniauth-github', '>= 1.0.1'

# permission
gem 'cancancan', '~> 1.13.1'

gem 'redis'
gem 'hiredis'
# Redis 命名空间
gem 'redis-namespace'
# 将一些数据存放入 Redis
gem 'redis-objects'

gem 'rails-settings-cached', '>= 0.5.3'

# Markdown 格式 & 文本处理
gem 'redcarpet', '~> 3.3.4'
gem 'rouge', '~> 1.8.0'
gem 'auto-space', '>= 0.0.4'
gem 'nokogiri'

# YAML 配置信息
gem 'settingslogic'

# 队列
gem 'sidekiq'
# Sidekiq Web
gem 'sinatra', github: 'sinatra/sinatra', require: nil

# 分享功能
gem 'social-share-button', '>= 0.1.10'

# 表单
gem 'simple_form', '>= 3.2.1'

# API
gem 'grape', '>= 0.14.0'
gem 'active_model_serializers', '0.9.2'
gem 'grape-active_model_serializers', '>= 1.3.2'

# Mailer
gem 'postmark', '>= 1.7.0'
gem 'postmark-rails', '>= 0.12.0'

# Dalli, kgio is for Dalli
gem 'kgio'
gem 'dalli'

gem 'puma'

gem 'parallel'

# for api 跨域
gem 'rack-cors', require: 'rack/cors'
gem 'rack-utf8_sanitizer', '>= 1.3.2'

# Mini profiler
gem 'rack-mini-profiler', github: 'MiniProfiler/rack-mini-profiler', require: false

gem 'oneapm_rpm'

group :development do
  gem 'capistrano', '2.9.0', require: false
  gem 'rvm-capistrano', require: false
  gem 'capistrano-sidekiq'

  gem 'derailed', '>= 0.1.0'

  # Better Errors
  gem 'better_errors', '>= 2.1.1'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'rubocop'

  gem 'rspec-rails', '3.5.0'

  gem 'rails-controller-testing', '>= 0.0.3'

  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'database_cleaner'
  gem 'capybara', '>= 2.6.0'

  gem 'jasmine-rails', '~> 0.10.8'

  gem 'colorize'
  gem 'letter_opener'

  gem 'bundler-audit', require: false
end
