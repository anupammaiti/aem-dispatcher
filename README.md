ld

```
docker build -t aem-docker .
```

### Run

You will need to have an AEM publish instance running on [localhost:4503](http://localhost:4503).

```
docker run -it -p 8081:80 aem-docker
```

Then open an AEM page at [localhost:8081](http://localhost:8080).
