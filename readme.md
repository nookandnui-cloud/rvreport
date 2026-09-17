
to initiate git
```
oc apply -f https://raw.githubusercontent.com/nookandnui-cloud/rvreport/refs/heads/main/configmap-rvreport.yaml
```
```
oc apply -f https://raw.githubusercontent.com/nookandnui-cloud/rvreport/refs/heads/main/deploy_nginx.yaml
```
```
oc apply -f https://raw.githubusercontent.com/nookandnui-cloud/rvreport/refs/heads/main/route.yaml
```
```
oc apply -f https://raw.githubusercontent.com/nookandnui-cloud/rvreport/refs/heads/main/service.yaml
```
#optional
```
oc apply -f https://raw.githubusercontent.com/nookandnui-cloud/rvreport/refs/heads/main/cloudflare-tunnel.yaml
```
