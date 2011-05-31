##coding: utf-8
require 'rake'
require 'rake/testtask'
require 'rcov/rcovtask'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |s|
    s.name = "rseg"
    s.summary = "A Chinese Word Segmentation(中文分词) routine in pure Ruby"
    s.email = "zhangyuanyi@gmail.com"
    s.homepage = "http://github.com/yzhang/rseg"
    s.description = "A Chinese Word Segmentation(中文分词) routine in pure Ruby"
    s.authors = ["Yuanyi Zhang"]
    s.files =  FileList["[A-Z]*", "{lib}/**/*", '.gitignore', 'dict/dict.hash']
  end
rescue LoadError
  puts "Jeweler, or one of its dependencies, is not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end

