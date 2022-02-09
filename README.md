# compute-windows-images
Windows images for Compute Engine on Google Cloud Platform
Windows Server 2022 Datacenter and Windows 10 IoT Enterprise LTSC 2021 built with [compute-image-tools](https://github.com/GoogleCloudPlatform/compute-image-tools)
## How to
1. Install [Google Cloud SDK](https://cloud.google.com/sdk/docs/quickstart) or launch Cloud Shell
2. Create a Windows Server instance with
`gcloud compute instances create VM_NAME --image-project golden-attic-301814 --image server`
3. Create a Windows 10 instance with
`gcloud compute instances create VM_NAME --image-project golden-attic-301814 --image ltsc`
