A simple Rails app with Devise (https://github.com/plataformatec/devise) and Bootstrap (https://github.com/twitter/bootstrap) pre-loaded.

Steps:

$ git clone https://github.com/letsalign/bootstrap-devise.git

$ cd bootstrap-devise/

$ bundle install

$ rails plugin install git@github.com:get/Rename.git

$ rails g rename_to NewAppName

You should also change the folder name to NewAppName

$ rake db:migrate

$ rails s

Your simple Rails app with Bootstrap theme and Devise auth system is now up and running!