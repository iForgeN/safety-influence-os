# Database Schema

Detailed PostgreSQL schema for the Safety Influence OS.

See the full outline in project planning for tables: organizations, users, projects, stakeholders, communications, frontline_signals, accountability_entries, audit_logs, etc.

## Core Design
- Multi-tenancy via org_id
- UUID primary keys
- JSONB for flexible fields
- Full audit logging