# redis-clone

A compact, hands-on project for learning systems programming by building a Redis-like server from scratch.

## Table of Contents

- [About](#about)
- [Learning goals](#learning-goals)
- [What is Redis?](#what-is-redis)
- [Why build Redis from scratch?](#why-build-redis-from-scratch)
- [Why C/C++?](#why-cc)
- [Who should do this](#who-should-do-this)
- [Benefits](#benefits)

## About

This repository guides you through implementing a Redis-style in-memory data-structure server. The aim is to teach practical systems skills by building a real piece of infrastructure rather than assembling high-level libraries.

## Learning goals

- Network programming: sockets, protocols, and building services that operate across machines (HTTP, RPCs, databases, distributed systems).
- Data structures: implement and use hash tables, lists, sorted sets and other primitives in real use cases (caching, ranking, list pagination).

## What is Redis?

Redis is an in-memory key-value store commonly used for caching and fast data access. Unlike a plain map<string,string>, Redis supports rich value types (hashes, lists, sorted sets), which makes it a data-structure server suitable for many real-world patterns.

## Why build Redis from scratch?

Implementing the core yourself gives deep understanding of design trade-offs, performance bottlenecks, and debugging techniques. These fundamentals make you a stronger engineer and expand the kinds of systems you can build and maintain.

## Why C/C++?

C/C++ provide the low-level control required for high-performance software. The code in this project is primarily plain C with minimal, optional C++ features so it stays readable even if you’re new to these languages. Higher-level languages (Go, Python, JavaScript) can teach parts of the stack but often hide the low-level details this project aims to surface.

## Benefits

- Stronger systems and debugging skills
- Better design decisions for performance-critical code
- A concrete portfolio project demonstrating low-level engineering ability

---

Happy hacking — building Redis from scratch is a compact, powerful way to level up as a software engineer.
