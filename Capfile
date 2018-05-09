# Load DSL and Setup Up Stages
require 'capistrano/setup'

# Includes default deployment tasks
require 'capistrano/deploy'

# If you are using rbenv add these lines:
require 'capistrano/rbenv'
set :rbenv_type, :user
set :rbenv_ruby, '2.5.1p57'

require 'capistrano/bundler'
require 'capistrano/rails'
require 'capistrano/passenger'


# Loads custom tasks from `lib/capistrano/tasks' if you have any defined.
Dir.glob('lib/capistrano/tasks/*.cap').each { |r| import r }
