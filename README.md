# awesome-web-dev

| Framework | Stars                                                                                       | Language   | Native Auth | ORM   |
| --------- | ------------------------------------------------------------------------------------------- | ---------- | ------------ | ---- |
| Vue       | ![GitHub Repo stars](https://img.shields.io/github/stars/vuejs/vue)                         |    Node    | [X]() |
| Next.js   | ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/next.js)                    | Node       | [V](https://nextjs.org/docs/pages/building-your-application/authentication) | X() |
| Django    | ![GitHub Repo stars](https://img.shields.io/github/stars/django/django)                     | Python     | [V](https://docs.djangoproject.com/en/5.0/topics/auth/) | [V](https://docs.djangoproject.com/en/5.0/topics/db/queries/) |
| Larael    | ![GitHub Repo stars](https://img.shields.io/github/stars/laravel/laravel)                   | PHP        | [V](https://laravel.com/docs/10.x/authentication) | [V](https://laravel.com/docs/10.x/eloquent) |
| Gin       | ![GitHub Repo stars](https://img.shields.io/github/stars/gin-gonic/gin)                     | Go         | [?]() | [X]() |
| Spring Boot | ![GitHub Repo stars](https://img.shields.io/github/stars/spring-projects/spring-boot)     | Java       | [V](https://spring.io/projects/spring-security) | [JPA -> Hibernate]() |
| FastAPI   | ![GitHub Repo stars](https://img.shields.io/github/stars/tiangolo/fastapi)                  | Python     | [V](https://fastapi.tiangolo.com/tutorial/security/) | [X]() |
| Flask     | ![GitHub Repo stars](https://img.shields.io/github/stars/pallets/flask)                     | Python     | [Flask-login](https://github.com/maxcountryman/flask-login) | [SQLAlchemy](https://github.com/pallets-eco/flask-sqlalchemy/) |
| Express   | ![GitHub Repo stars](https://img.shields.io/github/stars/expressjs/express)                 | Node       | [X]() | [X]() |
| Nest      | ![GitHub Repo stars](https://img.shields.io/github/stars/nestjs/nest)                       |     Node   | [V](https://docs.nestjs.com/security/authentication) | [V](https://docs.nestjs.com/techniques/database) |
| Rails     | ![GitHub Repo stars](https://img.shields.io/github/stars/rails/rails)                       | Ruby       | [V](https://guides.rubyonrails.org/security.html) | [V](https://guides.rubyonrails.org/active_record_basics.html) |
| Nuxt      | ![GitHub Repo stars](https://img.shields.io/github/stars/nuxt/nuxt)                         |    Node    | [V](https://auth.nuxtjs.org/) | [X]() |
| Meteor    | ![GitHub Repo stars](https://img.shields.io/github/stars/meteor/meteor)                     |    Node    | [V](https://guide.meteor.com/accounts) |
| ASP.NET Core | ![GitHub Repo stars](https://img.shields.io/github/stars/dotnet/aspnetcore)              | C#         | [V](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/?view=aspnetcore-8.0) |
| Symfony   | ![GitHub Repo stars](https://img.shields.io/github/stars/symfony/symfony)                   | PHP        | [V](https://symfony.com/doc/current/security.html) |
| Pheonix   | ![GitHub Repo stars](https://img.shields.io/github/stars/phoenixframework/phoenix)          | Elexir     | [V](https://hexdocs.pm/phoenix/mix_phx_gen_auth.html) |
| Sails.js  | ![GitHub Repo stars](https://img.shields.io/github/stars/balderdashy/sails)                 | Node       | [V](https://sailsjs.com/documentation/concepts/policies/access-control-and-permissions) |
| Play      | ![GitHub Repo stars](https://img.shields.io/github/stars/playframework/playframework)       | Scala      | [V](https://www.playframework.com/documentation/2.1.0/JavaGuide4) |

# Leightweight FE

- Django + htmx,
- Rails + Hotwire
- Laravel + livewire
- Phoenix + liveview
- asp.net + htmx
- spring boot + htmx
- express or sailsjs + htmx

# Other

- Sails.js
- Meteor
- https://github.com/gin-gonic/gin

# ChatGPT Overview

Here's a list of some of the most popular web frameworks grouped by programming language:

### Python:
1. Django
2. Flask

### JavaScript (Node.js):
1. Express.js
2. NestJS
3. Fastify
4. Hapi.js
5. Koa.js

### Ruby:
1. Ruby on Rails
2. Sinatra

### PHP:
1. Laravel
2. Symfony
3. CodeIgniter

### Java:
1. Spring Boot
2. Play Framework
3. Vaadin

### Go:
1. Gin
2. Echo
3. Revel

### .NET (C#):
1. ASP.NET Core

### Elixir:
1. Phoenix Framework

### TypeScript:
1. NestJS

These frameworks are widely used in their respective languages and have strong communities and ecosystems supporting them.

# ChatGPT Suggestions

## Django

Certainly! One of the popular batteries-included web frameworks that meet your criteria is Django. Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design. It comes with built-in features for database management through its ORM (Object-Relational Mapping) system, authentication, URL routing, template engine, form handling, and more.

Here are some of the key features of Django:

1. **ORM**: Django comes with a powerful ORM that abstracts away the complexities of database management. It supports various databases including PostgreSQL, MySQL, SQLite, and Oracle.

2. **Authentication**: Django provides a built-in authentication system that includes user authentication, permissions, groups, and sessions.

3. **Admin Interface**: Django offers a customizable admin interface out of the box, which allows you to manage your application's data models via a web interface without much effort.

4. **URL Routing**: Django provides a clean and elegant way to define URL patterns and map them to views using its URL routing system.

5. **Template Engine**: Django includes a template engine that allows you to build dynamic HTML templates with ease, separating the presentation layer from the business logic.

6. **Security Features**: Django comes with built-in security features such as protection against common web vulnerabilities like SQL injection, CSRF (Cross-Site Request Forgery), and XSS (Cross-Site Scripting).

7. **Internationalization and Localization**: Django provides built-in support for internationalization (i18n) and localization (l10n), allowing you to develop applications that can be easily translated into multiple languages.

8. **REST Framework**: While not part of Django core, Django REST Framework is a powerful and flexible toolkit for building Web APIs. It integrates seamlessly with Django and provides tools for serialization, authentication, permissions, and more.

Overall, Django provides a comprehensive set of tools and features that make it well-suited for developing a wide range of web applications, from simple websites to complex web platforms.

## Rails

Certainly! Another popular batteries-included web framework that you might consider is Ruby on Rails. Ruby on Rails, often referred to as Rails, is a full-stack web application framework written in Ruby. Like Django, Rails follows the convention over configuration (CoC) and don't repeat yourself (DRY) principles, which promotes rapid development and maintainability.

Here are some key features of Ruby on Rails:

1. **ORM (Active Record)**: Rails comes with an ORM called Active Record, which simplifies database operations by abstracting database tables into Ruby objects. It supports multiple databases including MySQL, PostgreSQL, SQLite, and others.

2. **Authentication**: While Rails does not have built-in authentication like Django, there are many third-party gems (libraries) available that provide authentication solutions, such as Devise or Sorcery.

3. **Routing**: Rails provides a powerful routing system that maps URLs to controller actions, allowing for clean and RESTful design.

4. **Action View**: Rails includes Action View, a component for handling templates and rendering HTML responses. It uses ERB (Embedded Ruby) syntax for embedding Ruby code in HTML templates.

5. **Security Features**: Rails comes with built-in security features such as protection against SQL injection, cross-site scripting (XSS), cross-site request forgery (CSRF), and more.

6. **Scaffolding**: Rails provides scaffolding generators that can automatically generate boilerplate code for CRUD (Create, Read, Update, Delete) operations, speeding up development time.

7. **Asset Pipeline**: Rails includes an asset pipeline for managing and serving static assets such as JavaScript, CSS, and images. It can also minify and concatenate assets for improved performance.

8. **Testing Framework**: Rails comes with a built-in testing framework that supports unit testing, integration testing, and functional testing. It encourages test-driven development (TDD) and behavior-driven development (BDD) practices.

Ruby on Rails is widely used for building web applications of various scales, from small startups to large-scale enterprise systems. Its strong community support, extensive documentation, and vast ecosystem of gems make it a solid choice for web development projects.

## Laravel

Certainly! Another option for a batteries-included web framework is Laravel. Laravel is a PHP web framework known for its elegant syntax, developer-friendly features, and robust ecosystem. It follows the MVC (Model-View-Controller) architectural pattern and prioritizes developer productivity and code readability.

Here are some key features of Laravel:

1. **ORM (Eloquent)**: Laravel comes with an ORM called Eloquent, which provides a simple ActiveRecord implementation for working with databases. It supports various databases including MySQL, PostgreSQL, SQLite, and SQL Server.

2. **Authentication**: Laravel includes built-in authentication scaffolding that allows you to easily add user registration, login, logout, and password reset functionalities to your application.

3. **Routing**: Laravel provides a powerful routing system that allows you to define application routes using expressive and readable syntax. It supports RESTful routing out of the box.

4. **Blade Templating Engine**: Laravel includes a powerful templating engine called Blade, which provides features like template inheritance, control structures, and layout files to help you build dynamic and reusable views.

5. **Middleware**: Laravel middleware allows you to filter HTTP requests entering your application. It's a flexible mechanism for implementing cross-cutting concerns such as authentication, logging, and CSRF protection.

6. **Eloquent ORM**: Laravel's Eloquent ORM simplifies database interactions by providing a fluent query builder and easy-to-use ActiveRecord implementation. It supports relationships, eager loading, and other advanced features.

7. **Artisan CLI**: Laravel includes a command-line interface called Artisan, which provides a set of handy commands for common development tasks such as database migrations, seeding, testing, and more.

8. **Testing Support**: Laravel comes with built-in support for writing and running tests using PHPUnit. It also provides convenient testing helpers and methods for testing various aspects of your application.

Laravel's expressive syntax, rich feature set, and active community make it a popular choice for building web applications of all sizes, from small projects to large-scale enterprise applications. Its extensive documentation and vibrant ecosystem of packages (via Composer) further contribute to its appeal among developers.

## ASP.NET Core

Certainly! Another option for a batteries-included web framework is ASP.NET Core. ASP.NET Core is a cross-platform, open-source framework for building modern, cloud-based, and internet-connected applications. Developed by Microsoft, ASP.NET Core is built on top of the .NET Core runtime and offers a wide range of features for web development.

Here are some key features of ASP.NET Core:

1. **MVC Framework**: ASP.NET Core includes a powerful MVC (Model-View-Controller) framework for building web applications. It follows the MVC architectural pattern, which promotes separation of concerns and clean code organization.

2. **Entity Framework Core**: ASP.NET Core includes Entity Framework Core, an ORM (Object-Relational Mapping) framework that simplifies database access and management. It supports various database providers such as SQL Server, PostgreSQL, MySQL, SQLite, and more.

3. **Authentication and Authorization**: ASP.NET Core provides built-in support for authentication and authorization, including cookie-based authentication, JWT (JSON Web Tokens), OAuth, and OpenID Connect. It also offers role-based and policy-based authorization mechanisms.

4. **Routing**: ASP.NET Core includes a robust routing system that allows you to define URL patterns and map them to controller actions. It supports attribute routing, convention-based routing, and endpoint routing.

5. **Razor Pages**: In addition to MVC, ASP.NET Core introduces Razor Pages, a lightweight alternative for building web pages with minimal ceremony. Razor Pages allow developers to create page-focused scenarios without the need for controllers.

6. **Dependency Injection**: ASP.NET Core includes a built-in dependency injection (DI) container, which promotes loose coupling and facilitates testability by allowing you to inject dependencies into your classes.

7. **Middleware Pipeline**: ASP.NET Core uses a middleware pipeline to handle HTTP requests and responses. Middleware components can be added to the pipeline to perform various tasks such as logging, error handling, authentication, and more.

8. **Cross-platform Support**: ASP.NET Core is designed to be cross-platform, meaning you can develop and run ASP.NET Core applications on Windows, macOS, and Linux environments.

ASP.NET Core's flexibility, performance, and integration with other Microsoft technologies make it a compelling choice for building web applications, APIs, and microservices. Its extensive documentation, tooling support, and community ecosystem further enhance its appeal for developers.

## Express

Certainly! Another option for a batteries-included web framework is Express.js. Express.js is a minimalist web application framework for Node.js, which is known for its simplicity, flexibility, and extensibility. Although it's not as fully featured out of the box as some of the other options mentioned, it offers a robust foundation for building web applications and provides numerous middleware and plugins to extend its functionality.

Here are some key features of Express.js:

1. **Middleware**: Express.js is built around the concept of middleware, which are functions that have access to the request and response objects in the application's HTTP request-response cycle. Middleware can be used for tasks such as logging, authentication, error handling, and more.

2. **Routing**: Express.js provides a simple and intuitive routing mechanism that allows you to define routes for different HTTP methods and URL patterns. It supports parameters, query strings, route handlers, and route chaining.

3. **Template Engines**: Although not included by default, Express.js can easily integrate with various template engines such as Pug (formerly Jade), EJS, Handlebars, and more, allowing you to dynamically generate HTML content.

4. **Static File Serving**: Express.js includes middleware for serving static files such as CSS, JavaScript, images, and other resources. This makes it easy to serve static content from a designated directory in your application.

5. **Error Handling**: Express.js provides middleware for handling errors in your application. You can define error-handling middleware functions that are invoked whenever an error occurs during the request-response cycle.

6. **Authentication and Authorization**: While Express.js does not include built-in authentication and authorization mechanisms, there are many third-party middleware and plugins available (such as Passport.js) that provide authentication strategies for various providers (e.g., local, OAuth, JWT).

7. **Database Integration**: Express.js can integrate with various databases through Node.js database drivers or ORMs (Object-Relational Mappers) such as Sequelize or Mongoose, allowing you to interact with databases like MySQL, MongoDB, PostgreSQL, and others.

8. **Community and Ecosystem**: Express.js has a large and active community, with a vast ecosystem of middleware, plugins, and extensions available via npm (Node.js package manager). This allows you to easily extend Express.js to meet the specific requirements of your project.

Express.js is well-suited for building lightweight, high-performance web applications and APIs. Its minimalist design and extensive ecosystem make it a popular choice among Node.js developers for a wide range of projects, from small prototypes to large-scale applications.

## Flask

Certainly! Another option for a batteries-included web framework is Flask. Flask is a lightweight and flexible web framework for Python, known for its simplicity, ease of use, and extensibility. While Flask is not as fully featured out of the box as some other frameworks, it provides a solid foundation for building web applications and offers a wide range of extensions to add additional functionality as needed.

Here are some key features of Flask:

1. **Routing**: Flask provides a simple and intuitive routing mechanism that allows you to define URL routes and map them to view functions. Routes can support dynamic URL parameters and HTTP methods.

2. **Template Rendering**: Flask includes a built-in templating engine called Jinja2, which allows you to generate dynamic HTML content by combining static templates with dynamic data.

3. **HTTP Request Handling**: Flask provides request and response objects that encapsulate HTTP requests and responses, making it easy to access request data and generate responses within your application.

4. **Middleware**: While Flask itself does not have a built-in middleware system like some other frameworks, you can easily add middleware functionality using Flask's extension ecosystem. There are many third-party extensions available for common middleware tasks such as authentication, session management, CSRF protection, and more.

5. **Extensions**: Flask has a rich ecosystem of extensions that provide additional functionality for common tasks such as form validation, database integration, authentication, API development, and more. These extensions allow you to add features to your Flask application without reinventing the wheel.

6. **Database Integration**: Flask can integrate with various databases through third-party extensions such as Flask-SQLAlchemy, Flask-MongoEngine, Flask-PyMongo, and others. These extensions provide ORM (Object-Relational Mapping) or ODM (Object-Document Mapping) functionality for interacting with relational databases like MySQL, PostgreSQL, SQLite, and non-relational databases like MongoDB.

7. **Development Server**: Flask includes a built-in development server that makes it easy to run and test your application locally during development. The development server supports automatic reloading of code changes, making the development process more efficient.

8. **Community and Documentation**: Flask has a vibrant community and extensive documentation, making it easy to find help, tutorials, and resources for learning Flask and building web applications with it.

Flask is well-suited for building small to medium-sized web applications, APIs, and prototypes. Its simplicity and flexibility make it a popular choice among Python developers who value ease of use and minimalism.

## Spring Boot

Certainly! Another option for a batteries-included web framework is Spring Boot. Spring Boot is a popular Java-based framework for building enterprise-grade web applications with minimal setup and configuration. It is built on top of the Spring Framework and provides a powerful platform for developing robust and scalable web applications.

Here are some key features of Spring Boot:

1. **Auto-Configuration**: Spring Boot uses convention over configuration principles to automatically configure your application based on sensible defaults. This reduces boilerplate code and configuration, allowing you to focus on writing business logic.

2. **Embedded Web Server**: Spring Boot includes an embedded web server (Tomcat, Jetty, or Undertow) which allows you to run your application as a standalone JAR file without needing to deploy it to a separate application server.

3. **Dependency Management**: Spring Boot simplifies dependency management by providing a curated list of dependencies through starter packages. Starter packages are opinionated sets of dependencies for common use cases such as web applications, data access, security, and more.

4. **Spring MVC**: Spring Boot includes support for Spring MVC, a powerful model-view-controller framework for building web applications. Spring MVC provides features such as request mapping, data binding, validation, and error handling.

5. **Spring Data**: Spring Boot integrates with Spring Data, which provides a consistent and unified API for accessing various data stores such as relational databases (JPA, JDBC), NoSQL databases (MongoDB, Redis), and more.

6. **Spring Security**: Spring Boot includes integration with Spring Security, a powerful authentication and authorization framework for securing your application. Spring Security provides features such as authentication providers, access control, CSRF protection, and more.

7. **Actuator**: Spring Boot Actuator provides built-in production-ready features for monitoring and managing your application in production. It includes endpoints for health checks, metrics, environment information, and more.

8. **DevTools**: Spring Boot DevTools provides development-time features such as automatic restarts, live reloading, and enhanced debugging to improve developer productivity.

Spring Boot's comprehensive feature set, strong ecosystem, and wide adoption in the enterprise make it a popular choice for building robust and scalable web applications in Java. Its focus on convention over configuration and developer productivity make it well-suited for both small and large projects.

## Symfony

Certainly! Another option for a batteries-included web framework is Symfony. Symfony is a PHP framework known for its stability, flexibility, and extensive set of reusable components. It follows the Model-View-Controller (MVC) architectural pattern and provides a wide range of features for building web applications, APIs, and microservices.

Here are some key features of Symfony:

1. **Symfony Components**: Symfony is built on top of a set of reusable and decoupled components that can be used independently in any PHP project. These components cover various aspects of web development, including HTTP handling, routing, templating, forms, security, authentication, and more.

2. **MVC Architecture**: Symfony follows the MVC architectural pattern, which separates the application's logic, presentation, and data layers. This promotes code organization, maintainability, and scalability.

3. **Twig Templating Engine**: Symfony uses Twig as its default templating engine, which provides a clean, concise, and secure syntax for generating HTML content. Twig templates support template inheritance, control structures, filters, and more.

4. **Doctrine ORM**: Symfony integrates with Doctrine, a powerful object-relational mapping (ORM) framework for working with databases. Doctrine allows developers to define database models as plain PHP objects (Entities) and perform database operations using a fluent query builder or Doctrine's query language (DQL).

5. **Routing**: Symfony provides a flexible routing system that allows developers to define URL routes using YAML, XML, PHP annotations, or a combination of these methods. Routes can be mapped to controller actions or PHP callables, enabling clean and expressive routing configurations.

6. **Form Component**: Symfony includes a form component that simplifies the process of creating and processing HTML forms. The form component provides features such as form rendering, data transformation, validation, CSRF protection, and error handling.

7. **Security Component**: Symfony includes a security component that provides authentication, authorization, and other security-related features out of the box. It supports various authentication methods, including HTTP basic/digest authentication, form-based authentication, JWT (JSON Web Tokens), and OAuth.

8. **Console Component**: Symfony includes a console component that allows developers to create command-line applications and utilities using a familiar syntax. The console component provides features such as command registration, input/output handling, argument parsing, and command chaining.

Symfony's modular architecture, comprehensive documentation, and active community make it a popular choice for building web applications of all sizes. Its flexibility and extensibility make it suitable for a wide range of use cases, from small personal projects to large-scale enterprise applications.

## Phoenix

Certainly! Another option for a batteries-included web framework is Phoenix. Phoenix is a web framework written in Elixir, a functional programming language built on top of the Erlang VM. Phoenix is known for its high performance, concurrency model, and productivity features, making it suitable for building scalable and fault-tolerant web applications.

Here are some key features of Phoenix:

1. **Elixir and Erlang**: Phoenix leverages the power of Elixir and Erlang to provide high concurrency, fault tolerance, and scalability. Elixir's functional programming paradigm and Erlang's actor-based concurrency model make Phoenix well-suited for building real-time web applications and distributed systems.

2. **MVC Architecture**: Phoenix follows the Model-View-Controller (MVC) architectural pattern, which separates the application's logic, presentation, and data layers. This promotes code organization, modularity, and maintainability.

3. **Channels**: Phoenix includes channels, which are a real-time communication mechanism that allows bidirectional communication between clients and servers. Channels enable features such as live updates, chat applications, multiplayer gaming, and more.

4. **Ecto ORM**: Phoenix integrates with Ecto, a domain-specific language (DSL) and database wrapper for Elixir. Ecto provides a powerful query interface, data validation, schema migrations, and other database-related features.

5. **Routing**: Phoenix provides a clean and flexible routing system that allows developers to define URL routes using a simple and expressive syntax. Routes can be mapped to controller actions or Phoenix channels, enabling clean and RESTful routing configurations.

6. **Templates**: Phoenix uses EEx (Embedded Elixir) templates for generating HTML content. EEx templates allow developers to embed Elixir code directly into HTML files, providing a familiar and concise syntax for dynamic content generation.

7. **Plug Middleware**: Phoenix uses plugs, which are composable modules that can be inserted into the request-response pipeline. Plugs allow developers to perform common tasks such as authentication, authorization, parameter parsing, and error handling in a modular and reusable way.

8. **Testing Support**: Phoenix includes built-in support for testing, including unit tests, integration tests, and end-to-end tests. Phoenix's testing framework provides utilities for mocking requests, asserting responses, and testing controller and channel logic.

Phoenix's performance, scalability, and fault tolerance make it a compelling choice for building modern web applications, especially those requiring real-time features and high concurrency. Its clean architecture, productive tooling, and growing ecosystem make it a popular framework within the Elixir community.

## FastAPI

Certainly! Another option for a batteries-included web framework is FastAPI. 

FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints. It is built on top of Starlette for the web parts and Pydantic for the data parts.

Here are some key features of FastAPI:

1. **High Performance**: FastAPI is built using Starlette, a high-performance ASGI (Asynchronous Server Gateway Interface) framework, which allows it to handle high loads and perform well in production environments.

2. **Automatic API Documentation**: FastAPI automatically generates interactive API documentation (using Swagger UI or ReDoc) based on your code's type hints, making it easy to understand and test your API endpoints.

3. **Built-in Validation**: FastAPI integrates with Pydantic, a powerful data validation library, to automatically validate request data against predefined models or schemas. This ensures that your API endpoints receive valid input data and reduces the need for manual validation code.

4. **Async Support**: FastAPI fully supports asynchronous programming using Python's async/await syntax. This allows you to write asynchronous code to handle I/O-bound operations efficiently, improving overall performance and scalability.

5. **Dependency Injection**: FastAPI supports dependency injection, allowing you to declare dependencies for your API endpoints and have them automatically injected by the framework. This promotes modularity, testability, and code reuse.

6. **Security Features**: FastAPI provides built-in support for common security features such as authentication, authorization, and CSRF (Cross-Site Request Forgery) protection. It also supports integration with third-party authentication providers and middleware for additional security measures.

7. **Simplified Routing**: FastAPI uses a simple and intuitive routing system based on standard Python decorators, making it easy to define API endpoints and their corresponding request handlers.

8. **Compatibility with Existing Python Ecosystem**: FastAPI is compatible with the existing Python ecosystem and libraries, allowing you to leverage existing tools and packages to extend its functionality and integrate with other systems.

FastAPI's combination of performance, simplicity, and modern features makes it an excellent choice for building fast and scalable APIs with Python. Whether you're building a small microservice or a large-scale API backend, FastAPI provides the tools and features you need to get the job done efficiently.

