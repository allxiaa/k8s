Promt k8s for AI

| NAME                    | PROMPT      | DESCRIPTION | EXAMPLE |
| ----------------------- | ----------- | ----------- | ------- | 
| app | ``` Create manifest k8s for an application Demo gcr.io/k8s-k3s/demo:v1.0.0 ``` | The deployment app "Demo" from image gcr.io/k8s-k3s/demo:v1.0.0 | [app.yaml](https://github.com/app.yaml)|
| app-livenessProbe | ``` Create an http livenessProbe for port 8080 and show it to me this like the k8s manifest ``` | The deployment add liveness probe | [app-livenessProbe.yaml](app-livenessProbe.yaml) |
| app-readinessProbe | ``` Create a Kubernetes Deployment manifest for an application using the image `gcr.io/k8s-k3s/demo:v1.0.0`. The deployment should: Expose port 8080. Include an HTTP readiness probe that checks the `/ready` endpoint after an initial delay of 20 seconds, with a check interval of 5 seconds and a failure threshold of 3. ``` | The deployment add readiness probe | [app-readinessProbe.yaml](app-readinessProbe.yaml) |
| app-volumeMounts | ``` Create a Kubernetes Deployment manifest for an application using the image `gcr.io/k8s-k3s/demo:v1.0.0`. The deployment should: volume mounts Mydata ``` | | [app-volumeMounts.yaml](app-volumeMounts.yaml) |
| app-cronjob | ``` Create task in cronjob when run ever y 7 minute clean.sh  like the k8s manifest ``` | | [app-cronjob.yaml](app-cronjob.yaml) |
| app-job | ``` Create a job as manifest k8s ``` | | [app-job.yaml](app-job.yaml) |
| app-multicontainer | ``` ``` | | [app-multicontainer.yaml](app-multicontainer.yaml) |
| app-resources | | | [app-resources.yaml](app-resources.yaml) |
| app-secret-env | | | [app-secret-env.yaml](app-secret-env.yaml) |
