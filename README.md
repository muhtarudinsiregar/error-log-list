<h1 align="center">Error List</h1>


## Angular 2
1. Shared Data from other component in services

 http://stackoverflow.com/questions/35273106/angular2-share-data-between-components-using-services
 
## Codeigniter
1. Class 'TestCase' not found
 
 https://github.com/kenjis/ci-phpunit-test/issues/39
 
## ESLint
 1. Unexpected console statement
 
 Fix: add `/* eslint-disable no-console */` di paling atas file
 
 2. 'require' is not defined
 
 Fix : add `/*eslint-env node*/` di paling atas file

## Istanbul 
1. basedir=$(dirname "$(echo "$0" | sed -e 's,\\,/,g')") SyntaxError: missing ) after argument list

 https://github.com/gotwarlost/istanbul/issues/677

## Homestead
 1. "No input file specified"
 
 http://stackoverflow.com/questions/24274387/using-laravel-homestead-no-input-file-specified
 
## JSHint
1. error : 'const' is available in ES6 (use esnext option) or Mozilla JS extensions (use moz).

 http://stackoverflow.com/questions/27441803/why-does-jshint-throw-a-warning-if-i-am-using-const

## Laravel
1. `Syntax error or access violation: 1071 Specified key was too long; max key length is 767 bytes`

 https://laravel-news.com/laravel-5-4-key-too-long-error
 
2. `Call to undefined method Tests\Feature\BookControllerTest::seeInDatabase()` in laravel 5.4
```php
  //change seeInDatabase()
  $this->seeInDatabase('books', ['title' => 'My Books!']);
  
  //to assertDatabaseHas()
  $this->assertDatabaseHas('books', ['title' => 'My Book!']);
```

## PHP
 1. A non-empty PSR-4 prefix must end with a namespace separator
 
 http://stackoverflow.com/questions/21463421/a-non-empty-psr-4-prefix-must-end-with-a-namespace-separator

## Node
1. Error when testing array with assert.equal(). use assert.deepEqual instead assert.equal()
 http://stackoverflow.com/questions/13225274/the-difference-between-assert-equal-and-assert-deepequal-in-javascript-testing-w

## NPM
1. No such file or directory after publish npm packages globally

 add `#!/usr/bin/env node` in first line 


## Lain-Lain

1. cURL error 60: SSL certificate: unable to get local issuer certificate

 http://stackoverflow.com/questions/29822686/curl-error-60-ssl-certificate-unable-to-get-local-issuer-certificate
