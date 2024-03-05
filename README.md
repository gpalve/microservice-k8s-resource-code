# Deploying Microservices on Kubernetes

## Overview

This project demonstrates the deployment of microservices on Kubernetes, utilizing various resources such as Deployments, Services, StatefulSets, ConfigMaps, and Volumes. The setup is designed for use with Minikube Kubernetes and includes essential components like Zipkin, RabbitMQ, and PostgreSQL. All the necessary definitions and creation codes are provided within this repository.

## Prerequisites

Before getting started, ensure you have the following installed:

- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

## Getting Started

1. Clone this repository:

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Deploy the microservices on Minikube Kubernetes:

    ```bash
    kubectl apply -f <directory-with-yaml-files>
    ```

3. Monitor the deployment:

    ```bash
    kubectl get pods
    ```

4. Access services:

    ```bash
    minikube service <service-name>
    ```

## Included Components

- **Zipkin:** Distributed tracing system
- **RabbitMQ:** Message broker
- **PostgreSQL:** Relational database

## Folder Structure

- `deployments/`: Kubernetes deployment configurations
- `services/`: Kubernetes service configurations
- `statefulsets/`: Kubernetes StatefulSet configurations
- `configmaps/`: Kubernetes ConfigMap configurations
- `volumes/`: Kubernetes PersistentVolumeClaim configurations

## Enjoy Deploying!

Feel free to explore the provided configurations and adapt them to your specific microservices. Happy deploying!
