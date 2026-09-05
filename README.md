# Bloggy Infrastructure

Docker infrastructure for the Bloggy application.

## Requirements

* Docker Desktop

## Start

From the root of this repository, run:

```bash
docker compose up -d
```

Keycloak will be available at:

```text
http://localhost:8080
```

The `bloggy` realm and `angular-client` configuration are automatically imported from:

```text
keycloak/bloggy-realm.json
```

## Stop

```bash
docker compose down
```

## Structure

```text
Bloggy-Infrastructure/
├── keycloak/
│   └── bloggy-realm.json
├── docker-compose.yml
└── README.md
```
