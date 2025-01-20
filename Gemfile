source "https://rubygems.org"

# 更新 Jekyll 版本
gem "jekyll", "~> 4.2.0"  # 或者使用最新的稳定版本

group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.17'  # 更新到最新版本
  gem 'jekyll-sitemap', '~> 1.4'  # 保持不变
  gem 'jekyll-compose', '~> 0.12.0'  # 保持不变
  gem 'jekyll-postfiles', '~> 3.1'  # 保持不变
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "wdm", "~> 0.1.0" if Gem.win_platform?
gem "webrick", "~> 1.7"

# 添加 ffi 和 sassc
gem 'ffi', '~> 1.15'
gem 'sassc', '~> 2.4'

# 添加缺失的库
gem 'csv', require: false  # 添加 csv
gem 'base64', require: false  # 添加 base64
gem 'bigdecimal', require: false  # 添加 bigdecimal
