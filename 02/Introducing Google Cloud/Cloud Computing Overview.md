The US National Institute of Standards and Technology created the term **cloud computing** .
Cloud computing is a way of using information technology (IT) that has these five equally important traits  : 
![[Pasted image 20240602092513.png]]


Why has cloud become so compelling : 
Some history behind cloud computing : 
Sure, let's break it down into simpler terms.

#### Early Days (1970s-1980s)

1. **Data Centers Begin**: Companies built their own data centers to store their computer servers. This was expensive because they had to pay for the building, power, cooling, and security.

#### 1990s

2. **Colocation Starts**: Instead of building their own data centers, companies started renting space in big data centers. These data centers provided power, cooling, and security. This was cheaper and easier than doing it themselves.

#### Transition to Cloud Computing (2000s)

3. **Managed Services**: Colocation centers started offering extra services like monitoring and backups.
4. **Cloud Computing Emerges**: Companies like Amazon, Google, and Microsoft started offering cloud services. Cloud computing provided easy access to computing resources over the internet, so businesses didn't need to manage physical servers.

#### Combining Colocation and Cloud (2010s)

5. **Hybrid Models**: Companies started using a mix of colocation and cloud services. They kept some servers in colocation centers but also used cloud services for flexibility.
6. **Direct Cloud Connections**: Colocation centers provided direct connections to cloud services, improving performance and speed.

#### Modern Times (2020s)

7. **Edge Computing**: With edge computing, data is processed closer to where it's created (like smart devices). 
### Timeline of Cloud Computing Evolution

#### 1st Wave: Colocation (1990s)

1. **Early 1990s: Emergence of Colocation**
   - Businesses began to rent space in third-party data centers.
   - Colocation centers provided power, cooling, physical security, and reliable internet connectivity.
   - This allowed companies to avoid the high costs of building and maintaining their own data centers.

#### 2nd Wave: Virtualized Data Centers (2000s)

2. **Early 2000s: Rise of Virtualization**
   - Virtualization technology allowed multiple virtual servers to run on a single physical server.
   - The components of virtualized data centers match the physical building blocks of hosted computing—servers, CPUs, disks, load balancers, and so on—but now they’re virtual devices. - GC
   - With virtualization, enterprises still maintain the infrastructure; but it also remains a user-controlled and user-configured environment.
   - This improved efficiency, reduced costs, and simplified management of data centers.
   - Companies could run more applications on fewer physical servers, leading to better resource utilization.

3. **Mid-2000s: Introduction of Cloud Computing**
   - Companies like Amazon (AWS in 2006) introduced cloud services, leveraging virtualization.
   - Cloud computing provided on-demand access to computing resources, allowing businesses to scale up or down as needed.
   - Services like Infrastructure as a Service (IaaS) and Software as a Service (SaaS) became popular.

#### 3rd Wave: Container-Based Architecture (2010s-2020s)

4. **2010s: Adoption of Containerization**
   - Technologies like Docker (introduced in 2013) made it easier to package applications and their dependencies into containers.
   - Containers are lightweight, portable, and can run consistently across different environments.
   - This led to faster development, deployment, and scaling of applications.

5. **Late 2010s - 2020s: Kubernetes and Orchestration**
   - Kubernetes (introduced by Google in 2014) became the standard for container orchestration.
   - It automates the deployment, scaling, and management of containerized applications.
   - Cloud providers offered managed Kubernetes services (e.g., Google Kubernetes Engine, Amazon EKS, Azure AKS).
	   - In the context of container-based architecture, the statement "services automatically provision and configure the infrastructure used to run applications" refers to the use of tools and platforms that manage the deployment, scaling, and operation of containerized applications without requiring manual intervention. Here’s what this means in detail:

		### Key Concepts in Container-Based Architecture
		
		1. **Containers**:
		   - Containers package an application and its dependencies into a single unit that can run consistently across different computing environments.
		   - They are lightweight, portable, and can be started or stopped quickly.
		
		2. **Container Orchestration**:
		   - Tools like Kubernetes manage the deployment, scaling, and operation of containers.
		   - Orchestration automates the scheduling, deployment, networking, and scaling of containerized applications.
		
		### Automatic Provisioning and Configuration
		
		#### 1. Infrastructure as Code (IaC)
		- **Definition**: Using code to manage and provision the computing infrastructure.
		- **Example Tools**: Terraform, Ansible.
		- **Function**: Define infrastructure (servers, networks, databases) in code, allowing automatic provisioning and configuration when needed.
		
		#### 2. Kubernetes and Container Orchestration
		- **Deployment Automation**: Kubernetes can automatically deploy containers across a cluster of machines.
		- **Scaling**: Kubernetes can automatically scale the number of container instances up or down based on demand (Horizontal Pod Autoscaler).
		- **Self-Healing**: Kubernetes can automatically replace or restart containers that fail or become unresponsive.
		- **Load Balancing**: Kubernetes can distribute network traffic to ensure no single container is overwhelmed.
		
		#### 3. Managed Kubernetes Services
		- **Providers**: Google Kubernetes Engine (GKE), Amazon Elastic Kubernetes Service (EKS), Azure Kubernetes Service (AKS).
		- **Function**: These services handle the setup and maintenance of the Kubernetes control plane, including provisioning, updates, and backups.
		- **Benefits**: Simplify the management of the underlying infrastructure, allowing developers to focus on application development.
		
		### How It Works
		
		1. **Provisioning Infrastructure**:
		   - Tools automatically set up the necessary compute resources (VMs, networks, storage) to host the containers.
		   - Example: Using Terraform to create a cluster of virtual machines in a cloud environment.
		
		2. **Deploying Applications**:
		   - A Kubernetes manifest file (YAML) describes the desired state of the application (e.g., number of replicas, container images, resource limits).
		   - Kubernetes reads this file and automatically deploys the specified number of containers to the cluster.
		
		3. **Configuration Management**:
		   - Kubernetes ensures the application configuration is consistent across deployments using ConfigMaps and Secrets for managing configuration data.
		   - Any changes to the configuration can trigger automatic updates to the running containers.
		
		4. **Monitoring and Scaling**:
		   - Kubernetes continuously monitors the health and performance of containers.
		   - If a container fails, Kubernetes restarts it automatically.
		   - If traffic increases, Kubernetes scales out by adding more container instances.
		
		### Example Scenario
		
		Imagine a web application that needs to handle varying amounts of traffic:
		
		1. **Setup**:
		   - Use Terraform to provision a Kubernetes cluster in a cloud provider.
		   - The cluster includes VMs, networking, and storage.
		
		2. **Deployment**:
		   - Create a Kubernetes deployment file for the web application.
		   - Kubernetes automatically deploys the application across the cluster.
		
		3. **Scaling**:
		   - Traffic increases during peak hours.
		   - Kubernetes detects the increased load and automatically starts more container instances.
		
		4. **Maintenance**:
		   - A container instance crashes.
		   - Kubernetes detects the failure and automatically restarts the container.
		
		This automation simplifies the management of complex infrastructures and ensures that applications are always running optimally, adapting to changes in load and recovering from failures with minimal human intervention.

6. **Modern Era: Hybrid and Multi-Cloud Strategies**
   - Companies use a mix of on-premises, colocation, cloud, and edge computing.
   - Hybrid cloud solutions integrate on-premises infrastructure with public and private clouds.
   - Multi-cloud strategies involve using multiple cloud providers to avoid vendor lock-in and improve reliability.

[[Google-Cloud-DevOps-learning-path/02/Introducing Google Cloud/Pasted image 20240602092729.png]]


- **1990s**: **Colocation** – Renting space in third-party data centers.
- **2000s**: **Virtualized Data Centers** – Running multiple virtual servers on a single physical server; rise of cloud computing.
- **2010s-2020s**: **Container-Based Architecture** – Adoption of containers and Kubernetes for efficient, scalable, and portable application deployment.


