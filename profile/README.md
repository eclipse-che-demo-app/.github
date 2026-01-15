# Angular & Quarkus Demo with Eclipse Che / OpenShift Dev Spaces

[![Contribute](https://www.eclipse.org/che/contribute.svg)](https://devspaces.apps.region-03.clg.lab/#https://github.com/eclipse-che-demo-app/che-demo-app)

This Github organization contains a demo app that was created to demonstrate live coding in Eclipse Che & OpenShift Dev Spaces:

[OpenShift - Your New Favorite IDE](https://upstreamwithoutapaddle.com/blog%20post/2023/04/06/Development-On-OpenShift-With-Eclipse-Che.html)

There are three code repositories for the demo:

1. [https://github.com/eclipse-che-demo-app/che-demo-app](https://github.com/eclipse-che-demo-app/che-demo-app)

   This repository holds the OpenShift Dev Spaces aka (Eclipse Che) & VS Code configuration for the project

1. [https://github.com/eclipse-che-demo-app/che-demo-app-ui](https://github.com/eclipse-che-demo-app/che-demo-app-ui)

   This repository contains an Angular SPA that provides the user interface for the demo app.

1. [https://github.com/eclipse-che-demo-app/che-demo-app-service](https://github.com/eclipse-che-demo-app/che-demo-app-service)

   This repository contains a Quarkus applications that provides the backend for the demo.  It leverages a PostgreSQL database for persistence, and exposed a REST API that is consumed by the Angular application.
