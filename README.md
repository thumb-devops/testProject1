Everytime there is an edit to main.py or dockerfile in the the app folder it will it will build a new docker image. Run the helmfile in the main folder to deploy the helm chart.

For use find the IP of the localhost and append it with the port number from the kubectl namespaces. Also add "/hello" to get the api to return.
EX: 172.168.1.145:31574/hello
