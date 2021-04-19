# MayaDataWebapp

In this task, I have created one webapp which is launched through a DockerFile via Jenkins CI/CD pipeline. 
The DockerFile is extracted by Jenkins masternode, which builds the image from it and also pushes the image on the DockerHub. 
After that, the container is launched on cloud instance which is a Jenkins slave node of the cluster through docker. This container launched is pulled the image that is pushed by the master node on the DockerHub.


Link to the screenshots of the Devops task done - https://drive.google.com/drive/folders/1OjlL0yHm78rwHJW-4GA-Q82QDqqtTu-U?usp=sharing


DockerHub link to the image repository created- https://hub.docker.com/r/utkarshp536/webapp/tags?page=1&ordering=last_updated


Thank you!!!
