require "rspec/core/rake_task"
require "rubocop/rake_task"
require "standard/rake"

RuboCop::RakeTask.new
RSpec::Core::RakeTask.new(:spec)

task :default => [:spec, :standard]
