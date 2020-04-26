# docker based on Centos 7
#### with python, vue.js environment and GUI 
## Step 1:  build a new image
docker build -t lyl
## Step 2:  view the image you just created
docker images
## Step 3:  run the container and execute the Python test program
docker run "image ID"
