HelloJavaJenkins
Overview
This repository contains a basic Java application, Main.java, and a Jenkins pipeline configuration, Jenkinsfile, to automate the build and deployment process.

Project Structure
Main.java: The main Java file that contains the "Hello World" application.
Jenkinsfile: Jenkins pipeline script that defines the stages to compile and run the Java application.
Prerequisites
Before running the pipeline, ensure you have the following installed:

Java JDK (version 11 or higher)
Jenkins (with access to Git and the necessary plugins)
Jenkins Pipeline
The Jenkins pipeline defined in the Jenkinsfile performs the following steps:

Build Stage: Compiles the Main.java file.
Run Stage: Executes the compiled Java application.
Steps to Setup Jenkins Pipeline
Create a new Jenkins job:

Select "Pipeline" as the project type.
Configure the pipeline:

Set the repository URL: https://github.com/Aashish-cyber/HelloJavaJenkins.git
Point to the Jenkinsfile located in the repository.
Run the pipeline:

The pipeline will automatically fetch the latest code, compile it, and run the application.
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/Aashish-cyber/HelloJavaJenkins.git
Navigate to the project directory:

bash
Copy code
cd HelloJavaJenkins
Compile the Java file:

bash
Copy code
javac Main.java
Run the compiled Java program:

bash
Copy code
java Main
Troubleshooting
Jenkins Build Failure: Ensure that the JDK is correctly configured in Jenkins and the necessary tools (e.g., Git) are available.
Java Compilation Errors: Verify that you have the correct version of JDK installed.


Contributing
If you find any issues or want to contribute to the project, feel free to open a pull request or raise an issue in the repository.

