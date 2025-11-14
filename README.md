# Azure-Concepts

# Azure Service Models

IaaS, PaaS, and SaaS are  three models of cloud computing services. IaaS (Infrastructure as a Service) provides virtualized computing resources like servers and storage over the internet. PaaS (Platform as a Service) offers a platform for developers to build, run, and manage applications without managing the underlying infrastructure. SaaS (Software as a Service) delivers complete software applications over the internet, which users access on a subscription basis.

**IaaS (Infrastructure as a Service)**

-   **What it is:** Provides access to fundamental computing resources like virtual machines, networks, and storage.
-  **What you manage:** The operating system, middleware, and applications.
-   **What the provider manages:** The underlying hardware, network, and physical data centers.
-   **Use case:** Companies that need a high degree of control over their infrastructure, similar to managing their own data center but without the physical hardware costs.
-   **Example:** Amazon Web Services (AWS), Microsoft Azure, Google Cloud (for core infrastructure services).
 
**PaaS (Platform as a Service)**

-   **What it is:** Provides a platform for developing, running, and managing applications
-   **What you manage:** The applications and data.
-   **What the provider manages:** The operating systems, middleware, and hardware infrastructure.
-   **Use case:** Developers who want to build and deploy applications without worrying about server management or OS updates.
-   **Example:** Google App Engine.

**SaaS (Software as a Service)**

-   **What it is:** Delivers software applications over the internet on a subscription basis.
-   **What you manage:** Just the usage of the application.
-   **What the provider manages:** Everything, including the infrastructure, platform, and application.
-   **Use case:** End-users and businesses that need to access a software application without the need for installation, management, or upgrades.
-   **Example:** Dropbox, HubSpot, DocuSign.


 ## Security Share Responsibility Model
 
The shared responsibility model  defines a cloud security partnership where the cloud provider is responsible for the security  **of**  the cloud, and the customer is responsible for security  **in**  the cloud. The division of labor shifts as you move from IaaS to PaaS to SaaS, with the customer having the most responsibility in IaaS and the provider


<img width="582" height="240" alt="image" src="https://github.com/user-attachments/assets/bc03690c-7d3d-42ff-9026-8ad75d39aac4" />

**IaaS**

-   **Provider:**  Secures the physical infrastructure like the hardware and network.
-   **Customer:**  Is responsible for everything they build on top of it, including the operating system, applications, middleware, and data.

**PaaS**

-   **Provider:**  Manages the infrastructure, OS, and runtime environment.
-   **Customer:**  Secures the applications they build, the data within them, and user access.

**SaaS**

-   **Provider:**  Secures the application and the underlying infrastructure.
-   **Customer:**  Is responsible for managing user access and ensuring data protection and account security.
-   
