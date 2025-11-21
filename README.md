# Portfolio Blog

Full-stack portfolio and blog platform built with **Spring Boot 4** (backend) and **Angular 20** (frontend).

## Architecture

`
portfolio-blog/
  backend/    -> Spring Boot 4, Java 25, WebFlux, R2DBC, PostgreSQL
  frontend/   -> Angular 20, TypeScript 5.9, SSR, PWA
`

## Quick Start

`ash
# Clone with submodules
git clone --recurse-submodules git@github.com:vunter/portfolio-blog.git

# Run with Docker Compose
docker compose -f docker-compose.dev.yml up
`

## Tech Stack

| Layer     | Technology                                    |
|-----------|-----------------------------------------------|
| Backend   | Spring Boot 4, Java 25, WebFlux, R2DBC        |
| Frontend  | Angular 20, TypeScript 5.9, Angular Material   |
| Database  | PostgreSQL 17, Redis 7                         |
| Deploy    | Docker, Nginx, GitHub Actions                  |

## Repositories

- [Backend](https://github.com/vunter/portfolio-blog-backend) -- REST API, authentication, email, PDF generation
- [Frontend](https://github.com/vunter/portfolio-blog-frontend) -- SPA with SSR, admin panel, resume builder

## License

MIT
