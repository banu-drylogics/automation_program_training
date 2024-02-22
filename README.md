
1. Include following gems in Gemfile and run bundle install
        gem 'selenium-webdriver'
        gem 'byebug'
        gem 'webdrivers', '~> 5.0'
2. Install Chromedriver in path
    a) mkdir ~/bin
    b) download driver from https://chromedriver.chromium.org/downloads for your chrome version
        find chrome version from brower help (About Chrome)
    c) unzip it to ~/bin
    d) add ~/bin to $PATH
        i) Open ~/.bashrc file
        ii) Include the statement at the end of the file
             PATH="$HOME/bin:$PATH"
    e) run source ~/.bashrc


Execution
    bundle exec ruby ./my-first-selenium.rb
