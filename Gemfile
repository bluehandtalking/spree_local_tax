source 'http://rubygems.org'
gemspec

group :test do
  if RUBY_PLATFORM.downcase.include? "darwin"
    gem 'guard-rspec'
    gem 'rb-fsevent'
    gem 'growl'
  end
end

# specific to my dev setup
#gem 'ruport', :git => 'https://github.com/iloveitaly/ruport.git', :branch => 'wicked-pdf'
#gem 'spree_advanced_reporting', :git => 'https://github.com/iloveitaly/spree_advanced_reporting.git'

# jet require spree 1.1.2
gem 'spree', '~> 1.1.2'

# use tax cloud as a gem
gem 'tax_cloud', :git => 'git://github.com/bluehandtalking/tax_cloud.git'

