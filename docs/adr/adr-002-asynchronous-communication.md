# ADR-002: Use of Asynchronous Messaging

## Status
Accepted

## Context
Synchronous communication may fail under unstable network conditions during
disasters.

## Decision
Use asynchronous event messaging between services.

## Alternatives Considered
- Direct REST calls

## Consequences
- Increased resilience
- Eventual consistency
- More complex debugging
