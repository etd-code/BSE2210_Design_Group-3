# ADR 001 — Choose Microservices Architecture:
Date: 2025-09-16  
Status: Proposed  

## Context
USEP must integrate academic, support, and community services, scale for international students, and evolve beyond 2025.

## Decision:
Adopt a microservices architecture with an API Gateway and bounded services (Course, Timetable, Results, Advising, Community, Payments).

## Rationale:
- Independent deployment for high-change services (like AI Advising).  
- Flexibility in outsourcing (different teams can own different services).  
- Ability to scale each service separately.  

## Consequences:
- More operational complexity (needs strong DevOps).  
- Must manage cross-service contracts carefully.
