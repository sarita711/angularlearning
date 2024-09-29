

# Angular Course Summary

## Lecture 1: Introduction to Angular
- **What is Angular?**
  - Angular is a web framework that enables teams to confidently build web applications.

- **Angular Team Core Values:**
  1. Apps developers love to build.
  2. Apps users love to use.

- **Why Choose Angular?**
  - **Tooling and Productivity**: Integrated tools that enhance development efficiency.
  - **Batteries Included**: Comes with a rich set of features out of the box.
  - **Evergreen**: Regular updates and improvements keep it up to date.
  - **TypeScript**: Angular uses TypeScript as its primary programming language, providing type safety and advanced features.

## Lecture 2: Installation and Setup
- **Requirements:**
  - **Node.js**: Use the Active LTS or Maintenance LTS version.
  - **npm**: Included with Node.js.

- **Development Convenience**:
  - Use `ng serve` for automatic refresh during development.

## Lecture 3: Understanding Components
- **TypeScript Component Class**:
  - Serves as a place to build application logic.
  - Includes an HTML template that defines the user interface.
  - Can incorporate CSS styles within the component.

## Lecture 4: Custom Components and Directives
- **Passing Data Between Components**:
  - Use the `@Input` decorator to pass data to child components.

## Lecture 5: Routing
- **Navigating with Angular Router**:
  1. Navigate within the application using the Angular Router and the `routerLink` directive.
  2. Pass information using parameterized routes.
  3. Retrieve route parameters in components with `ActivatedRoute`.

- **Standalone Components**: Understanding how they operate independently.

### Services and Dependency Injection
- **Dependency Injection**:
  - A design pattern that allows for better separation of concerns.

- **Benefits**:
  - Testable code.
  - Reusable code.
  - Maintainable code.

## Lecture 6: Creating Services
- **Learning Outcomes**:
  1. How to create a Service.
  2. Utilizing Dependency Injection in components.

## Lecture 7: Forms in Angular
- **Working with Forms**:
  - Bind a `FormGroup` to an HTML form using templates.
  - Use event binding to handle user interactions.

## Lecture 8: HTTP Requests
- **Making HTTP Requests**:
  - Install and use `json-server` for mock API endpoints.
  - Use `fetch` to make HTTP requests to live endpoints with `json-server`.
  - Refactor the housing service to utilize promises and async/await for asynchronous operations.

---
