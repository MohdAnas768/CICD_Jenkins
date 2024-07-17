# CICD_Jenkins
# Jenkins Pipeline Example

This repository contains an example Jenkins pipeline defined using both YAML and Groovy formats.

## Jenkins Pipeline in YAML

The Jenkins pipeline can be defined in YAML format using the Pipeline YAML plugin. Below is the sample YAML configuration:

```yaml
pipeline:
  agent: any
  stages:
    - stage: Build
      steps:
        - sh: 'echo "Building..."'
    - stage: Test
      steps:
        - sh: 'echo "Testing..."'
    - stage: Deploy
      steps:
        - sh: 'echo "Deploying..."'
