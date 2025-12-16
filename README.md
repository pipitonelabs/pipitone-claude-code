# Joe's Claude Code Setup

My personal Claude Code configuration for productive web development. This plugin provides **14 slash commands** and **159 specialized AI agents** to supercharge your development workflow. This is based on [edmund-io](https://github.com/edmund-io/edmunds-claude-code) and [0xfurai's](https://github.com/0xfurai/claude-code-subagents) repos.

## Quick Install

```bash
# Step 1: Add the marketplace
/plugin marketplace add pipitonelabs/pipitone-claude-code

# Step 2: Install the plugin
/plugin install pipitone-claude-code
```

## What's Inside

### 📋 Development Commands (7)

- `/new-task` - Analyze code for performance issues
- `/code-explain` - Generate detailed explanations
- `/code-optimize` - Performance optimization
- `/code-cleanup` - Refactoring and cleanup
- `/feature-plan` - Feature implementation planning
- `/lint` - Linting and fixes
- `/docs-generate` - Documentation generation

### 🔌 API Commands (3)

- `/api-new` - Create new API endpoints
- `/api-test` - Test API endpoints
- `/api-protect` - Add protection & validation

### 🎨 UI Commands (2)

- `/component-new` - Create React components
- `/page-new` - Create Next.js pages

### 💾 Supabase Commands (2)

- `/types-gen` - Generate TypeScript types
- `/edge-function-new` - Create Edge Functions

### 🤖 Specialized AI Agents (159)

**Core Architecture & Planning**
- **tech-stack-researcher** - Technology choice recommendations with trade-offs
- **system-architect** - Scalable system architecture design
- **backend-architect** - Backend systems with data integrity & security
- **frontend-architect** - Performant, accessible UI architecture
- **requirements-analyst** - Transform ideas into concrete specifications

**Code Quality & Performance**
- **refactoring-expert** - Systematic refactoring and clean code
- **performance-engineer** - Measurement-driven optimization
- **security-engineer** - Vulnerability identification and security standards
- **owasp-top10-expert** - OWASP Top 10 security vulnerabilities and mitigation

**Documentation & Research**
- **technical-writer** - Clear, comprehensive documentation
- **deep-research-agent** - Comprehensive research with adaptive strategies
- **learning-guide** - Teach programming concepts through progressive learning

**Communication & Prompting**
- **apply-thinking-to** - Enhance prompts using Anthropic's extended thinking patterns
- **create-readme-section** - Generate specific README sections with best practices
- **create-release-note** - Create customer-facing and technical release notes
- **batch-operations-prompt** - Optimize prompts for parallel file operations
- **convert-to-test-driven-prompt** - Transform requests into TDD-style prompts

**Development Tools**
- **cc-usage** - Analyze Claude Code usage costs and statistics
- **bash** - Shell scripting and automation

**Memory & Context Management**
- **memory-bank-synchronizer** - Align memory bank documentation with codebase state
- **cleanup-context** - Optimize memory bank files to reduce token waste
- **update-memory-bank** - Update CLAUDE.md and memory bank files

**Frontend Frameworks & Libraries**
- **react-expert** - React development with hooks, context, and modern patterns
- **vue-expert** - Vue.js with composition API and reactive patterns
- **angular-expert** - Angular with TypeScript, RxJS, and component architecture
- **angularjs-expert** - AngularJS (1.x) with best practices and migration guidance
- **svelte-expert** - Svelte and SvelteKit with reactive programming
- **solidjs-expert** - SolidJS with fine-grained reactivity and performance
- **nextjs-expert** - Next.js with SSR, SSG, and modern React patterns
- **astro-expert** - Astro framework for content-focused websites
- **remix-expert** - Remix with full-stack web fundamentals
- **nuxt-expert** - Nuxt.js for Vue.js applications
- **gatsby-expert** - Gatsby with React and GraphQL
- **sveltekit-expert** - SvelteKit with file-based routing
- **preact-expert** - Preact for lightweight React applications
- **lit-expert** - Web Components with Lit library
- **stencil-expert** - Stencil for building design systems
- **alpine-expert** - Alpine.js for lightweight interactions
- **ember-expert** - Ember.js with conventions and best practices
- **backbone-expert** - Backbone.js with models, views, and events
- **knockout-expert** - Knockout.js with observable patterns
- **mithril-expert** - Mithril.js for single-page applications
- **sura-expert** - Sura framework development
- **qwik-expert** - Qwik for instant-on applications
- **fresh-expert** - Fresh framework for Deno
- **htmx-expert** - HTMX for hypermedia-driven applications
- **hyperscript-expert** - HyperScript for interactive web pages

**Mobile Development**
- **flutter-expert** - Flutter for cross-platform mobile development
- **react-native-expert** - React Native with native modules and performance
- **expo-expert** - Expo for React Native development
- **ionic-expert** - Ionic for hybrid mobile applications
- **android-expert** - Native Android development with Kotlin/Java
- **ios-expert** - Native iOS development with Swift/Objective-C
- **swiftui-expert** - SwiftUI for modern iOS development
- **tauri-expert** - Tauri for desktop applications

**Frontend Technologies**
- **tailwind-expert** - Tailwind CSS with utility-first patterns
- **css-expert** - Advanced CSS with modern features and animations
- **html-expert** - Semantic HTML and accessibility best practices
- **javascript-expert** - Modern JavaScript (ES6+) and Node.js
- **typescript-expert** - TypeScript with advanced typing and patterns
- **electron-expert** - Electron for desktop applications
- **webcomponent-expert** - Web Components and Custom Elements

**Backend Frameworks**
- **express-expert** - Express.js with middleware and routing
- **fastify-expert** - Fastify for high-performance Node.js APIs
- **nestjs-expert** - NestJS with TypeScript and decorators
- **koa-expert** - Koa.js with async/await patterns
- **sails-expert** - Sails.js for real-time applications
- **hapi-expert** - Hapi.js for API development
- **loopback-expert** - LoopBack for API creation
- **adonisjs-expert** - AdonisJS for Node.js applications
- **strapi-expert** - Strapi headless CMS development
- **feathers-expert** - Feathers for real-time applications

**Python Frameworks**
- **django-expert** - Django with ORM, admin, and REST framework
- **flask-expert** - Flask with extensions and microservices
- **fastapi-expert** - FastAPI with automatic documentation
- **pyramid-expert** - Pyramid for flexible web applications
- **tornado-expert** - Tornado for asynchronous web frameworks
- **bottle-expert** - Bottle micro web framework
- **cherrypy-expert** - CherryPy object-oriented web framework
- **sanic-expert** - Sanic for async Python web servers
- **quart-expert** - Quart for async Python web development

**Java & JVM**
- **java-expert** - Core Java with modern features and patterns
- **spring-boot-expert** - Spring Boot with microservices and cloud-native
- **spring-expert** - Spring Framework with dependency injection
- **grails-expert** - Grails for rapid web development
- **play-expert** - Play Framework for reactive applications
- **quarkus-expert** - Quarkus for Kubernetes-native Java
- **micronaut-expert** - Micronaut for microservices
- **vertx-expert** - Vert.x for reactive applications
- **ktor-expert** - Ktor for Kotlin web applications

**.NET & C#**
- **aspnet-core-expert** - ASP.NET Core with modern web development
- **csharp-expert** - C# language and .NET ecosystem
- **dotnet-expert** - .NET platform and tooling
- **fsharp-expert** - F# functional programming on .NET

**Go & Rust**
- **go-expert** - Go with concurrency patterns and microservices
- **rust-expert** - Rust with ownership, borrowing, and performance
- **actix-expert** - Actix for high-performance Rust web services
- **gin-expert** - Gin web framework for Go
- **fiber-expert** - Fiber for Go web applications

**PHP Frameworks**
- **laravel-expert** - Laravel with Eloquent, Blade, and ecosystem
- **symfony-expert** - Symfony with components and bundles
- **codeigniter-expert** - CodeIgniter for rapid development
- **cakephp-expert** - CakePHP with conventions and rapid development
- **yii-expert** - Yii framework for modern applications
- **zend-expert** - Zend Framework (Laminas) for enterprise applications
- **phalcon-expert** - Phalcon high performance framework
- **slim-expert** - Slim for PHP microframework
- **php-expert** - Core PHP with modern practices

**Ruby & Elixir**
- **rails-expert** - Ruby on Rails with conventions and ecosystem
- **ruby-expert** - Ruby language and best practices
- **phoenix-expert** - Phoenix for Elixir web development
- **elixir-expert** - Elixir with OTP and functional programming
- **plug-expert** - Plug for Elixir web components

**Other Languages**
- **swift-expert** - Swift language and iOS/macOS development
- **kotlin-expert** - Kotlin for JVM, Android, and multiplatform
- **dart-expert** - Dart language and Flutter development
- **haskell-expert** - Haskell with functional programming concepts
- **ocaml-expert** - OCaml with type inference and functional programming
- **scala-expert** - Scala with functional and object-oriented patterns
- **clojure-expert** - Clojure with Lisp and functional programming
- **erlang-expert** - Erlang with concurrency and fault tolerance
- **perl-expert** - Perl for text processing and automation
- **lua-expert** - Lua for embedded scripting and gaming
- **r-expert** - R for statistical computing and data science
- **julia-expert** - Julia for high-performance numerical computing
- **nim-expert** - Nim language for systems programming
- **crystal-expert** - Crystal language with Ruby-like syntax
- **pony-expert** - Pony for systems programming
- **reason-expert** - ReasonML for type-safe applications
- **rebol-expert** - REBOL for symbolic computation
- **forth-expert** - Forth for low-level programming
- **factor-expert** - Factor concatenative programming language

**Databases - Relational**
- **postgres-expert** - PostgreSQL with advanced features and optimization
- **mysql-expert** - MySQL with replication and performance tuning
- **sqlite-expert** - SQLite for embedded and mobile applications
- **mariadb-expert** - MariaDB with high availability and performance
- **mssql-expert** - Microsoft SQL Server with T-SQL and optimization
- **oracle-expert** - Oracle Database with PL/SQL and enterprise features
- **sql-expert** - SQL fundamentals and advanced querying

**Databases - NoSQL & Distributed**
- **mongodb-expert** - MongoDB with document modeling and aggregation
- **redis-expert** - Redis with caching and data structures
- **cassandra-expert** - Apache Cassandra for distributed databases
- **dynamodb-expert** - AWS DynamoDB with serverless patterns
- **neo4j-expert** - Neo4j graph database and Cypher queries
- **cockroachdb-expert** - CockroachDB for distributed SQL
- **elasticsearch-expert** - Elasticsearch for search and analytics
- **opensearch-expert** - OpenSearch for search and observability
- **elk-expert** - ELK Stack (Elasticsearch, Logstash, Kibana)
- **couchdb-expert** - Apache CouchDB with replication
- **mongodb-atlas-expert** - MongoDB Atlas cloud database
- **couchbase-expert** - Couchbase with distributed features
- **arangodb-expert** - ArangoDB multi-model database
- **influxdb-expert** - InfluxDB for time series data
- **timescaledb-expert** - TimeScaleDB for time series on PostgreSQL

**Database Tools & ORMs**
- **prisma-expert** - Prisma ORM for type-safe database access
- **mongoose-expert** - Mongoose for MongoDB object modeling
- **sequelize-expert** - Sequelize ORM for Node.js
- **typeorm-expert** - TypeORM for TypeScript and Node.js
- **knex-expert** - Knex.js query builder for Node.js
- **sqlalchemy-expert** - SQLAlchemy for Python ORM
- **hibernate-expert** - Hibernate for Java ORM
- **entity-framework-expert** - Entity Framework for .NET
- **dapper-expert** - Dapper micro-ORM for .NET
- **flyway-expert** - Flyway for database migrations
- **liquibase-expert** - Liquibase for database change management

**Cloud & DevOps**
- **docker-expert** - Docker containerization and best practices
- **kubernetes-expert** - Kubernetes orchestration and deployment
- **terraform-expert** - Infrastructure as Code with Terraform
- **ansible-expert** - Ansible for configuration management
- **github-actions-expert** - GitHub Actions for CI/CD
- **gitlab-ci-expert** - GitLab CI/CD pipelines
- **circleci-expert** - CircleCI for continuous integration
- **jenkins-expert** - Jenkins for automation and CI/CD
- **aws-expert** - Amazon Web Services platform and services
- **azure-expert** - Microsoft Azure cloud services
- **gcp-expert** - Google Cloud Platform services
- **digitalocean-expert** - DigitalOcean cloud infrastructure
- **cloudflare-expert** - Cloudflare CDN and security services
- **vercel-expert** - Vercel for frontend deployment
- **netlify-expert** - Netlify for JAMstack deployment
- **heroku-expert** - Heroku for platform as a service
- **openshift-expert** - OpenShift container platform
- **consul-expert** - Consul for service discovery
- **nomad-expert** - Nomad for workload orchestration
- **vault-expert** - Vault for secrets management
- **prometheus-expert** - Prometheus monitoring and alerting
- **grafana-expert** - Grafana for metrics visualization
- **loki-expert** - Grafana Loki for log aggregation
- **opentelemetry-expert** - OpenTelemetry for observability
- **observability-expert** - Application observability and monitoring

**Testing Frameworks**
- **jest-expert** - Jest for JavaScript/TypeScript testing
- **mocha-expert** - Mocha testing framework for Node.js
- **jasmine-expert** - Jasmine for JavaScript testing
- **cypress-expert** - Cypress for end-to-end testing
- **playwright-expert** - Playwright for cross-browser testing
- **selenium-expert** - Selenium for browser automation
- **testcafe-expert** - TestCafe for web testing
- **puppeteer-expert** - Puppeteer for Chrome automation
- **vitest-expert** - Vitest for Vite-powered testing
- **ava-expert** - AVA test runner for Node.js
- **pytest-expert** - Pytest for Python testing
- **unittest-expert** - Python unittest framework
- **nose-expert** - Nose testing framework for Python
- **junit-expert** - JUnit for Java testing
- **testng-expert** - TestNG for Java testing
- **rspec-expert** - RSpec for Ruby testing
- **minitest-expert** - Minitest for Ruby testing
- **phpunit-expert** - PHPUnit for PHP testing
- **go-test-expert** - Go testing package and best practices
- **rust-test-expert** - Rust testing with cargo test
- **cpp-expert** - C++ with modern features and testing

**API & Web Technologies**
- **graphql-expert** - GraphQL schema design and Apollo
- **rest-expert** - REST API design and best practices
- **grpc-expert** - gRPC for high-performance APIs
- **websocket-expert** - WebSocket implementation and patterns
- **trpc-expert** - tRPC for end-to-end type safety
- **openapi-expert** - OpenAPI/Swagger documentation
- **http-expert** - HTTP protocols and best practices
- **webservice-expert** - Web services and SOAP

**Authentication & Security**
- **auth0-expert** - Auth0 authentication and authorization
- **oauth-oidc-expert** - OAuth 2.0 and OpenID Connect
- **jwt-expert** - JSON Web Tokens implementation
- **keycloak-expert** - Keycloak identity and access management
- **passport-expert** - Passport.js authentication middleware
- **bcrypt-expert** - Password hashing and security

**Message Queues & Streaming**
- **rabbitmq-expert** - RabbitMQ message broker
- **kafka-expert** - Apache Kafka for streaming
- **mqtt-expert** - MQTT for IoT messaging
- **nats-expert** - NATS for cloud-native messaging
- **bullmq-expert** - BullMQ for Redis-based job queues
- **celery-expert** - Celery for Python distributed tasks
- **sidekiq-expert** - Sidekiq for Ruby background jobs
- **resque-expert** - Resque for Ruby background jobs
- **bee-queue-expert** - Bee Queue for Node.js
- **agenda-expert** - Agenda for MongoDB-based job scheduling

**Payment & E-commerce**
- **stripe-expert** - Stripe payment processing integration
- **braintree-expert** - Braintree payment platform
- **paypal-expert** - PayPal payment integration
- **shopify-expert** - Shopify e-commerce platform
- **woocommerce-expert** - WooCommerce WordPress plugin

**Data Processing & Analytics**
- **pandas-expert** - Pandas for data manipulation in Python
- **numpy-expert** - NumPy for numerical computing
- **scipy-expert** - SciPy for scientific computing
- **scikit-learn-expert** - Scikit-learn for machine learning
- **tensorflow-expert** - TensorFlow deep learning framework
- **pytorch-expert** - PyTorch machine learning library
- **spark-expert** - Apache Spark for big data processing
- **hadoop-expert** - Hadoop ecosystem for distributed computing
- **airflow-expert** - Apache Airflow for workflow orchestration
- **kafka-streams-expert** - Kafka Streams for stream processing

**Search & Vector Databases**
- **vector-db-expert** - Vector databases for AI/ML applications
- **pinecone-expert** - Pinecone vector database
- **weaviate-expert** - Weaviate vector database
- **qdrant-expert** - Qdrant vector similarity search engine
- **chroma-expert** - Chroma open-source embedding database

**Development Tools**
- **webpack-expert** - Webpack module bundling
- **rollup-expert** - Rollup module bundler
- **vite-expert** - Vite build tool and dev server
- **esbuild-expert** - Esbuild JavaScript bundler
- **parcel-expert** - Parcel web application bundler
- **babel-expert** - Babel JavaScript compiler
- **typescript-expert** - TypeScript configuration and optimization
- **eslint-expert** - ESLint code linting
- **prettier-expert** - Prettier code formatting
- **husky-expert** - Husky Git hooks
- **lint-staged-expert** - Lint-staged for pre-commit hooks

**Infrastructure & Networking**
- **nginx-expert** - Nginx web server and reverse proxy
- **apache-expert** - Apache web server configuration
- **traefik-expert** - Traefik reverse proxy and load balancer
- **istio-expert** - Istio service mesh
- **envoy-expert** - Envoy proxy and load balancer
- **caddy-expert** - Caddy web server with automatic HTTPS

**Monitoring & Observability**
- **datadog-expert** - Datadog monitoring and analytics
- **newrelic-expert** - New Relic application monitoring
- **sentry-expert** - Sentry error tracking and performance monitoring
- **rollbar-expert** - Rollbar error tracking
- **airbrake-expert** - Airbrake error tracking service

## Installation

### From GitHub (Recommended)

```bash
# Add marketplace
/plugin marketplace add pipitonelabs/pipitone-claude-code

# Install plugin
/plugin install pipitone-claude-code
```

### From Local Clone (for development)

```bash
git clone https://github.com/pipitonelabs/pipitone-claude-code.git
cd edmunds-claude-code

# Add as local marketplace
/plugin marketplace add /path/to/pipitone-claude-code

# Install plugin
/plugin install pipitone-claude-code
```

## Best For

- Next.js developers
- TypeScript projects
- Supabase users
- React developers
- Full-stack engineers
- Any technology stack (we have experts for 100+ technologies!)

## Usage Examples

### Planning a Feature

```bash
/feature-plan
# Then describe your feature idea
```

### Creating an API

```bash
/api-new
# Claude will scaffold a complete API route with types, validation, and error handling
```

### Research Tech Choices

Just ask Claude questions like:
- "Should I use WebSockets or SSE?"
- "How should I structure this database?"
- "What's the best library for X?"

The tech-stack-researcher agent automatically activates and provides detailed, researched answers.

## Philosophy

This setup emphasizes:
- **Type Safety**: Never uses `any` types
- **Best Practices**: Follows modern Next.js/React patterns
- **Productivity**: Reduces repetitive scaffolding
- **Research**: AI-powered tech decisions with evidence
- **Comprehensive Coverage**: Expert knowledge for 100+ technologies

## Requirements

- Claude Code 2.0.13+
- Works with any project (optimized for Next.js + Supabase)

## Customization

After installation, you can customize any command by editing files in `.claude/commands/` and `.claude/agents/`.

## Contributing

Feel free to:
- Fork and customize for your needs
- Submit issues or suggestions
- Share your improvements

## License

MIT - Use freely in your projects

## Author

Created by Edmund

---

**Note**: This is my personal setup that I am currently testing with. Commands are optimized for Next.js + Supabase workflows but work great with any modern web stack. With 159 specialized agents, there's expert knowledge available for virtually any technology stack.
