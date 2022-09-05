# 
#     This repo holds yaml file(s) used by ARGO CD Pipelines for deploying Kubernetes Infrastructure
#
##    By: Mamun Rashid
###   Connect with me on Linkedin:  https://www.linkedin.com/in/mamunrashid/
#

#

##  HOW TO USE THIS REPO
###
### When you are setting up an ARGO CD "app", use URL of this repo and nginx_deployment as the path
      For example:
        argocd app create foobar-nginx --repo https://github.com/mamun001/argocd_playground.git --path nginx_deployment --dest-server https://kubernetes.default.svc --dest-namespace default
#

#


