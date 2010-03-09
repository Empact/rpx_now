task :default => :spec
require 'spec/rake/spectask'
Spec::Rake::SpecTask.new {|t| t.spec_opts = ['--color']}

begin
  require 'jeweler'

  Jeweler::Tasks.new do |gem|
    gem.name = 'Empact-rpx_now'
    gem.summary = "Helper to simplify RPX Now user login/creation"
    gem.email = "grosser.michael@gmail.com"
    gem.homepage = "http://github.com/Empact/rpx_now"
    gem.authors = ["Michael Grosser"]
    gem.add_dependency ['json_pure']
  end

  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler, or one of its dependencies, is not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end
