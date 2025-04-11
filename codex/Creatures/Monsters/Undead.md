```markdown
# Understanding Azure Pipelines and YAML

Azure Pipelines is a cloud service that automatically builds and tests your code project. It supports multiple languages, project types, and platforms. You define your build and release pipelines using YAML files.

## What is YAML?

YAML (YAML Ain't Markup Language) is a human-readable data-serialization language. It's commonly used for configuration files and in applications where data is being stored or transmitted. In Azure Pipelines, YAML is used to define the steps in your build, test, and deployment process.

## Key Concepts

*   **Pipeline:** The top-level construct, representing your entire CI/CD process.
*   **Stage:** A logical division within the pipeline, often representing different environments (e.g., Dev, Test, Prod).
*   **Job:** A collection of steps that runs on a single agent.
*   **Step:** The smallest unit of work in a pipeline, like running a script, publishing artifacts, or deploying code.
*   **Task:** A pre-packaged script or tool that performs a specific action (e.g., `AzureFileCopy@5`, `DotNetCoreCLI@2`).
*   **Agent:** A compute resource (either Microsoft-hosted or self-hosted) that executes your jobs.

## Example YAML Pipeline

Here's a basic example of an Azure Pipelines YAML file:

```yaml
# Starter pipeline
trigger:
- main

pool:
  vmImage: ubuntu-latest

steps:
- script: echo "Hello, world!"
  displayName: 'Run a one-line script'

- script: |
    echo "Add any other script commands here"
  displayName: 'Run a multi-line script'
```

## Using Variables

You can use variables to customize your pipeline and make it more reusable.  Variables can be defined at different levels (pipeline, stage, job, step) and can be used in scripts, tasks, and other configurations.

```yaml
variables:
  buildConfiguration: 'Release'

steps:
- script: dotnet build --configuration $(buildConfiguration)
  displayName: 'Build the project'
```

## Resources

*   [Azure Pipelines Documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/?view=azure-devops)
*   [YAML Schema Reference](https://docs.microsoft.com/en-us/azure/devops/pipelines/yaml-schema/?view=azure-devops)

## Conclusion

YAML-based Azure Pipelines provide a powerful and flexible way to automate your CI/CD processes. Understanding the core concepts and YAML syntax allows you to create efficient and reliable pipelines for your projects.
```


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._