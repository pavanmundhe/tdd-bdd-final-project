# TDD / BDD Final Project

Product Catalog REST API and browser interface built from IBM's official Coursera final-project template. The project exercises test-driven development with model and API tests, and behavior-driven development with Behave and Selenium.

## Run in the Skills Network lab

1. Create your own repository from the IBM template named `tdd-bdd-final-project`.
2. In the lab terminal, clone your repository and enter its directory.
3. Run `bash bin/setup.sh`, then close and reopen the terminal so the virtual environment activates.
4. Start the application and database using the lab's supplied instructions.

## Project files

- `tests/factories.py`: generated product test data.
- `tests/test_models.py`: product model behavior tests.
- `tests/test_routes.py`: REST API tests.
- `service/routes.py`: product CRUD and search endpoints.
- `features/products.feature`: browser behavior scenarios.
- `features/steps/load_steps.py`: BDD background data setup.
- `features/steps/web_steps.py`: Selenium actions for the scenarios.

The REST API is rooted at `/products` and supports create, read, update, delete, list, and filtering by name, category, and availability.
