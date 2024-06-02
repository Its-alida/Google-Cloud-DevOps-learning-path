The move to virtualized data centers introduced customers to two new types of offerings: **infrastructure as a service**, commonly referred to as IaaS, and **platform as a service**, or PaaS.

Cloud computing provides various service models that cater to different needs. Two of the most commonly discussed models are Infrastructure as a Service (IaaS) and Platform as a Service (PaaS).

Certainly, here's the comparison table with examples focusing only on Google Cloud Platform (GCP):

| ** Feature**    | ** Infrastructure as a Service (IaaS)**                             | **Platform as a Service (PaaS)**                                       |
| --------------- | ------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| **Definition**  | Provides virtualized computing resources over the internet.         | Offers a platform for developing, running, and managing applications.  |
| **Control**     | More control over infrastructure components (OS, middleware, etc.). | Less control; focuses on application development.                      |
| **Flexibility** | High; allows customization of OS, configurations, and applications. | Limited; offers pre-configured environments and tools.                 |
| **Scalability** | Users manually scale infrastructure resources based on demand.      | Automatically handles scaling, load balancing, and other tasks.        |
| **Ease of Use** | Requires more technical expertise to set up and manage.             | Easier to use, with pre-configured environments and tools.             |
| **Cost**        | Pay-as-you-go pricing based on resource usage.                      | Predictable pricing based on application usage.                        |
| **Examples**    | Hosting custom enterprise applications on GCP Compute Engine.       | Developing and deploying web applications on GCP App Engine.           |
| **Use Cases**   | Custom environments, legacy applications, development/testing.      | Rapid development, scalable applications, microservices architectures. |

![[Pasted image 20240602094449.png]]![[Pasted image 20240602094510.png]]
<img src="https://github.com/Its-alida/Google-Cloud-DevOps-learning-path/blob/main/Pasted%20image%2020240602094449.png">

## As cloud computing has evolved, the momentum has shifted toward managed infrastructure and managed services :

1. Initially, cloud computing focused on providing infrastructure resources like virtual machines, storage, and networking (IaaS). Users had to manage and maintain these resources themselves.

2. Over time, cloud providers introduced higher-level services, such as databases, messaging queues, and machine learning tools (PaaS and SaaS). These services abstracted away the complexities of managing underlying infrastructure, allowing users to focus more on application development and business outcomes.

### Shift Towards Managed Services :

1. **Managed Infrastructure**: Cloud providers now offer managed versions of traditional infrastructure components like databases, storage, and networking. These services handle tasks such as provisioning, scaling, patching, and monitoring, reducing the burden on users.

2. **Managed Services**: Beyond infrastructure, cloud providers offer managed services that cater to specific use cases and industry needs. These services, such as AI/ML, IoT, and analytics, come with built-in functionality and pre-configured settings, enabling users to leverage advanced capabilities without the need for specialized expertise.

> [!NOTE]
> - Leveraging managed resources and services allows companies to concentrate more on their business goals and spend less time and money on creating and maintaining their technical infrastructure.
> - It allows companies to deliver products and services to their customers more quickly and reliably.


# Server-less computing 

- represents the next step in the progression of cloud computing. 
- It enables developers to focus solely on writing code without worrying about server configuration or infrastructure management. 
- With serverless technologies like Google Cloud Functions, developers can deploy event-driven code that scales automatically and is billed based on usage. 
- Similarly, services like Google Cloud Run allow users to deploy containerized microservices applications in a fully managed environment, eliminating the need for manual infrastructure management. 
- This shift to serverless computing simplifies development, increases agility, and reduces operational overhead for businesses.
# Software as a service, SaaS 

- SaaS provides the entire application stack, delivering an entire cloud-based
application that customers can access and use.
- Software as a Service applications are not installed on your local computer.
- Instead, they run in the cloud as a service and are consumed directly over the
internet by end users

![[Pasted image 20240602095639.png]]
<img src="https://github.com/Its-alida/Google-Cloud-DevOps-learning-path/blob/main/Pasted%20image%2020240602095639.png">

Popular Google applications such as Gmail, Docs, and Drive, that are a part of Google
Workspace, are all examples of SaaS.


# Extra references

- https://www.capgemini.com/insights/expert-perspectives/optimizing-your-cloud-roi-with-serverless-architecture/
	![[Pasted image 20240602100248.png]]
	<img src="https://github.com/Its-alida/Google-Cloud-DevOps-learning-path/blob/main/Pasted%20image%2020240602100248.png">
- An example of serverless computing is Amazon Lambda -  Function as a Service (FaaS)
	- ![[Pasted image 20240602100532.png]]
	- https://www.datadoghq.com/knowledge-center/serverless-architecture/
	
- https://kinsta.com/blog/function-as-a-service/
- CLOUD-NATIVE MEETS HYBRID CLOUD: A STRATEGY GUIDE - RedHat e book https://www.redhat.com/en/engage/cloud-native-meets-hybrid-cloud-strategy-guide?intcmp=701f2000001OMH6AAO
![[Pasted image 20240602101907.png]]

