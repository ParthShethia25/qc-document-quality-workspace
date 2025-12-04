# Retool App Structure – QC Workspace

Components:
- Table (documentsTable)
- Dropdown (statusFilter)
- Container (documentDetailPanel)
- TextArea (commentInput)
- Buttons (retryBtn, resolveBtn)

Logic:
- Temporary state for qcDocuments
- Status filtering via dropdown
- Retry sets status = processing
- Resolve sets status = resolved

Role-based access:
- Viewer: read-only
- Editor: full access