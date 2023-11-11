------------------------------------------------- **install docker** -------------------------------------------------------------------------

sudo apt-get update sudo apt-get install ca-certificates curl gnupg sudo install -m 0755 -d /etc/apt/keyrings curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg sudo chmod a+r /etc/apt/keyrings/docker.gpg

# Add the repository to Apt sources: echo \ "deb [arch="$(dpkg --print-architecture)" signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \ "$(. /etc/os-release && echo "$VERSION_CODENAME")" stable" | \ sudo tee /etc/apt/sources.list.d/docker.list > /dev/null sudo apt-get update

 #apt  install docker.io

 #systemctl status docker

**add ubuntu user to docker group**
if you get following error for non root user follow below procedure

permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Get "http://%2Fvar%2Frun%2Fdocker.sock/v1.24/containers/json": dial unix /var/run/docker.sock: connect: permission denied

** add ubuntu user to docker group**
 sudo usermod -aG docker ubuntu
 systemctl restart docker 

** check docker command working or not for ubuntu user**

------------------------------------------------------ **docker installation  compleated** --------------------------------------------------------------------



**#step 1 
clone the code from github**
**root@ip-172-31-17-122:/home/webapp# git clone https://github.com/edureka-devops/projCert.git**

Cloning into 'projCert'...
remote: Enumerating objects: 112, done.
remote: Total 112 (delta 0), reused 0 (delta 0), pack-reused 112
Receiving objects: 100% (112/112), 9.17 MiB | 5.77 MiB/s, done.
**Resolving deltas: 100% (55/55), done**.

**Step 2**
git init

git add .

git commint -m "project files added"

**step 3**
  **push code to your github repo**

  ------------------------------------------------------------------------------------------------------------------------------------------------------------

  
       

