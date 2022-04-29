# Efoye - Happy baby, Happy Family

ReacJS web UI for SNS eCommerce.  

## Installation

System requirements:

- [node v14](https://nodejs.org/download/release/v14.18.3/)


From the Efoye directory run:

```bash
npm install
```

## Run

```bash
npm run dev
```

## Developing Standards



- /src directory

  The bulk of the development should be in this directory.  Each component or module should have its own top level directory here.  The directory structure under each component/module should be:

  ```text
  src    
      SomeModule
      components (react components)
      lib (common classes, libraries, utilities for the module)
      state (if a state object is required)
  ```

- DB access

## Database Schema Updates

  ```text
  Database is used  pass which is firebase 
  ```


## Branch Structure

The production branch is the "main" branch.  Only pull requests from master will be allowed to change the main branch.

Developers should create branches for each feature/bug.  Once the unit of work it complete, create a pull request into master.  Squash merge the pull requests into master.

## CI/CD

Any commit into master or main branch with kick off a "GitHub Action" to deploy to Firebase.  The actions will:


1. Deploy to Firebase.  Check the action log to view the deployed site.
