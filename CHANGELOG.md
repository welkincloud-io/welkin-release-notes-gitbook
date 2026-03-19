# Welkin Health — Changelog

All product updates, new features, and improvements to the Welkin Health platform.

---

## Version 2026.71.0 — March 5, 2026

**Release Date:** March 5, 2026 — 1:00 AM PST

### New Functionality

**FT-2580: Question Groups in Assessments.** Assessment builders can now organize questions into named groups within a single assessment. Groups can be collapsed and expanded by the care team member completing the assessment, making long assessments easier to navigate. Group names appear as section headers and are included in exported assessment records.

### Enhancements

**FT-2583: Bulk Export of Patient Records.** Care team administrators can now export multiple patient records simultaneously from the patient list view. Exports include all structured data fields, CDT records, and encounter summaries. Export jobs run asynchronously and deliver a download link via in-app notification when complete.

---

## Version 2026.70.0 — February 19, 2026

**Release Date:** February 19, 2026 — 1:00 AM PST

### New Functionality

**FT-2571: Role-Based Dashboard Configuration.** Organization administrators can now configure which dashboard widgets are visible to each role. Widgets can be set as required, optional, or hidden per role. Individual users can further personalize their view within the bounds set by their role configuration.

**FT-2573: Automated Outreach Campaigns.** Program builders can now define automated outreach campaigns that send a sequence of SMS or email messages to patients based on program enrollment, phase transitions, or calendar proximity. Campaign steps support conditional branching based on patient response or lack of response within a defined window.

### Enhancements

**FT-2576: Assessment Scoring Improvements.** Scoring logic for assessments now supports weighted scoring across question groups. Score thresholds can trigger automated flags visible to the assigned care team member. Scores are displayed on the assessment summary and included in patient timeline entries.

**FT-2578: Worklist Filter Persistence.** Filters applied to the worklist view now persist across sessions for each user. Users can also save named filter sets and switch between them from a dropdown at the top of the worklist. Saved filters are user-specific and do not affect other team members' views.

---

## Version 2026.68.0 — February 5, 2026

**Release Date:** February 5, 2026 — 1:00 AM PST

### New Functionality

**FT-2562: Encounter Workflow Templates.** Encounter types can now be configured with step-by-step workflow templates that guide care team members through a defined sequence of actions, including assessments, CDT updates, and task creation. Templates support conditional steps that appear based on values entered earlier in the workflow.

**FT-2564: Patient Communication History View.** A unified communication history panel is now available on each patient profile, displaying all SMS messages, emails, and chat messages in a single chronological timeline. Each entry shows the channel, direction, timestamp, and the team member who sent the message if applicable.

### Enhancements

**FT-2567: Improved Calendar Conflict Detection.** The calendar now detects and surfaces scheduling conflicts across all calendar types for a given care team member, including encounters, tasks with due dates, and blocked time. Conflicts are highlighted in the scheduling modal before the appointment is confirmed.

---

## Version 2026.67.0 — January 22, 2026

**Release Date:** January 22, 2026 — 1:00 AM PST

### New Functionality

**FT-2551: Program Enrollment Automation Rules.** Designers can now configure automation rules that enroll patients in a program or advance them to a new program phase based on CDT field values, assessment scores, or calendar events. Rules are evaluated in real time when the triggering condition is met and support multi-condition logic with AND/OR operators.

**FT-2553: Enhanced SMS Message Templates.** SMS message templates now support dynamic variables that pull from patient profile fields, CDT records, and program data. Template authors can preview rendered messages for a specific patient before saving. Templates marked as active are available to care team members when composing messages.

### Enhancements

**FT-2556: Task Due Date Sorting.** The task list now defaults to sorting by due date ascending, with overdue tasks surfaced at the top regardless of sort selection. Users can override the sort order for the current session. Overdue tasks are visually distinguished with a color indicator on the due date field.

---

## Version 2026.65.0 — January 8, 2026

**Release Date:** January 8, 2026 — 1:00 AM PST

### New Functionality

**FT-2540: Bulk Reassignment of Care Team Tasks.** Administrators can now reassign open tasks in bulk from one care team member to another. The reassignment tool is accessible from the task list and supports filtering by assignee, task type, and due date range before confirming the reassignment.

**FT-2543: Patient Profile Custom Fields.** Organization designers can now add custom fields to the patient profile using the existing CDT framework. Custom fields are displayed in a configurable section on the patient profile page and support all standard CDT field types including text, number, date, and single-select.
