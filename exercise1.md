# exercise1.md

Language: Java

## What tools take care of linting, testing and building in Java?
Linting: In Visual Studio Code you can use Format Document command and you can set formatter settings in settings.json (xml file).  
Extension Pack for Java can be used to edit formatter profile.  
SonarLint is an extension for VS Code and it also helps finding bugs and security issues.  
Checkstyle for Java extension can provide Quick Fixes on the fly.  

Unit testing, testing small parts in isolation, is popular in Java. The most common library for unit testing is JUnit. It's also supported in most programming environments.

For building Java projects, you can use Maven or Gradle.

## What alternatives are there to set up the CI besides Jenkins and GitHub Actions?
GitLab also provides CI. Other tools include Bitbucket Pipelines, AWS CodePipeline and Azure Pipelines.

## Would this setup be better in a self-hosted or a cloud-based environment?
Since the team is small (6 people) a cloud-based environment might work better, since the configuration is simple, so no time is wasted on setting up the CI. It should also be cheaper for smaller projects.  
Smaller team can usually mean that the application is on the smaller side (though not always). I would decide based on the application's size, team size and if there are some special hardware requirements.  