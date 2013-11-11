#source 'https://rubygems.org'
source 'http://rubygems.railscamp.org'

gem 'rake', :group => [:development, :test]
gem 'rbtree-pure'

group :development do
  gem 'jeweler'
  gem 'rspec', '~>2.6.0'
  gem 'ruby-debug', :platforms => [:mri_18]
  gem 'debugger', :platforms => [:mri_19, :mri_20]
  gem 'pry', :platforms => [:jruby, :rbx]
end

group :test do
  # rcov 1.0.0 is broken for jruby, so 0.9.11 is the only one available.
  gem 'rcov', '~>0.9.11', :platforms => [:jruby, :mri_18], :require => false
  gem 'simplecov', '~>0.6.4', :platforms => :mri_19, :require => false
end
