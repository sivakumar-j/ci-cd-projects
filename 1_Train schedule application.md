# ci-cd-projects-1

### Train schedule application

   * [Phase 1-Legacy-Deployment](https://github.com/sivakumar-j-secondary-ac/15.1.1.0.ci-cd-train-schedule-legacy-deployment)
   
     * **Objective** 
         * Create a build from nodejs code,deploy in staging and production server( need auth)
         
     * **Tools used** - Gradle,Jenkins
     
   * [Phase 2-With-Docker](https://github.com/sivakumar-j-secondary-ac/15.1.2.0-ci-cd-train-schedule-with-docker)
   
     * **Objective** 
         * Create a build from nodejs code,dockerize it and then pull run it, in  production server( need auth)
         
     * **Tools used** - Docker,Gradle,Jenkins

   * [Phase 3-With-kubernetes](https://github.com/sivakumar-j-secondary-ac/15.1.3.0-ci-cd-train-schedule-with-k8)
   
     * **Objective** 
         * Create a build from nodejs code,dockerize it,create a kubernetes deployment for it and deploy in production( need auth)
         
     * **Tools used** - Docker&Dockerhub,Gradle,Jenkins,Kubernetes
     
   
   * [Phase 4-Monitors and Alerts](https://github.com/sivakumar-j-secondary-ac/15.1.4.0--ci-cd-train-schedule-monitors-and-alerts)
   
     * **Objective** 
         * Since the application is up&running, we need to monitor the infra and application and get freq alerts
         
     * **Tools used** - helm charts, prometheus & grafana
     
   * [Phase 5-Self-Healing-feature](https://github.com/sivakumar-j-secondary-ac/15.1.5.0--ci-cd-train-schedule-self-heal)
   
     * **Objective** 
         * If the applications crashes, application container needs be restarted instantly. 
         
     * **Tools used** - no new tools. Just added breakpoints and livenessProbe added in k8 deployment     


   * [Phase 6-Autoscaling](https://github.com/sivakumar-j-secondary-ac/15.1.6.0--ci-cd-train-schedule-auto-scale)
   
     * **Objective** 
         * Increase/Decrease pods according to the cpu utilization
         
     * **Tools used** - no new tools. Just added autoscaling in k8 deployment     
     
   * [Phase 7-canary deployment](https://github.com/sivakumar-j-secondary-ac/15.1.7.0--ci-cd-train-schedule-canary-deployment)
   
     * **Objective** 
         * For real time testing of application, perform a canary testing by canary deployment
         
     * **Tools used** - no new tools. Just added autoscaling in k8 deployment 
   * [Phase 8-Auto deployment](https://github.com/sivakumar-j-secondary-ac/15.1.8.0--ci-cd-train-schedule-auto-deploy)
   
     * **Objective** 
         * No intervention deployment. New message needs to be added to home page
         
     * **Tools used** - Nothing new 
