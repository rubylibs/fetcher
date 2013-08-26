require 'hoe'
require './lib/fetcher.rb'

Hoe.spec 'fetcher' do
  
  self.version = Fetcher::VERSION
  
  self.summary = 'fetcher - Fetch Text Documents or Binary Blobs via HTTP, HTTPS'
  self.description = summary

  self.urls    = ['https://github.com/geraldb/fetcher']
  
  self.author  = 'Gerald Bauer'
  self.email   = 'webslideshow@googlegroups.com'
    
  # switch extension to .markdown for gihub formatting
  self.readme_file  = 'README.markdown'
  self.history_file = 'History.markdown'

  self.extra_deps = [
    ['logutils', '>= 0.6']
  ]

  self.licenses = ['Public Domain']

  self.spec_extras = {
   :required_ruby_version => '>= 1.9.2'
  }
  
end
