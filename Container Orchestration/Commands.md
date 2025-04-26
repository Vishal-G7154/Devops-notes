#🚀 Working with Pods

```bash
kubectl run POD-NAME --image=IMAGE       # 🚀 Create a Pod
kubectl describe pod POD-NAME             # 🔍 Get Pod details
kubectl logs POD-NAME                     # 📜 Get Pod logs
kubectl exec -it POD-NAME -- /bin/bash    # 🛠️ Open Pod terminal
```

📦 Deployments and ReplicaSet

```bash
kubectl create deployment DEPLOYMENT-NAME --image=IMAGE    # 🎬 Create Deployment
kubectl get deployments                                   # 📋 List Deployments
kubectl scale deployment DEPLOYMENT-NAME --replicas=NUMBER # 📈 Scale Deployment
kubectl rollout status deployment/DEPLOYMENT-NAME          # 🔄 Check rollout status
kubectl rollout undo deployment/DEPLOYMENT-NAME            # 🔙 Rollback Deployment

🛰️ Services

```bash
kubectl expose deployment DEPLOYMENT-NAME --type=LoadBalancer --port=PORT  # 📡 Expose Deployment
kubectl get svc                                                            # 🌐 List Services
```

🔄 Ingress

```bash
kubectl create ingress INGRESS-NAME --rule="HOST/PATH=SERVICE:PORT"  # 📡 Create Ingress
```

🔍 Monitoring & Logging

```bash
kubectl top node NODE-NAME  # 📈 Check Node CPU/Memory
kubectl logs POD-NAME      # 📜 Get Pod logs
kubectl logs -l app=APP-NAME # 📜 Get Pod logs with label
```

🎁 Helm

```bash
helm install my-release my-repo/my-chart  # 🎁 Install Chart
helm list                                # 📋 List installed charts
helm upgrade my-release my-repo/my-chart  # 🔄 Upgrade Chart
helm uninstall my-release                 # 🗑️ Uninstall Chart
```                        
