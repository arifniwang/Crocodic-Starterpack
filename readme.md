# Laravel - Main Project Manager
<br>

> ## Included Package :

* CRUDBooster : https://github.com/crocodic-studio/crudbooster/blob/5.4.0/docs/en/index.md
* CB Laravel Model : https://github.com/crocodic-studio/cb-model
* Laravel Debugbar : https://github.com/barryvdh/laravel-debugbar
* Intervention Image : https://github.com/Intervention/image | https://stackoverflow.com/questions/27374613/laravel-intervention-image-class-class-not-found
* Spatie Laravel Backup : https://github.com/spatie/laravel-backup | https://docs.spatie.be/laravel-backup/v6/installation-and-setup/
* Guzzle HTTP client : https://github.com/guzzle/guzzle | https://guzzle.readthedocs.io/en/latest/
* Laravel FFMpeg : https://github.com/pascalbaljetmedia/laravel-ffmpeg
* Laravel Socialite : https://github.com/laravel/socialite | https://laravel.com/docs/6.x/socialite 
* File System Aws S3 : https://laravel.com/docs/6.x/filesystem | https://joelennon.com/using-digitalocean-spaces-in-laravel
* Cache Adapter : https://github.com/lukewaite/laravel-aws-cache-adapter | https://laravel.com/docs/6.x/filesystem
* API Logger : https://github.com/aungwinthant/apilogger
<br>

> ## Configuration
1. Clone Repository.

2. Remove directory with all files **.git** directory to clean up new repository.

3. Unremark file **.gitignore** in root directory
* Before : 
    ```
    #/node_modules
    #/public/hot
    #/public/storage
    #/storage/*.key
    #/vendor
    #.env
    #.phpunit.result.cache
    #Homestead.json
    #Homestead.yaml
    #npm-debug.log
    #yarn-error.log
    ```
* After : 
    ```
    /node_modules
    /public/hot
    /public/storage
    /storage/*.key
    /vendor
    .env
    .phpunit.result.cache
    Homestead.json
    Homestead.yaml
    npm-debug.log
    yarn-error.log
    ```
    

4. Import Database in this repository **mainprojectmanager.sql**.

5. Setting the database configuration, open .env file at project root directory. For example look on this line :
```
DB_DATABASE=**yourdatabase**
DB_USERNAME=**your_db_user**
DB_PASSWORD=**password**
```
<br>

> ## Supported By 

- [Crocodic - Mobile Apps Development](crocodic.com)
- [PT. Taman Media Indonesia](http://tamanmedia.co.id)
