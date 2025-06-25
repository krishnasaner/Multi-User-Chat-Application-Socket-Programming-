# Multi-User-Chat-Application-Socket-Programming-
# Real-Time Chat Application (Python Socket + Threading)

A real-time TCP chat server-client system built using Python's `socket` and `threading` libraries. The application supports multiple concurrent clients, username-based identification, and basic moderation commands for server control.

## Overview

This project implements a simple messaging system where clients can connect to a central server, exchange messages in real time, and be managed by moderation tools. It demonstrates core concepts in networking, multithreading, and concurrency in Python.

## Features

- Real-time message broadcasting to all connected clients
- Unique username prompt on client connection
- Support for simultaneous multiple clients
- Server-side moderation commands:
  - Kick users
  - Broadcast server messages
  - View active connections
- Graceful disconnection and error handling

## Tech Stack

| Component | Technology      |
|----------|------------------|
| Language  | Python 3.x       |
| Network   | TCP Sockets      |
| Concurrency | `threading` module |



