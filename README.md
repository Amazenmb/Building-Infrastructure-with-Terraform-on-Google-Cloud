# Building-Infrastructure-with-Terraform-on-Google-Cloud
Note: This is done as a part of Quick lab on GCP and for learning purposes only.

**What is Terraform?**

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Configuration files describe to Terraform the components needed to run a single application or your entire data center. Terraform generates an execution plan describing what it will do to reach the desired state, and then executes it to build the described infrastructure. As the configuration changes, Terraform can determine what changed and create incremental execution plans that can be applied.
The infrastructure Terraform can manage includes both low-level components such as compute instances, storage, and networking, and high-level components such as DNS entries and SaaS features.


**Key features**


**Infrastructure as code:**

Infrastructure is described using a high-level configuration syntax. This allows a blueprint of your data center to be versioned and treated as you would any other code. Additionally, infrastructure can be shared and re-used.

**Execution plans:**

Terraform has a planning step in which it generates an execution plan. The execution plan shows what Terraform will do when you execute the apply command. This lets you avoid any surprises when Terraform manipulates infrastructure.

**Resource graph:**

Terraform builds a graph of all your resources and parallelizes the creation and modification of any non-dependent resources. Because of this, Terraform builds infrastructure as efficiently as possible, and operators get insight into dependencies in their infrastructure. When performing operations, Terraform creates a dependency graph to determine the correct order of operations. In more complicated cases with multiple resources, Terraform will perform operations in parallel when it's safe to do so.

**Change automation:**

Complex changesets can be applied to your infrastructure with minimal human interaction. With the previously mentioned execution plan and resource graph, you know exactly what Terraform will change and in what order, which helps you avoid many possible human errors.

----------------------------------------------------------------

**Concepts tested in this Quick lab**
1. Import existing infrastructure into your Terraform configuration.
2. Build and reference your own Terraform modules.
3. Add a remote backend to your configuration.
4. Use and implement a module from the Terraform Registry.
5. Re-provision, destroy, and update infrastructure.
6. Test connectivity between the resources you've created.
---------------------------------------------------------------

**Scenario**
You are tasked with creating infrastructure in a quick and efficient manner and generating a mechanism to keep track of it for future reference and changes. You have been directed to use Terraform to complete the project. For this project, you will use Terraform to create, deploy, and keep track of infrastructure on the startup's preferred provider, Google Cloud. You will also need to import some mismanaged instances into your configuration and fix them.

---------------------------------------------------------------

**Tasks**
1. Create the configuration files
2. Import existing infrastructure of computing instance and network
3. Configure a remote backend
4. Modify and update infrastructure
5. Destroy resources
6. Use a module from the registry
7. Configure a firewall

-----------------------------------------------------------------

**Execution**
Please check the **Steps** file.
.








