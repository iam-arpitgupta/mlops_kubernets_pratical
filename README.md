# MLOps Kubernetes Practical

This project demonstrates the use of Minikube for Kubernetes services and Postman for monitoring real-time APIs.

## Prerequisites

- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [Postman](https://www.postman.com/downloads/)

## Setup

### Minikube

1. **Start Minikube:**
    ```sh
    minikube start
    ```

2. **Deploy Kubernetes Services:**
    ```sh
    kubectl apply -f your-kubernetes-config.yaml
    ```

3. **Check the status of your services:**
    ```sh
    kubectl get services
    ```

### Postman

1. **Import your API collection:**
    - Open Postman and import your API collection.

2. **Monitor Real-time API:**
    - Use the Postman interface to send requests to your Kubernetes services and monitor the responses in real-time.

## Usage

1. **Access your application:**
    - Use the Minikube IP and the service port to access your application.
    ```sh
    minikube service your-service-name
    ```

2. **Send API requests via Postman:**
    - Use Postman to send requests to your application's endpoints and observe the real-time responses.

## Cleanup

1. **Stop Minikube:**
    ```sh
    minikube stop
    ```

2. **Delete Minikube cluster:**
    ```sh
    minikube delete
    ```

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Minikube Documentation](https://minikube.sigs.k8s.io/docs/)
- [Postman Documentation](https://learning.postman.com/docs/getting-started/introduction/)
