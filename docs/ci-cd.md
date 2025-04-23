# 🔄 CI/CD Pipeline Integration

This lab includes optional setup for full CI/CD pipelines using Jenkins and Ansible.

### Workflow Overview

1. Developer pushes code to GitHub
2. Docker VM builds the image
3. Image pushed to Docker Hub
4. Kubernetes picks up and updates app via:
   - Manual rollout
   - ArgoCD or Jenkins pipeline (optional)
