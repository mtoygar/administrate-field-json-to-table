# frozen_string_literal: true

begin
  require 'bundler/setup'
rescue LoadError
  puts 'You must `gem install bundler` and `bundle install` to run rake tasks'
end

require File.expand_path('spec/example_app/config/application', __dir__)

Rails.application.load_tasks
