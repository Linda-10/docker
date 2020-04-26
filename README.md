# docker based on Centos 7
with python, vue.js environment and GUI 
## STEP(1/3) build a new image
docker build -t lyl
## STEP(2/3) view the image you just created
docker images
## STEP(3/3) run the container and execute the Python test program
docker run "image ID"
