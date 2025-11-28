# Express CI/CD Pipeline 🚀

A simple Express.js application with automated CI/CD using Jenkins, Docker, and GitHub.

## What This Project Does

Every time you push code to GitHub:
1. ✅ Jenkins automatically builds the app
2. ✅ Runs tests
3. ✅ Creates a Docker image
4. ✅ Pushes to DockerHub
5. ✅ Deploys to the server

**No manual deployment needed!**

---

## Tech Stack

- **Node.js** - Runtime
- **Express.js** - Web framework
- **Docker** - Containerization
- **Jenkins** - CI/CD automation
- **GitHub** - Source control
- **DockerHub** - Image registry
- **Ngrok** - Webhook tunnel

### Pipeline Stages

**Stage 1: Checkout**
- Pulls latest code from GitHub

**Stage 2: Test**
- Installs npm packages
- Runs test suite

**Stage 3: Build Image**
- Creates Docker image
- Tags with build number

**Stage 4: Push Image**
- Uploads to DockerHub
- Available for deployment

**Stage 5: Deploy**
- Stops old container
- Starts new container
- App is updated!

