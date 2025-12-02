# MAPFRE-Insurance-Project
The MAPFRE Insurance Project leverages Guidewire Suite for monitoring insurance operations and ServiceNow for logging and managing operational issues. This integration ensures real-time visibility, efficient issue tracking, and timely resolution across policy, billing, and claim workflows.
🔹 Key Components:
✔ 🟦 Guidewire PolicyCenter, BillingCenter, ClaimCenter – Used for job/status monitoring across policies, billing, and claims:
 • PolicyCenter – Monitors the status of insurance policies and related jobs.
 • BillingCenter – Tracks billing-related job statuses and payment workflows.
 • ClaimCenter – Oversees the status of claims processing jobs and updates.
 • Job Status Colors: 🟢 Passed, 🟡 In Progress, 🔴 Failed. For example, if three jobs are running and one turns 🔴 (failure) while others are 🟦 (running) and 🟢 (passed), the system highlights the failed job for immediate attention.

✔ 🟩 ServiceNow (Ticketing Tool) – Used for logging, tracking, and resolving incidents, service requests, and operational issues.
✔ 🟨 MAPFRE Implementation – Tracking workflows and improving operational oversight.

📊 Additional Enhancements:
✔ 📁 Excel Documentation & Reports – Detailed tracking of job statuses, performance metrics, and operational data.
✔ 🎯 Bug Monitoring via ServiceNow Tickets – Categorizing issues by priority:

🔴 Critical (High Priority) – Urgent resolution required for major system failures.
🟠 Major (Medium Priority) – Significant but non-blocking issues affecting processes.
🟡 Minor (Low Priority) – Small-scale bugs with minimal impact.

By combining Guidewire & ServiceNow, the MAPFRE project improved operational monitoring, reporting, and real-time issue tracking.
MAPFRE-Insurance-Project/
│
├── 1_Guidewire-Monitoring/
│   ├── README.md
│   ├── PolicyCenter.md
│   ├── BillingCenter.md
│   ├── ClaimCenter.md
│   ├── Job-Status-Monitoring.md
│   └── Screenshots/
│
├── 2_ServiceNow-Ticketing/
│   ├── README.md
│   ├── Ticketing-Workflow.md
│   ├── Priority-Levels.md
│   ├── Incident-LifeCycle.md
│   └── Screenshots/
│https://github.com/nemani1997/MAPFRE-Insurance-Project
