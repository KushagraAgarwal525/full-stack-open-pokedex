# Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked?

I chose the language **Python** for my answer. For linting, Pylint and PyFlakes can be used. For testing Pytest can be used. And for building, PyBuilder can be used. There are many other tools that may be better-suited for a specific task.

# What alternatives are there to set up the CI besides Jenkins and GitHub Actions? 

To set up the CI, there are many alternatives such as:

- GitLab
- Atlassian Bamboo
- JFrog Pipelines
- Spinnaker
- JetBrains TeamCity
- AWS CodePipeline
- Azure DevOps Server (formerly Microsoft Team Foundation Server)
- Maven and Gradle
- CloudBees CI (formerly CloudBees Core)

The choice may differ on what best suits the project.

# Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

Depends. For a small-medium project which does not have a specific requirement like a GPU, a cloud-based environment is better-suited since it does not involve the work of setting up a self-hosted server. For large projects or resource-specific projects a self-hosted server may be better suited.