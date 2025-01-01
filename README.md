# mission-kubernetes
This Repo is to track and document all the learnings I do to get complete Kubernetes understanding. End goal is to be able to work with kubernetes as a tool and also have some understanding of kubernetes as a software. 

While working on this. Any point will be assumed as given for example - I will spinup an EKS and start working app deployment using helm , argocd setup etc.. Here I'm taking Kubernetes as given and working on it. Later on when I cover the setup of Kubernetes . I will remove EKS and test with K8 cluster spinned up . 

### Kubernetes as a Tool : 
*  Spin up a kubernetes cluster the hardway 
* Deploy multiple controllers 
    1. Deploy Block Storage CSI drivers like longhorn.
    2. Deploy Minio , Cert Manager , Nginx Controller . 
    3. Deploy External Secrets Operator. 

* Deploy an application through helm chart and  kustomize .

* Use ArgoCD to manage application Deployments and access. 



### Understanding working of Kubernetes : 
* Linux Fundamentals that makeup container runtime - using bocker can be helpful 
* Linux Networking that translate to K8 networking - using bocker can be helpful

### Internal working of Kubernets as a Software : 
* Learning go language 
* Building sufficient level of proficiency.
* Write a kubectl plugin in go . 
* Write a basic controller in go . 

---

## Project Tasks and Sprint Details.

* Each week is considered as sprint and a set of tasks are take up to complete in that week.
* Weekly updates are tracked [here](./sprint-details)
* Each Task will have a clear and concise description . A clear outcome should be mentioned for each task . 
* Every task completed must be documented . 