source 'https://rubygems.org'

gem 'rake'

group :docs do
    gem 'yard'
    gem 'redcarpet'
end

group :spec do
    gem 'simplecov', require: false, group: :test

    gem 'rspec', '2.99'
    gem 'faker'

    gem 'puma' if !Gem.win_platform? || RUBY_PLATFORM == 'java'

    gem 'sinatra'
    gem 'sinatra-contrib'
end

group :prof do
    gem 'stackprof'
    gem 'sys-proctable'
    gem 'ruby-mass'
end

gem 'ethon',           github: 'zapotek/ethon',           branch: 'windows-fixes'
gem 'arachni-reactor', github: 'arachni/arachni-reactor', branch: 'experimental'
gem 'arachni-rpc',     github: 'arachni/arachni-rpc',     branch: 'experimental'
# gem 'arachni-reactor', path: '/home/zapotek/workspace/arachni-reactor'
# gem 'arachni-rpc', path: '/home/zapotek/workspace/arachni-rpc'

gemspec
