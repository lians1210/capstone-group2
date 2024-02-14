# capstone-group2
Original repository: https://github.com/GNiruthian/Europe-Travel-Website-html-css-js.git 

Step 1: Download Docker in the Debian distribution.
https://docs.docker.com/engine/install/debian/ 

Step 2: Clone repository to a new directory called 'capstone' with git clone

Step 3: How to Use the NGINX Docker Official Image 
https://www.docker.com/blog/how-to-use-the-official-nginx-docker-image/ 

Step 4: Deploying a containerized web application - through Cloud Shell
https://cloud.google.com/kubernetes-engine/docs/tutorials/hello-app 

Challenges: repository name in the command should only have lowercase letters.

Step 5: Push image to Artifact Registry 

https://cloud.google.com/artifact-registry/docs/docker/pushing-and-pulling 

Part 1 tag the local image

docker tag SOURCE-IMAGE LOCATION-docker.pkg.dev/PROJECT-ID/REPOSITORY/IMAGE:TAG

Part 2 Push the image to Artifacts Registry

docker push LOCATION-docker.pkg.dev/PROJECT-ID/REPOSITORY/IMAGE

Step 6: Deploy it with a load balancer through the GCP Console. Selecting the option “Deploy to GKE” and selecting the port, load balancer, etc. Purpose: make it public.

Result: external endpoint: http://34.67.118.108/ 
