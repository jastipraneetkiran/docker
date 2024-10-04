# How to run containers
## Images are used to run containers
> In this guide, you create an image using a Dockerfile and a sample application.

![image](https://github.com/user-attachments/assets/844ea7b6-5fea-47a3-9fc6-3f735e6dea95)

## Get the sample application
>   Clone the repository at
 https://github.com/docker/welcome-to-docker⁠.
```
git clone https://github.com/docker/welcome-to-docker
```
The rest of this guide requires you to run commands in the new project directory. Run the following command before moving on.
```
cd welcome-to-docker
```
## verify your docker file
Open the sample application in your IDE. Note that it already has a Dockerfile. For your own projects you need to create this yourself.

![image](https://github.com/user-attachments/assets/407427aa-5844-4e13-8182-8a1dbf118f14)

## Build your first Image

You can build an image using the following docker build command via a CLI in your project folder.

```
docker build -t welcome-to-docker .
```
Breaking down this command

The -t flag tags your image with a name. (welcome-to-docker in this case). And the . lets Docker know where it can find the Dockerfile.

## Run Your Container

Once the build is complete, an image will appear in the Images tab. Select the image name to see its details. Select Run to run it as a container. In the Optional settings remember to specify a port number (something like 8089).

![image](https://github.com/user-attachments/assets/8fc337cc-d7c2-4d5c-af7e-4891d7823cf3)

## View the frontend

You now have a running container. If you don't have a name for your container, Docker provides one. View your container live by selecting the link below the container's name.

![image](https://github.com/user-attachments/assets/1f648a57-1476-455a-8e2c-aab657d9d56c)

You learned how to run a container from a single image. Next, learn how you can run other people's images from Docker Hub.



