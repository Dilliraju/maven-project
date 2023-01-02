
<b>Manually - Build and Push to Jfrog Artifactory</b>
* [Block Elements](#block-elements)
## Prerequisites:
  <b>1. Git is installed</b><br>
  <b>2. Maven is installed</b><br>
  <b>3. Jfrog Artifactory is installed<b><br>

  ## Step 1: Clone the repository
  
```xml
  github url: https://github.com/techworldwithmurali/nodejs-application.git
          branch name:
```


```xml
 <distributionManagement>
      <snapshotRepository>
        <id>jfrog-snapshots</id>
        <url>http://your-host:8081/repository/maven-snapshots/</url>
      </snapshotRepository>
      <repository>
        <id>jfrog-releases</id>
        <url>http://your-host:8081/repository/maven-releases/</url>
      </repository>
    </distributionManagement>
```
<h6>Step 3: Update the jfrog credentials in settings.xml</h6>
<h6>Step 4: Run the below command to push the artifacts to Jfrog Artifactory.</h6>
mvn deploy
<h6>Step 5: Verify whether artifact(war) is published or not in Jfrog Artifactory</h6>

Congratulations. You have successfully Published the artifact(war) file in Jfrog repository
