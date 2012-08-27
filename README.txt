A simple rails app with devise and bootstrap pre-loaded.

Steps:

$ git clone https://github.com/letsalign/bootstrap-devise.git

$ cd bootstrap-devise/

$ bundle install

$ rails plugin install git@github.com:get/Rename.git

$ rails g rename_to NewAppName

You should also change the folder name to NewAppName

$ rake db:migrate

$ rails s