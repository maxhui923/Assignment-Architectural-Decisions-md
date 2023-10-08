# Title of ADR
Deciding Data Storage Methods for the Mobile App

## Status
Proposed

## Context
A reliable data storage method ensures user data is stored securely and is accessible for offline usage.

## Options Considered
• SQLite
• MongoDB
• PostgreSQL
• Realm

## Decision
SQLite for local offline data storage and MongoDB for backend storage.

## Consequences
Pros:
- SQLite is lightweight, perfect for local storage.
- MongoDB is scalable and flexible for backend storage.

Cons:
- Requires synchronization logic between local and backend storage.

## Rationale
SQLite and MongoDB offer the right combination of local and backend storage capabilities for the app.

## Follow-Up Actions
- Set up SQLite for local storage.
- Configure MongoDB for backend data storage.
- Develop data synchronization logic.
