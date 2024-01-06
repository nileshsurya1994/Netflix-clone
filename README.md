<h1 align="center">Project Overview</h1>

![Project Overview](https://github.com/shubnimkar/Netflix-clone/blob/master/Project%20Overviewt.png)


<h1 align="center"> Objective </h1>

As we set out to deploy our Netflix clone, simplicity meets effectiveness in our tool choices. Jenkins will handle our deployment pipeline, Kubernetes ensures smooth application deployment, and for monitoring Jenkins, we’ve got Grafana, Prometheus, and Node Exporter. Adding an extra layer of security, we’re embracing DevSecOps tools.



<h1 align="center"> Technology Stack Used in deployment </h1>

* Version Control
  - Github
    
* Monitoring
  - Prometheus
  - Grafana
  
* Code Analysis
  - Sonarqube

* Deployment
  - Docker
  - Kubernetes

* Security
  - Trivy Scan
  - OWASP Dependency Scan


<h1 align="center"> Steps Involving  </h1>


Step 1 — Launch an Ubuntu t2.large Instance 

Step 2 — Install Jenkins, Docker and Trivy. Create a Sonarqube Container using Docker. 

Step 3 — Create a TMDB API Key. 

Step 4 — Install Prometheus and Grafana On new Server. 

Step 5 — Install the Prometheus Plugin and Integrate it with the Prometheus server. 

Step 6 — Email Integration With Jenkins and Plugin setup. 

Step 7 — Install Plugins like JDK, Sonarqube Scanner, Nodejs, and OWASP Dependency Check. 

Step 8 — Create a Pipeline Project in Jenkins 

Step 9 — Install OWASP Dependency Check Plugins 

Step 10 — Docker Image Build and Push 

Step 11 — Deploy the image using Docker

Step 12 — Kubernetes master and slave setup on Ubuntu.

Step 13 — Access the Netflix app on the Browser. 

Step 14 — Terminate the AWS EC2 Instances.


<h1 align="center"> Prerequisites   </h1>

- Create an account if you don't have on [TMDB](https://www.themoviedb.org/).
  Because I use its free API to consume movie/tv data.
- And then follow the [documentation](https://developers.themoviedb.org/3/getting-started/introduction) to create API Key
- Finally, if you use v3 of TMDB API, create a file named `.env`, and copy and paste the content of `.env.example`.
  And then paste the API Key you just created.








<h1 align="center"> The Application </h1>



<div align="center">
  <a href="http://netflix-clone-with-tmdb-using-react-mui.vercel.app/">
    <img src="./public/assets/netflix-logo.png" alt="Logo" width="100" height="32">
  </a>



  <p align="center">
    <a href="https://netflix-clone-react-typescript.vercel.app/">View Application Demo</a>
  </p>
</div>

<br />

<div align="center">
  <img src="./public/assets/home-page.png" alt="Logo" width="100%" height="100%">
  <p align="center">Home Page</p>
  <img src="./public/assets/mini-portal.png" alt="Logo" width="100%" height="100%">
  <p align="center">Mini Portal</p>
  <img src="./public/assets/detail-modal.png" alt="Logo" width="100%" height="100%">
  <p align="center">Detail Modal</p>
  <img src="./public/assets/grid-genre.png" alt="Logo" width="100%" height="100%">
  <p align="center">Grid Genre Page</p>
  <img src="./public/assets/watch.png" alt="Logo" width="100%" height="100%">
  



