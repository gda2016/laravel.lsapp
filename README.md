# Laravel From Scratch
#### [Source :](https://www.youtube.com/watch?v=H3uRXvwXz1o)
#### [MeisterTask]()
#### [GitHub]()
#### [CODE: Complete Code For This Series](https://github.com/bradtraversy/lsapp)
## TODO
- [x]  1 : [Laravel From Scratch [Part 1] - Series Introduction](https://www.youtube.com/watch?v=EU7PRmCpx-0&list=PLillGF-RfqbYhQsN5WMXy6VsDMKGadrJ-)
- [x]  2 : [Laravel From Scratch [Part 2] - Environment Setup & Laravel Installation](https://www.youtube.com/watch?v=H3uRXvwXz1o&list=PLillGF-RfqbYhQsN5WMXy6VsDMKGadrJ-&index=2)
- [x]  3 : [Basic Routing & Controllers](https://www.youtube.com/watch?v=sLFNVXY0APk&list=PLillGF-RfqbYhQsN5WMXy6VsDMKGadrJ-&index=3)
- [x]  4 : [Blade Templating & Compiling Assets](https://www.youtube.com/watch?v=bSG2YMqJJys&index=4&list=PLillGF-RfqbYhQsN5WMXy6VsDMKGadrJ-)
- [ ]  5 :
- [ ]  6 :
- [ ]  7 :
- [ ]  8 :
- [ ]  9 :
- [ ] 10 :
- [ ] 11 :
- [ ] 12 : 
- [ ] 13 :

## Step : 3
### [Basic Routing & Controllers](https://www.youtube.com/watch?v=sLFNVXY0APk&list=PLillGF-RfqbYhQsN5WMXy6VsDMKGadrJ-&index=3)
#### 6 : Create Controller
`$ php artisan make:controller PagesController`

## Step : 4
### [Blade Templating & Compiling Assets](https://www.youtube.com/watch?v=bSG2YMqJJys&index=4&list=PLillGF-RfqbYhQsN5WMXy6VsDMKGadrJ-)

#### 5 : NPM instal pakage depenedsies
`$ npm install`
##### Troubleshooting
```
$ npm uninstall uuid --self
$ npm install uuid --self
```
##### Using
```
$ npm run dev
$ npm run watch
```

##### 6 : Add Custom CSS



## Postscript
### Git
`$ git -b step_4 https://github.com/gda2016/laravel.lsapp.git lr`

### Composer
`$ compiser install`
#### [Trubleshooting](https://stackoverflow.com/questions/28893710/whoops-looks-like-something-went-wrong-laravel-5-0#28893877)
1. Give write permission to storage and bootstrap/cache directories
1. Rename .env.example file to .env
1. If you get "RuntimeException... No supported encrypter found. The cipher and / or key length are invalid." error, stop the application and generate key from command line
`$ php artisan key:generate`

# Previous
## Example of Artisan Commands
     $ php artisan list
     $ php artisan help migrate
     $ php artisan make:controller TodosController
     $ ph partisan make:model Todo -m
     $ php artisan make migration add_todos_to_db-table=todos
     $ php artisan migrate
     $ php artisan tinker
     $ php artisan serve

## Installation localy
     $ composer create-project --prefer-dist laravel/laravel project-name
     $ php artisan serve
## [Laravel 5 IDE Helper Generator](https://github.com/barryvdh/laravel-ide-helper)

## Start after git clone
     $ composer install -dev
     $ cp .env.example .env
     $ php artisan key:generate

## Package for Atom
     - language blade
## node_modules
     $ npm install
     $npm run dev
### Troubleshuting
       $ npm cache clean -f