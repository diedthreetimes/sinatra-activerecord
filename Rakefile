require 'bundler'
Bundler::GemHelper.install_tasks

require 'appraisal'

task :default => :spec

require "rspec/core/rake_task"
RSpec::Core::RakeTask.new(:spec) do |t|
  t.verbose = true
end
