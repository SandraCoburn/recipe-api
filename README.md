# recipe-api
Recipe API - Backend built using Test Driven Development (TDD)

## Tech Stack
- Python
- Django
  - Python web framework
  - Build web apps rapidly
  - Object relational mapper (ORM)
    - Convert objects to database rows
  - Django admin
    - Out-of-the-box admin site
    - Manage models
    - Visualize database
- django REST framework
  - Extension to Django
  - Built in authentication
  - Viewsets
  - Serializers
  - Browsable API
- Docker
  - Isolate project dependencies
  - Lightweight virtual machine
  - Single image
  - Consistent dev environment
  - Deploy to cloud platform
- Travis-CI
  - Automate testing and linting
  - Email notification if build breaks
  - Identify issues early
- PostgreSQL
  - Production grade database
  - Easy to setup with Docker
- DDT
  - UNIT TESTS
    - Checks that your code works
    - Isolate specific code
      - Functions
      - Class
      - API endpoints
  - TEST STAGES
    1. Setup -> Create sample database objects
    2. Execution -> Call the code
    3. Assertions -> Confirm expected output