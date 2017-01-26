# Error-log-list

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b2a17092851a4ef8bd0bca07c031c0c0)](https://www.codacy.com/app/muhtarudinOrganization/error-log-list?utm_source=github.com&utm_medium=referral&utm_content=muhtarudinsiregar/error-log-list&utm_campaign=badger)

======

## Angular 2
1. Shared Data from other component in services

 [http://stackoverflow.com/questions/35273106/angular2-share-data-between-components-using-services](http://stackoverflow.com/questions/35273106/angular2-share-data-between-components-using-services)
 
## ESLint
 1. Unexpected console statement
 
 Fix: add `/* eslint-disable no-console */` di paling atas file
 
 2. 'require' is not defined
 
 Fix : add `/*eslint-env node*/` di paling atas file

## Istanbul 
1. basedir=$(dirname "$(echo "$0" | sed -e 's,\\,/,g')") SyntaxError: missing ) after argument list

 https://github.com/gotwarlost/istanbul/issues/677
 
## JSHint
1. error : 'const' is available in ES6 (use esnext option) or Mozilla JS extensions (use moz).

 `http://stackoverflow.com/questions/27441803/why-does-jshint-throw-a-warning-if-i-am-using-const`

## NPM
1. No such file or directory after publish npm packages globally

 add `#!/usr/bin/env node` in first line 


