# Kaleidocode DevOps Assessment

```Note: Fork this repository to your own account and ensure that assessers have access to the repository```

## Overview

This assessment intention is to:
   * Understand knowledge and potential for knowledge of a candidate
   * Create talking points with a candidate about DevOps techniques and tools

Knowledge of how this code works is __not__ required


## Goal
    
   * The Candidate will attempt to set up a **build and test** cycle for a [Continuous Integration pipeline](https://dzone.com/articles/learn-how-to-setup-a-cicd-pipeline-from-scratch) for DevOpsAssessment.sln in the Root of the Repository


### Tools

   * CI Engine
     * Gitlab CI is the recommended 
       * ```Note: As long as assesses are able to view the pipeline in action, any CI engine can be used.```
   * Code tooling
     * [dotnet cli](https://docs.microsoft.com/en-us/dotnet/core/tools/) should be used for commands for Building and testing of the components


### Extra but not required

   * Docker to be pushed on successful build
   * Status Badges to be displayed on the readme.md
   * Different pipeline steps for builds inteded for develop and production respecitvely
   * Build Failure Builds for `BrokenBuild` and `BrokenTest` Respectively


