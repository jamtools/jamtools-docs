---
title: "Accessing a database"
description: "Guides lead a user through a specific task they want to accomplish, often with a sequence of steps."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
weight: 810
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

Use Prisma schemas and Kysely for ubiquitous database access. Different platforms/modules can extend the schema as needed.

Be sure to get some observability tooling around your queries.

It's up to you how you choose to implement your database access. It's a good idea to put the boilerplate for setting up the database in its own module. Queries can be defined as actions, so you can have type-safety and universal support for the logic.

## Further reading

- Read [about how-to guides](https://diataxis.fr/how-to-guides/) in the Diátaxis framework
