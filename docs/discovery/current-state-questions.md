# **Current State Questions**

### Infrastructure:

1. What container orchestration platform are you currently using?
2. Are you currently using any container registry?
3. Where is your physical infrastructure geographically located?
4. What is your current underlying infrastructure for containerized workloads?
5. Are you currently using any monitoring and visualization tools for containers and clusters?
6. Is any portion of your current physical infrastructure is being supported or hosted by a 3rd party

### Security

1. Are you currently using any security context constraints and network policies?
2. Are you currently using any automated security controls and compliance checks?
3. What security solution are you currently using for vulnerability scanning and runtime protection?
4. What method(s) of access control (RBAC, MAC, ABAC, ACL) do you currently implement?
5. How are you currently managing your SSL certificates?
6. Are there additional security concerns around access currently implemented?
7. Given your current security posture, how does your organization align with industry best practices?

### SRE considerations

1. Are you currently using any operator to automate and manage the lifecycle of applications running on clusters?
2. Are you currently using any automatic rollouts and rollbacks?
3. Are you currently using any event router to collect and analyze events from clusters?
4. Are you currently using any tool to manage and control resources in multiple clouds?
5. What means/tool(s) are you currently using any automation platform for the deployment and management of containerized environments?
6. Do you have a comprehensive list of all applications and their dependencies
7. What mechanisms do you have in place to account for potential traffic spikes during migrations and updates?

### Applications

1. What percentage of your internal and external applications are containerized?
2. Can you provide information for Health Checks?
3. Can you provide information on historical resource utilization?
4. Can you provide information for historical ingress/egress?
5. Are these using any form of sidecar container?
6. Where are your container images stored? Is this consistent throughout your organization?
7. What type of base image are currently utilizing? Custom/Public
8. Are the applications exposed externally, internally, or both?
9. What load balancers, if any are you currently using?
10. What proxies such as NGINX/Envoy/etc are you using?
11. Are you using a manual method or a configuration management tool for deployment?
12. How many Secrets/Configmaps are there?
14. Do these applications use any Volume Mounts to access static files?
13. Are any applications CPU or Memory intensive?
15. How much storage is currently provisioned per cluster?
16. What is your preferred container orchestration? Are there many in use in your organization?
17. Are you currently using any kind of Service Mesh?
18. Are you using any cluster-based data services to hold static data?
19. Of the containerized applications, how many are Stateful Sets, Replicasets, DaemonSets, Jobs, or CronJobs?
20. What are the sizes of your Node Pools (prod/non-prod)?
21. What is the release (versions) of Kubernetes you are currently running?
22. What container runtime are you using (containerd, CRI-O, etc.)?
23. Does any application require a GPU/TPU?
24. Do you want to utilize usage metering to monitor cluster namespace/label/attribute usage?


