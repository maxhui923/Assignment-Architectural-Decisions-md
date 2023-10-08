# Title of ADR
Determining Permissions for the Mobile App

## Status
Proposed

## Context
To provide core functionalities like offline browsing, push notifications, and image caching, the app requires specific permissions.

## Options Considered
• Internet access
• Push notifications
• Device storage
• Camera
• Location

## Decision
The app will request permissions for Internet access, push notifications, and device storage.

## Consequences
Pros:
- Ensures core functionalities work as intended.

Cons:
- Users might be wary of granting permissions; clear communication is essential.

## Rationale
Internet, notifications, and storage permissions are fundamental for the app's core features.

## Follow-Up Actions
- Integrate permissions requests in the app.
- Ensure GDPR and other data protection regulations are followed.