# Angular & Quarkus Demo with Eclipse Che / OpenShift Dev Spaces

This Github organization contains a demo app that was created to demonstrate live coding in Eclipse Che & OpenShift Dev Spaces.

There are three code repositories for the demo:

1. [https://github.com/eclipse-che-demo-app/che-demo-app](https://github.com/eclipse-che-demo-app/che-demo-app)

   This repository holds the Eclipse Che & VS Code configuration for the project

1. [https://github.com/eclipse-che-demo-app/che-demo-app-ui](https://github.com/eclipse-che-demo-app/che-demo-app-ui)

   This repository contains an Angular SPA that provides the user interface for the demo app.

1. [https://github.com/eclipse-che-demo-app/che-demo-app-service](https://github.com/eclipse-che-demo-app/che-demo-app-service)

   This repository contains a Quarkus applications that provides the backend for the demo.  It leverages a PostgreSQL database for persistence, and exposed a REST API that is consumed by the Angular application.
