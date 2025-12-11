# EvOps :whale:

Self-hosted ecosystem with web-UI & Android app mayde with recommendation system to publish and notificate about YOUR events.

## Quick Start

### How to run the application

- Clone the repository with all submodules.

  ```shell
  git clone --recurse-submodules https://github.com/evops-sum25/evops.git
  ```

- Set up the [`.env`](/.env.example),
  [`backend/.env`](https://github.com/evops-sum25/evops-backend/blob/main/.env.example),
  [`ml/.env`](https://github.com/evops-sum25/evops-ml/blob/main/.env.example),
  and
  [`website/.env`](https://github.com/evops-sum25/evops-website/blob/main/.env.example)
  files.

- Run the app with Docker Compose.

  ```shell
  docker compose up --build
  ```

The services will be available on the following URLs:

- Back end: http://localhost:8080
- Website: http://localhost:3000
