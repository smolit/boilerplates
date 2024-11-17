
#### Get Eventstream of namespace
  kubectl get events -w -n <namespace>

#### Get Endpoints in namespace
  kubectl get endpoints -n <namespace>

#### Kubectl port-forward 

 - to a pod

    kubectl -n \<namespace\> port-forward pod/\<pod-name\> \<local-port\>:\<pod-port\>
      
 - to a service
   
    kubectl -n \<namespace\> port-forward service/\<service-name\> \<local-port\>:\<pod-port\>
 

## Troubleshooting

- Curl
    - -i, --include       Include protocol response headers in the output
    - -k, --insecure      Allow insecure server connections when using SSL
    - -L, --location      Follow redirects
