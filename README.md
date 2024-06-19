## Introduction:
* 👋 Hey everyone! Welcome back to my GitHub.
* 🎥 This repo shows you how to install the ELK Stack using Docker Compose.
* 📊 ELK Stack stands for Elasticsearch, Logstash, and Kibana, and it's great for data analysis and visualization.

## Prerequisites:
* 💻 A computer with Docker and Docker Compose installed.
* 📁 Basic understanding of Docker and command-line interface.

## Steps:
**1. Create a Docker Compose file:**
    * Open your terminal and create a new directory for your ELK Stack setup.
    * Inside the directory, create a file named docker-compose.yml 📝.

**2. Define services:**
    * Open docker-compose.yml and define the services for Elasticsearch, Logstash, and Kibana.
    * Use the following configuration:

**3. Get the codes/scripts from this repo.**   

**4. Create Logstash pipeline:**
    * Create a directory named logstash-pipeline and inside it, create a file named logstash.conf 📝.
    * Add the pipeline configuration from this repo.  

**5. Run Docker Compose:**
    * In your terminal, navigate to your project directory and run docker-compose up -d 🐳.
    * Docker Compose will pull the necessary images and start the containers

**6. Access Kibana:**
    * Open your browser and go to http://localhost:5601 🌐.
    * You should see the Kibana interface.

## Troubleshooting:
* 🚨 Make sure Docker is running and you have sufficient resources allocated.
* 🛠️ Check container logs using docker logs <container_name> if something goes wrong.

## Outro:
* 🎉 Congrats! You have successfully installed the ELK Stack using Docker Compose.
* 💬 Leave any questions or comments down below, and I'll be happy to help!
