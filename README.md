# terraform-provider-ibm-docker

This docker file is used to build the image with terraform core version 0.13.5 and terrform ibmcloud provider version 1.27.2.

If you would like to run this container, either do the following:

```bash
docker pull ibmterraform/
docker run -it terraform-provider-ibm-docker /bin/bash
```

or build the `Dockerfile`

```bash
git clone https://github.com/IBM-Cloud/terraform-provider-ibm-docker.git
cd terraform-provider-ibm-docker
docker build -t="terraform-ibm-docker" . --no-cache
docker run -it terraform-ibm-docker /bin/bash
```
