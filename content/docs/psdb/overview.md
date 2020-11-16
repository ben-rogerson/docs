---
title: 'PlanetScaleDB Overview'
---

# PlanetScaleDB Overview

## PlanetScaleDB is scalable MySQL on Kubernetes

PlanetScaleDB is an easy-to-use, cloud-native MySQL database-as-a-service (DBaaS). It implements [Vitess](http://vitess.io), an open source MySQL scaling solution, to grow your database easily and reliably. You can choose to create a fully managed database or to host a managed PlanetScaleDB database in your own [Kubernetes](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/) cluster.

## Vitess scales your MySQL database with high reliability  
 
Vitess manages MySQL replication and *sharding*, or breaking up database tables across multiple instances of MySQL. This allows you to grow your database to massive scale while maintaining high availability and avoiding the pain of manual resharding. Vitess also protects your database by rewriting or restricting low-performance queries. Vitess can also run on Kubernetes, taking advantage of container management and orchestration. 

## PlanetScaleDB manages Vitess

Configuring and managing Vitess to take advantage of these features requires significant work and expertise. PlanetScaleDB's user interface provides a way to use Vitess to create a MySQL database with features like horizontal sharding, replication, and query handling in a few minutes. You can import data from an existing database to gain the benefits of Vitess, or export data to another platform. You can also customize your database to use specific schemas, sharding configurations, regions or zones, and resource requirements, all through PlanetScaleDB's console.


## PlanetScaleDB offers fully managed or self-hosted deployments

When you create a PlanetScaleDB database, you can choose between a fully managed database or a [custom region](custom-regions). In a fully managed deployment, PlanetScale manages your database inside a virtual private cloud. In a custom region, PlanetScaleDB deploys a managed database in an existing Kubernetes cluster that you control.

## What's next

+ Get started using PlanetScaleDB by [creating a cluster](creating-cluster), which is a set of resources you can use to [create a database](creating-database).
+ Learn more about PlanetScaleDB [clusters](clusters) and [sharding](sharding-schemes).