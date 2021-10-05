# cicd_fintech_project

#1. Create a repository in Google Cloud

gcloud source repos create hello-fintech

#2. Clone the repo locally

gcloud source repos clone hello-fintech

#3. Go into the local ‘hello-fintech’ folder

cd hello-fintech

#4. Create a main.py file that contains messages to be printed to the website

nano main.py           (and then copy the code found in ‘main.py’ file)

#5. Create a app.yaml file

nano app.yaml          (and then copy the code found in ‘app.yaml’ file)

#6. Add, commit and push to git

git add .

git commit -m “Add hello fintech to cloud source repositories”

git push origin master

#7. Deploy app.yaml file 

gcloud app deploy app.yaml

#8. Open website

gcloud app browse       (and then click the url to open it)

![site1](https://user-images.githubusercontent.com/89763616/135952460-348c50ec-0fea-499b-89fd-fb93bab76ff4.jpg)

#9. Create a cloudbuild.yaml file

nano cloudbuild.yaml    (and then copy the code found in ‘cloudbuild.yaml’ file)

#10. Add, commit and push the cloudbuild.yaml file to git

git add .

git commit -m “Add cloudbuild yaml file”

git push origin master

#11. Create a cloud build trigger in GCP console

#12. Enable service account permissions for “App Engine” and “Service Accounts” in Cloud Build settings

#13. Make changes to the main.py file

#14. Add, commit and push the edited main.py file to git

![site2](https://user-images.githubusercontent.com/89763616/135952932-9997a74b-5c07-469a-8c95-bacac026d393.jpg)

