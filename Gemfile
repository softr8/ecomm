source 'http://rubygems.org'

gem 'rails', '3.1.2'

gem 'unicorn'

gem 'haml'
gem 'jquery-rails'
gem 'mysql2'
gem 'spree', '0.70.3'#git: 'https://github.com/spree/spree.git', branch: '0-70-stable'
#gem "spree_paypal_express", :git => "git://github.com/spree/spree_paypal_express.git"
gem 'spree_recently_viewed', git: 'git://github.com/spree/spree_recently_viewed.git', branch: "1156bdb9b4b2872bd625aa38507451d2e5b22bde"
gem 'spree_editor', git: "git://github.com/spree/spree_editor.git"
gem 'spree_social', git: 'git://github.com/spree/spree_social.git' , :tag => 'v1.2'
gem 'spree_sunspot_search', git: 'git://github.com/jbrien/spree_sunspot_search.git'



# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'compass'
  gem 'sass-rails',   '~> 3.1.5.rc.2'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'foreman'
  gem 'rspec'
  gem 'sunspot_solr'
end
