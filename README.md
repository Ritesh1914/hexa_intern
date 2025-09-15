# Node.js Express Hello World Local CI Pipeline

This project demonstrates a local CI/CD pipeline using Docker for a Node.js + Express app.
The pipeline builds, lints, tests, and deploys the app in a container. We used the same node.js Expresshello world app with Dockerfilw which we used in the Task-1.

## Project Structure
    node-express-hello-world/
    │── app.js
    │── package.json
    │── package-lock.json
    │── Dockerfile
    │── pipeline.sh
    │── .dockerignore
    │── .eslintrc.json
    │
    ├── routes/
    │   └── route.js
    │
    ├── views/
    │   └── home.ejs
    │
    ├── public/
    │   └── images
    │
    └── test/
        └── basic.test.js
 
## Prerequsites
   * Use the Task-1 file or clone it in our machine
   * Install Docker desktop
   * Use the Dockerfie from Task-1
     
