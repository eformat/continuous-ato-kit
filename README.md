# Continuous ATO Kit

The Continuous ATO Kit is a reference implementation of continuous compliance automation--security checking, compliance testing, and compliance artifact maintenance--in the Continuous Integration/Continuous Deployment (CI/CD) pipeline.

![Diagram showing a build pipeline environment consisting of a Source Code Repository (GitHub) a Build Server (Jenkins), a Target Application Instance, a Security and Monitoring Server (OpenSCAP), a Compliance Server (GovReady-Q), a DevSecOps Workstation, and Production Environment.](docs/c-a-k-system-diagram-p1.png)

The example scenerio is getting and continuously monitoring an ATO (Authority To Operate) for an IT system at an agency in the federal government under the NIST RMF (Risk Management Framework).

Documentation for this project can be found in the following documents:

1. [The Need for Continuous ATO](Purpose.md) explains why it will be valuable to incorporate the Authority to Operate A&A process into an agile build pipeline.
1. [Example Build Pipeline](Pipeline.md) explains the pipeline constructed in this reference implementation, using Jenkins, a security and monitoring server running OpenSCAP and nmap, and a compliance server running GovReady-Q.
1. [Try It Using Docker Compose](TryIt.md) is a step-by-step tutorial to running the example build pipeline on your local workstation using docker-compose.
1. [Enterprise Deployment Guide](Enterprise.md) is a step-by-step tutorial for deploying the pipeline on separate, virtualized servers in a data center.
