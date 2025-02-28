### Secure Kubernetes Deployment (`secure-k8s-deploy`)
- **Objective:** Deploy a Kubernetes cluster with built-in security best practices.
- **Features:**
  - RBAC (Role-Based Access Control)
  - Network Policies for pod isolation
  - Pod Security Standards (PSS) implementation
  - Security tools: `kube-bench`, `kube-hunter`, `Falco`
- **Tech Stack:** Kubernetes, Helm, Trivy, kube-hunter, Falco
- **Status:** 🚧 In Progress
- 🔗 [Repository](https://github.com/yourusername/secure-k8s-deploy)

#### 📂 Initial Files
```
secure-k8s-deploy/
│── README.md
│── manifests/
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── network-policy.yaml
│   ├── rbac.yaml
│── security-tools/
│   ├── kube-bench.sh
│   ├── kube-hunter.sh
│   ├── falco-rules.yaml
```
