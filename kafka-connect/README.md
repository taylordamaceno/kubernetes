debezium + kafka-connect + hpa + ingress
#create the namespace
kubectl create ns kafka-connect
# Clone the repository
git clone https://github.com/taylordamaceno/kubernetes.git
#adjust the endpoints in all yaml files
#create the resources
cd kubernetes; kubectl create -f .
