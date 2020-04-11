# Google-Cloud-Commands
![image](https://github.com/sanket9006/Google-Cloud-Commands/blob/master/google-cloud.png)




## <p> Download any file using wget</p>
sudo wget https://launcher.mojang.com/v1/objects/d0d0fe2b1dc6ab4c65554cb734270872b72dadd6/server.jar




## <p> Create Bucket </p>
gsutil mb gs://<BUCKET_NAME>

gsutil mb gs://2b1dc6ab4c65554cb73




## <p> Copy files to Bucket  </p>
gsutil cp [MY_FILE] gs://[BUCKET_NAME]

gsutil cp setup.html gs://2b1dc6ab4c65554cb73





## <p> list the available VPC networks</p>
gcloud compute networks list




## <p> Make Copy</p>
cp setup.html setup2.html

cp setup.html setup3.html




## <p> To list the available VPC subnets</p>
gcloud compute networks subnets list --sort-by=NETWORK


## <p> Set time zone subnets</p>
gcloud config set compute/zone us-central1-b


## <p> Create Virtual Machine Instance</p>
gcloud compute instances create gcelab2 --machine-type n1-standard-2 --zone us-central1-c


## <p> Create Cluster</p>
gcloud container clusters create io

