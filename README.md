# Laravel WWW Redirect

Simple package to redirect www domains to non-www in your Laravel application.

# Install
##### Install with composer
```
$ composer require redcenter/laravel-www-redirect
```

# Adding middleware
Add the middleware class to your Kernel.php in App\Http:
```
    protected $middlewareGroups = [
        'web' => [
            ...
            LaravelWwwRedirectMiddleware::class,
            ...
        ],
    ];
```

## Questions?
You can contact me through my website: redcenter.nl

##### Good bye!

Check out the documentation on Bitbucket for all details!

https://bitbucket.org/redcenter/laravel-www-redirect
