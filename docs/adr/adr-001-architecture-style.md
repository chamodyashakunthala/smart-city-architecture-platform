# ADR-001: Selection of Event-Driven Microservices Architecture

## Status
Accepted

## Context
The disaster management system must handle sudden traffic spikes, partial
failures, and coordination across multiple independent organizations.

## Decision
Adopt an Event-Driven Microservices Architecture.

## Alternatives Considered
- Monolithic Architecture
- Layered Architecture

## Consequences
- Improved scalability and fault tolerance
- Increased operational complexity
- Need for message brokers and monitoring
