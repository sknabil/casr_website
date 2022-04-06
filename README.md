# CASR Lab Website

1. Make sure you have gcc.
gcc -v

2. Install ruby

sudo gem install ruby
sudo gem install bundler

3. Now, Create a directory, and add a file called Gemfile. The file doesn't contain an extension. Type the following contents into the file and save it.

gem 'github-pages'
source 'https://rubygems.org'

4. In Terminal, run this command in the directory that contains the Gemfile:
bundle install

This command should run for a while. It might ask you for your sudo password, or for you to run sudo bundle install. 

5. If the bundle install shows error, do the following.
sudo apt-get upgrade ruby
sudo apt-get install ruby-dev

Also, install pygments
sudo gem install pygments.rb

6. Now, download the git project:
git clone https://github.com/sknabil/casr_website.git casrlab

7. Inside the casrlab, run following:
jekyll serve



Copyright Allan Lab. Code released under the MIT License.

