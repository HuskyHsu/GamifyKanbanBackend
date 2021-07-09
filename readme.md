# Backend Template

##Project Description

---
## Requirement

- **Language**: TypeScript / nodeJS
- **FrameWork**: Express / Prisma
- **DataBase**: mySql/MariaDB
- **Lint**: eslint, AirBnb
- **Test**: jest
- **CI/CD**: Drone 
- 
---
## Development
```
// start databse

// start dev server
git clone git@
cd project
npm install
npm run dev // This will run lint first than dev
```

## Test
```
npm run test
```

## Build
```
npm run build
```
## How to run
```
docker build -t backend:1.0 .
docker-compose -f backend-dev-dockre-compose.yaml up
```