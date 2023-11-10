1. Build the Docker Image:
In the terminal, navigate to the directory containing your Dockerfile and run the following command to build the Docker image:

docker build -t python_image .


2. Run the Docker Container:
Once the image is built, you can run a container based on that image:

docker run -p 4000:80 python_image

This maps port 80 inside the container to port 4000 on your host machine. Adjust the ports as needed.