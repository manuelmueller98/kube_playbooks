Das Playbook ```install-kubernetes.yml``` benutzt die Rollen in diesem Repository. Es installiert die notwendigen Pakete für einen Kubernetes Cluster auf Debian 13 (trixie)

```ansible-playbook install-kubernetes.yml -i hosts.yml```

Anschließend kann mit dem initialisieren des Clusters begonnen werden.
