
# Development Tasks

## Backend
- [ ] Integrate container image scanner (e.g., Trivy, Clair).
- [ ] Build API endpoints for:
  - Fetching image scan results
  - Triggering scans
  - Filtering images by severity
- [ ] Store vulnerability data in a database (PostgreSQL, MongoDB, etc).

## Frontend
- [ ] Create dashboard UI with sortable/filterable table of images.
- [ ] Build details panel for individual image vulnerabilities.
- [ ] Implement scan trigger button and status feedback.
- [ ] Implement filters (severity, name search).

## DevOps
- [ ] Schedule periodic scans using cron or event triggers.
- [ ] Set up containerized deployment pipeline.
- [ ] Configure alerting/notifications (email, Slack integration).

## Bonus (Optional)
- [ ] Export report as CSV or PDF.
- [ ] Integrate with ticketing system (e.g., Jira).
