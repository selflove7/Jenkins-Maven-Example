# Jenkins-Maven-Example

This is an example Maven project that demonstrates how to use Jenkins to execute the project.

Prerequisites
To execute this project, you'll need the following tools installed on your system:

1) Java JDK (version 8 or higher)
2) Apache Maven (version 3.6.0 or higher)
3) Jenkins (version 2.249.1 or higher)

#Installation

Clone the repository to your local machine:

git clone https://github.com/selflove7/Jenkins-Maven-Example.git

#Navigate to the project directory:

cd example-maven-project

Install the project dependencies using Maven:

mvn install

Usage

To execute the project using Jenkins:

Create a new Jenkins job.

In the job configuration, specify the following:

1) Source code management: select Git and provide the URL of the Git repository.
2) Build: select "Invoke top-level Maven targets" and specify the Maven goals to execute (e.g. "clean install").
3) You can also configure additional build settings such as triggers, build parameters, and post-build actions as needed.

Save the job configuration and run the job to execute the Maven project.
