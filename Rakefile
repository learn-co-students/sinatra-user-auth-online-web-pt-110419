require_relative './config/environment'
require 'sinatra/activerecord/rake'
# Type `rake -T` on your command line to see the available rake tasks.

desc 'Pry console yo!'
task :console do
  require_rel './app/models/user.rb'
  Pry.start
end