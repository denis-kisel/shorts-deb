# Shorts

This is package for short bash code for web development

## Installation

Open bash and run commands

``` bash
$ cd ~/Downloads && git clone https://github.com/denis-kisel/shorts-deb.git
$ cd shorts-deb && sudo dpkg -i shorts_0.1-1.1_all.deb
```

## Usage

``` bash
#Git commands
$ commit 'commit comment'  #Equivalent
                           $ git add --all
                           $ git commit -m 'commit comment'
                           
$ git-reset                #Equivalent
                           git reset --hard HEAD

#Laravel commands                           
$ lara {command}           #Equivalent
                           php artisan {command}
                            
               
#Apache
$ a2rest                   #Equivalent
                           $ sudo service apache2 restart 


```

## Depends
php7.2-cli  
git  
apache2  
laravel(php framework)
