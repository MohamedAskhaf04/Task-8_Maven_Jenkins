Task-8: Maven and Jenkins CI/CD Pipeline
Overview

This task demonstrates how to set up a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins and Maven. The goal is to automatically fetch source code from a GitHub repository, build it using Maven, and prepare the packaged artifact for deployment.

Process

Jenkins Setup
Jenkins was installed and configured with the required plugins. The Maven integration plugin was added to allow Jenkins to run Maven build tasks.

Maven Configuration
Maven was installed on the Jenkins environment and configured in the Jenkins global tool settings. This enabled Jenkins to access Maven for project builds.

Source Code Integration
Jenkins was connected to a GitHub repository containing the Maven project. The job was configured to fetch the latest code whenever a build is triggered.

Build Stage
Jenkins used Maven to compile the code, run tests, and generate the build artifact based on the project’s configuration file.

Artifact Archiving
The generated build files (such as JAR files) were archived in Jenkins so they can be downloaded and used for deployment.

Outcome

By the end of the task, Jenkins was able to:

Automatically pull the latest source code from GitHub.

Build the project with Maven.

Store the build artifacts for deployment.

This setup ensures faster development cycles, consistent builds, and a reliable foundation for future deployment automation.
