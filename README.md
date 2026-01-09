# ValoStrats

Full-stack Valorant strategy management platform. Users organize into Groups, create/share game strategies with JWT authentication.

## Tech Stack

### Backend
- **Framework:** NestJS 11
- **Language:** TypeScript
- **Database:** PostgreSQL 13
- **ORM:** Prisma
- **Authentication:** JWT (Dual-token architecture with Argon2 hashing)

### Frontend
- **Framework:** Next.js 15
- **Language:** TypeScript
- **UI Library:** HeroUI v2
- **Styling:** Tailwind CSS 4

### Infrastructure
- **Containerization:** Docker
- **Orchestration:** Docker Compose

## Getting Started

To start the project with all services (Backend, Frontend, and Database):

`ash
docker compose up --build
`

## Repository Structure

- \ackend/\: NestJS API
- \Frontend/\: Next.js app
- \docker-compose.yml\: Service orchestration
