require 'pathname'

source 'http://rubygems.org'

DM_VERSION     = '~> 1.2.0'
DO_VERSION     = '~> 0.10.6'

gem 'data_objects', DO_VERSION, do_options.dup
gem 'dm-core', DM_VERSION

group :development do

  gem 'jeweler', '~> 1.6.4'
  gem 'rake',    '~> 0.9.2'
  gem 'rspec',   '~> 1.3.2'

end

platforms :mri_18 do
  group :quality do

    gem 'rcov',      '~> 0.9.10'
    gem 'yard',      '~> 0.7.2'
    gem 'yardstick', '~> 0.4'

  end
end
