# Heading

---

##  Sub Heading

1.  Item 1
2.  Item 2
3.  Item 3
   
*this text is italic*

**This is blod text**

[Google_Verif_link](https://www.google.com)

#   Kubernetes basic command:

1.  kubernetes get pods 
* To Check default namespace pods
2.  kubernetes get pods --namespace <namespace_name_type_here>
* To Check Specific  Namespace pods 
3. Kubernetes get pods -A
* To Check All Namespace Pods
  


#   Kubernetes find description level  resources :

1.  kubectl describe pods <pods_name>  -n <namespace_name>
*   To check pods indepth details for using this command
2.  kubectl describe nodes <node_name>
*   To check nodes indepth details for using this command
3   kubectl describe deployment <deployment_name>  -n <namespace_name>
*   To check deployment details 