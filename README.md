# ci-cd-projects

* Creating repo for each ci-cd projects will end up in lot of repos

* So, will create repo in my secondary account github.com/sivakumar-j-secondary-ac and document here

### 1.[simple-devops-1](https://github.com/sivakumar-j-secondary-ac/15.0.1.0.devops_cicd_webpage_1)
 
  * **Objective**
      * Create a docker build from web application and push to docker hub
      * Pull it in another node and run it
      
  * **Tools used** - Ansible,Docker

### 2.Train schedule application

   * [Phase 1-Legacy-Deployment](https://github.com/sivakumar-j-secondary-ac/15.1.1.0.ci-cd-train-schedule-phase-1)
   
     * **Objective** 
         * Create a build from nodejs code,deploy in staging and production server( need auth)
         
     * **Tools used** - Gradle,Jenkins
     
   * [Phase 2-With-Docker](https://github.com/sivakumar-j-secondary-ac/15.1.2.0-ci-cd-train-schedule-phase-2)
   
     * **Objective** 
         * Create a build from nodejs code,dockerize it and then pull run it, in  production server( need auth)
         
     * **Tools used** - Docker,Gradle,Jenkins

   * [Phase 3-With-kubernetes](https://github.com/sivakumar-j-secondary-ac/15.1.3.0-ci-cd-train-schedule-phase-3)
   
     * **Objective** 
         * Create a build from nodejs code,dockerize it,create a kubernetes deployment for it and deploy in production( need auth)
         
     * **Tools used** - Docker&Dockerhub,Gradle,Jenkins,Kubernetes
     
   
   * [Phase 4-Monitors and Alerts](https://github.com/sivakumar-j-secondary-ac/15.1.4.0--ci-cd-train-schedule-phase-4)
   
     * **Objective** 
         * Since the application is up&running, we need to monitor the infra and application and get freq alerts
         
     * **Tools used** - helm charts, prometheus & grafana
     
   * [Phase 5-Self-Healing-feature](https://github.com/sivakumar-j-secondary-ac/15.1.5.0--ci-cd-train-schedule-phase-5)
   
     * **Objective** 
         * If the applications crashes, application container needs be restarted instantly. 
         
     * **Tools used** - no new tools. Just added breakpoints and livenessProbe added in k8 deployment     
     
     
  
