---
title: "Overview for Appsody Stacks"
path: /docs/stacks/stack-overview
section: Stacks
---
# Appsody Stacks

Appsody provides pre-configured application stacks that enables rapid devlopement of quality microservice-based applications. Stacks include a base container image and project templates which act as a starting point for your application development.

Appsody stacks include language runtimes, frameworks and any additonal libraries an tools that are required simplify your local application development. They are often created by technology experts and are an easy way to manage consistency and adopt best practises across many applications.

**Template:** A template utilises the base image and provides a starter application that is ready to use. It leverages existing capabilities provided by that image and can extend functionality to meet your application requirements.

## Using Stacks
To get started using Appsody stacks go to [using-stacks](using-appsody.md) or use the [quick start](#quick-start).

## Stack structure
Each stack must follow the [stack structure](stack-structure.md) which explains each component of the stack and what is expected for it to be considered a stack.

## Creating or Modifying
To create or modify a stack go to [creating or modifying](https://github.com/appsody/stacks/blob/master/docs/create-or-modify.md) stacks.

*Note:* to list all available Appsody stacks run `appsody list`.

## Contributing Stacks
Stacks are catagorised as either `stable`, `incubator` or `experimental` depending on the content of the stack. To contribute a stack you must read the [contributing guidelines](https://github.com/appsody/docs/blob/master/CONTRIBUTING.md) and be sure to create a new GitHub issue to track the discussion.

- `stable/`: Stable stacks meet a set of technical requirements which are yet to be defined.

- `incubator/`: The incubator folder allows stacks to be shared and improved on until they meet the stable critria.

- `experimental/`: These stacks are labeled experimental as they may not fulfill the requirements of a appsody stack. Experimental stacks are also not expected to move out of this category into incubator or stable.

### Quick start
1. Create a new directory
``` bash
mkdir my-app &&
cd my-app
```
2. Initalise Appsody stack
``` bash
appsody init java-microprofile
```
3. Launch application in development environment
``` bash
appsody run
```

If you have a question that you can't find an answer to, we would also like to hear about that too. You can also reach out to the community for assistance on [Slack]().