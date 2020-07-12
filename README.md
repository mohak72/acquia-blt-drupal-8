# acquia-blt-drupal-8
   # Installing Acquia BLT
install git composer drush
composer global require hirak/prestissimo:^0.3
composer global require zaporylie/composer-drupal-optimizations:^1.1
  # Creating new project with BLT
https://docs.acquia.com/blt/install/creating-new-project/
To create a new Acquia BLT project, complete the following steps:

    Determine a machine name for your new project (such as my-project). For compatibility with third-party tools, Acquia recommends you use only letters, numbers, and hyphens for the machine name.

    In a command prompt window, run the following command to both create your new project and download all dependencies (including Acquia BLT):

    composer create-project --no-interaction acquia/blt-project my-project

    Change to your project directory. For example:

    cd my-project

    If this is your first time using Acquia BLT on this computer, restart your shell to allow Bash to detect the new Acquia BLT alias.

    Customize your blt/blt.yml file to select an install profile. The build.yml file includes all available configuration values.

    By default, Acquia BLT installs websites using the Lightning profile. You can change this setting to any other core, contributed, or custom profile in your codebase.
