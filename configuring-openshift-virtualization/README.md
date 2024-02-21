# Installing and configuring OpenShift Virtualization  

1. Prepare your environment:
* Ensure you have a compatible OpenShift cluster up and running. Refer to the OpenShift documentation for cluster installation instructions.
* Make sure your cluster meets the prerequisites for installing OpenShift Virtualization, including sufficient resources and compatible versions.
2. Access OpenShift Container Platform:
* Log in to the OpenShift Container Platform web console with appropriate credentials.
3. Navigate to Operators Hub:
* In the web console, navigate to the Operators Hub by selecting Operators > Operator Hub from the left sidebar menu.
4. Search for OpenShift Virtualization:
* In the Operator Hub, use the search bar to find "OpenShift Virtualization."
![1.png](/assets/1.png)
5. Install OpenShift Virtualization:
* Click on the OpenShift Virtualization tile to access its details.
* Click the "Install" button.
* Choose the appropriate installation mode (e.g., A specific namespace on the cluster).
* Click "Install" again to confirm.
6. Monitor Installation Progress:
* After installation, navigate to the Installed Operators page (Operators > Installed Operators).
* Check the status of the OpenShift Virtualization Operator. It should show "Succeeded" when the installation is complete.