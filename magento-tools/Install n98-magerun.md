How Install n98-magerun on windows

  1- Open cmd.exe and cd D:\xampp\htdocs 
  
  #Installing Composer locally on your director
  2-php -r "readfile('https://getcomposer.org/installer');" | php
  
  #To Create Project with project name "firstproject"
  3-php -f ./composer.phar -- create-project n98/magerun firstproject
  
  
