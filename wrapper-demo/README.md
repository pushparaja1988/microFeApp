# WrapperDemo

## Install dependencies to individual projects

header/
footer/

Run `npm ci` 

## angular custom element dependencies

ng add @angular/elements 
ng add ngx-build-plus

## -install the http-server module

Run `npm i -g http-server --save`

## Build individual projects

header/
footer/

Run `ng build --prod --output-hashing none --single-bundle true`

## Running individual projects

header/
footer/

Run `http-server dist/header/ -p 3000` 
Run `http-server dist/footer/ -p 3001`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:1388/`. The app will automatically reload if you change any of the source files.
