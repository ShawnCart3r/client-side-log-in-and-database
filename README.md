WordPress Client Registration & Management System

Complete client onboarding and management system for a healthcare marketplace platform. Handles the full lifecycle from registration through verification to admin management.

Features

- Dual-table architecture: Separate Users and VisitorRequests tables with proper relationships
- Multi-criteria filtering: Search by name/email/city, filter by verification status, visit type preference, insurance status
- Bulk operations: Select and delete multiple clients with safety confirmations
- Safe deletion: Unlinks WordPress users without deleting accounts (preserves login capability)
- Advanced admin tools: Real-time stats, recent registration feed, one-click CSV export
- Professional matching: Links clients to preferred healthcare providers during registration
- Insurance tracking: Captures provider details and policy numbers with smart optional fields

What Makes This Different

Unlike the Professionals plugin (separate codebase), this handles client-specific workflows:
- Simpler registration (no NPI, company details)
- Visitor request tracking (preferred provider, insurance details)
- Different verification flow endpoints
- Client-specific admin dashboard

Both systems share the same Users table structure but remain completely independent - demonstrating proper multi-tenant architecture.

Admin Features

- Advanced search: Real-time filtering across multiple fields
- Bulk delete: Safe multi-select deletion with confirmation
- Export filtered results: CSV export respects all active filters
- Dashboard widget: At-a-glance metrics without leaving WP admin
- Relationship preservation: Deletes custom table data but preserves WP user accounts

Built to handle HIPAA-sensitive healthcare client data with proper security and data integrity practices.
