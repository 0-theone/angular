# AngularTestApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

# angularino
Test app - angular at version 15

- Angular is an application design framework and development platform for creating efficient and sophisticated single-page apps.
- Angular is a platform and framework for building single-page client applications using HTML and TypeScript. Angular is written in TypeScript. It implements core and optional functionality as a set of TypeScript libraries that you import into your applications.
- The basic building blocks of the Angular framework are Angular components that are organized into NgModules.
- An Angular application is defined by a set of NgModules
- An application always has at least a root module that enables bootstrapping, and typically has many more feature modules.

## Components
- Components define views, which are sets of screen elements that Angular can choose among and modify according to your program logic and data.
- Components use services, which provide specific functionality not directly related to views. Service providers can be injected into components as dependencies, making your code modular, reusable, and efficient.
- The @Component() decorator identifies the class immediately below it as a component, and provides the template and related component-specific metadata.
- A component consists of three things:
   - A component class that handles data and functionality.
   - An HTML template that determines the UI.
   - Component-specific styles that define the look and feel.

## Modules
- Angular NgModules differ from and complement JavaScript (ES2015) modules. An NgModule declares a compilation context for a set of components that is dedicated to an application domain, a workflow, or a closely related set of capabilities.
- An NgModule can associate its components with related code, such as services, to form functional units.
- Every Angular application has a root module, conventionally named AppModule, which provides the bootstrap mechanism that launches the application. An application typically contains many functional modules.

**Modules, components and services are classes that use decorators. These decorators mark their type and provide metadata that tells Angular how to use them.**

**Decorators are functions that modify JavaScript classes. Angular defines a number of decorators that attach specific kinds of metadata to classes, so that the system knows what those classes mean and how they should work.**

## Templates, directives, and data binding
-  A template combines HTML with Angular markup that can modify HTML elements before they are displayed.
-  Template directives provide program logic, and binding markup connects your application data and the DOM.
-  There are two types of data binding:
   - Event binding lets your application respond to user input in the target environment by updating your application data.
   - Property binding lets youn interpolate values that are computed from your application data into the HTML.

**Before a view is displayed, Angular evaluates the directives and resolves the binding syntax in the template to modify the HTML elements and the DOM, according to your program data and logic. Angular supports two-way data binding, meaning that changes in the DOM, such as user choices, are also reflected in your program data.**

## Services and dependency injection
- For data or logic that isn't associated with a specific view, and that you want to share across components, you create a service class. A service class definition is immediately preceded by the @Injectable() decorator. The decorator provides the metadata that allows other providers to be injected as dependencies into your class.

**Dependency injection (DI) lets you keep your component classes lean and efficient. They don't fetch data from the server, validate user input, or log directly to the console; they delegate such tasks to services.**

## Routing
- The Angular Router NgModule provides a service that lets you define a navigation path among the different application states and view hierarchies in your application. It is modeled on the familiar browser navigation conventions:
   - Enter a URL in the address bar and the browser navigates to a corresponding page.
   - Click links on the page and the browser navigates to a new page.
   - Click the browser's back and forward buttons and the browser navigates backward and forward through the history of pages you've seen.
   
![angular](https://angular.io/generated/images/guide/architecture/overview2.png)

