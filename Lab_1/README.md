# Lab 1 : Création d'un cluster AKS via le portail Azure + visualisation des ressources via le portail Azure
## Objectif:<br/>
L'objectif de ce lab est de vous faire déployer un premier cluster Azure Kubernetes Services en utilisant la console. Une fois le cluster déployé, nous naviguerons dans la console et installerons une application.<br> 
Dans la console Azure :
1. "Create a resource"
<img width='800' src='../images/Lab_1/Lab_1_0.png'/>
2. Aller dans "Containers" et cliquez dans "Create" (Kubernetes Service)
<img width='800' src='../images/Lab_1/Lab_1_1.png'/>
3. Parametrage du Cluster
<img width='800' src='../images/Lab_1/Lab_1_2.png'/>
<img width='800' src='../images/Lab_1/Lab_1_3.png'/>
<img width='800' src='../images/Lab_1/Lab_1_4.png'/>
<img width='800' src='../images/Lab_1/Lab_1_5.png'/>
- <a href="https://docs.microsoft.com/en-us/azure/aks/availability-zones#overview-of-availability-zones-for-aks-clusters">Information sur les "Avaibility zones"</a><br>
- <a href="https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.24.md" target="_blank" >Changes Log</a><br>
- <a href="https://docs.microsoft.com/fr-fr/azure/aks/supported-kubernetes-versions?tabs=azure-cli">Versions de Kubernetes prises en charge dans Azure Kubernetes Service</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/uptime-sla">API server availability</a><br>
- <a href="https://docs.microsoft.com/fr-fr/azure/aks/concepts-scale">Scale method</a><br><br><br><br>
<img width='800' src='../images/Lab_1/Lab_1_6.png'/>
- <a href="https://docs.microsoft.com/en-us/azure/aks/use-multiple-node-pools">Create and manage multiple node pools for a cluster in Azure Kubernetes Service</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/azure-disk-customer-managed-keys">Bring your own keys (BYOK) with Azure disks in Azure Kubernetes Service</a><br><br><br><br>
<img width='800' src='../images/Lab_1/Lab_1_7_1.png'/>
- <a href="https://docs.microsoft.com/en-us/azure/aks/kubernetes-service-principal?tabs=azure-cli">Use a service principal with Azure Kubernetes Service</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/use-managed-identity">Use a managed identity in Azure Kubernetes Service</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/managed-aad">AKS-managed Azure Active Directory integration</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/manage-azure-rbac">Use Azure RBAC for Kubernetes Authorization</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/azure-ad-rbac">Control access to cluster resources using Kubernetes role-based access control and Azure Active Directory identities in Azure Kubernetes Service</a><br><br><br><br>
<img width='800' src='../images/Lab_1/Lab_1_8.png'/>
- <a href="https://docs.microsoft.com/en-us/azure/aks/configure-azure-cni">Configure Azure CNI networking in Azure Kubernetes Service</a><br><br><br><br>
<img width='800' src='../images/Lab_1/Lab_1_9.png'/>
- <a href="https://docs.microsoft.com/en-us/azure/aks/load-balancer-standard">Use a public Standard Load Balancer in Azure Kubernetes Service</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/http-application-routing">HTTP application routing</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/private-clusters">Create a private Azure Kubernetes Service cluster</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/api-server-authorized-ip-ranges">Secure access to the API server using authorized IP address ranges in Azure Kubernetes Service</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/aks/use-network-policies">Secure traffic between pods using network policies in Azure Kubernetes Service</a><br><br><br><br>
<img width='800' src='../images/Lab_1/Lab_1_10.png'/>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/containers">Container insights overview</a><br>
- <a href="https://docs.microsoft.com/en-us/azure/governance/policy/concepts/policy-for-kubernetes">Understand Azure Policy for Kubernetes clusters</a><br><br><br><br>
<img width='800' src='../images/Lab_1/Lab_1_11_1.png'/>
- <a href="https://docs.microsoft.com/en-us/azure/aks/csi-secrets-store-driver">Use the Azure Key Vault Provider for Secrets Store CSI Driver in an AKS cluster</a><br><br><br><br>
<img width='800' src='../images/Lab_1/Lab_1_12.png'/>
<img width='800' src='../images/Lab_1/Lab_1_13.png'/>
<img width='800' src='../images/Lab_1/Lab_1_14.png'/>
<img width='800' src='../images/Lab_1/Lab_1_15.png'/>
4. visualisation des ressources via le portail Azure
<img width='800' src='../images/Lab_1/Lab_1_16.png'/>
<img width='800' src='../images/Lab_1/Lab_1_17.png'/>
Kubernetes resources
<img width='800' src='../images/Lab_1/Lab_1_18.png'/>
<img width='800' src='../images/Lab_1/Lab_1_19.png'/>
<img width='800' src='../images/Lab_1/Lab_1_20.png'/>
<img width='800' src='../images/Lab_1/Lab_1_21.png'/>
<img width='800' src='../images/Lab_1/Lab_1_22.png'/>
<img width='800' src='../images/Lab_1/Lab_1_23.png'/>
<img width='800' src='../images/Lab_1/Lab_1_24.png'/>
<img width='800' src='../images/Lab_1/Lab_1_25.png'/>
<img width='800' src='../images/Lab_1/Lab_1_26.png'/>
<img width='800' src='../images/Lab_1/Lab_1_27.png'/>
Settings
<img width='800' src='../images/Lab_1/Lab_1_28.png'/>
<img width='800' src='../images/Lab_1/Lab_1_29.png'/>
<img width='800' src='../images/Lab_1/Lab_1_30.png'/>
<img width='800' src='../images/Lab_1/Lab_1_31.png'/>
<img width='800' src='../images/Lab_1/Lab_1_32.png'/>
<img width='800' src='../images/Lab_1/Lab_1_33.png'/>
Ressources du cluster AKS
<img width='800' src='../images/Lab_1/Lab_1_34.png'/>
<img width='800' src='../images/Lab_1/Lab_1_35.png'/>
Test du cluster AKS
<img width='800' src='../images/Lab_1/Lab_1_36.png'/>
<img width='800' src='../images/Lab_1/Lab_1_36_bis.png'/>
<img width='800' src='../images/Lab_1/Lab_1_37.png'/>
<img width='800' src='../images/Lab_1/Lab_1_38.png'/>
<img width='800' src='../images/Lab_1/Lab_1_39.png'/>
<img width='800' src='../images/Lab_1/Lab_1_40.png'/>
<img width='800' src='../images/Lab_1/Lab_1_41.png'/>
<img width='800' src='../images/Lab_1/Lab_1_42.png'/>
<img width='800' src='../images/Lab_1/Lab_1_43.png'/>
<img width='800' src='../images/Lab_1/Lab_1_44.png'/>
<img width='800' src='../images/Lab_1/Lab_1_45.png'/>
<img width='800' src='../images/Lab_1/Lab_1_46.png'/>
Dans votre navigateur allez sur "l'External IP"

5. Supprimer le "Resource group" du cluster AKS<br>
Fin du lab
