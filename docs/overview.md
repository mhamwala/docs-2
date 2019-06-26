---
title: "Overview"
path: /docs/overview
---
# Welcome to Appsody
Appsody has been designed to help you compose a masterpiece of an application for cloud. 

Our aims were to simplify the experience for developers - now asked to have full-stack expertise and responsibilities, and allow them to focus on their application code; and to enable architects to curate an opinionated set of technologies - configurable, reusable and already infused with cloud native capabilities.

There are 3 key components of Appsody:

### Appsody Stacks
These are configurable technology stacks built with popular runtimes and frameworks, such as Java with Eclipse Microprofile and Node.js with Express, that provide the foundation for building applications which can be deployed and managed effectively in Kubernetes. Stacks allow for rapid development, whilst giving the stack provider the ability to control how the applications are composed, for example which security policies are applied, or which version of a dependency is pulled.

[More info on Appsody Stacks](link)

### Appsody Hub
The central point of control for Appsody Stacks. This is where you can find available stacks, create new stacks or modify existing ones. You can utilize what's in the public repo, and/or clone to provide a private/internal Hub based on your requirements. By making changes to the Stacks in the Hub, you are able to mass-apply updates to applications which have been built on these, simply by restarting the application.

[More info on Appsody Hub](link)

### Appsody CLI
No project is complete without a nice new CLI to play with. The Appsody CLI is powerful and intuitive, and allows developers to discover available stacks, bring them into their local development environment, and build/run/test/deploy locally. The Docker container, which is built for your application, can be integrated with Tekton pipelines as described [here](TODO) and deployed to Kubernetes cloud environments.

[More info on Appsody CLI](link)

## How does it work?
[TODO CHRIS / Neeraj] Describe common workflow/controller


## Contributing

We welcome all contributions, see [CONTRIBUTING](https://github.com/appsody/docs/blob/master/CONTRIBUTING.md) and come chat to us in [Slack](if you'd like to get involved).

Want to see your framework available as an Appsody Stack? See [Link](here) and join the #content-providers channel on the above Slack to introduce yourself!


## Documentation

Follow the links to learn more about Appsody:

### Getting Started
- [Installing Appsody](getting-started/installation.md)
- [Quick Start](getting-started/quick-start.md)
### Architecture
- [Technical Overview](architecture/technical-overview.md)
- [Controller](architecture/quick-start.md)
- [Mounts](architecture/mounts.md)
### Stacks
- [Overview of Stacks](stacks/stacks-overview.md)
- [Creating Stacks](stacks/creating-stacks.md)
- [Modifying Stacks](stacks/modifying-stacks.md)
### Using Appsody
- [Local Development](using-appsody/local-development.md)
- [CLI commands](using-appsody/cli-commands.md)
- [Creating Project](using-appsody/creating-project.md)
- [Building and Deploying](using-appsody/building-and-deploying.md)

## License
This project is licensed under the Apache 2.0 license, and all contributed stacks must also be licensed under the Apache 2.0 license. Each contributed stack should include a LICENSE file containing the Apache 2.0 license. More information
can be found in the LICENSE file or online at

http://www.apache.org/licenses/LICENSE-2.0
