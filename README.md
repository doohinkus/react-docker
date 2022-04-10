## Docker React Boilerplate

- No need to worry about node versions.
  Run

```
docker-compose up
```

Open http://localhost:3000

The app is running in the docker container. When making edits, the page will update!

To stop

```
docker-compose stop
```

To view running containers:

```
docker ps
```

Most CORs issues can be resolved in package.json:
https://create-react-app.dev/docs/proxying-api-requests-in-development/
