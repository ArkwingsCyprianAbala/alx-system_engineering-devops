Issue Summary
On 14th February 2024 at 9AM (EAT), our software company experienced a severe issue with our server that lasted for one hour. This resulted in a system outage, impacting multiple clients. The root cause was some of the aging infrastructure we had in the company.  This postmortem report aims to analyze the incident, propose corrective actions to prevent recurrence.
Timeline (EAT).
14th February, 9:00AM: Our clients started receiving a http 500 error.
14th February, 9:15AM: Our customer service support informed on the issue by our clients.
14th February, 9:20AM: HTTP 500 error confirmed; mitigation measures initiated.
14th February, 9:24AM: Collaborated with the hardware team to replace the faulty parts on the server.
14th February, 9:30AM: Mitigation efforts ongoing; services still experiencing intermittent downtime.
14th February, 10:00 AM: Successfully fixed the server; services gradually restored.
Root Cause.
The root cause to the problem was our aging infrastructure that had not been looked into for a while and needed an upgrade on the hardware. This was corrected by replacing the faulty parts on the server with new ones which brought the server back to normal working condition.
Corrective and Preventive Measures.
Migration to Cloud Services: Consider migrating server workloads and applications to cloud-based platforms or Infrastructure-as-a-Service (IaaS) providers.
Hardware Upgrades: Replace or upgrade outdated server hardware components
Virtualization and Consolidation: Implement server virtualization technologies to consolidate multiple physical servers into virtual machines running on fewer hardware resources.
Monitoring and Maintenance: Deploy server monitoring tools to proactively monitor server health, performance metrics, and resource utilization.
Lifecycle Management: Develop a comprehensive server lifecycle management strategy to systematically retire, replace, or upgrade aging infrastructure components according to predefined schedules, budgets, and technology refresh cycles.


