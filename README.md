# DevOps Foundations: Version Control and CI/CD with Jenkins

## Project: Insured Assurance CI/CD Pipeline

### Objective

The goal of this project is to create a GitHub Actions CI/CD pipeline workflow that triggers the deployment of a Java application as a Jenkins job using Tomcat Apache.

### Problem Statement and Motivation

**Scenario**:  
Insured Assurance, a leading global insurance provider based in the US, offers various insurance products, including home, health, car, and life insurance. The company is transitioning to a DevOps architecture and aims to automate code builds and deployments across multiple environments.

To meet this objective, Insured Assurance has adopted GitHub Actions for automating code checkout, building, and testing processes, and Jenkins for continuous deployment. As a DevOps engineer at Insured Assurance, your task is to implement a CI/CD pipeline that integrates these tools for seamless automation.

### Industry Relevance

This project involves using the following industry-standard tools:

- **Jenkins**: An open-source automation server that supports continuous integration and continuous delivery (CI/CD). It is widely used in the software development industry to increase efficiency, detect issues early, and accelerate software releases.

- **GitHub Actions**: A CI/CD platform that automates the software development process within GitHub, making it easier for developers to manage and deploy code updates.

- **Tomcat Apache**: An open-source web server and servlet container that supports Java servlets and JSPs, commonly used in web application development and deployment.

### Tasks

Follow the steps below to implement CI/CD using GitHub Actions and Jenkins:

1. **Create a code repository on GitHub**
    - Set up a new repository to host your project code.

2. **Create a GitHub Actions pipeline to perform continuous integration**
    - Configure GitHub Actions to automate the build and testing processes.

3. **Configure Tomcat Apache for automated code deployment**
    - Set up Tomcat Apache to automatically deploy the code from your pipeline.

4. **Integrate the GitHub Actions pipeline to invoke the Jenkins pipeline**
    - Configure your GitHub Actions workflow to trigger the Jenkins pipeline for continuous deployment.

5. **Invoke pipeline to validate automated deployment**
    - Test the complete CI/CD pipeline by triggering it to ensure the deployment process works as expected.

### Project References

To assist you with the tasks, refer to the following lessons:

- **Task 1**: Lesson 02
- **Task 2**: Lesson 10
- **Task 3**: Lesson 07
- **Task 4**: Lesson 10
- **Task 5**: Lessons 08 and 10

### Output Screenshots

Ensure to capture screenshots at various stages of the project, including:

- Maven workflow file configuration in GitHub Actions
- Tomcat Apache setup
- SSH pipeline configuration in the `maven.yml` workflow file
- GitHub repository secrets
- Freestyle job creation in Jenkins for continuous deployment
- Workflow configuration to integrate Jenkins and GitHub Actions
- Jenkins job invocation from the GitHub Actions pipeline
- Deployment of the Java application on Tomcat by invoking the Jenkins job from the GitHub Actions pipeline

### Conclusion

This project will help you gain practical experience in setting up and integrating CI/CD pipelines using GitHub Actions and Jenkins, which is a crucial skill in modern DevOps practices.

---

**Thank you!**