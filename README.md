## Basset for Laravel 4

Simple CDN provides a simple way of re-writing your URL's for specific assets using custom defined rules.
Offload your assets to a content delivery network by using an origin-pull and re-writing your URL's to point to your off-site host.

### Installation

To get the latest version of Simple CDN simply require it in your `composer.json` file.

~~~
"damianromanowski/laravel-simplecdn": "dev-master"
~~~

You'll then need to run `composer install` to download it and have the autoloader updated.

> Note that once Simple CDN has a stable version tagged you should use a tagged release instead of the master branch.

Once Simple CDN is installed you need to register the service provider with the application. Open up `app/config/app.php` and find the `providers` key.

~~~
'providers' => array(
    
    'Damianromanowski\Simplecdn\SimplecdnServiceProvider'

)
~~~

### Documentation

Coming soon!
