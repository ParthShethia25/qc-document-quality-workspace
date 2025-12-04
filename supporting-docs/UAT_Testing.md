# Acceptance Criteria & UAT

Scenario: Customer fixes invoice
Given invoice is failed
When customer edits and retries
Then invoice moves to processing

Scenario: Permission
Given viewer role
When opening document
Then fields are read-only

Regression:
Successful documents never appear in QC workspace