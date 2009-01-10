#!/usr/bin/env ruby
require 'pathname'
require 'rubygems'
require 'rake'
require 'rake/rdoctask'
require 'spec/rake/spectask'

require 'lib/dm-core/version'

ROOT = Pathname(__FILE__).dirname.expand_path

AUTHOR = "Dan Kubb"
EMAIL  = "dan.kubb@gmail.com"
GEM_NAME = "dm-core"
GEM_VERSION = DataMapper::VERSION
GEM_DEPENDENCIES = ["data_objects", "~>0.9.10"],
                   ["extlib", "~>0.9.9"],
                   ["addressable", "~>2.0.1"]

PROJECT_NAME = "datamapper"
PROJECT_DESCRIPTION = "Faster, Better, Simpler."
PROJECT_SUMMARY = "An Object/Relational Mapper for Ruby"
PROJECT_URL  = "http://datamapper.org"

require ROOT + 'tasks/hoe'
require ROOT + 'tasks/gemspec'
require ROOT + 'tasks/install'
require ROOT + 'tasks/dm'
require ROOT + 'tasks/doc'
require ROOT + 'tasks/ci'
