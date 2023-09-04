# Time Trak

Time Trak is a todo and activity-time tracking website built using AngularJS, Redux, Axios, and moment.js. The platform used for hosting is Firebase, and it is styled using Material UI Bootstrap and Font Awesome. This repository contains the code for the project.

## Libraries

- AngularJS: This is the primary library used for building the web application. It is used for creating templates and data binding, as well as for communication with the backend using HTTP requests and Firebase.

- Redux: This is used for state management and enables consistency of data across components.

- Axios: This is an HTTP client used to communicate with the backend.

- moment.js: This is used for date-time parsing and calculations.

## Languages

- TypeScript: This is a superset of JavaScript that adds optional static typing, classes, and interfaces. It is used in this project for better scalability and maintainability.

- HTML: This is used for creating the structure of the website.

- CSS: This is used for styling the website.

## Platforms

- Firebase: This is used for hosting and to support the database for storing user-specific data.

## Frameworks

- Material UI: This is a styling framework for React, but it was used in this project to style the website.

- Bootstrap: This popular framework was used despite the Material UI for the handling of responsiveness, grid systems, etc.

- Font Awesome: This was used for adding icons to the website. 

## Books/Resources

- Angular Documentation: The official documentation for Angular.

- Material UI Documentation: The official documentation for Material UI.

- Bootstrap Documentation: The official documentation for Bootstrap.

- Stack Overflow: This was used to find solutions to issues or questions that arose during development.


The file structure of the project is as follows:

```
.
├── src/
│   ├── app/
│   │   ├── components/
│   │   ├── models/
│   │   ├── pages/
│   │   └── services/
│   └── index.html
│   └── index.ts
├── .gitignore
├── package.json
└── README.md
```

The `src` folder contains all the TypeScript code, including components, models, pages, and services. The `index.html` file is the main HTML file for the project. The `index.ts` file is where the AngularJS app is bootstrapped. 

The `.gitignore` file is included to prevent unnecessary files from being committed to the repository. 

The `package.json` file contains the dependencies and commands required for installing and running the application.

## Running the Application

1. Clone the repository:

```
git clone https://github.com/your-username/time-trak.git
```

2. Install dependencies using npm:

```
npm install
```

3. Build the application:

```
npm run build
```

4. Serve the application:

```
npm run serve
```

The application should now be accessible at http://localhost:4200.

## Contributing

Contributions to this project are welcome. If you notice a bug or have a suggestion for improvement, please feel free to submit an issue or a pull request.

## Credits

The project was developed by me [Uche-Okoro Jefferson] as part of a project in the [ALX Software Engineering Programme].
 
# TodoApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.6.

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
