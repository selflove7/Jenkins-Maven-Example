# Jenkins-Maven-Example

This is an example Maven project configured to run in Jenkins. The project contains a simple Java program that outputs "Hello, world!" to the console.

<h2 style="font-size:24px;"> Prerequisites </h2>

Jenkins server
Maven installed on the Jenkins server
Java Development Kit (JDK) installed on the Jenkins server

<h3> Setup </h3>

Clone this repository onto your Jenkins server.
Create a new Jenkins job using the "Maven project" option.
In the "Source Code Management" section of the job configuration, select "Git" and provide the URL of the cloned repository.
In the "Build" section of the job configuration, add a new "Invoke top-level Maven targets" build step.
In the "Goals" field of the build step, enter "clean package".
Save the job configuration.


<h3> Execution </h3>

Run the Jenkins job by clicking the "Build Now" button on the job page.
Once the build completes, navigate to the "Console Output" section to view the build log.
If the build was successful, the "Hello, world!" message should be printed to the console.

