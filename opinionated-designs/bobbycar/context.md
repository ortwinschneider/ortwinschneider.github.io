---
layout: home
title: Business scenario
nav_order: 1
has_children: false
parent: Bobbycar
grand_parent: Opinionated Designs
---

# Building a cloud-native IoT architecture

An IoT / Cloud / Edge architecture is overwhelming at first glance with its heterogeneity. A wide variety of device types, different partial architectures and protocols, various physical locations, different workload characteristics, multi and hybrid cloud environments, machine learning, data science, security across the entire stack, monitoring, etc.

The complete solution therefore does not consist of one technology, product or even architecture concept that guarantees successful implementation. The aim is to find a modular, scalable architecture that supports the need-oriented addition or removal of functions and already supports as many requirements and use cases as possible.

## Standard IoT architecture
There are various reference models and descriptions of IoT architectures. Depending on the level of detail, they have four to seven layers. An overview of currently widespread models can also be found at

[A-Detailed-Analysis-of-IoT-Platform-Architectures-Concepts-Similarities- and-Differences.pdf](https://www.iaas.uni-stuttgart.de/publications/INBOOK-2018-01-A-Detailed-Analysis-of-IoT-Platform-Architectures-Concepts-Similarities- and-Differences.pdf) 

For a basic understanding we only consider a simplified model with four layers:

**Perception Layer**: IoT devices / things that are equipped with sensors. Sensors collect the data and transmit it over a network, and actuators carry out actions.

**Connectivity Layer**: Sends the data from the IoT devices to the next higher layer. This can be via 2G / 3G / 5G, or via WiFi, ZigBee, Bluetooth or other industrial protocols. 

**IoT Platform Layer**: A layer similar to middleware. Processes, distributes and stores the data coming from the transport layer. Technologies such as Apache Kafka, traditional messaging systems, time series databases (TSDB), big data and stream data processing are usually used at this level.

**Application Layer**: The technical applications are managed on this level. There are various IoT applications that differ in complexity and functionality and use different technology stacks and operating systems. Some examples are device monitoring and control software, mobile apps, business intelligence services, and other solutions that implement machine learning. These applications are based directly on the IoT platform.

The criteria that a specific IoT solution should or must meet determine the choice of suitable technologies and IoT platforms. The starting point should always be an evaluation of the functional and non-functional requirements in the context of a catalog of criteria.

As an example, the following list applies as a first approach:

- Functionality and scope of functions
- Performance
- Scalability
- Operability
- Maintainability
- Connectivity, supported protocols
- Device types and classes
- Security (across the entire stack)
- Portability (of applications and middleware components)
- Cloud capability 
- Interfaces and APIs
- Automation
- Fault tolerance and reliability
- Observability
- Interoperability
- Governance 
- Data protection

Since a large part of the applications of an IoT solution are usually operated in different cloud environments, the requirements outlined often lead to the requirement for a secure and powerful hybrid cloud infrastructure for end-to-end data processing support.

## Cloud-native IoT platform
It is a great advantage to establish a uniform platform with consistent development and operational experience, if possible across all cloud environments. Such a hybrid cloud-native IoT platform already covers many of the requirements mentioned, such as automated scale-up and scale-down of computing and storage capacity in accordance with policies. 

The portability of applications is very important. Often, applications are developed centrally and then have to be rolled out into the various cloud environments down to the edge components. 

Furthermore, the platform must be able to cope with sudden changes in the amount of IoT data generated without negatively affecting the entire system in any way. 

From a technological point of view, container technology and Kubernetes as a container orchestration framework have also increasingly proven to be the right choice in an IoT and edge environment. 

The cloud-native approach is also very well suited creating scalable, cost-efficient and reliable IoT solutions. 

In contrast to traditional applications, which you simply deploy and operate in the cloud, cloud-native applications are developed to take advantage of cloud computing. 

Cloud-native is an agile, conceptual method to develop and operate applications completely in the cloud and for the cloud. Cloud-native is about how applications are created and being deployed, not where. Therefore, cloud-native applications usually have the following things in common: