# nodejs-project-demo

# Requirements: 
  Linux (Built in Ubuntu 16.04)
  
  Docker Installed : sudo apt-get install docker.io
  
Step 1: Create project dir: sudo mkdiir ~/"NEW DIRECTORY"

Step 2: Clone repo into dir: sudo git clone https://github.com/alex-hayhoe/nodejs-project.demo.git

Step 3: Edit index.html or css files to suit requirements

Step 4: Build Docker Image: sudo docker build -t "YOURDOCKERUSERNAME"/"DOCKERIMAGENAME" .

Step 5 (Optional): Login to your Docker repo: sudo docker login -u "DOCKERUSERNAME" -p "DOCKERPASSWORD"

Step 6 (Optional): Push docker iamge to your repo: sudo docker push "YOURDOCKERUSERNAME"/"DOCKERIMAGENAME"

Step 7: Run/pull docker image: sudo docker run --name "DOCKERIMAGE" -p 80:8080 -d "YOURDOCKERUSERNAME"/"DOCKERIMAGENAME"

Step 8: Check Website: Navigate to machine IP address
