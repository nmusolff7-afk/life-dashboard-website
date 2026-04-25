# Life Dashboard Website

This folder is the public marketing and legal website for `lifedashboardapp.com`.

It is intentionally separate from the Flask app so the deployment can be clean:

- `lifedashboardapp.com` -> this website service
- `www.lifedashboardapp.com` -> redirect to `lifedashboardapp.com`
- `api.lifedashboardapp.com` -> Flask backend

## Railway setup

Create a new Railway project from this repository.

Recommended Railway settings:

- Builder: `Dockerfile`
- Root directory: blank
- Start command: blank

Then attach:

- `lifedashboardapp.com`
- optional `www.lifedashboardapp.com`

Keep Microsoft 365 DNS records untouched. Only adjust website records for the root domain and `www`.
