# Health Tracker
The main purpose of this app is to be a playground to work with activities' data and make it available in some data visualization tool.  
It will have three main modules:
1. Backend: Mainly build in Java
2. Dataviz: Data visualization tool's configs. Probably Grafana.
3. Database: DB's configs, tables and query definitions. Probably MySQL.

## Decisions
- As Garmin has a very straight API policy, only allowing enterprise registered users to connect directly into their endpoints, we are going to use Strava's API ecosystem to gather data (which has a free tier and friendly documentation).

## Learnings through the process
- Swagger Codegen: Tool that generates stubs and client SDKs for any API, based on a JSON specification.

## Open questions
- x