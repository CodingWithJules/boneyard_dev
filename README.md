# Docker - Getting Started 🐳

Hands-on Docker training completed as part of **The Boneyard**, my engineering learning and project repository.

## Lab

This lab covers the fundamentals of:

- Running containers
- Building Docker images
- Creating a `Dockerfile`
- Containerizing an application
- Managing the container lifecycle

**Tutorial:** [Docker - Getting Started Lab](https://docs.docker.com/guides/lab-container-getting-started/)

## Commands Practiced

```bash
docker build -t getting-started .
docker run -dp 3000:3000 getting-started
docker ps
```

## Key Takeaway

A Docker **image** is the packaged application and its dependencies. A **container** is a running instance of that image.

---

*Part of The Boneyard - learning by building, breaking, and rebuilding.*