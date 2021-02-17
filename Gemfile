source 'https://rubygems.org'

solidus_branch = ENV.fetch('SOLIDUS_BRANCH', 'elia/fix-factory-loading')
gem "solidus_core", github: "nebulab/solidus", branch: solidus_branch, ref: '2c28337b07'
gem "solidus_frontend", github: "nebulab/solidus", branch: solidus_branch, ref: '2c28337b07'
gem "solidus_backend", github: "nebulab/solidus", branch: solidus_branch, ref: '2c28337b07'

alchemy_branch = ENV.fetch('ALCHEMY_BRANCH', 'main')
gem "alchemy_cms", github: "AlchemyCMS/alchemy_cms", branch: alchemy_branch
gem 'alchemy-devise', github: "AlchemyCMS/alchemy-devise", branch: 'main'

# Specify your gem's dependencies in alchemy-solidus.gemspec
gemspec

gem 'sqlite3'
gem 'pry-rails'
gem 'sprockets', '< 4'
