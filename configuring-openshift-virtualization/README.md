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
![2.png](/assets/2.png)
* Choose the namespaces recommended which is ```openshift-cnv```. 
* Click "Install" again to confirm.
6. Monitor Installation Progress:
* After installation, navigate to the Installed Operators page (Operators > Installed Operators).
* Check the status of the OpenShift Virtualization Operator. It should show "Succeeded" when the installation is complete.
![3.png](/assets/3.png)
8. Create a hyper-converged instance 
* Go to installed Operator and click on OpenShift Virtualization 
* Select ```OpenShift Virtualization Deployment``` tab, and click on ```Create HyperConverged``` blue button 
![4.png](/assets/4.png)
* click on create
9. Check the progress 
* Click on ```Workload``` --> ```Pods``` and check the status of all pods, it should either be  Completed or Running
![5.png](/assets/5.png)
> The process will take around 15 minutes to provision the entire deployment.
