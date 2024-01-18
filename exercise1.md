I decided to work with Python. For linting we can use Pylint software.  Unittest seems to be a popular Python testing framework. Python does not need to be built by itself as it is interpreted language. However, PyBuilder is used for automating the deployment. Here is a list of alternative options for CI: 
 

    Travis CI: Travis CI is a cloud-based CI service that integrates well with GitHub. It supports a variety of programming languages and offers a simple configuration process using a .travis.yml file in your repository. 

    CircleCI: CircleCI is another cloud-based CI/CD platform that supports multiple languages and allows you to define your build process using a configuration file. It integrates with popular version control systems, including GitHub. 

    GitLab CI/CD: GitLab provides an integrated CI/CD solution as part of its platform. It allows you to define CI/CD pipelines directly within your GitLab repository using a .gitlab-ci.yml file. 

    Bamboo: Atlassian's Bamboo is a CI/CD server that integrates with Bitbucket, Jira, and other Atlassian products. It supports automatic branching, parallel builds, and other advanced features. 

    TeamCity: JetBrains' TeamCity is a powerful CI/CD server that supports a variety of build and deployment scenarios. It has a user-friendly web interface and integrates with popular version control systems. 

    Azure Pipelines: Microsoft's Azure Pipelines is a cloud-based CI/CD service that works with Azure DevOps and GitHub repositories. It supports a wide range of platforms, languages, and deployment targets. 

    Buildkite: Buildkite is a CI/CD platform that allows you to run builds on your own infrastructure. It provides flexibility in terms of agent deployment and supports parallel builds. 

    Semaphore: Semaphore is a hosted CI/CD service that offers fast and customizable pipelines. It supports parallelism, caching, and provides a simple configuration process. 

    Drone: Drone is an open-source CI/CD platform that uses Docker containers to run builds. It integrates with various version control systems and allows you to define build steps using a .drone.yml file. 

    GoCD: GoCD is an open-source CI/CD server that focuses on continuous delivery. It supports complex pipelines, can be configured using code, and has plugins for integration with various tools. 

For deciding if we should use cloud or selfhosted setup we want to know how much resources our pipeline will take.  