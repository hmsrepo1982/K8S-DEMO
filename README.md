# K8S-DEMO
 K8S-DEMO project is a learning project for Kubernetes.
 
 Using local Docker which hosts a kubernetes node, this project is built.
 
 1. Docker made to run on mac.
 2. MiniKube is running using local Docker instance.
 3. start minikube --driver docker
 4. minikube is a single node instace containing all components of K8s
 5. minikube status - will give all the components like controle pane, ecstd, API server etc
 6. kubectl also gets installed along with minikube so we can interact with Node.
 7. Create a Deployment config map to define variables.
 8. Create a secret file which would hold base 64 encoded secrets for DB service.
 8. Create a deployment config which will host blueprint for pod config and service definition.
 
 ---
 
 kubectl apply -f filename [ configmap, secret, mongo, webapp ] 
 
 kubectl get pod
 kubectl get all 
 kubectl logs podName
 kubectl describe service 
 kubectl get deployments
 kubectl delete nameofdeployment
 
 
 Config code is committed. It is very useful project and explains all the details.
