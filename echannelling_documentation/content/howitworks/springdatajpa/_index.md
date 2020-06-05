---
title: "Spring Data JPA"
date: 2020-06-05T17:03:27+06:38
weight: 3
draft: false
# search related keywords
keywords: [""]
---

Spring Data JPA, part of the larger Spring Data family, makes it easy to easily implement JPA based repositories. This module deals with enhanced support for JPA based data access layers. It makes it easier to build Spring-powered applications that use data access technologies.

Implementing a data access layer of an application has been cumbersome for quite a while. Too much boilerplate code has to be written to execute simple queries as well as perform pagination, and auditing. Spring Data JPA aims to significantly improve the implementation of data access layers by reducing the effort to the amount that’s actually needed. As a developer you write your repository interfaces, including custom finder methods, and Spring will provide the implementation automatically.

#### Features
- Sophisticated support to build repositories based on Spring and JPA

- Support for Querydsl predicates and thus type-safe JPA queries

- Transparent auditing of domain class

- Pagination support, dynamic query execution, ability to integrate custom data access code

- Validation of @Query annotated queries at bootstrap time

- Support for XML based entity mapping

- JavaConfig based repository configuration by introducing @EnableJpaRepositories.