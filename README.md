# CI-CD-Jenkins-K8
# Step 1 Create a EC2 Instance 
* Jenkins, Maven, SonarQube, Argo CD, Helm and Kubernetes
# ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/7ca8dfa3-fb8e-4552-a8c5-882e0c82f7fa)
 * Because of the size of our App we need more compute SO we be using a t2.large
 * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/6e0ec649-634a-49ec-9927-931e17b23504)
# Step 2 Clone your Source Code to your personal workstation
  * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/922f2eff-9bd4-4d9c-943e-b1a0b2d68d63)
  * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/cceeadd5-c19f-4f2c-ae17-1622263f6d61)
# Step 3 Open the application I will be using docker
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/e753a2e7-70b3-4029-b095-1194d8004fb6)
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/2b89bafb-38fd-4b0e-a213-6dfafac8dca9)
# Step 3 Go to Local host 8010 to verify Application is running
 *![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/cab6bb39-fdcf-4241-af38-5fc58b35dada)
# Step 4 is to SSH into you Instance and download Jenkins
 * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/c57bdcd3-c8e1-4875-b31d-2bac98550797)
 * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/271a65ed-159a-4ddf-9543-8dbb42474ef2)
# Step 5 Download and install JDK and Jenkins
 *![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/0e68a94d-b83e-4b6a-9027-914f7fabfd05)
 ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/c7faeb31-a46e-45a5-9446-218f1345066c)
# Step 6 Download and install Jenkins
 *![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/2c1d2649-e296-4ad6-b0a5-3d891f18de24)
 * If you try to access Jenkins on Port 8080 you will be denied access we will need to update our inpound rules
 * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/8887aae5-2c05-4e7d-a121-ee0d13f874c0)
# Step 7 We are now login to Jenkins
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/a4df2d7d-0179-4604-a73e-4461b46ca50d)
* lets Install the required plugins
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/8d1786f5-0f85-4532-a551-b56295ad9ff7)
# Step 8 Install SonarQube
 * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/c088f652-533d-4e1f-b4b2-93978fe0b9da)
*  In the terminal lets Configure Sonar Server locally
*  ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/a4ac83a9-50b8-46ff-a42b-848a3168ea57)
*  ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/aa838bfb-bbd0-4834-8bb2-65eef06c64a6)
*  ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/c8db7149-f422-430c-8217-358d49d0255d)
# Step 9 We need to have Jenkins Authenticate with SonarQube 
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/7c1f7df6-c12f-481b-815b-b3b999059758)
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/ee5573aa-41fb-4cb1-a45d-fe3fde6e6b11)
# Step 10 install Docker on you instance 
 *![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/01b527de-6cde-46a6-968d-f28e7e731b22)
# Step 11 Install Kubernetes Cluster and argoCD
 * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/6e1c4b9a-7d11-4935-9ab4-a4d1ec07b95c)

# Step 12 Install ArgoCD
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/d4350b79-f9cc-4272-8d4e-583b08aced86)
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/489a679b-ac4a-4e5f-8791-94a9a998c6be)
# Step 13 Give access to Jenkins For docker hub and Github
*![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/97670a53-01e9-44f6-91d2-d941aa6c32df)

# Step 14 Run your Jenkin Pipeline  (after 30 fail attempts)
 *![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/468f8bc0-88af-4e63-8c8a-7ecf099cf2ea)
 * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/ece4547d-37ed-439f-b546-b42bd3f46cd1)
 * ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/41718e88-1ddc-4782-bdd8-a6e2c1262700)
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/ac533095-1882-4c37-9835-a5cac760af2c)
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/bb6c6d3f-9e08-42d9-b09d-f4cdbd2f885c)

# Step 15 We will run the ArgoCD Operator
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/050b3c6d-2e65-44ec-b99d-1a04ec2b45e3)
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/47d181ae-f529-4ef3-ada4-b8ff7bea1a0b)
* ![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/00bc669b-e10c-40f8-99fd-76603c18940a)
 *![image](https://github.com/rogerbarrow/CI-CD-Jenkins-K8/assets/46138186/0187829c-19fd-4255-bcd3-01d4bd46f144)














