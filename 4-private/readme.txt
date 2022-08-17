kubectl create secret docker-registry tksdemo --docker-server=docker.io --docker-username=tksdemo --docker-password=xxx --docker-email=thisadee_pre@truecorp.co.th


docker build . -t tksdemo/my-nginx
docker push tksdemo/my-nginx