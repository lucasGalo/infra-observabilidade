
Referencia de configuração
https://www.youtube.com/watch?v=Ni26hv-FTeg&t=384s

kubectl get svc -n argocd


kubectl get svc loki -n argocd -o yaml


kubectl port-forward svc/grafana -n argocd --address 0.0.0.0 32000:32000 &

kubectl port-forward svc/prometheus -n argocd --address 0.0.0.0 9090:9090 &


ps aux | grep kubectl


kubectl get deployments -n argocd


kubectl delete deployment prometheus -n argocd

kubectl delete service prometheus -n argocd





