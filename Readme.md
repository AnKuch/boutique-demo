## Fork Information

This is a fork of Google's microservices-demo, customized for learning purposes.

**Deployment Manifests:** Moved to separate repository
- Repo: https://github.com/<USER>/boutiquedeployment
- Reason: Separation of application code and deployment configuration

**Removed from this fork:**
- Google Cloud specific tooling (.deploystack, cloudbuild.yaml, skaffold.yaml)
- Kubernetes manifests (now in deployment repo)

**Infrastructure:**
- Deployed on Proxmox-based Kubernetes cluster
- Infrastructure Repo: https://github.com/<USER>/kubernetesspielwiese
- GitOps via Argo CD

**Original:** https://github.com/GoogleCloudPlatform/microservices-demo