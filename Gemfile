source :rubygems

platform :jruby do
  gem 'redstorm', '~> 0.6.4.b1', :git => "git://github.com/colinsurprenant/redstorm.git", :branch => "v0.6.4"
end

platform :mri  do
  gem 'twitter-stream', '~> 0.1.16'
  gem 'redis', '~> 3.0.2'
  gem 'hiredis', '~> 0.4.5'
end

group :topology do
  gem 'redis', '~> 3.0.2', :platforms => :jruby
  gem 'json', :platforms => :jruby
end