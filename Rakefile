desc "A dependancy"
task :dependancy1 do
  puts "Executed first"
end

desc "Second dependancy"
task :dependancy2 do
  puts "The second dependancy is the second"
end

desc "Hello World test for CI in Ruby"
task :test => ["dependancy1", "dependancy2"] do
  puts "Hello, travis CI!"
end

task :default => :test
