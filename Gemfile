source 'https://rubygems.org'

gem 'spree', github: 'spree/spree', branch: 'master'

platforms :jruby do
  gem 'activerecord-jdbcsqlite3-adapter'
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'activerecord-jdbcmysql-adapter'
end

platforms :ruby do
  gem 'sqlite3'
  gem 'pg'
  gem 'mysql2'
end

gemspec
