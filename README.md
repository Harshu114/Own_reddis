# Own_reddis
⚡ A lightweight in-memory key-value store built in C, inspired by Redis. Supports basic Redis-like commands, custom memory management, and efficient data structures. Perfect for learning internals of databases and distributed caching systems.

# MyRedis

MyRedis is a lightweight, in-memory key-value store implemented in C, inspired by Redis. It provides a simplified Redis-like interface with basic commands for storing, retrieving, and managing data in memory.

## Features
- SET / GET commands
- Expiry support (TTL)
- In-memory hash table implementation
- Custom memory management
- Single-threaded event loop
- Command-line interface (CLI) interaction
- Educational project for understanding database internals

## Goals
- Learn and demonstrate how in-memory databases work
- Build scalable data structures from scratch
- Extend with additional features: lists, sets, pub/sub, persistence, etc.

## Usage
```bash
git clone https://github.com/yourusername/myredis.git
cd myredis
make
./myredis
