# go-website
 
sudo docker build -t test_app .
docker tag app-image:latest gcr.io/roi-takeoff-user69/app-image:latest
docker push gcr.io/roi-takeoff-user69/app-image:latest