# Production Elixir

##### by Donald Plummer

My preferred setup for a production Elixir application.

1. Project Setup
1. Logging
1. Continuous Integration
1. Docker image building
1. Environmental variable usage
1. Exception tracking
1. Metrics reporting
1. Health and status endpoints
1. Deployed cluster setup (Kubernetes)
1. Security

## Project Setup

When creating a new Elixir project, you can choose if you want an [Umbrella
app](https://elixir-lang.org/getting-started/mix-otp/dependencies-and-umbrella-projects.html#umbrella-projects)
or not.

## Metrics reporting

Prometheus.ex and /metrics

## Health and status endpoints

* /health
* /health/readiness

## Deployed cluster setup (Kubernetes)

libcluster

## Security

Require TLS

© 2018 Donald Plummer
