# Deploy Nessus as a Docker Image
You can deploy a managed Nessus scanner or an instance of Nessus Professional as a Docker image to run on a container. The base image is a CentOS 8 instance of Nessus. You can configure the Nessus instance with environment variables to automatically configure the image with the settings you configure.

Tenable does not recommend deploying Nessus in a Docker container that shares a network interface controller (NIC) with another Docker container.
