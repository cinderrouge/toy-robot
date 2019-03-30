source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in toy_robot.gemspec
#gemspec

# gem 'rspec-core'

%w[rspec-core rspec-expectations rspec-mocks rspec-support].each do |lib|
  gem lib, :git => "https://github.com/rspec/#{lib}.git", :branch => 'master'
end