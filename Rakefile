require 'rake'

desc "Build clippy.swf"
task :default => 'build'

desc "Build clippy.swf"
task :build do
  system "swfmill simple library.xml library.swf && haxe compile.hxml"
end

task :preview => :build do
  system "firefox build/clippy.swf"
end
