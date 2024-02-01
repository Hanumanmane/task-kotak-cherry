### To intsalll helm###

curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 > get_helm.sh
chmod 700 get_helm.sh
./get_helm.sh

helm version  --> To check helm version

To create New helm chart:
helm create <chart_name>

Copy deployment.yaml file in template Dir

Then Run :
helm install <chart_name> .

To check pods are running :

kubectl get pods
kubectl get svc


Note --> To access application use <nlb-endpoint>:3000/login.html
