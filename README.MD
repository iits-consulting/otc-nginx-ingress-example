Demo for a very simple and stupid nginx setup withing one hour.

Please follow this steps on OTC.

Replace all the "REPLACE_ME" Strings in this project with your values.

helm install crds crds
helm install registry-creds registry-creds
helm install cert-manager cert-manager
helm install ingress-nginx ingress-nginx
helm install http-inspector http-inspector