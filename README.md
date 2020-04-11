# Google-Cloud-Commands
![image](https://github.com/sanket9006/Google-Cloud-Commands/blob/master/google-cloud.png)




## <p align="center"> Download any file using wget</p>
sudo wget https://launcher.mojang.com/v1/objects/d0d0fe2b1dc6ab4c65554cb734270872b72dadd6/server.jar




## <p align="center"> Create Bucket </p>
gsutil mb gs://<BUCKET_NAME>

gsutil mb gs://2b1dc6ab4c65554cb73




## <p align="center"> Copy files to Bucket  </p>
gsutil cp [MY_FILE] gs://[BUCKET_NAME]

gsutil cp setup.html gs://2b1dc6ab4c65554cb73





## <p align="center"> list the available VPC networks</p>
gcloud compute networks list




## <p align="center"> Make Copy</p>
cp setup.html setup2.html

cp setup.html setup3.html




## <p align="center"> To list the available VPC subnets</p>
gcloud compute networks subnets list --sort-by=NETWORK


