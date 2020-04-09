source "https://rubygems.org"

gemspec

# ADD THESE LINES TO WORKAROUND
gem 'mini_portile'
gem 'mini_portile2', '>=2.4'
# END OF WORKAROUND

if File.exist?(File.expand_path("../../vagrant-spec", __FILE__))
  gem 'vagrant-spec', path: "../vagrant-spec"
else
  gem 'vagrant-spec', git: "https://github.com/hashicorp/vagrant-spec.git", ref: '161128f2216cee8edb7bcd30da18bd4dea86f98a'
end
