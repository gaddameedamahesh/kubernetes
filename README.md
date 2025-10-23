# Kubernetes Basics

Welcome to the **Kubernetes Basics** repository!  
This repo is designed for beginners who want to learn and experiment with Kubernetes using practical, easy-to-understand YAML examples.

---

## 📚 What You'll Find Here

- **Kubernetes Concepts Explained Simply**
- **Sample YAML Files** for Pods, Deployments, and Services
- **Step-by-Step Instructions** to apply and test resources
- **Contribution Guidelines** for sharing your own examples
- **Helpful Resources** for further learning

---

## 🚀 Getting Started

### 1. Prerequisites

- Basic knowledge of containers (Docker recommended)
- Access to a Kubernetes cluster (Minikube, Docker Desktop, kind, or cloud provider)
- `kubectl` installed on your machine

### 2. Cloning the Repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

---

## 📝 Example YAML Files

- [`pods/`](pods/) - Simple Pod definitions
- [`deployments/`](deployments/) - Deployment YAMLs for scalable apps
- [`services/`](services/) - Service YAMLs for exposing applications

### Applying a YAML File

```bash
kubectl apply -f path/to/file.yaml
```

### Example: Deploying a Pod

```bash
kubectl apply -f pods/simple-pod.yaml
kubectl get pods
```

---

## 🤝 How to Contribute

Contributions are welcome!  
To add your own example or improve documentation:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/my-example`)
3. Add your YAML files or docs
4. Open a Pull Request

Please follow the [contribution guidelines](CONTRIBUTING.md) if available.

---

## 📖 Learn More

- [Kubernetes Official Docs](https://kubernetes.io/docs/home/)
- [Learn Kubernetes with Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [YAML Basics](https://learnk8s.io/kubernetes-yaml)

---

## 🛡️ License

This repository is licensed under the MIT License.

---

## ✨ Badges

![Kubernetes](https://img.shields.io/badge/kubernetes-beginner-blue)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)

---

Happy learning! 🚢
