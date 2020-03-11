# terraform-provider-ibm-docker

This docker file is used to build the image with terraform core version 0.12.8 and terrform ibmcloud provider version 1.2.4.

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
