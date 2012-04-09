# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  gem.name        = "smartdict"
  gem.homepage    = "http://github.com/greyblake/smartdict"
  gem.license     = "MIT"
  gem.summary     = %Q{Simple dictinionary written in Ruby}
  gem.description = %Q{Simple dictinionary written in Ruby}
  gem.email       = "blake131313@gmail.com"
  gem.authors     = ["Sergey Potapov"]
end
Jeweler::RubygemsDotOrgTasks.new

