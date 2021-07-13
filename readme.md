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
docker-compose -f docker/backend-dev-docker-compose.yaml up --build
```
or
```
./run.sh
```