---
title: Hasura
description: A Hasura instance with a PostgreSQL database
tags:
  - postgresql
  - hasura
---

# Hasura example

This example sets up a [Hasura](https://hasura.io/opensource/) instance with a [PostgreSQL](https://www.postgresql.org/) database.

## ✨ Features

- Postgres
- Hasura

## 💁‍♀️ How to use

- Set up a `HASURA_GRAPHQL_ADMIN_SECRET` to secure your endpoints and console.
- Visit your console after the deployment is complete

## 📝 Notes

- This starter automagically provisions a PostgreSQL database for you when you click the `Deploy on Railway`. The `DATABASE_URL` enviroment variable used in the `Dockerfile` is picked up from there.
- The Hasura console and dev mode are enabled by default for a better development experience. You may want to read the [production checklist](https://hasura.io/docs/latest/graphql/core/deployment/production-checklist.html) before going live with your app.
