$:.unshift File.dirname(__FILE__) + 'lib'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new

task :default => :spec

desc "Run lib/fraccion.rb"
task :spec do
  	sh "rspec -I. spec/fraccion_spec.rb"
end

desc "Run tests with --format documentation"
task :doc do
  	sh "rspec -I. spec/fraccion_spec.rb --format documentation"
end

desc "Run tests with format: html"
task :thml do
	sh "rspec -I. spec/fraccion_spec.rb format: html"
end


