# High-Level System Components – Disaster Management System

## 1. Citizen Reporting Service
Provides interfaces (mobile/web) for citizens to report emergencies, including
location, type of incident, and severity.

## 2. Event Processing Service
Acts as the central event handler, consuming emergency reports and triggering
appropriate actions using event-driven messaging.

## 3. Notification & Alert Service
Sends real-time alerts and notifications to rescue teams, hospitals, and
authorities based on event severity and location.

## 4. Coordination & Command Dashboard
Provides emergency coordinators with real-time visibility into incidents,
resources, and response progress.

## 5. Data Storage Layer
Stores emergency reports, user data, resource status, and historical data for
analysis and auditing.

## 6. External Integration Layer
Integrates with external systems such as weather services, mapping APIs, and
telecommunication providers.
