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


```vi /opt/homebrew/Cellar/jenkins-lts/2.xxx.x/homebrew.mxcl.jenkins-lts.plist```

```
<array>
                <string>/opt/homebrew/opt/openjdk@17/bin/java</string>
                <string>-Dmail.smtp.starttls.enable=true</string>
                <string>-jar</string>
                <string>/opt/homebrew/opt/jenkins-lts/libexec/jenkins.war</string>
                <string>--httpListenAddress=127.0.0.1</string>
                <string>--httpPort=9090</string>
</array>
```







