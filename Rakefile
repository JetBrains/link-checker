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
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "link-checker"
  gem.homepage = "git@github.com:endymion/link-checker.git"
  gem.license = "MIT"
  gem.summary = %Q{Check the links in a web site before deploying.}
  gem.description = %Q{Check the links in a web site before deploying, using Nokogiri.}
  gem.authors = ["Ryan Alyn Porter"]
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new

require 'rspec/core/rake_task'
desc "Run specs"
RSpec::Core::RakeTask.new