Demo for a very simple nginx setup withing one hour according to this [guide](https://community.open-telekom-cloud.com/community?id=community_blog&sys_id=08f3fb40132c0190d15ac969a674412b&view_source=searchResult)

Please follow this steps on OTC.

Replace all the "REPLACE_ME" Strings in this project with your values.

- helm install crds crds
- helm install registry-creds registry-creds
- helm install cert-manager cert-manager
- helm install ingress-nginx ingress-nginx
- helm install http-inspector http-inspector
