### **Project 3: Getting Started with Docker Compose**  
**Objective**: Learn to manage multi-container applications using Docker Compose. You'll create and manage a simple application that includes multiple services.  

---

#### **Tasks**:

1. **Installing Docker Compose**:  
   - How do you check if Docker Compose is installed on your system?  
   - If not installed, how do you install Docker Compose?  

2. **Basic Compose File**:  
   - How do you create a `docker-compose.yml` file?  
   - What are the required fields in a basic Compose file to define a service?  

3. **Single Service Application**:  
   - How do you define a single service (e.g., `nginx`) in a `docker-compose.yml` file?  
   - How do you start the service using Docker Compose?  

4. **Multi-Service Application**:  
   - How do you add a second service (e.g., `redis`) to your `docker-compose.yml`?  
   - How do you start both services at once using Docker Compose?  

5. **Environment Variables**:  
   - How do you define and use environment variables in a Compose file?  
   - How do you pass environment variables from a `.env` file?  

6. **Networking**:  
   - How do you ensure that two services (e.g., a web app and a database) can communicate within the same Docker Compose network?  
   - What is the default network created by Docker Compose?  

7. **Volumes**:  
   - How do you add a volume to persist data in one of your services?  
   - How do you verify that the volume is being used by your container?  

8. **Service Logs**:  
   - How do you view logs for a specific service?  
   - How do you view logs for all services managed by Docker Compose?  

9. **Stopping and Cleaning Up**:  
   - How do you stop all running services defined in your `docker-compose.yml`?  
   - How do you remove all containers and networks created by Docker Compose?  

10. **Scaling Services**:  
   - How do you scale a service (e.g., `web`) to run multiple instances using Docker Compose?  
   - How can you verify that scaling has worked?  

---

**Challenge**:  
- Create a multi-container application with the following:  
  - A **Python Flask app** serving "Hello, Docker Compose!" on port 5000.  
  - A **Redis service** for caching.  
  - Use a volume to persist Redis data.  
- Write a `docker-compose.yml` file to define the setup.  
- Start the application and confirm the Flask app communicates with Redis.  
- Scale the Flask app to 3 instances.  

--- 
