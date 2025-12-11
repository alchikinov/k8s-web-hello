# k8s-web-hello

A simple Node.js service used for practicing Docker containerization and Kubernetes deployments.

## Tech Stack

- **Node.js** – base application runtime  
- **Docker** – containerized application build  
- **Kubernetes** – deployment and orchestration (coming soon)  
- **GitHub Actions** – CI/CD pipelines (coming soon)

## Run Locally (without Docker)

```bash
npm install
npm start
```

The application listens on port 3000 by default.

### Build Docker Image
- docker build -t alchikinov/k8s-web-hello:1.0.0 .

### Run the container:
- docker run --rm -p 3000:3000 alchikinov/k8s-web-hello:1.0.0

### The service will be available at:
- The application listens on port 3000 by default.