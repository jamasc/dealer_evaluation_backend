# coding-project-template

command to deploy app on ibm cloud engine cli:

ibmcloud ce application create --name dealerdetails --image us.icr.io/${SN_ICR_NAMESPACE}/dealerdetails --registry-secret icr-secret --port 8080 --build-context-dir dealer_details --build-source https://github.com/ibm-developer-skills-network/dealer_evaluation_backend.git

ibmcloud ce application create 
  --name dealerdetails 
  --image us.icr.io/${SN_ICR_NAMESPACE}/dealerdetails 
  --registry-secret icr-secret 
  --port 8080 
  --build-context-dir dealer_details 
  --build-source https://github.com/ibm-developer-skills-network/dealer_evaluation_backend.git
