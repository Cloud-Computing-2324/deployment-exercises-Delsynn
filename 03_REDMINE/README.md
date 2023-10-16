#Redmine

Opdracht 3 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.  
  
Commando's :  
  
helm repo add bitnami https://charts.bitnami.com/bitnami  
helm install redmine oci://registry-1.docker.io/bitnamicharts/redmine --values .\values.yaml --namespace redmine --create-namespace