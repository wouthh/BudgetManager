# BudgetManager

> **Historical project**
>
> This Java desktop experiment is preserved as part of my development history. Its exchange-rate integration now requires local environment configuration.
>
> Provider availability and current compatibility have not been verified. Do not use production credentials with this project.

## Configuration

`.env.example` documents the required `BUDGET_MANAGER_EXCHANGE_RATE_BASE_URL` and `BUDGET_MANAGER_EXCHANGE_RATE_API_KEY` variables. Java does not load this file automatically; export both variables in the local environment before starting the application.

The base URL must use HTTPS and must not include credentials, a query, or a fragment. If the provider requires the API key as a query parameter, URLs containing it must never be logged.
