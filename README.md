# Readme about project Stack


**Note** -  follow the below steps.

## Run it local without Docker

### Prerequisite

- Install `npm`

#### Start Server:

```
cd mern/server
npm install
npm start
```

#### Start Client

```
cd mern/client
npm install
npm run dev
```

## Run it local with Docker

Go to frontend folder

# Create docker image frontend

```
docker build -t nebulaestack:dev .
docker run -p 5173:5173 nebulaestack:dev
```

Go to backend folder

# Create docker image backend

```
docker build -t nebulaestack:start .
docker run -p 5050:5050 nebulaestack:start
```
