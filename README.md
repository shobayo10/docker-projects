# docker-projects
This Docker file builds an image of a container app that outputs the current date and time.
This project uses the Docker tag command 

STEP 1
run docker build -t "image name" "context" 

Docker creates a single image from intermediate images. Docker also tags the final image with the command in step 1 

STEP 2 
For the app in the image to output the time and date.

Run  
docker run "image name" to run a container of the first image.
