# ITI Docker Labs - Image Examples

This repository contains screenshots of Docker commands and examples used in ITI Docker labs.

---

## Hello World
**Run the `hello-world` Docker image for the first time:**  
![Run Hello World](imgs/1-run_hello_world_img.png)

**Remove the `hello-world` Docker image:**  
![Remove Hello World](imgs/rm_hello_world_img.png)

---

## Ubuntu Containers
**Run an Ubuntu container in interactive mode (`-it`):**  
![Run Ubuntu Interactive](imgs/run_ubuntu_it.png)

**Execute commands inside Ubuntu container interactively:**  
![Run Command in Ubuntu](imgs/run_comand_in_ubunto_it.png)

**Create a file inside Ubuntu container using `touch`:**  
![Create File in Ubuntu](imgs/run_touch_ubuntu_bash.png)

---

## Containers Management
**List all running Docker containers:**  
![List All Processes](imgs/list_all_processes.png)

**Remove a specific container:**  
![Remove Container](imgs/rm_cont.png)

**Remove all containers at once:**  
![Remove All Containers](imgs/rm_all_containers.png)

**Start a previously stopped container:**  
![Start Container](imgs/start_container.png)

---

## Nginx Web Server
**Run Nginx container and change the `index.html` page:**  
![Run Nginx and Change Index](imgs/run_nginx_img_change_index.png)

**Access Nginx page from browser:**  
![Access Nginx from Browser](imgs/access_nginx_fromm_brws.png)

---

## MySQL
**Run a MySQL container:**  
![Run MySQL Container](imgs/run_mysql.png)

---

## Dockerfile
**Example of a Dockerfile used in labs:**  
![Dockerfile Example](imgs/dockerfile.png)

---

## Flask App
**Run a Flask app container:**  
![Run Flask Image](imgs/run_flask_img.png)

**Access the Flask app from the browser via mapped port:**  
![Access Flask from Browser](imgs/access_flask_from_brows.png)

---
## Volumes
**create named volumes:**  
![named vol](imgs/create_named_volume.png)
**create bind volumes:**  
![bind vol](imgs/create_bind_volumes.png)

**attach 2 named volumes to container, then change index.html inside container:**
![attach named vol](imgs/run_cont_with_named_vol.png)

**attach to bind volumes to container, then change index.html inside container:**  
![attach bind vol](imgs/run_container_with_bind_vol.png)


**remove old container, then attach named volumes to new container:**  
![attach bind vol](imgs/attach_named_vol_to_new_container.png)

**remove old container, then attach bind volumes to new container:**  
![attach bind vol](imgs/attach_bind_vol_to_new_cont.png)

**access new contaienr with browser:**  
![attach bind vol](imgs/access_from_browser.png)

---
## Network

**Create 2 networks:**  
![Run MySQL Container](imgs/create-2-network.png)

**Run nginx  container in network1:**  
![Run MySQL Container](imgs/run-nginx-container-in-network-1.png)

**Run a flask container in network1:**  
![Run MySQL Container](imgs/run-flask-container-in-network-1.png)

**execute nginx contianer with ```curl flask_container:port```:**  
![Run MySQL Container](imgs/exec-nginx-curl-flask-app.png)

---
**Note:** All images are located in the `imgs/` folder. Open this `Readme.md` in GitHub, VS Code, or any markdown viewer to see the screenshots directly.