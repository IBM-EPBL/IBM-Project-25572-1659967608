# create a docker file and build that file using the name of icr.io/<namespace-name>/<repo-name>:tag
docker build . --tag icr.io/ibm_2002/ovya
# push the image to the IBM Container Registry using
docker push icr.io/ibm_2002/ovya