require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('UniqToken', '0.2.1') do |p|
  p.description = "Generate a Unique token with ActiveRecords"
  p.url = "https://github.com/kususun/Uniquify-Gem"
  p.author = "Lintang Arief"
  p.email = "lintangarief13@gmail.com"
  p.ignore_pattern  = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
