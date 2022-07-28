# pythondeploywithGCP
step 1
Dockerizing app 1)create a docker file for this app 
![dockerrunimage](https://user-images.githubusercontent.com/86315031/181631911-dc537416-227e-422a-9be5-140aaeec1460.png)
2)push this image to gcr registrey
![dockerpushimage](https://user-images.githubusercontent.com/86315031/181632271-2763e24f-df61-475b-b144-18122b71052b.png)
step 2
create the infrastructure on GCP using terrafom (Iac )
step 3
create deployment 
1 ) setup kubectl on bastin server 
2 )setup gcloud on bastian server to connect to jke and run the deployment
![connect to jke](https://user-images.githubusercontent.com/86315031/181633352-cc51ffa1-2fc5-437f-9d70-53ba53fc7f9a.png)
create deployment.yml file
![deploymentyaml](https://user-images.githubusercontent.com/86315031/181633483-301b3172-dc6a-4797-ab25-13c3508e72aa.png)
run deployment.yml file
![rundeployment](https://user-images.githubusercontent.com/86315031/181633692-5c96e261-92d5-4d8f-bacb-37dbe58c15b0.png)
create service.yml
![serviceyml](https://user-images.githubusercontent.com/86315031/181633805-7a546984-c326-423f-b912-27b7a9c37acf.png)
![runsevice](https://user-images.githubusercontent.com/86315031/181633900-fdcf0934-4f60-43a9-b146-bf860f727649.png)
take public ip on service description with port 8000 on browser
![frombrawoser](https://user-images.githubusercontent.com/86315031/181634175-a1c9fcb8-bbdb-499e-919d-f4ae57ad3ca9.png)

