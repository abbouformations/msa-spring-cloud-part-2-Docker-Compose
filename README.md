- We used Docker Compose to deploy the application https://github.com/abbouformations/msa-spring-cloud-part-1.git
- Step 1 : Clone the application https://github.com/abbouformations/msa-spring-cloud-part-1.git
- Step 2 : execute mvn clean install  
- Step 3 : For each micro service, create a Dockerfile file with the following content :
  ![image](https://github.com/user-attachments/assets/b136dcf8-4ed1-4de0-b903-7ba7a136efc6)
- Step 4 : Create a docker-compose.yml in the project root :
  ![image](https://github.com/user-attachments/assets/2e691f20-025c-4054-b881-7d990d31aca2)
  ![image](https://github.com/user-attachments/assets/0488a722-390c-4fbb-b0ff-b37b5ed31570)
  ![image](https://github.com/user-attachments/assets/29f2b305-c2d8-4706-811a-8a881c645377)
  ![image](https://github.com/user-attachments/assets/fd845f51-de2f-49b9-bae2-73490270e6d5)
  ![image](https://github.com/user-attachments/assets/6fdf34a8-a400-458f-b6b7-e840d3031472)

- Step 5 : launch the folowing command : docker compose up -d
- Check that the 5 containers are started with success :
  ![image](https://github.com/user-attachments/assets/2460e7be-5c50-474f-baee-2c5617f87663)

  






  
