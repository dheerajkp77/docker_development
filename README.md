# To create image run

docker build -f Dockerfile.dev -t reactDockerImage .

# to run docker dev file have to use -f tag

# After successful creation of imgae to create container run

docker run -it --name reactDocker -p 3000:3000 reactdocker
