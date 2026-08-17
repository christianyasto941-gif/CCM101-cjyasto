# Client Recommendations

## Client A – Startup Company

**Recommended platform: AWS**

AWS is a suitable choice for the startup because it provides a broad set of services that can support a mobile application as it grows. The startup can begin with a relatively small infrastructure footprint and scale resources as demand increases. AWS also provides services that can support application hosting, storage, databases, and networking without requiring the startup to build physical infrastructure.

**Possible services:**
- Amazon EC2
- Amazon S3
- Amazon RDS
- Amazon VPC

## Client B – University

**Recommended platform: Microsoft Azure**

Azure is the strongest fit because the university already uses Windows Server, Microsoft 365, and Active Directory. Azure can provide a familiar Microsoft-centered environment and support hybrid connections between on-premises systems and cloud resources. This can make migration and identity management easier to organize.

**Possible services:**
- Azure Virtual Machines
- Microsoft Entra ID
- Azure Virtual Network
- Azure SQL Database

## Client C – AI Research Company

**Recommended platform: Google Cloud**

Google Cloud is a strong recommendation because the company specializes in AI and machine learning and requires high-performance computing. Google Cloud provides AI/ML services, compute infrastructure, and specialized GPU/TPU-oriented infrastructure for demanding workloads. Its broader data and AI ecosystem can also support experimentation, model development, and deployment.

**Possible services:**
- Compute Engine
- Cloud GPUs / AI infrastructure
- Vertex AI
- Google Kubernetes Engine (GKE)

## Client D – Global E-Commerce Company

**Recommended platform: AWS**

AWS is a strong choice for a multinational e-commerce company because it provides global infrastructure and services for highly available and scalable applications. The company can distribute workloads across multiple Availability Zones and Regions and use load balancing and automatic scaling to respond to changing traffic. This architecture can help support customers in different geographic locations.

**Possible services:**
- Amazon EC2
- Elastic Load Balancing
- EC2 Auto Scaling
- Amazon S3
- Amazon RDS

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | Broad services and flexible scaling |
| Enterprise Organization | AWS | Mature enterprise service portfolio and broad infrastructure options |
| Microsoft Environment | Azure | Strong integration with Microsoft's ecosystem |
| AI / Machine Learning | Google Cloud | Strong AI/ML infrastructure and services |
| Kubernetes Deployment | Google Cloud | Google Kubernetes Engine provides a managed Kubernetes environment |
| Global Web Application | AWS | Broad global infrastructure and scalable application services |

## Important Note

These are recommendations based on the scenarios in the laboratory activity. In a real project, the final decision should also consider current pricing, required compliance, region availability, existing contracts, technical skills, latency, and workload-specific requirements.
