### JENKINS INSTALL ON UBUNTU 18.04
 * PRERQUSITES
   * JAVA
   * GIT 
   * MAVEN
 * java home and maven home paths are must be set.
 * we can export java home but this is not permnetly so for this we should add the java home and maven home
  in .bashrc and restart terminal or take new terminal  
  ### create jenkins user
   * sudo -i
   * adduser jenkins 
   * su jenkins
   * sudo usermod -aG root jenkins
   * or add jenins user in /etc/sudoers
   ```
   jenkins ALL=(ALL:ALL)    ALL
   ```
* install java
* instal jenkins
* add the repositories which are search in google
```
sudo apt-get update
sudo apt-get install openjdk -y
sudo apt-get install jenkins -y
```