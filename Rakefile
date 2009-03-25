require 'rake'

desc "Build clippy.swf"
task :default => 'build'

desc "Build clippy.swf"
task :build do
  system "swfmill simple library.xml library.swf && haxe compile.hxml && open -a Firefox.app build/clippy.swf"
end
