# Laravel Playbook

## Setup

## Design Patterns

### Services & Repositories

#### Services

The Service Layer is a design pattern that will help you to abstract your logic for your domain logic. You delegate the application logic to a common service (the service layer) and have only one class to maintain when your application grows or needs an update. This is also a good way to clean up your controllers, and make them more readable.

More info:

* [Design Pattern : Service Layer with Laravel ](https://m.dotdev.co/design-pattern-service-layer-with-laravel-5-740ff0a7b65f)

#### Repositories

A repository represents the concept of a storage collection for a specific type of entity. The most important distinction about repositories is that they represent collections of entities. They do not represent database storage or caching or any number of technical concerns. Repositories represent collections.

More info:

* [The Repository Pattern](http://shawnmc.cool/the-repository-pattern)
## Deployment

### Artisan Commands

#### Speed up Laravel.

This will cache the config
```
php artisan config:cache
```
This will cache the routes
```
php artisan route:cache
```
Optimize the autoloader and compile all your views for you
```
php artisan optimize
```

## Monitoring
