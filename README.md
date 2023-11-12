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

**add repository**

  git remote add origin https://github.com/your-username/your-repository.git
  
  **eg**
  
  git remote add origin https://github.com/satishgore01/php-webapp.git

  
  first create clasic token and add it into linux machine. use following command to add token in linux machine.
  go to your git repository  and add token
  
**syntax**

  git remote set-url origin https://**username**:**token**@github.com/**username**/**repository**.git

**eg.**
  git remote set-url origin https://satishgore01:ghp_K3mxrvAe4556u4PMVNel1zO2vIAG51yF0y13l0@github.com/satishgore01/php-webapp.git

**git push**
        **git push -u origin main**



 

       

