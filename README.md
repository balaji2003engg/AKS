Create the AKS cluster 

      https://k21academy.com/microsoft-azure/az-104/create-aks-cluster-step-by-step-procedure/

**Connect to the Azure Kubernetes Cluster**
There are two ways to connect the AKS cluster:
I) Using Cloud Shell
II) Using Azure CLI

I am going to cover how do we connect using Cloud Shell. We can see the option on top of our screen (marked red in the below image).

Cloud shell
Step 1: Run the following command, on the Azure bash shell:

   
  $ az aks get-credentials --resource-groups <name of resource group> --name <name of cluster

Cloud shell
Check Out: Best Kubernetes Monitoring Tools. Click here

Step 2: To get the Nodes running in our cluster, run the following command, and you will see all the nodes in your AKS cluster.

   
  $ kubectl get nodes
