---
title: "Stack Structure"
path: /docs/stacks/stack-stucture
section: Stacks
---
## Stack structure
```
my-stack
├── README.md
├── stack.yaml
├── image/
|   ├── project/
|   |   └── Dockerfile
│   └── Dockerfile-stack
└── templates/
    └── my-starter/
        └── .appsody-config.yaml
```

## Image

The image provides foundational capabilities that can be extended or replaced by the user application that is based on it. The image has mechanisms to control which aspects can and cannot be overridden by the developer.

### Project directory:
The project folder should contain a production [Dockerfile](#Dockerfile) for your application and the project you are going to contribute as a content provider.

#### Dockerfile
Defines the final image that contains content from both the [image](#Image) and [template](#Templates). This is used to run the application as a whole.

### Dockerfile-stack:
The Dockerfile-stack defines the foundation application image, and a set of environment variables that specify the desired behaviour during local development cycle. It also defines what is exposed from the host machine to the container.

The environment variables that can be set to alter the behaviour of the CLI and controller are described in the [environment variables](environment-variables) overview.

## Templates
A template is a pre-configured starter application that is ready to use with a particular image. It has access to all the dependencies supplied by that image and is able to include new functionality and extra dependencies to enhance the image where allowed.

### .appsody-config.yaml
The `.appsody-config.yaml` allows you to specify the image which the template will use.
For example, the following specifies that the template will use the nodejs-express image: 
```
image: nodejs-express:0.2.0
```