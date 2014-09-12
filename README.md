# Spree Payumoney

This is a PayUMoney extension for spree 2.4.


## Installation

1. Add this extension to your Gemfile with this line:

        gem 'spree_payumoney', :github => "milinpaul/spree_payumoney"

        If you want to use the latest build add this line to GemFile

        gem 'spree_payumoney', :github => "milinpaul/spree_payumoney", :branch => "master"


2. Install the gem using Bundler:

        bundle install

3. Copy & run migrations

        bundle exec rails g spree_payumoney:install

4. Restart your server


###Thanks 
This code is a re-write of https://github.com/meetdestiny/spree_payupaisa_express to support payupaisa. Thanks a ton to the original author.


###Legal 
Use it at  your own risk. Use however you want. But don't bug me if your server is fried - make toast on it.  
