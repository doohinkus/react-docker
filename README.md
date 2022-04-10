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

To work around other issues, you can specify your public development host in a file called .env.development in the root of your project:

(.env.development)

```
HOST=mypublicdevhost.com
```

If you restart the development server now and load the app from the specified host, it should work.
