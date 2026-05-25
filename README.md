# FitLife Deployment

This repository contains the deployment setup for the FitLife Digital PoC.

## Purpose

The repository is used to start the system with Docker Compose.

It includes:

- UserService
- ClassService
- BookingService
- AdminService
- AuthService
- MongoDB

## Run locally

From this repository:

```powershell
docker compose up --build

docker compose down