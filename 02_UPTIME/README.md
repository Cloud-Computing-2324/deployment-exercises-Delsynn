#Uptime
Opdracht 2 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.


Commando's :  
  
helm repo add uptime-kuma https://helm.irsigler.cloud
helm install uptime uptime-kuma/uptime-kuma --values .\values.yaml --namespace uptime --create-namespace