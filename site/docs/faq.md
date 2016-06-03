---
title: FAQ
---

## What is Apache Quarks?

Quarks provides APIs and a lightweight runtime to analyze streaming data at the edge.

## What do you mean by the edge?

The edge includes devices, gateways, equipment, vehicles, systems, appliances and sensors of all kinds as part of the Internet of Things.

## How is Apache Quarks used?

Quarks can be used at the edge of the Internet of Things, for example, to analyze data on devices, engines, connected cars, etc. Quarks could be on the device itself, or a gateway device collecting data from local devices. You can write an edge application on Quarks and connect it to a Cloud service, such as the IBM Watson IoT Platform. It can also be used for enterprise data collection and analysis; for example log collectors, application data, and data center analytics.

## How are applications developed?

Applications are developed using a functional flow API to define operations on data streams that are executed as a graph of "oplets" in a lightweight embeddable runtime. The SDK provides capabilities like windowing, aggregation and connectors with an extensible model for the community to expand its capabilities.

## What APIs does Apache Quarks support?

Currently, Quarks supports APIs for Java and Android. Support for additional languages, such as Python, is likely as more developers get involved. Please consider joining the Quarks open source development community to accelerate the contributions of additional APIs.

## What type of analytics can be done with Apache Quarks?

Quarks provides windowing, aggregation and simple filtering. It uses Apache Common Math to provide simple analytics aimed at device sensors. Quarks is also extensible, so you can call existing libraries from within your Quarks application. In the future, Quarks will include more analytics, either exposing more functionality from Apache Common Math, other libraries or hand-coded analytics.

## What connectors does Apache Quarks support?

Quarks supports connectors for MQTT, HTTP, JDBC, File, Apache Kafka and IBM Watson IoT Platform. Quarks is extensible; you can add the connector of your choice.

## What centralized streaming analytic systems does Apache Quarks support?

Quarks supports open source technology (such as Apache Spark, Apache Storm, Flink and samza), IBM Streams (on-premises or IBM Streaming Analytics on Bluemix), or any custom application of your choice.

## Why do I need Apache Quarks on the edge, rather than my streaming analytic system?

Quarks is designed for the edge, rather than a more centralized system. It has a small footprint, suitable for running on devices. Quarks provides simple analytics, allowing a device to analyze data locally and to only send to the centralized system if there is a need, reducing communication costs.

## Why do I need Apache Quarks, rather than coding the complete application myself?

Quarks is a tool for edge analytics that allows you to be more productive. Quarks provides a consistent data model (streams and windows) and provides useful functionality, such as aggregations, joins, etc. Using Quarks lets you to take advantage of this functionality, allowing you to focus on your application needs.

## Where can I download Apache Quarks to try it out?

Quarks is migrating from github quarks-edge to Apache. You can download the source from Apache and build it yourself [here](https://github.com/apache/incubator-quarks). You can also find already built pre-Apache releases of Quarks for download [here](https://github.com/quarks-edge/quarks/releases/latest). These releases are not associated with Apache.

## How do I get started?

Getting started is simple. Once you have downloaded Quarks, everything you need to know to get up and running, you will find [here](quarks-getting-started). We suggest you also run the [Quarks sample programs](samples) to familiarize yourselves with the code base.

## How can I get involved?

We would love to have your help! Visit [Get Involved](community) to learn more about how to get involved.

## How can I contribute code?

Just submit a [pull request](https://github.com/apache/incubator-quarks) and wait for a committer to review. For more information, visit our [committer page](committers) and read [DEVELOPMENT.md](https://github.com/apache/incubator-quarks/blob/master/DEVELOPMENT.md) at the top of the code tree.

## Can I become a committer?

Read about Quarks committers and how to become a committer [here](committers).

## Where can I get the code?

The source code is available [here](https://github.com/apache/incubator-quarks).

## Can I take a copy of the code and fork it for my own use?

Yes. Quarks is available under the Apache 2.0 license which allows you to fork the code. We hope you will contribute your changes back to the Quarks community.

## How do I suggest new features?

Click [Issues](https://issues.apache.org/jira/browse/QUARKS) to submit requests for new features. You may browse or query the Issues database to see what other members of the Quarks community have already requested.

## How do I submit bug reports?

Click [Issues](https://issues.apache.org/jira/browse/QUARKS) to submit a bug report.

## How do I ask questions about Apache Quarks?

Use [site.data.project.user_list](mailto:{{ site.data.project.user_list }}) to submit questions to the Quarks community.

## Why is Apache Quarks open source?

With the growth of the Internet of Things there is a need to execute analytics at the edge. Quarks was developed to address requirements for analytics at the edge for IoT use cases that were not addressed by central analytic solutions. These capabilities will be useful to many organizations and that the diverse nature of edge devices and use cases is best addressed by an open community. Our goal is to develop a vibrant community of developers and users to expand the capabilities and real-world use of Quarks by companies and individuals to enable edge analytics and further innovation for the IoT space.
