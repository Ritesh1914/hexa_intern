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


## Steps:
  ## Clone the repository
     git clone https://github.com/Ritesh1914/Task-1 
     cd Task-1       
  ## Install dependencies if not
    - check if npm is install or not 
       npm -v
    -  if not
       npm install
    -  download the eslint and jest dependecies
       npm install --save-dev eslint@8 jest
    -  to check the list of npm dependencies
       npm list --dept=0
       npx install -v r eslint -v

   ## Run th script pipeline.sh
      to make the script executable run
        chmod +x pipeline.sh
      to run the script 
         ./pipeline.sh
   ## To set the env for eslint we need to create a json file name as .eslintrc.json
   ## To set the env for jest we need to create a js file in task folder (ex best.test.js).
   ## After running script we would find some error in app.js file and we have edit the error and again run our pipeline.
   ## Our Pipeline runs successfully!
    
