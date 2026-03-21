# 2024 Changelog

All product updates, new features, and improvements to the Welkin Health platform.

---

## Version 2024.38.0 — December 11, 2024

**Release Date:** December 11, 2024 — 1:00 AM PST

### New Functionality

**FT-1600: Billing and Invoice Management.** Organizations can now generate and manage patient invoices from the billing module. Invoices support itemized billing for encounters, procedures, and assessments with configurable templates. Invoice status tracking shows sent, viewed, and payment received states with automatic reminders for unpaid invoices.

**FT-1597: Payment Plan Configuration.** Billing administrators can now set up flexible payment plans that allow patients to pay outstanding balances over time. Payment plans support multiple installments with customizable due dates and amounts. Automated reminders notify patients of upcoming and overdue payments.

### Enhancements

**FT-1603: Encounter Archive and Retrieval.** Older encounters can now be archived to improve system performance while remaining searchable and retrievable. Archived encounters are displayed in a separate section of the encounter history with indicators showing archive status. Organizations can configure automatic archival policies based on encounter age.

---

## Version 2024.36.0 — November 13, 2024

**Release Date:** November 13, 2024 — 1:00 AM PST

### New Functionality

**FT-1585: DocuSign Integration for Consents.** Document signing can now be managed through DocuSign integration for patient consents and authorization documents. Documents are automatically sent to patients for e-signature and returned documents are securely stored in patient records. Signature status is tracked and administrators receive notifications when signatures are complete.

**FT-1589: Advanced Patient Demographics Reporting.** Organizations can now generate demographic reports that include age distributions, geographic spread, insurance coverage analysis, and insurance claim status. Reports support filtering by program, care team, and enrollment date ranges. Demographics data can be exported to support population health management initiatives.

### Enhancements

**FT-1592: Improved Encounter Search Across Dates.** Encounter search now supports efficient filtering by date ranges and encounter type combinations. Search results display key encounter details without requiring record opening. Saved search criteria can be applied to future queries for common encounter lookup patterns.

---

## Version 2024.34.0 — October 16, 2024

**Release Date:** October 16, 2024 — 1:00 AM PST

### New Functionality

**FT-1573: Task Template Library.** Organizations can now create and manage a library of task templates for common activities. Task templates support customizable descriptions and can include pre-populated due date offsets relative to task creation. Templates are available when creating new tasks and reduce data entry burden.

**FT-1577: Automated Encounter Reminders.** Encounter reminders can now be automated based on encounter type and scheduled date. Reminders support customizable timing (24 hours, 1 week before) and delivery channels (SMS, email). Patients can confirm attendance directly from reminder messages reducing no-shows.

### Enhancements

**FT-1580: Performance Improvements for Large Patient Cohorts.** The platform now optimizes performance when working with organizations managing large patient populations over 10,000 records. Query performance improvements reduce dashboard load times by 40% and list view filtering responds in under 1 second. Database indexing enhancements improve search speed.

---

## Version 2024.32.0 — September 18, 2024

**Release Date:** September 18, 2024 — 1:00 AM PST

### New Functionality

**FT-1561: Custom Assessment Question Types.** Assessment builders can now create custom question types beyond standard multiple choice and yes/no formats. Custom types include matrix questions, ranking questions, and image-selection questions. Custom types maintain scoring logic and integrate with branching conditions.

**FT-1565: Patient Communication Preferences.** Patients can now set communication preferences specifying preferred contact methods, best times to reach them, and topics they wish to discuss. Care team members see preferences on the patient profile before initiating contact. Communication compliance rules enforce preferences to prevent contact violations.

### Enhancements

**FT-1568: Calendar Sync with External Providers.** Care team members can now sync their Welkin calendar with external calendar systems including Google Calendar and Outlook. Synced appointments appear in both systems ensuring care team members see all scheduled commitments. Sync direction is configurable as one-way or bidirectional.

---

## Version 2024.30.0 — August 21, 2024

**Release Date:** August 21, 2024 — 1:00 AM PST

### New Functionality

**FT-1549: Webhook Integration Framework.** External systems can now subscribe to events from the Welkin platform including patient enrollment, assessment completion, and task assignment. Webhook payloads include full event context and can be filtered by event type. Webhook management includes delivery logs and retry configuration.

**FT-1553: Program Module Reporting Tools.** Program managers can now access a comprehensive set of reports on program enrollment, phase progression, and outcome metrics. Reports support cohort analysis comparing outcomes across patient groups. Data exports support common formats for use in external analytics tools.

### Enhancements

**FT-1556: Assessment Export to PDF.** Completed assessments can now be exported as formatted PDF files suitable for printing and sharing with patients or external providers. PDFs include assessment title, questions, responses, and calculated scores. Export formatting is customizable by organization.

---

## Version 2024.28.0 — July 24, 2024

**Release Date:** July 24, 2024 — 1:00 AM PST

### New Functionality

**FT-1537: Role Permission Granularity Enhancements.** Organization administrators can now configure permissions at a finer level of granularity including read-only versus edit access for specific modules. Roles can restrict access to patient data by program or care team assignment. Permission violations are logged and reported to administrators.

**FT-1541: Automated Program Phase Transitions.** Program designers can configure rules that automatically transition patients to the next program phase based on completion criteria. Transitions can be triggered by task completion, assessment score thresholds, or calendar dates. Automated transitions log completion of prior phases and begin new phase workflows.

### Enhancements

**FT-1544: Improved Patient Education Content Library.** The patient education content library now supports custom organization-specific materials in addition to built-in templates. Content can be organized into categories and tagged for easy search. Patients can view assigned education materials in a dedicated portal section.

---

## Version 2024.26.0 — June 26, 2024

**Release Date:** June 26, 2024 — 1:00 AM PST

### New Functionality

**FT-1525: Enhanced CDT Field Types.** Custom Data Types now support additional field types including nested objects, arrays of values, and rich text fields. Field validation supports custom regex patterns and cross-field dependencies. Field descriptions and examples guide users completing CDT records.

**FT-1529: Assessment Library with Sharing.** Organizations can now create assessment templates and share them with other organizations in their network. Shared assessments are marked as read-only in recipient organizations but can be cloned for customization. Sharing audit logs track template usage across organizations.

### Enhancements

**FT-1532: Improved Notification Delivery Reliability.** Notification delivery now supports retry logic with exponential backoff for failed attempts. Delivery failures are logged with status codes to enable troubleshooting. Administrators receive reports of delivery failures requiring intervention.

---

## Version 2024.24.0 — May 29, 2024

**Release Date:** May 29, 2024 — 1:00 AM PST

### New Functionality

**FT-1513: SMS Message Delivery Tracking.** SMS messages now include delivery status indicators showing queued, sent, delivered, and failed states. Failed messages display error codes and support retry functionality. Delivery analytics show success rates and common failure reasons.

**FT-1517: Email Template Variables and Personalization.** Email templates now support dynamic variables that populate with patient and team member information. Template authors can include conditional sections that display based on patient attributes. Preview functionality shows rendered emails before sending.

### Enhancements

**FT-1520: Encounter Activity Timeline.** Encounters now display a detailed activity timeline showing all actions taken including assessments completed, CDT records updated, and notes added. Activity entries include timestamps and performing user information. Timeline provides audit trail for care delivery oversight.

---

## Version 2024.22.0 — May 1, 2024

**Release Date:** May 1, 2024 — 1:00 AM PST

### New Functionality

**FT-1501: Care Team Workload Visualization.** Care team managers can now see a dashboard displaying open task counts, patient caseload, and upcoming appointments by team member. Workload data identifies over-allocation and supports load balancing decisions. Workload trends over time reveal staffing needs.

**FT-1505: Multi-Organization Administration.** Super administrators can now view and manage multiple organizations from a single dashboard. Organization switcher allows quick navigation between organizations with distinct environments. Cross-organization reports support network-wide analytics.

### Enhancements

**FT-1508: Bulk Assessment Creation from Template.** Assessment designers can now bulk create assessment instances across multiple patient cohorts from a single template. Bulk operations include progress tracking and generate completion reports identifying assessment assignments. Assessment completion reminders are automatically triggered.

---

## Version 2024.20.0 — April 3, 2024

**Release Date:** April 3, 2024 — 1:00 AM PST

### New Functionality

**FT-1489: Appointment No-Show Tracking.** The calendar module now tracks appointment no-shows and allows care team members to mark appointments as attended, completed, cancelled, or no-show. No-show analytics identify patterns and prompt follow-up contact. Organizations can configure automatic task creation for no-shows.

**FT-1493: Patient Communication Portal.** Patients can now access a secure patient portal to view assigned assessments, read educational materials, and respond to care team messages. Portal messaging creates communication threads for organized conversations. Patients can request document access through the portal.

### Enhancements

**FT-1496: Improved Automation Rule Testing.** Automation rules can now be tested against sample patient data before publication. Test results show which actions would be triggered by specific patient states. Dry-run mode allows validation without modifying real patient data.

---

## Version 2024.18.0 — March 6, 2024

**Release Date:** March 6, 2024 — 1:00 AM PST

### New Functionality

**FT-1477: Advanced CDT Search and Query.** CDT records can now be searched and filtered using complex query syntax supporting logical operators. Saved searches preserve filter criteria for common lookups. Search results can be exported for external analysis.

**FT-1481: Patient Insights Dashboard.** Patients enrolled in programs can access a personalized insights dashboard showing their program progress, completed assessments, and upcoming tasks. Dashboard displays goals and tracks progress toward defined outcomes. Patient dashboards support customization by care team members.

### Enhancements

**FT-1484: Improved Automation Logging and Debugging.** Automation execution now logs detailed step-by-step information showing inputs, outputs, and branching decisions. Automation logs identify where rules may be failing or not triggering as expected. Debug mode can be enabled per automation rule for detailed troubleshooting.

---

## Version 2024.16.0 — February 7, 2024

**Release Date:** February 7, 2024 — 1:00 AM PST

### New Functionality

**FT-1465: Program Enrollment Workflows.** Programs can now be configured with enrollment workflows that collect information from patients before finalizing enrollment. Enrollment workflows can include assessments, questionnaires, and consent forms. Incomplete enrollments are saved as drafts allowing patients to resume later.

**FT-1469: Enhanced Report Builder.** The report builder now supports more advanced filtering, sorting, and grouping options. Reports can combine data from multiple modules including patients, encounters, assessments, and programs. Report results can be exported in multiple formats including CSV, Excel, and PDF.

### Enhancements

**FT-1472: Improved API Documentation.** API documentation now includes code examples in multiple programming languages and interactive API explorer for testing endpoints. Endpoint documentation shows request and response formats with sample data. Changelog tracks new and modified API endpoints.

---

## Version 2024.14.0 — January 10, 2024

**Release Date:** January 10, 2024 — 1:00 AM PST

### New Functionality

**FT-1453: Single Sign-On (SSO) Authentication.** Organizations can now configure SSO using SAML 2.0 or OpenID Connect protocols. SSO configuration supports organization-level enforcement requiring all users to log in through the SSO provider. User provisioning during SSO login creates accounts automatically in Welkin.

**FT-1457: Task Assignment and Reassignment.** Tasks can now be assigned to specific care team members with due dates and priority levels. Task assignments can be changed by supervisors or team members with delegation permissions. Task assignment changes are logged with timestamp and performing user information.

### Enhancements

**FT-1460: Mobile Responsive Design Improvements.** The Welkin platform now supports improved mobile responsiveness across all major modules. Touch-optimized controls improve usability on mobile devices. Mobile browser support includes iOS Safari, Android Chrome, and Firefox Mobile.

