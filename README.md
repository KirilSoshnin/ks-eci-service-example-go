## Build and Run

```bash
docker build -t test .

# Display env vars
docker run -it --rm --env=KS_PUBLIC_INSTRUCTOR=Kiril --env=KS_PUBLIC_LOCATION=QC -p 8080:80 test

# Greet
curl http://localhost:8080

# Display env vars
curl http://localhost:8080/env
```
