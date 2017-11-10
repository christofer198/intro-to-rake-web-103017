desc 'outputs hello to the terminal'
namespace :greeting do
  task :hello do
    puts "hello from Rake!"
  end
  task :hola do
    puts "hola de Rake!"
  end
end

namespace :db
  task :migrate => :environment do
    Student.create_table
  end

  task :seed do
    require_relative '/db/seeds.rb'
  end
end
