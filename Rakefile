# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project'
require 'bundler'
Bundler.setup
Bundler.require

require 'bubble-wrap/all'
require 'bubble-wrap/test'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'motion-template'
end

namespace :spec do
  task motion: :spec
  task all: :motion
end
