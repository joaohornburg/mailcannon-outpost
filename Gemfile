source 'https://rubygems.org'

ruby "2.1.0", :engine => "rbx", :engine_version => "2.2.1"

gem 'rubysl', platform: :rbx
gem 'rake'
gem "kiqstand", '>= 1.1.0'
gem 'mailcannon', github: 'lucasmartins/mailcannon'

# https://github.com/heroku/heroku-buildpack-ruby/issues/206
# If you have trouble with Heroku at deploy time, try this temporary fix:
# heroku config:set BUILDPACK_URL=https://github.com/heroku/heroku-buildpack-ruby.git#v84 --app YOURAPP