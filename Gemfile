source "https://rubygems.org"

gemspec

gem "rdf",                git: "git://github.com/ruby-rdf/rdf.git", branch: "develop"
gem "rdf-aggregate-repo", git: "git://github.com/ruby-rdf/rdf-aggregate-repo.git", branch: "develop"
gem "sparql",             git: "git://github.com/ruby-rdf/sparql.git", branch: "develop"
gem "jruby-openssl",      platforms: :jruby
gem "nokogiri",           '~> 1.6'

group :development, :test do
  gem "rdf-spec",    git: "git://github.com/ruby-rdf/rdf-spec.git", branch: "develop"
  gem 'sxp',         git: "git://github.com/gkellogg/sxp-ruby.git"
  gem 'rdf-turtle'
end

group :debug do
  gem 'shotgun'
  gem "wirble"
  gem "byebug", platforms: [:mri_20, :mri_21]
end

platforms :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'rubinius', '~> 2.0'
end
