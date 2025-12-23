# Event and Data Flow – Disaster Management System

## Event Flow: Emergency Reporting

1. A citizen submits an emergency report using a mobile or web interface.
2. The Citizen Reporting Service validates the request and publishes an
   EmergencyReported event.
3. The Event Processing Service consumes the event and evaluates severity,
   location, and resource requirements.
4. The Notification & Alert Service subscribes to the event and sends alerts
   to relevant rescue teams and hospitals.
5. The Coordination Dashboard updates in real time to reflect the new incident.
6. The Data Storage Layer persists the report and related metadata.

## Event Flow: Rescue Operation Update

1. A rescue team updates the status of an assigned task.
2. The update triggers a RescueStatusUpdated event.
3. The Coordination Dashboard refreshes the operational view.
4. Notifications are sent if escalation or reassignment is required.
