---
title: "Overview for Appsody Stacks"
path: /docs/stacks/stack-overview
section: Stacks
---
# Appsody Stacks

Appsody provides pre-configured application stacks that enables rapid devlopement of quality microservice-based applications. Stacks include a base container image and project templates which act as a starting point for your application development.

Appsody stacks include language runtimes, frameworks and any additonal libraries an tools that are required simplify your local application development. They are often created by technology experts and are an easy way to manage consistency and adopt best practises across many applications.

**Template:** A template utilises the base image and provides a starter application that is ready to use. It leverages existing capabilities provided by that image and can extend functionality to meet your application requirements.

---
Stacks are catagorised as either `stable`, `incubator` or `experimental` depending on the content of the stack.

- `stable/`: Stable stacks meet a set of technical requirements which are yet to be defined.

- `incubator/`: The stacks in the incubator folder are activly been worked upon to satisfy the stable critria.

- `experimental/`: Exprimental stacks are not been actively been worked upon and  may not fulfill the requirements of an Appsody stack. These can be used for trying out specific capabilites or proof of concept work.

## Getting started
Follow the [quick start guide](../getting-started/quick-start.md) to get you up and running with Apposdy stacks.

To explore existing stacks that are available to you:
- Visit the [Appsody website](https://appsody.dev) or
- Run `appsody list` command using our CLI

For detailed information about using Appsody go to [using-stacks](using-appsody.md).

## Modifying existing stacks
You might want to modify an existing stack to suit your development needs, for example you might want to use a different library or runtime version.

To learn how to go about modifying an existing stack go to [modifying a stack](create-or-modify.md#modifying-a-stack).

## Creating new stacks
We are actively working to create new stacks so that more people can adopt Appsody. If you find that none of the existing stacks meet your needs please reach out to us on the [Appsody slack]() or create a new GitHub issue to track the discussion.

We always welcome any contributions. If you wanted to create your own stack for a framework or language that we do not currently support, please review the [contributing guidelines](../../CONTRIBUTING.md) and follow the steps outlined in [creating a stack](create-or-modify.md#creating-a-stack).

## Need help?
If you have a question that you can't find an answer to, we would also like to hear about that too. You can also reach out to the community for assistance on [Slack]().