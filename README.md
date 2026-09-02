# Hey, I'm Aishwarya 👋

I work on production infrastructure and cloud environments, with a focus on reliability, troubleshooting, automation, and understanding how systems behave when things go wrong.

In my current role at **DXC Technology**, I work with production environments across AWS and GCP. My day-to-day work involves Nginx, Docker, Kubernetes, MariaDB, PostgreSQL/RDS, PHP-based applications, Python, and Bash.

A big part of my work is investigating production issues — service failures, performance problems, slow queries, database locking, resource issues, and availability problems. I’m also involved in on-call support and incident troubleshooting.

Outside of work, I’ve been using **Rust to build systems from the ground up** and get a deeper understanding of networking, concurrency, distributed systems, and failure handling.

## What I've been building

###  Rust Edge Proxy

An asynchronous reverse proxy built with Rust and Tokio.

The project focuses on understanding what happens between a client and backend service, including:

* TCP connection handling
* HTTP request forwarding
* Async I/O and concurrency
* Backend failures
* Timeouts and retries
* Request/response handling
* Basic observability

###  Rust Distributed Load Balancer

A TCP load balancer built in Rust with multiple backend servers.

It implements:

* Round-robin routing
* Least-connections routing
* Backend health checks
* Failure detection
* Backend recovery
* Connection tracking
* Prometheus metrics

The goal was to understand how a load balancer behaves when backends become unhealthy and how traffic can be redistributed without taking the entire service down.

###  Rust Distributed Routing

A small distributed routing system built to explore how nodes maintain and recover shared state.

It covers concepts such as:

* State replication
* Version ordering
* Stale updates
* Deletions and tombstones
* Failure detection
* Node recovery
* State synchronization

I built this primarily as a way to understand distributed systems concepts by implementing and testing them rather than treating them as abstractions.

## Technologies

**Systems & Programming**

Rust · Linux · Python · Bash · Processes · Concurrency · Async I/O

**Networking**

TCP · HTTP · DNS · Reverse Proxies · Load Balancing · Routing

**Infrastructure**

AWS · GCP · Docker · Kubernetes · Nginx

**Databases**

MariaDB · PostgreSQL · RDS

**Web & Application**

PHP · Web Services · REST APIs

**Observability**

Prometheus · Metrics · Logging · Production Troubleshooting

## How I approach systems

I like understanding what is happening underneath the abstraction.

When something fails, slows down, or behaves unexpectedly, I try to trace the problem through the system rather than treating the symptom in isolation — from the application and network layer down to processes, resources, connections, and the underlying system.

I also like deliberately breaking the systems I build. Failure scenarios are often where the interesting engineering problems show up.

## What I'm interested in

* Systems engineering
* Infrastructure
* Networking
* Distributed systems
* Linux and operating systems
* Reliability and failure recovery
* Performance troubleshooting
* Automation
* Observability

**Currently:** building systems, breaking them, debugging them, and learning why they behave the way they do.
