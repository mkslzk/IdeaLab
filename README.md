# IdeaLab

Ein moderner 3D-Webserver als Spielwiese für Webtechnologien mit Three.js, Auth-System und Docker-Infrastruktur.

## Tech-Stack
- **Backend:** Node.js + Fastify
- **Frontend:** React 18 + Vite
- **3D:** Three.js + React Three Fiber
- **Auth:** JWT + bcrypt
- **DB:** PostgreSQL + Prisma
- **Styling:** Tailwind CSS + shadcn/ui
- **Infra:** Docker + Nginx

## Struktur
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