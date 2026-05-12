# Salesforce QA Bug Tracker

A QA management app built on Salesforce to track bugs, 
test cases and sprints for a banking portal project.

## What I built
- 4 Custom Objects: Project, Sprint, Bug, Test Case
- 3 Automated Flows for bug lifecycle management
- Custom Lightning App called QA Hub
- 3 Reports and 1 Dashboard for QA metrics

## Objects and relationships
- Project has many Sprints
- Project has many Bugs
- Sprint has many Bugs
- Bug has many Test Cases

## Automation
- Flow 1: Auto stamps Date Reported when bug is created
- Flow 2: Sends email when bug is marked Fixed
- Flow 3: Updates Bug to Verified when Test Case passes

## Sample bugs logged
- BUG-001: Login fails with valid credentials (Critical)
- BUG-002: Password shows in plain text (High)
- BUG-003: Fund transfer allows negative amount (Critical)
- BUG-004: Confirmation email not received (Medium) - Verified
- BUG-005: Session does not expire after inactivity (High)
- BUG-006: Validation error message not descriptive (Low)

## Test cases executed
- TC-001: Verify confirmation email - Pass
- TC-002: Verify no email on failed transfer - Fail
- TC-003: Verify regression after fix - Pass

## Tools used
Salesforce Developer Org, Flow Builder, 
Lightning App Builder, Report Builder
