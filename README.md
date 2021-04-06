# ad440-winter2021-tuesday-repo
NSC AD 440 Winter 2021 Tuesday cohort practicum repo

- Change to trigger action

## Description:
  This was a 12 week contract to build a simple task manager app and implement automation, cloud monitoring, and testing.
  
## Services Utilized:
  - Github projects
  - Github actions
  - Azure (functions, Database, Storage)
  - AWS (lamda functions)
  - Python
  - ReactJS
  - SQL
  - JavaScript
  
## My Contributions:
  - Built the api with python and hosted with azure functions
  - Implemented multi level Logging to api functions
  - Implemented Caching via Azure Redis cache
  - Setup SQL database/ connected to API

## To test api endpoints visit links: (Will be offline soon)
  - View all users: https://nsc-func-dev-usw2-tuesday.azurewebsites.net/api/users
  - View target user by ID: https://nsc-func-dev-usw2-tuesday.azurewebsites.net/api/users/1  *(1 is the desired ID)*
  - View target users tasks: https://nsc-func-dev-usw2-tuesday.azurewebsites.net/api/users/1/tasks
  - View details on specific task: https://nsc-func-dev-usw2-tuesday.azurewebsites.net/api/users/tasks/2  *(2 is the disired task ID)*

### Troubleshooting tips
- if the site initially hangs or fails refresh the site as the database is paused when not in use to reduce cost

