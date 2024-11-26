### **Project 5: Introduction to Kubernetes**  
**Objective**: Learn the basics of Kubernetes by deploying and managing containerized applications in a cluster environment.

---

#### **Tasks**:

1. **Setting Up Kubernetes**:  
   - How do you install Minikube or Kind to create a local Kubernetes cluster?  
   - How do you configure `kubectl` to interact with your cluster?  

2. **Basic Deployment**:  
   - How do you create a Kubernetes Deployment for a simple application (e.g., an `nginx` web server)?  
   - How do you verify that the deployment has created the expected pods?  

3. **Exposing Your Application**:  
   - How do you expose your application to make it accessible outside the cluster using a Kubernetes Service?  
   - What is the difference between `ClusterIP`, `NodePort`, and `LoadBalancer` service types?  

4. **Scaling Applications**:  
   - How do you scale your deployment to run 3 replicas?  
   - How do you confirm that scaling has worked?  

5. **ConfigMaps and Secrets**:  
   - How do you use a ConfigMap to provide configuration data to your application?  
   - How do you store sensitive information in a Kubernetes Secret and use it in a pod?  

6. **Persistent Storage**:  
   - How do you create a PersistentVolume (PV) and PersistentVolumeClaim (PVC)?  
   - How do you mount a PVC to a pod to persist application data?  

7. **Health Checks**:  
   - How do you define `liveness` and `readiness` probes in your deployment YAML file?  
   - How do these probes help maintain the stability of your application?  

8. **Monitoring Pods**:  
   - How do you view the logs of a running pod?  
   - How do you use `kubectl describe` to debug a failing pod?  

9. **Namespace Isolation**:  
   - How do you create a namespace in Kubernetes?  
   - How do you deploy resources into a specific namespace?  

10. **Updating Applications**:  
    - How do you perform a rolling update for your application?  
    - How do you roll back to a previous version if the update fails?  

---

**Challenge**:  
- Deploy a **multi-tier application** on Kubernetes:  
  - **Frontend**: A React app served via NGINX.  
  - **Backend**: A Node.js API.  
  - **Database**: PostgreSQL with persistent storage.  
- Include:  
  - A ConfigMap to configure the database connection.  
  - Secrets to store database credentials.  
  - Health checks for all services.  
  - Use separate namespaces for development and production environments.  
- Document the steps to deploy, scale, and update the application.  

---

