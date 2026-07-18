# CLAUDE.md

## Overview

Fork of upstream github.com/wmnnd/nginx-certbot (remote is github.com/andrius/nginx-certbot) - boilerplate for running nginx as a reverse proxy with automatic Let's Encrypt certificates via Certbot on docker-compose.

## Stack

Docker Compose (`docker-compose.yml`) with `nginx/` and `certbot/` configs. `init-letsencrypt.sh` bootstraps and renews certs for one or more domains. Config via `.env` (from `.env-sample`). MIT licensed.

Last commit: 2021-01-16.
