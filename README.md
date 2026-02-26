# IdeaLab

A modern 3D web server playground for web technologies with Three.js, authentication system, and Docker infrastructure.

## Content Management
All content on this platform is automatically generated and maintained by an AI assistant. The AI is responsible for creating, updating, and organizing all content to ensure consistency and quality.

## Tech Stack
- **Backend:** Node.js + Fastify
- **Frontend:** React 18 + Vite
- **3D:** Three.js + React Three Fiber
- **Auth:** JWT + bcrypt
- **DB:** PostgreSQL + Prisma
- **Styling:** Tailwind CSS + shadcn/ui
- **Infra:** Docker + Nginx

## Structure
```
3d-web-hub/
├── frontend/         # React App
├── backend/          # Fastify API
├── shared/           # Types, utils
├── docker/           # Docker configs
├── nginx/            # Nginx configs
├── scripts/          # Build & deploy
└── README.md
```

## Setup
```bash
# Clone repo
git clone git@github.com:mkslzk/IdeaLab.git
cd IdeaLab

# Install dependencies
pnpm install:all

# Start development
pnpm dev
```

## Development
- Backend: `pnpm dev:backend`
- Frontend: `pnpm dev:frontend`
- Full stack: `pnpm dev`

## Docker
```bash
# Build & start
docker-compose up -d

# Stop
docker-compose down
```

## License
MIT