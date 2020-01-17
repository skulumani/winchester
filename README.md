[![Netlify Status](https://api.netlify.com/api/v1/badges/a70e6ff3-8952-4cc2-a7de-4b4493606dca/deploy-status)](https://app.netlify.com/sites/condescending-cori-6a87f1/deploys)


## Winchester Underwood Cooperative

Website for the community. 

Can be reached at 

[https://winchester.netlify.com/](https://winchester.netlify.com/)


## TODO

* [X] Instructions for riot and community forum
* [ ] instructions for Google calendar
* [ ] Provide access to documents
* [X] Add community letters as posts
* [ ] Instructions on how to run/edit and build for others

# Installing Jekyll

* Install [RVM](https://rvm.io/)
~~~
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
\curl -sSL https://get.rvm.io | bash -s stable --ruby
rvm install ruby-2.3.0-dev
rvm install ruby --latest
sudo apt-get install nodejs
~~~
* Load rvm scripts
~~~
source ~/.rvm/scripts/rvm
~~~
* Install bundler
~~~
gem install bundler 
~~~
* Clone repo and navigate to the directory
~~~
bundle install
bundle update
~~~
* Create website
~~~
bundle exec jekyll serve
~~~

## Steps to run locally

1. Make sure you're using a login bash shell via `$ bash -l`
2. Install Ruby RVM and get `bundler` gems
3. Run `bundle exec jekyll serve`
