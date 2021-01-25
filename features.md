---
title: "Features"
draft: true
---

# Features

## Business Continuity

YottaDB’s business continuity and real-time replication features keep even Internet-scale applications continuously available not just in the face of unplanned events, but also planned events, such as application upgrades and even schema changes.

[Learn More](/stands/yottadb/business_continuity)

## Daemon-less

The YottaDB architecture places a premium on speed and responsiveness with a daemon-less, in-memory database engine, streamlining workloads by minimizing latency and parsimoniously using system resources.

## Security

With a philosophy that complexity is the enemy of security, the simply-explained YottaDB security model is based on the mature and easily understood [user-group-world](https://en.wikipedia.org/wiki/File-system_permissions) permissions for processes to access database files. Security can be further enhanced with layered controls like [SELinux](https://en.wikipedia.org/wiki/Security-Enhanced_Linux).

## Multi-Language Database Access

![YottaDB architecture](/stands/yottadb/multi-lang-db-access.svg)

While the historic roots of YottaDB are in the M/MUMPS language, YottaDB extends the tight integration of the language with the database to other languages. As C is the lingua franca of programming languages (in that all programming languages have the ability to call a C API), YottaDB’s C language API extends the database engine to all programming languages. In the future, YottaDB LLC intends to create standard bindings from other languages through the C API.

[Learn More](/stands/yottadb/hello_world)

## Optimistic Concurrency Control

Unlike most high-end transactional database engines, YottaDB uses Optimistic Concurrency Control (OCC) to implement ACID transactions. Since transactions do not typically collide, optimistic techniques scale up better than pessimistic techniques such as locking.

[Learn More](/stands/yottadb/occ)

## Strongly ACID transactions

ACID transactions are YottaDB's strong suit, and give applications a data source they can rely on.

[Learn More](/stands/yottadb/acid)