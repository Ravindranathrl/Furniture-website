# Welcome to Ecommerce-Website Project
![Screenshot (127)](https://user-images.githubusercontent.com/108757431/224565249-eaed0360-eac0-4fcb-b3b2-bef3d466f419.png)
![Screenshot (129)](https://user-images.githubusercontent.com/108757431/224565290-1e91dab1-0c8f-4684-a316-95c31fc2fff1.png)
![Screenshot from 2023-03-28 23-24-01](https://user-images.githubusercontent.com/108757431/228326527-5a3e2645-3088-46b7-b605-4de0c54260b6.png)

# Now the Deployment part

This project is deployed in kubernetes cluster using Docker,ArgoCD and Github Action.

To see the ci pipeline click here - https://github.com/Tanmoy037/Furniture-website/actions

After every commit or PR new Docker image get created and pushed into private DockerHub repository and manifest get updated -
![Screenshot from 2023-05-30 19-23-48](https://github.com/Tanmoy037/demo-go-gin/assets/108757431/faf17ed3-e228-4780-afd9-e589175724b6)

Manifiest repository link - https://github.com/Tanmoy037/Furniture-website_manifiest.git

After manifest get updated the changes get deployed into Kubernetes cluster using ArgoCD-


![Screenshot from 2023-05-24 19-55-31](https://github.com/Tanmoy037/demo-go-gin/assets/108757431/16c20c20-c61d-4f7b-8cdc-48738b0802c0)


![Screenshot from 2023-05-24 19-53-10](https://github.com/Tanmoy037/demo-go-gin/assets/108757431/2e2d294d-6210-437f-8329-cca6d17e97f7)

![Screenshot from 2023-05-24 19-57-17](https://github.com/Tanmoy037/demo-go-gin/assets/108757431/40b201b3-bb37-4c30-858f-8c89e888f96a)








