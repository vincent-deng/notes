```
gcloud config get-value project

gcloud projects list 

gcloud config set project [PROJECT_ID]

gcloud compute instances list

gcloud compute instances delete riding-school-vm

gcloud compute instances create riding-school-app \
    --machine-type=e2-medium \
    --zone=asia-southeast1-b \
    --image-family=ubuntu-2204-lts \
    --image-project=ubuntu-os-cloud \
    --boot-disk-size=50GB \
    --boot-disk-type=pd-balanced \
    --boot-disk-device-name=riding-school-app
```
