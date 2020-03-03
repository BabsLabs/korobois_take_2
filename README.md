# Koroibos Take 2

## About
Koroibos is an application that returns data on olympic athletes and events from the 2016 olympics. This is my take 2... done the way I should have done it in the first place.

## Setup
1. Clone repo
1. Change into project directory
1. Install dependancies with `bundle install`
1. Create database `rails db:create`
1. Migrate `rails db:migrate"`
1. Migrate `rails db:migrate RAILS_ENV=test"`
1. Import CSV data to development database `rake import`
1. import CSV data to test database `rake import_test`

## Testing
Testing is done with Rspec

### Running all tests
All tests can be run with `rspec`

### Running an individual test
An individual test can be run with `rspec /PATH/TO/TEST`

## How to Use / Endpoints

### Versioning
This is the first version of this API. All endpoints are prepended with `/api/v1`

### Available Endpoints
#### Olympians
#### Youngest Olympian
#### Oldest Olympian
#### Olympian Stats
#### Events
#### Medalist by Event ID

## Known Issues
None so far!

## How to Contribute
Contact @babslabs on github

## Core Contributors
@babslabs

## Schema Design

## Tech Stack
- Ruby
- Rails
- Rspec
- Shoulda-matchers
- Pry

## Dependancies
- Ruby 2.4.1 or greater
- Rails 5.2.4.1 or greater