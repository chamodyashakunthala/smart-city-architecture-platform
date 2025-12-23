# Architecture Style Selection – Disaster Management System

## Selected Architecture
Event-Driven Microservices Architecture

## Justification

### Scalability
Microservices allow independent scaling of critical components such as
emergency reporting, alert distribution, and dashboard services during
disaster events.

### Fault Tolerance
Failure of one service (e.g., notification service) does not bring down the
entire system, which is essential during emergencies.

### Event-Based Communication
Disaster systems are driven by events (emergency reports, alerts, status
updates). Event-driven architecture allows services to react asynchronously
to these events in real time.

### Organizational Flexibility
Different organizations (police, hospitals, NGOs) can own and manage separate
services without tight coupling.

### Resilience
Asynchronous messaging ensures the system remains functional even under
network instability or partial outages.

## Alternative Considered: Monolithic Architecture

### Reason for Rejection
A monolithic architecture would introduce a single point of failure and
limit scalability during sudden disaster-related traffic spikes.

## Alternative Considered: Layered Architecture

### Reason for Rejection
While layered architecture improves maintainability, it does not handle
asynchronous event processing and large-scale distributed coordination
effectively during disasters.
