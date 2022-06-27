# PERSISTING-DATA-IN-KUBERNETES
project 23 of www.darey.io Project Based DevOps Learning Platform

Project 23 is a continuation of [project 22](https://github.com/uzukwujp/Deploying-Apps-in-K8s-Cluster/blob/main/README.md).

We learnt about the ephemeral nature of pods hence the need for persistent volume which saves the state of the pod upon crashing or when the pod is killed.

The StorageClass makes persistent Volume possible

We explored how to create Dynamic and static Persistent Volume as well as Persistent Volume claim which is simply a request for storage.

We also explored configmap. Which is k8s solution for Application configuration


![AZ-prj23](https://user-images.githubusercontent.com/52359007/176003102-f94e6dd7-78bc-4b01-a25b-a2f559d37ec9.PNG)

![created-pv-bound](https://user-images.githubusercontent.com/52359007/176003193-710717c0-eade-425d-8ea6-9fdc7c0e0500.PNG)

![default-conf-prj23](https://user-images.githubusercontent.com/52359007/176003248-c5512f46-1ff6-49ca-88d4-0cbb52bc98c0.PNG)

![EBS-volume-prj23](https://user-images.githubusercontent.com/52359007/176003295-28b064df-66d6-4029-90e2-adc300bccc53.PNG)

![Identify-ec2-running-pods-prj23](https://user-images.githubusercontent.com/52359007/176003318-c227174c-00dc-43a6-8193-70cac5e9389a.PNG)

![list-configmap](https://user-images.githubusercontent.com/52359007/176003372-fe30f462-340b-421e-81e2-12a0a4fdac03.PNG)

![mounted-configmap](https://user-images.githubusercontent.com/52359007/176003398-05f17f4d-4f35-47c9-a5df-6a2f26ce2df0.PNG)

![nginx-deployment-prj23](https://user-images.githubusercontent.com/52359007/176003494-d20c6732-33ed-4222-883f-0d68432119d0.PNG)

![nginx-filesystem](https://user-images.githubusercontent.com/52359007/176003523-dd7c6e18-c149-41af-bd2b-5accd81f3604.PNG)
