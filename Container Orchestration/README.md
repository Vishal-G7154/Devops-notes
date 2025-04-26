# ☸️ Kubernetes - Key Concepts

## 🔹 Cluster
# - Group of Nodes managed together.
# - Consists of 1 Master (Control Plane) + multiple Worker Nodes.

# 🔹 Node
# - Physical or Virtual machine.
# - Runs your applications inside containers.

# 🔹 Pod
# - 🧱 Smallest deployable unit.
# - Can run 1 or more tightly coupled containers.

# 🔹 Deployment
# - 🔄 Ensures the desired number of Pods are running.
# - Supports scaling, rolling updates, and rollbacks.

# 🔹 Service
# - 📡 Provides a stable network endpoint to access Pods.
# - Types:
#   - ClusterIP (internal-only)
#   - NodePort (exposes via Node IP:Port)
#   - LoadBalancer (external cloud load balancer)

# 🔹 Namespace
# - 🗂️ Logical partition inside a cluster to isolate resources.

# 🔹 ConfigMap
# - ⚙️ Inject configuration into applications (as env variables/volumes).

# 🔹 Secret
# - 🔐 Securely stores sensitive information (passwords, tokens).

# 🔹 Volume
# - 💾 Persistent storage for Pods.
# - Types:
#   - emptyDir
#   - hostPath
#   - PersistentVolume (PV) + PersistentVolumeClaim (PVC)

# 🔹 Ingress
# - 🌐 Manages external HTTP/HTTPS access to Services.
# - Acts like a smart web traffic router.

# 🔹 ReplicaSet
# - ♻️ Ensures a set number of Pod replicas are always running.

# 🔹 StatefulSet
# - 🗃️ Like Deployment but for stateful apps (e.g., databases).
# - Maintains sticky identities for Pods.

# 🔹 DaemonSet
# - 📦 Ensures a Pod runs on every Node (or selected Nodes).

# 🔹 Job
# - ⏳ Runs Pods to completion (one-off tasks, batch jobs).

# 🔹 CronJob
# - ⏰ Schedule Jobs to run at specified times (like crontab).

# ⚙️ Control Plane Components

# - kube-apiserver: 📣 Exposes Kubernetes API.
# - etcd: 🗝️ Key-value store for cluster data.
# - kube-scheduler: 📅 Assigns Pods to Nodes.
# - kube-controller-manager: 🎛️ Maintains the cluster's desired state.

# ⚙️ Worker Node Components

# - kubelet: 🔍 Ensures containers run properly on Nodes.
# - kube-proxy: 🛡️ Handles networking between Pods.
# - Container Runtime: 🛠️ Software to run containers (Docker, containerd).

# 🔹 Labels & Selectors
# - 🏷️ Labels: Key/Value metadata attached to objects.
# - 🔍 Selectors: Query to select objects based on labels.

# 🔹 Resource Limits
# - 🚦 Define CPU/Memory limits for containers.
#   - Requests = Minimum guaranteed resources.
#   - Limits = Maximum allowed usage.

# 🔹 Autoscaling
# - 📈 Horizontal Pod Autoscaler (HPA): Scales Pods horizontally based on CPU/Memory.
# - 📏 Vertical Pod Autoscaler (VPA): Adjusts Pod resource requests automatically.

# 🔹 Rolling Updates & Rollbacks
# - 🔄 Update Deployments with zero downtime.
# - 🔙 Roll back to previous versions if needed.

# 🔹 Monitoring & Logging
# - 🖥️ Monitoring: Prometheus + Grafana
# - 📜 Logging: ELK Stack (Elasticsearch, Logstash, Kibana)

# 🔹 Helm
# - 🎁 Package manager for Kubernetes.
# - Uses Charts 📦 to deploy complex applications easily.

## 🔄 Rolling Updates & Rollbacks

- Update Deployments with zero downtime.
- Roll back to previous versions if needed.

---

# ☸️ Kubernetes Common `kubectl` Commands

---

## 🎬 Basic Commands

```bash
kubectl version              # 📜 Show client and server version info
kubectl cluster-info          # 🌐 Display cluster master and services info
kubectl get nodes             # 🖥️ List all nodes
kubectl get pods              # 📦 List all pods
kubectl get all               # 🧹 List all resources (pods, svc, deployments, etc.)

