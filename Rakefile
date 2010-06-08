require 'rubygems'
require 'rake'

begin
  gem 'jeweler', '~> 1.4'
  require 'jeweler'

  Jeweler::Tasks.new do |gem|
    gem.name        = 'dm-do-adapter'
    gem.summary     = 'DataObjects Adapter for DataMapper'
    gem.description = gem.summary
    gem.email       = 'dan.kubb@gmail.com'
    gem.homepage    = 'http://github.com/datamapper/%s' % gem.name
    gem.authors     = [ 'Dan Kubb' ]

    gem.rubyforge_project = 'datamapper'

    gem.add_dependency 'data_objects', '~> 0.10.1'
    gem.add_dependency 'dm-core',      '~> 1.0.0'

    gem.add_development_dependency 'rspec', '~> 1.3'
  end

  Jeweler::GemcutterTasks.new

  FileList['tasks/**/*.rake'].each { |task| import task }
rescue LoadError
  puts 'Jeweler (or a dependency) not available. Install it with: gem install jeweler'
end

task(:spec) {} # this adapter only provides shared specs that are excercised by real adapters
