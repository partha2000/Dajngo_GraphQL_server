# Dajngo_GraphQL_server

This is my practice project to learn graphene

## Project Desciption:

A simple tech blog post.

Not yet decided! 😁

### Technologies used:

- Backend : Django
- API query language : GraphQL (Graphene) _Graphene is a python library that makes it easier to add graphql api_

### Targeted Features:

[ ] List of users and links
[ ] Users creation and authentication
[ ] Users can create links and vote on them

Not yet decided! '😒

### TIPS

- Always start the development in a venv

### Getting atarted

- install django and graphene: `pip install django==2.1.4 graphene-django==2.2.0 django-filter==2.0.0 django-graphql-jwt==0.1.5`
- inside the <project>/settings.py add this
  `INSTALLED_APPS = ( # After the default packages 'graphene_django', )`
- Add this at the bottom of the settings.py file:
  `GRAPHENE = { 'SCHEMA': '<project_name>.schema.schema', }`
