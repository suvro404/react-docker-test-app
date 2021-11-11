react-docker-test-app
A demo app to practice docker with a react app.

## Project setup
```
npm install
```

### Run the app in the development mode.
```
npm start
```

### Builds the app for production to the `build` folder.
```
npm run build
```

### Create docker image and containers for development.
```
docker-compose -f docker-compose.yml -f docker-compose-dev.yml up -d --build
```

### Create docker image and containers for production.
```
docker-compose -f docker-compose.yml -f docker-compose-prod.yml up -d --build
```