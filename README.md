# Kubernetes
Kubernetes Infrastructure and Application Orchestration

## Scope
This project covers a series of operational Kubernetes tasks. Each step includes screenshots, the commands used, and an explanation of the task's purpose. The focus areas include cluster and ReplicaSet deployment (manual and automated), pod management, manifest creation and modification, and live troubleshooting.

## Environment
- Kubernetes: v1.32.0+k3s1
- kubectl for CLI management and troubleshooting
- Operating System: Alpine Linux 3.16.9
- YAML manifests both authored manually or provided and manipulated/updated during troubleshooting
  
## Tasks

### Determine the node count, cluster information, and the host operating system.
![Step1](images/step1.jpg)

### Delete a pod, create manifest file, monitor pod creation status, confirm number of pods running matches what is in the manifest file.
![Step2](images/step2.jpg)

### Update the replicaset with the correct image to ensure pods are deployed using the correct image.
![Step3](images/step3.jpg)

### Correct issue with the manifest, then created a new replicaset, validated both replicasets are now running, each has the desired number of pods, and that all pods are ready.
![Step4](images/step4.jpg)

### Validate the container providing the image to the underlying pods is correct.
![Step5](images/step5.jpg)

### Horizontally scale the number of pods in the replicaset without editing the manifest, confirm the number of running pods mirrors the updated count.
![Step6](images/step6.jpg)

### Created manifest and new replicaset, updated number of replicas in the manifest confirmed running pods were horizontally scaled after updating replica count.
![Step7](images/step7.jpg)

### Create the manifest for new deployment, then created new deployment off manifest.
![Step8](images/step8.jpg)

### Validate the image used by the pods by the deployment.
![Step9](images/step9.jpg)

### Review deployment manifest for accuracy.
![Step10](images/step10.jpg)

### Validate the current number of running pods, deployments and replicasets.
![Step11](images/step11.jpg)

### Update the image used by the deployment.
![Step12](images/step12.jpg)

### Determine the image and the update strategy type used by the deployment.
![Step13](images/step13.jpg)

### Determine the image used by the pods from the deployment.
![Step14](images/step14.jpg)

### Review services running on the cluster to determine the endpoints, labels and target port.
![Step15](images/step15.jpg)

### Configure NodePort manifest for use with the cluster.
![Step16](images/step16.jpg)
