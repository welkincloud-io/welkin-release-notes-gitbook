# 2025 Changelog

All product updates, new features, and improvements to the Welkin Health platform.

---

## Version 2025.63.0 — December 10, 2025

**Release Date:** December 10, 2025 — 1:00 AM PST

### New Functionality

**FT-2301: Territory-Based Patient Routing.** Organizations can now configure nested territory hierarchies that automatically route new patient enrollments to appropriate care team members. Territory assignment rules support criteria based on patient geography, program type, and care team availability. The territory routing engine prevents double-assignment and maintains historical records of territory changes.

**FT-2305: E-Signature Integration for Documents.** Documents uploaded to patient records now support embedded e-signature requests through DocuSign integration. Care team members can configure which document types require e-signature, set expiration dates, and track signature status from the document list. Signed documents are automatically archived with timestamp verification.

### Enhancements

**FT-2308: Enhanced Mobile Push Notifications.** Push notification preferences are now fully configurable per notification type, allowing users to customize frequency, quiet hours, and delivery channels. Notification digest emails consolidate multiple related notifications into a single daily summary delivered at a user-specified time.

---

## Version 2025.61.0 — November 12, 2025

**Release Date:** November 12, 2025 — 1:00 AM PST

### New Functionality

**FT-2290: Multi-Step Automation Workflows.** Automation rules now support sequential actions with configurable delays between steps. Workflows can branch based on intermediate results or patient responses, enabling complex care coordination sequences. Step execution is logged for audit purposes with visibility into timing and outcomes.

**FT-2293: Assessment Template Library.** Assessment builders can now select from a curated library of clinically validated assessment templates covering common screening and monitoring use cases. Templates are fully customizable after selection and can be saved back to the library for organizational reuse. Template versions track changes and allow rollback to previous versions.

### Enhancements

**FT-2297: Improved CDT Field Validation Rules.** Custom validation rules for CDT fields now support regex patterns, conditional requirements based on other field values, and cross-field dependencies. Validation errors are presented in real time as users edit records and prevent invalid data submission. Rules are configured in the CDT designer with preview capability.

---

## Version 2025.59.0 — October 15, 2025

**Release Date:** October 15, 2025 — 1:00 AM PST

### New Functionality

**FT-2278: Patient Merge Functionality.** Care team administrators can now merge duplicate patient records after confirming the merge will not result in data loss. The merge process consolidates encounter history, assessment records, and CDT data into a single patient profile. An audit trail records the merge action with timestamp and user who performed the action.

**FT-2282: Webhook Event Delivery Receipts.** The API now supports confirmation that webhook payloads were successfully delivered and processed by subscriber systems. Webhook event log displays delivery status, response codes, and retry attempts for each dispatched event. Failed deliveries automatically retry with exponential backoff over 24 hours.

### Enhancements

**FT-2285: Calendar Availability Templates.** Care team members can now create reusable availability templates that specify working hours, lunch breaks, and buffer time between appointments. Templates can be applied to one or multiple calendar weeks with a single action. Holiday closures and vacation periods can be marked to automatically block time for the duration specified.

---

## Version 2025.57.0 — September 17, 2025

**Release Date:** September 17, 2025 — 1:00 AM PST

### New Functionality

**FT-2266: Field-Level Audit Logging for Security Policies.** Organizations can now configure field-level audit logging that captures every change to sensitive patient data fields, including who made the change, when, and the previous and current values. Audit logs are tamper-evident and retained indefinitely for compliance purposes. Audit reports can be filtered by field, user, date range, and change type.

**FT-2270: Scheduled Report Exports.** Report builders can now schedule reports to run automatically on a recurring basis and deliver results via email or to a secure download portal. Scheduled reports support filtering and formatting customization that persists across scheduled runs. Report recipients can subscribe to or unsubscribe from scheduled emails independently.

### Enhancements

**FT-2273: Document Request Workflows.** Organizations can now define document request workflows that automatically request documents from patients at key moments in their care journey. Workflows support approval routing where designated staff must review submitted documents before marking the request complete. Patient-facing document request templates can include instructions and deadline information.

---

## Version 2025.55.0 — August 20, 2025

**Release Date:** August 20, 2025 — 1:00 AM PST

### New Functionality

**FT-2254: IP Allowlisting Security Policy.** Organizations can now configure IP allowlist rules that restrict platform access to specified IP address ranges. IP allowlist is configurable per organization and supports both IPv4 and IPv6 addresses. Failed login attempts from non-allowlisted IPs are logged and administrators receive alerts for repeated violations.

**FT-2258: Program Auto-Enrollment Based on Criteria.** Program designers can now configure auto-enrollment rules that automatically enroll new patients in one or more programs based on criteria including demographics, CDT values, or assessment results. Auto-enrollment happens at patient creation or when triggering conditions are met. Historical records track which rules triggered enrollment for each patient.

### Enhancements

**FT-2261: Bulk User Provisioning via CSV.** Organization administrators can now upload a CSV file to bulk provision new users or update existing user permissions. The provisioning process validates all data before creating or modifying users, with detailed reports showing success and error rows. Users receive automated welcome emails with credential setup instructions.

---

## Version 2025.53.0 — July 23, 2025

**Release Date:** July 23, 2025 — 1:00 AM PST

### New Functionality

**FT-2242: Custom Data Views with Saved Filters.** Users can now create and save custom views of patient lists, worklists, and reports that preserve filter and sort settings. Custom views can be shared with specific team members or made available to all users in a role. View ownership is tracked and views can be deleted by their creator or administrators.

**FT-2246: MFA Enforcement Policies.** Organization administrators can now enforce multi-factor authentication for all users or specific roles. Enforcement policies support exemptions for service accounts and integration users. MFA status is visible in user management and administrators receive notifications when enforcement is not yet adopted by users.

### Enhancements

**FT-2249: Data Masking for Sensitive Fields.** Organization administrators can configure which patient profile fields are masked for users below a specified permission level. Masked fields display a generic placeholder but retain underlying values for care delivery. Unmasking events are logged for audit purposes when a user with sufficient permissions views masked data.

---

## Version 2025.51.0 — June 25, 2025

**Release Date:** June 25, 2025 — 1:00 AM PST

### New Functionality

**FT-2230: Recurring Appointment Templates.** Care team members can now create recurring appointments from the calendar that automatically generate instances on a specified frequency. Recurring appointments support interval customization (weekly, bi-weekly, monthly) and can be assigned to multiple team members. Individual instances can be edited, rescheduled, or deleted without affecting the template.

**FT-2234: Phase Transition Rules Engine.** Program designers can now define automatic phase transition rules based on time elapsed, assessment scores, CDT field values, or completion of required tasks. Rules are evaluated daily and transitions occur without manual intervention when criteria are met. A transition audit log records all phase changes with timestamps and rule details.

### Enhancements

**FT-2237: Encounter Notes Formatting.** Encounter notes now support rich text formatting including bold, italics, bullet points, and numbered lists. A WYSIWYG editor guides note entry and previews rendered output. Formatted notes maintain structure in PDF exports and are preserved when notes are included in care transition documents.

---

## Version 2025.49.0 — May 28, 2025

**Release Date:** May 28, 2025 — 1:00 AM PST

### New Functionality

**FT-2218: Zoom Integration Improvements.** The Zoom integration now supports launching Zoom calls directly from encounter records and automatically logging the call as a communication event. Call recordings can be requested at meeting initiation and are securely stored as encounter attachments. Call metadata including participant list and duration is captured in the encounter record.

**FT-2222: SMS/Email Template Variables.** Communication templates now support advanced variable substitution including conditional text, date formatting, and data transformations. Template authors can preview rendered messages with sample data and test variables before publishing. Template variable documentation is available in-app with examples of common use cases.

### Enhancements

**FT-2225: New API Endpoints for Care Coordination.** The API now includes endpoints for retrieving patient program enrollment, querying assessment history, and managing task assignments programmatically. New endpoints support filtering, pagination, and bulk operations. Rate limits have been increased to 1000 requests per minute per API key.

---

## Version 2025.47.0 — April 30, 2025

**Release Date:** April 30, 2025 — 1:00 AM PST

### New Functionality

**FT-2206: Recurring Task Templates.** Care team members can now create recurring task templates that automatically generate task instances on a specified schedule. Template instances include description templates that can be customized per patient. Recurring tasks support manual skip or pause options for specific instances without affecting future generations.

**FT-2210: Patient Search with Advanced Filters.** Patient search now supports filtering by program enrollment, care team assignment, last encounter date, and assessment score ranges. Search results display summary information for quick scanning. Saved search filters can be created and shared with team members for common lookup patterns.

### Enhancements

**FT-2213: Automated Care Transition Documents.** Care transition documents can now be configured to auto-generate from encounter notes, assessment results, and program status at discharge or program exit. Generated documents use configurable templates and support approval workflows before sending to external providers. Document generation logs track creation and delivery attempts.

---

## Version 2025.45.0 — April 2, 2025

**Release Date:** April 2, 2025 — 1:00 AM PST

### New Functionality

**FT-2194: CDT Import/Export Capabilities.** Organizations can now export CDT definitions as structured JSON or CSV files for backup or migration to other systems. Import functionality supports bulk CDT creation from formatted files with validation of field definitions. Version control for CDT definitions tracks changes and allows rollback to previous states.

**FT-2198: Assessment Branching Logic.** Assessment designers can now configure conditional display of questions based on answers to prior questions. Branch logic supports simple and complex conditions involving multiple questions with AND/OR operators. Branched assessments display only relevant questions, streamlining the completion experience.

### Enhancements

**FT-2201: Improved Encounter Type Configuration.** Encounter types can now be configured with default status workflows, required data elements, and allowed team member roles. Organizations can enable or disable encounter types per program, restricting types available in specific care contexts. Default workflows reduce data entry errors and ensure consistent documentation.

---

## Version 2025.43.0 — March 5, 2025

**Release Date:** March 5, 2025 — 1:00 AM PST

### New Functionality

**FT-2182: Batch CDT Record Operations.** Care team members can now apply CDT field updates to multiple patient records simultaneously using bulk operations accessible from list views. Bulk operations support filtering and preview before execution. A job status view shows progress and provides detailed reports when operations complete.

**FT-2186: Assessment Response Timing Metrics.** Assessment completion analytics now track response times for individual questions and overall assessment duration. Analytics highlight questions with high abandonment rates or unusually long completion times. Insights help organizations identify assessment usability issues and potential patient confusion points.

### Enhancements

**FT-2189: Program Reporting Dashboard.** Program managers now have access to a dedicated dashboard showing enrollment trends, phase progression rates, task completion rates, and outcome metrics. Dashboard widgets are customizable and support exporting underlying data as CSV files. Historical comparisons help identify program performance trends.

---

## Version 2025.41.0 — February 12, 2025

**Release Date:** February 12, 2025 — 1:00 AM PST

### New Functionality

**FT-2170: SSO Provider Configuration Improvements.** Organizations can now configure multiple SSO providers and enforce provider selection at login. SSO configuration supports just-in-time user provisioning that creates user accounts on first login. Just-in-time provisioning can be configured to assign roles automatically based on SSO attributes.

**FT-2174: Notification Preference Center.** Patients and care team members now have access to a unified notification preference center where they can enable or disable notification categories. Preferences support granular control including frequency thresholds and delivery channel selection. Preferences persist across browser sessions and device logins.

### Enhancements

**FT-2177: Enhanced Patient Profile Search.** The patient profile search function now supports searching across multiple fields including name, medical record number, insurance member ID, and custom CDT fields. Search results are ranked by relevance and display key patient information for quick identification. Search history is tracked to provide suggestions for repeat lookups.

---

## Version 2025.39.0 — January 29, 2025

**Release Date:** January 29, 2025 — 1:00 AM PST

### New Functionality

**FT-2158: CDT Versioning System.** Custom Data Type definitions can now be versioned with change tracking that records which fields were added, modified, or removed in each version. Organizations can roll back to previous CDT versions which affects new instances but preserves historical data integrity. Version history displays change summaries and effective dates.

**FT-2162: Automated Care Team Assignment.** Program designers can configure auto-assignment rules that allocate newly enrolled patients to care team members based on workload, expertise tags, or team availability. Rules support round-robin and weighted assignment strategies. Assignment history is visible on patient profiles and can be reassigned manually if needed.

### Enhancements

**FT-2165: Assessment Score Visualization.** Assessment scores now display in graphical format showing score trajectory over time for tracked assessments. Score visualization includes reference ranges and threshold markings that indicate risk levels. Graphs can be included in patient reports and shared with external providers.

