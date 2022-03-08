---
layout: home
title: Home
nav_order: 1
---

# Red Hat Opinionated Designs

An *“Opinionated Design”* is a general repeatable solution or architecture pattern to a commonly occurring problem. It is a Red Hat recommendation and template for how to solve a problem that can be used in many different situations with the Red Hat OpenShift Container platform and Red Hat’s Middleware and Automation Portfolio.

An Opinionated Design describes best practices, good designs, and capture Red Hat’s experience in a way that it is possible for others to reuse this experience.

![Opinionated Designs](./images/od_logo.png)

## Design and Pattern

A [design](https://en.wikipedia.org/wiki/Design) is a plan or specification for the construction of an object or system or for the implementation of an activity or process, or the result of that plan or specification in the form of a prototype, product or process. 

A "pattern" has been defined as: "an idea that has been useful in one practical context and will probably be useful in others" (Source: Analysis Patterns - Re-usable Object Models, by M. Fowler).

## Why should I use Opinionated Designs?

- Helping architects and developers by using building blocks that have been proven to provide effective solutions
- Best practices using cloud-native patterns with Red Hat technologies
- Helping developers and architects heading to production
- Speed up the development and deployment process by using existing templates and code snippets

## General Structure

All patterns assume an OpenShift cluster is available to deploy the application(s) that are part of the pattern. If you do not have an openshift cluster you can use [cloud.redhat.com](https://console.redhat.com/openshift). 

The documentation will use the `oc` command syntax but `kubectl` can be used interchangeably. For each deployment it is assumed that the user is logged into a cluster using the `oc login` command or by exporting the `KUBECONFIG` path.