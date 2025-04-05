## Deploying Taipy

---

```sh
docker build -t taipy_webapp .
#podman build -t taipy_webapp .
```

```sh
docker run -d \
  --name flask_sensor_webapp \
  -v flaskwebapp:/app \
  -w /app \
  -p 9999:9999 \
  taipy_webapp \
  /bin/sh -c "python3 app.py"
```