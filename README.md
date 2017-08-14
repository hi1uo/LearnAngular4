#### About
Introduction of Angular4 course project, including:
Angular CLI
Components
Services
Types
Directives
Events
ngIf
ngModel & Data Binding
Services & HTTP
Routing
NgModule

#### Angular Version History
- AngularJS/Angular1
- Angular2: Complete rewrite of AngularJS
- Angular3: Skipped
- Angular4: Backward compatible with Angular2

#### Components
Sections of UI can be broken up into encapsulated Components

#### Services
Classes that send data and functionality across Components
- keep Components lean
- DRY, don't repeat yourself
- Ideal place for Ajax calls

#### 2 main ways to install
- Angular CLI (recommended)
- Quickstart Seed
##### Dependencies
- Node.js & NPM

#### install
- Need npm (install)
- ```npm install -g @angular/cli```
- ```ng new [application name]```
- run application on a development server ```ng serve```
- 如何建一个components: create components folder and then ```ng g component components/user```

#### Deal with the backend data (demo with jsonplaceholder fake data):
- Inside the app folder, create a "services" folder
- In terminal type ```ng g service services/data```

#### Router
use router to use different URLs for different components
- generate another component: ```ng g component components/about```

##### References:
- [Angular 4 In 60 Minutes](https://youtu.be/KhzGSHNhnbI)
- [Angular 4 Front To Back](https://www.udemy.com/angular-4-front-to-back/?couponCode=DISCOUNT387487)
