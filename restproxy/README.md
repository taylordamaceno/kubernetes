restproxy + hpa + ingress
#create the namespace
kubectl create ns restproxy
# Clone the repository
git clone https://github.com/taylordamaceno/restproxy.git
#adjust the endpoints in all yaml files
#create the resources
cd restproxy ; kubectl create -f .

