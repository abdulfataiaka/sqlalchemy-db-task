## Database Modeling

Time Box: 1 Day

Here, you are ONLY expected to describe how you would model (Tables + Fields + Relationships) a database for an application named `Polyfiz`.

Polyfiz is an application you are to build to support independent music artists that has no relations with any record label yet but wishes to get their music on some of the different streaming platforms we have today, such as Youtube, Apple Music, Spotify, etc, and in addition do the following
- Earn and withdraw money based on the volume of people listening to their musics on these platforms
- Request for funds or loans to be able to push their career forward

This application will be used by the following users

`Artists`
- Should be able to upload songs to the different streaming platforms
- Should be able to see withdrawal history
- Should be able to request for funds or loans

`Admins`
- Should be able to get fund request notifications
- Should be able to either approve or disapprove fund requests
- Should be able to view artists information
- Should be able to activate or deactivate artists accounts

`SuperAdmin`
- Should be able to add/remove other admins

Resources
- https://app.diagrams.net/
- https://creately.com/blog/diagrams/uml-diagram-types-examples/#ClassDiagram

Advice
- Ensure to understand the solution first before starting to model

Output
- Create some UML diagrams as you see fit
- Commit and push the UML diagram to this repository
- Ensure to have an authentic and close to unique model solution

## Play Around with SQLAlchemy

Time Box: 1 Days

Define the database models using SQLAlchemy's directives for an application that manages authors and articles. This application will have ONLY the following models
- Article: Model for managing scholarly articles to be published by different authors on the application
  * Fields: id, author_id, title, pdf_link
- Author: Model for managing different authors on the application
  * Fields: id, username, password

Output
- Define the two models with relationship using SQLAlchemy ORM and Directives
- Write simple unit tests for the models that does data CRUD on a test database
- Ensure to configure Github Workflow to run your tests
- Use SQLite database with SQLAlchemy. But do not push the database file to the repository
- Ensure to set up this repository with whatever might be missing, such as `tests` with unit tests, `.github` with PR template, etc.

## Roundup Previous Work

Time Box: 1 Day

https://docs.google.com/document/d/1WT_rya4AArX3VUI9WKnYbsd0ckmR3pOo4FH_A4sjkic/edit?usp=sharing
- Complete section `Build a Django UI for web scraper` in project documentation linked above
- Create a Heroku account, install heroku CLI (Heroku Toolbelt) and host the UI application to Heroku
- Post the link to the heroku app below
