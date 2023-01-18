Steps for deploying the code locally:

1) git clone https://github.com/Josip-github/Learning-Resources-Project.git
(if you are not a collaborator of this private github repository, just unzip the folder and proceed to number 2)

2) in the root folder of the project run following command:
docker build -t vuejs-cookbook/learning-resources .

3) run the app in a Docker container with this command:
docker run -it -p 8080:8080 --rm --name resources vuejs-cookbook/learning-resources

Finally, the app should be accessible on localhost:8080
