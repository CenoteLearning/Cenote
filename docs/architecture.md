# Architecture

You can find diagrams showing the architecture of the  different planned development phases here: 
* [MVP](docs/diagrams/development%20phases/MVP.md)
* [phase1](docs/diagrams/development%20phasesphase1.md)
* [phase2](docs/diagrams/development%20phasesphase2.md)

## Architectural Style Decision

The core functionally will be a monolith for the core Cenote service. 

## Component Breakdown

### Frontend

The frontend creates a comfortable user experience, which allow them to create and edit courses, and to generate data-insights from the insight service.

### Course Service

The course service integrates various external sources, which facilitates course creation, and course migration from other platforms.

### Insight Service

The insight service use external sources to generate student reports, and handle the their storage to a postgres database.


### Auth

The Auth service safely authenticate and give the correct authorizations to their users.