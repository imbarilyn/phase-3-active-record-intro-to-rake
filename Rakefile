namespace :db do
desc "migrate changes to your database"
task migrate: :environment do
  Student.create_table  
end
task :environment do
  require_relative './config/environment'
end

desc "Seed the databaase with some dummy data"
task seed: :environment do
  require_relative './db/seeds'
end

desc 'drop into the pry console'
task console: :environment do
  pry.start
end
end

namespace :greeting do
  task :hello do 
    puts "hello from Rake!"
end

task :hola do
  puts "hola de Rake!"
end
end

task :console do 
end





