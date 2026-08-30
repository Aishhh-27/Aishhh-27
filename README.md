# Hey, I'm Aishwarya

I like figuring out how things work under the hood, especially when something breaks and I have to figure out why.

My background is in technical support, systems, cloud infrastructure, troubleshooting, and automation. Recently I've been spending more time building things with Rust because I wanted to understand the systems I'm working with at a deeper level.

## What I've been building lately

### [Rust Edge Proxy](https://github.com/Aishhh-27/rust-edge-proxy)

A small asynchronous proxy written in Rust and Tokio.

I started this project to get more comfortable with network connections, forwarding traffic between services, handling concurrent connections, and adding some basic observability.

### [Rust Distributed Load Balancer](https://github.com/Aishhh-27/rust-distributed-load-balancer)

A TCP load balancer that distributes connections across multiple backend services.

It supports round-robin and least-connections routing, along with health checks and backend failure recovery. I also added metrics and a Docker Compose setup so I could run the whole thing locally.

### [Rust Distributed Routing](https://github.com/Aishhh-27/rust-distributed-routing)

A small routing service that runs as multiple nodes and keeps routing information replicated between them.

While building this one, I spent more time thinking about what happens when nodes fail, when updates arrive out of order, and what happens when a node comes back after being unavailable.

It uses versioned updates, deletion tombstones, peer health checks, and state recovery.

## Things I use

**Rust** · **Tokio** · **Axum** · **TCP** · **Async I/O** · **Linux** · **Docker** · **Prometheus** · **Python** · **Bash**

## How I learn

I usually learn by building something small and then trying to break it.

If something doesn't work, I want to understand what happened rather than just patching the error. That's been a useful way for me to learn more about networking, Rust, Linux, and distributed systems.

I'm still learning and building one project at a time.

---

Currently building, breaking, debugging, and learning.
