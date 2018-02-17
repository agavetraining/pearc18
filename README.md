## Abstract (250 word max)

As science becomes increasingly digital, researchers face new challenges and opportunities to analyze, share, and understand large volumes of data more effectively. Gateways are at the forefront of this challenge, and the Agave Platform has been at the forefront of the gateway movement. Over the last 6 years, the authors have been working to develop this Science-as-a-Service platform, making it possible for users to go from the desktop, to their local data center, to the cloud.
But Agave isn’t simply a tool for building web portals, it is, first and foremost, a sophisticated tool chain that enables developers to run code, manage data, collaborate meaningfully, and integrate with the world around them. As such, it is versatile and adaptable to new environments and interfaces.

This tutorial will present a cohesive 





## Summarize the proposed topic.

Science Gateways provide web-based methods of accessing collection of applications, data services, and tools that enable domain scientists who are not familiar with computers to make use of computational science. Agave provides a collection of these data services and tools in a form that can easily wrap around existing, traditional applications and HPC systems and transform them into a usable gateway.
In addition, over the last four years, the popularity of container technologies such as Docker, Singularity, and Shifter resulted in their adoption within traditional HPC data centers. While not yet the dominant workload within many of the major centers, the portability of containerized applications has led to an explosion in the availability of bespoke and custom built codes alike.
This containerized approach to computational science has enabled contributions by hundreds of new developers by bringing scalable, heterogeneous HPC to the web. It has empowered existing command line users by allowing them to commoditize their existing codes and pipelines as reproducible building blocks, and it has lowered the barrier to HPC for thousands more end users by giving them flexibility in how they interact with science and computation. This tutorial introduces these concepts to a new audience.


## Describe the proposed organizational format.

* Overview and introductions: Introduce instructors and learners. Lay out learning objectives for the morning session. Present an overview of containers and Science-as-a-Service APIs (Presentation and Discussion; 25 minutes)
* Jupyter, Sandbox, and Logging In: Connect participant laptops to on-line resources: (Hands-on; 20 minutes)
* Code, Build, and Test: Participants will build, commit, and publish a sample MPI application code, FUNWAVE using their sandbox tutorial environment. (Hands-on; 15 min)
* Hands on with Agave: Short primer on the Agave Platform using the Agave CLI and SDK. (Hands-on; 30 min)
* Short break
* Docker and Singularity: Participants will build Docker and Singularity images of the FUNWAVE code and run them on HPC, HTC, and cloud resources spanning XSEDE and the Open Science Grid. They will look at code performance between their local machine, the cloud, running in a container on HPC hardware, and running without a container on HPC hardware. We will discuss the pros and cons of containers and different container technologies. (40 minutes)
* Automation and Benchmarking: Participants will create an automated pipeline to build, test, benchmark and publish their application with the Agave Platform. They will learn best practices around source code control, metadata management, container labeling, tagging, naming, and versioning. We will discuss the pros and cons of alternative approaches using cyberinfrasturcture and resources commonly available at national and campus datacenters, as well as the major commercial clouds. (Hands-on: 30 min)
* Packaging, Publishing, and Portability: Participants will publish and share their code, data, images, and systems through the Agave Platform. They will then run a basic parameter sweep mixing and matching Docker, Singularity, and native versions of the application running across HPC, HTC, and cloud systems from their training notebook. We will discuss the challenges and advantages of scaling this approach across hybrid cloud environments and special considerations for gateway developers. (Hands-on: 20 min)


## Who is the intended audience?

We are targeting researchers who have struggled to take full advantage of the diversity of HPC, HTC, cloud, container, and storage resources for their digital science. Developers new to adopting and scaling heterogeneous compute infrastructures, container technologies, federated identity and access management, and Agave will also find the material extremely beneficial. Practitioners responsible for running HPC resources will be interested in using the tools we demonstrate to deploy new software tools and improve the accessibility to non-traditional HPC re- searchers.


## Are there any special technical requirements (A/V, network, power etc.)?

Projector, high speed wifi connection, and power for each attendee.
