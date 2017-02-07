<h1 align="center">Error List</h1>
===

## Angular 2
1. Shared Data from other component in services

 http://stackoverflow.com/questions/35273106/angular2-share-data-between-components-using-services
 
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

## NPM
1. No such file or directory after publish npm packages globally

 add `#!/usr/bin/env node` in first line 


