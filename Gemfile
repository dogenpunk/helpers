source 'https://rubygems.org'
gemspec

unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'pry-debugger-jruby', require: false, platforms: :jruby
  gem 'yard', require: false
end

gem 'hanami-utils',       '~> 1.2', git: 'https://github.com/hanami/utils.git',       branch: 'master'
gem 'hanami-validations', '~> 1.2', git: 'https://github.com/hanami/validations.git', branch: 'master'
gem 'hanami-controller',  '~> 1.2', git: 'https://github.com/hanami/controller.git',  branch: 'master'
gem 'hanami-view',        '~> 1.2', git: 'https://github.com/hanami/view.git',        branch: 'master'

gem 'hanami-devtools', git: 'https://github.com/hanami/devtools.git', require: false
gem 'coveralls', require: false
