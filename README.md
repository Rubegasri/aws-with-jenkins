1.for automate installation and updation:

sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
    https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
    
 2. add a Jenkins apt repository entry:

  echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
    https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
    /etc/apt/sources.list.d/jenkins.list > /dev/null

  3.Update your local package index, then finally install Jenkins:

  a.sudo apt-get update
 b. sudo apt-get install fontconfig openjdk-17-jre
c.  sudo apt-get install jenkins

    
