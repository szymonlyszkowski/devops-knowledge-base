---
description: >-
  7 R's is a methodology of adoption/migration from in-house datacenter into
  cloud.
---

# 7 R's

Detailed information about migration can be found in:

{% file src="../.gitbook/assets/aws-migration-whitepaper.pdf" caption="aws migration whitepaper" %}

## Re-hosting \(lift & shift\)

The purpose of rehosting is basically moving all servers using lift and shift method from on-premise to cloud environment. Move applications with **NO** change. Such move can already save significant amount of money

## Re-hosting \(hypervisor-level lift and shift\)

Use AWS Migration Service to migrate Hyper-V based VMs to AWS.

## Re-platforming \(lift & reshape\)

Try to move your applications to use infrastructure services.

Example: Instead of installation & maintenance of a database use ready to use AWS RDS service by your applications.

## Refactor/Reachitect

Consider moving your product applications \(responsible for making your business profit\) to cloud-native environment. E.g. move monolithic applications to service oriented archtecture or microservices, Avoid using licence-expensive software to opensource e.g. move weblogic to apache tomcat

## Repurchase \(drop & shop\)

Try to adopt your system by using 3rd party vendor software.  
Example: Use Workday in SaaS model for HR in your organisation instead of hosting it on your own.

## Retire

Revisit all applications deployed within your datacanter before moving to cloud. Usually it appears that 10-20% of software is **NOT** being used and can be dropped from maintenance or migration.

## Retain

Leave your business critical application inside your datacenter but only those **which require major refactoring**

