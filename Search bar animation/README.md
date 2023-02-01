create a docker file
docker build . -t search-bar-img
docker images
docker run -d --name search-bar-ctr -p 80:80 search-bar-img:latest
