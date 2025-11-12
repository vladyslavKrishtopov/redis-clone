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
- [Getting started](#getting-started)
- [Recommended prerequisites](#recommended-prerequisites)
- [Next steps](#next-steps)
- [Contributing](#contributing)

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

## Who should do this

- Students and engineers seeking a substantive systems project
- Candidates preparing for systems-level interviews
- Curious developers who want to understand how infrastructure works under the hood

## Benefits

- Stronger systems and debugging skills
- Better design decisions for performance-critical code
- A concrete portfolio project demonstrating low-level engineering ability

## Getting started

1. Explore the repository lessons and source files to follow a step-by-step implementation.
2. Read the code and run examples (if present) to see data structures and networking in action.

If you’d like, I can add an explicit quick-start section with build and run commands once the repository contains the implementation files.

## Recommended prerequisites

- Basic familiarity with C/C++ and compiling C projects
- Comfort reading C-style code and simple Makefiles or build scripts
- Sockets/networking knowledge is helpful but not strictly required — the lessons will walk through networking basics

## Next steps

- Read the lessons and walkthroughs included in this repo.
- Start with the simplest components (a single-threaded server and an in-memory map), then move to richer data structures and concurrency.

## Contributing

Contributions are welcome. Small, focused pull requests (fixes, documentation, small implementations) are easiest to review. If you want to work on a larger piece, open an issue first to discuss the design.

---

Happy hacking — building Redis from scratch is a compact, powerful way to level up as a software engineer.
