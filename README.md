
<b>Manually - Build and Push to Jfrog Artifactory</b>
* [Block Elements](#block-elements)
<h2>Prerequisites:</h2>
  <b>1. Git is installed</b><br>
  <b>2. Maven is installed</b><br>
  <b>3. Jfrog Artifactory is installed<b><br>

  <h6>Step 1: Clone the repository</h6>
<pre>github url: https://github.com/techworldwithmurali/nodejs-application.git
          branch name:</pre>

<h6>Step 2: Update the jfrog Artifactory details in pom.xml</h6>
 ![image](https://user-images.githubusercontent.com/115227391/210240087-3c4acba7-818d-4e2a-baa7-363a3f28973f.png)

<h6>Step 3: Update the jfrog credentials in settings.xml</h6>
<h6>Step 4: Run the below command to push the artifacts to Jfrog Artifactory.</h6>
mvn deploy
<h6>Step 5: Verify whether artifact(war) is published or not in Jfrog Artifactory</h6>

Congratulations. You have successfully Published the artifact(war) file in Jfrog repository
