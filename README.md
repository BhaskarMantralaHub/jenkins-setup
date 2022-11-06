# jenkins-setup
https://www.jenkins.io/download/lts/macos

# **Install LTS version** 

1. Install:

    brew install jenkins-lts

2. Start the Jenkins service: 

    brew services start jenkins-lts

3. Restart the Jenkins service: 

    brew services restart jenkins-lts

4. Jenkins path:

    /opt/homebrew/Cellar/jenkins-lts

5. Change Jenkins default port (8080)

    Open Jenkins config file from following location and update default port:


```vi /opt/homebrew/Cellar/jenkins-lts/2.xxx.x/homebrew.jenkins-lts.service```







