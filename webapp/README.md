#  Quickstart Guide 

This is my simple dockerized web app with database in kubernetes using helm!

  to deploy web app locally run commands:
 
     $ git clone https://github.com/nick1846/helm-web.git
     $ helm install <deploy_name> <helm_path>  (need to download dependency chart first)

  to download a dependency run commands:
 
     $ helm repo add https://nick1846.github.io/helm-postgres
     $ helm dependency update  (in my-web/)
 
  to see web app in the browser add DNS record to etc/hosts
  to see DNS name run:
 
     $ kubectl get ingress
 
 Happy Helming!
 

