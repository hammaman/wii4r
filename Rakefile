require 'rake/extensiontask'
require 'rubygems/package_task'

load "wii4r.gemspec"

Gem::PackageTask.new(GEM_SPEC) do |pkg|
	pkg.need_zip = false
	pkg.need_tar = false
end

Rake::ExtensionTask.new("wii4r", GEM_SPEC)
