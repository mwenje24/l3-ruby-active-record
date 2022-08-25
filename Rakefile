require_relative './config/environment'
require 'sinatra/activerecord/rake'

# CREATE TASK WITHOUT DESCRIPTION

task :hello_world do
    puts "Hello world"
end

# CREATE TASK WITH DESCRIPTION
desc 'Find .01% of 14M'
task :complex_math do
    output = (0.01/100) * 14000000
    puts output
end

# ORGANIZE TASKS IN NAMESPACES
namespace :math_concepts do
    desc 'addition'
    task :add, [:num1, :num2] do
        sum = num1 + num2
        puts "Addition is #{sum}"
    end

    desc 'subtraction'
    task :subtract do
        puts "subtraction"
    end
end