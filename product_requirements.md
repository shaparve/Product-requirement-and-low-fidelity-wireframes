
# Product Requirements Document (PRD)
## Title: Container Image Vulnerability Dashboard

### Overview
This product is designed to help security and DevOps teams detect, understand, and manage vulnerabilities within container images. It provides a dashboard interface to scan and monitor images for known vulnerabilities and prioritize remediation actions based on severity.

---

### Goals
- Identify container images with vulnerabilities.
- Prioritize vulnerabilities by severity (Critical, High, Medium, Low).
- Enable users to filter and act on vulnerable images at scale.

---

### Functional Requirements

1. **Dashboard View**
   - Display all container images with vulnerability summaries.
   - Include columns for image name, scan date, severity breakdown, and fix availability.

2. **Filtering & Search**
   - Filter by severity level (e.g., show only Critical/High).
   - Search images by name or tags.

3. **Details Panel**
   - View all vulnerabilities in a selected image.
   - Include CVE ID, severity, affected packages, and remediation steps.

4. **Remediation Guidance**
   - Show available fixes or updated base images.

5. **Scan Trigger**
   - Ability to manually trigger a scan on any image.

6. **Notification System (optional)**
   - Notify when new vulnerabilities are detected in existing images.

---

### Non-Functional Requirements
- Scalable to handle 10,000+ images.
- Secure access using RBAC (Role-Based Access Control).
- Real-time performance updates.
