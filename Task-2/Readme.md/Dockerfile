### 1. Install Docker

```bash
sudo apt update
sudo apt install docker.io -y
```

### 2. Create index.html

```html
<h1>Hello DevOps Project</h1>
```

### 3. Create Dockerfile

```Dockerfile
FROM nginx:latest
COPY index.html /usr/share/nginx/html/
```

### 4. Build Image

```bash
docker build -t myapp .
```

### 5. Run Container

```bash
docker run -d -p 8000:80 myapp
```

---

## Access Application

Open in browser:
http://<server-ip>:8000

---

## Outcome

Successfully deployed a containerized web application.
