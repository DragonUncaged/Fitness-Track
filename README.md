# Fitness Tracker

This project is a web-based fitness tracker application that allows users to log their meals, workouts, and workout routines. It also provides analytics to view graphs for calorie intake and active time trends.

## Technologies Used
- Ruby: Version 3.2.2
- Rails: Version 7.0.8
- SQLite3: Used as the database for Active Record
- Installation
- To get started with the project, clone the repository and install the dependencies:

## Installation
To get started with the project, clone the repository and install the dependencies:

```
bundle install
```
## Database Setup
To set up the database, run the following commands:
```
rails db:create
rails db:migrate
rails db:seed
```

## Running Locally
To run the project locally, use the following command:
rails server

## Usage
- Sign up or log in to the application.
- Navigate to the Meals section to log your meals.
- Navigate to the Workouts section to log your workouts.
- Navigate to the Workout Routines section to log your workout routines.
- Navigate to the Analytics section to view graphs for calorie intake and active time trends.

## Features
- Meals: Log your daily meals with details like calories, date, and name.
- Workouts: Log your workouts with details like type, duration, and calories burned.
- Workout Routines: Create and manage your workout routines.
Analytics: View graphs for calorie intake and active time trends.

## Running Tests
To run the test suite, use the following command:
rails test

## Deployment
For deployment instructions, refer to the Deployment section.

## Services
- Job Queues: Managed by Active Job.
- Cache Servers: Configured in production.rb.
- Search Engines: Not applicable.

# Configuration
Configuration files are located in the config directory. Key files include:

- application.rb
- database.yml
- config/environments/*.rb

### System Dependencies
- Ruby 3.2.2
- Rails 7.0.8
- SQLite3