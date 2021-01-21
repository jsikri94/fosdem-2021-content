---
title: "Features"
draft: true
---

# Features

## Business Continuity

YottaDB’s business continuity and real-time replication features keep even Internet-scale applications continuously available not just in the face of unplanned events, but also planned events, such as application upgrades and even schema changes.

## Daemon-less

The YottaDB architecture places a premium on speed and responsiveness with a daemon-less, in-memory database engine, streamlining workloads by minimizing latency and parsimoniously using system resources.

## Security

With a philosophy that complexity is the enemy of security, the simply-explained YottaDB security model is based on the mature and easily understood [user-group-world](https://en.wikipedia.org/wiki/File-system_permissions) permissions for processes to access database files. Security can be further enhanced with layered controls like [SELinux](https://en.wikipedia.org/wiki/Security-Enhanced_Linux).

## Optimistic Concurrency Control

Unlike most high-end transactional database engines, YottaDB uses Optimistic Concurrency Control (OCC) to implement ACID transactions. Since transactions do not typically collide, optimistic techniques scale up better than pessimistic techniques such as locking.