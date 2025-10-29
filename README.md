TheraConnect – Client Registration & Management System

A complete client onboarding and management solution for healthcare marketplace platforms.
Built as a custom WordPress plugin, this system handles the entire lifecycle — from client registration and verification to administrative management — with an emphasis on data integrity, security, and usability.

🚀 Overview

This plugin powers secure client onboarding for healthcare environments.
It enables clients to register, verify their email, manage provider preferences, and store optional insurance details — all while giving administrators full control through searchable tables, reporting tools, and safety-focused data operations.

🧩 Core Features

Dual-Table Architecture
Two purpose-built database tables (tc_users and tc_visitor_requests) maintain clean separation between base user info and client-specific data, ensuring scalability and normalization.

Email Verification Workflow
Secure token creation and verification logic prevents unauthorized access.
Clients must verify before any WordPress login or data interaction.

Multi-Criteria Search & Filters
Admins can filter by name, email, city, insurance status, visit type, or verification state.

Bulk Operations with Safety Checks
Supports selecting multiple records for deletion with nonce validation and confirmation prompts.

Safe Deletion Logic
Removes client records from custom tables while safely unlinking (not deleting) their WordPress user accounts — preserving login credentials and minimizing data loss risk.

Professional Matching Integration
Each client can be linked to a preferred healthcare professional or provider directly at registration.

Insurance Tracking
Captures optional insurance provider details and policy numbers with smart validation for partial or unknown entries.

Admin Dashboard Tools
Full-featured interface with live stats, search, pagination, export, and at-a-glance metrics via dashboard widget.

⚙️ Technical Stack

Language: PHP 7.4+

Platform: WordPress 5.8+

Database: MySQL (custom tables with schema verification)

Frontend: HTML5, CSS3 (responsive)

Integration: WordPress authentication & admin hooks

Security Layer: Nonces, sanitization, prepared queries, hashed verification tokens

🧠 What This Plugin Does

Handles client registration and validation

Normalizes and stores client data into custom tables

Links each client to their selected provider or professional

Creates or links a WordPress user account for login capability

Sends secure verification links with hash-based validation

Blocks unverified users from accessing the platform

Provides admins with search, reporting, and export functionality

Displays real-time metrics and recent registrations in the WP dashboard

🛠️ Key Engineering Challenges Solved
Challenge	Solution
Data Segregation	Maintains clients and professionals in separate, isolated systems while using a shared user schema
Verification State Management	Uses HMAC-hashed tokens with single-use validation logic
Data Integrity	Handles NULL vs. 0/1 insurance states correctly; avoids coercion or data loss
User Preservation	Unlinks but never deletes WordPress user accounts when removing client data
Bulk Safety	Nonce-protected mass actions to prevent accidental or malicious data removal
Efficient Filtering	Optimized indexed queries for searching by multiple criteria simultaneously
Scalable Exporting	CSV export respects current filters and paginated results for precise reporting
🔐 Security and Compliance Notes

Built with WordPress security best practices: nonces, input sanitization, and prepared SQL statements.

Email verification and rate limiting prevent abuse or enumeration.

Designed to protect sensitive data, but not a certified HIPAA solution.
Full HIPAA compliance requires dedicated hosting, encryption at rest, and a Business Associate Agreement (BAA) with the provider.

🧾 Admin Tools

Advanced filtering and multi-field search

Safe bulk deletion with confirmation dialogs

CSV export (respects all active filters)

Verification status tracking

Dashboard snapshot widget (total, verified, unverified counts + latest signups)

Simple, secure, and responsive admin interface

📦 Summary

The TheraConnect Client Registration & Management System delivers a secure, scalable, and intuitive onboarding experience tailored for healthcare clients.
It complements the Professional Registration System while maintaining strict separation of roles and data — demonstrating a proper multi-tenant architecture inside WordPress.

Both systems work independently yet share a unified design philosophy:
security, clarity, and professional-grade control.
