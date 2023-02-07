# Title

- [General](#general)
- [Quick Links](#quick-links)
- [Code](#code)
- [Deployment](#deployment)
- [Telemetry and Alerting](#telemetry-and-alerting)
- [Backup and Recovery](#backup-and-recovery)
- [Common Tasks](#common-tasks)
- [Ownership and SLAs](#ownership-and-slas)
- [Outages](#outages)
- [Notes](#notes)
- [Links](#links)

## General

Brief description of the workload. How is it used? Who uses it? What other workloads does it interface with? Is it an internal or external application? What environments does this workload have?

## Quick Links

Links to monitoring dashboards, logs or any other links that are commonly used for the application.

## Code

Links to the various repositories where the relevant code is kept.

## Deployment

Where is it? What AWS account is it deployed in? You can include IPs or server names, but if this information changes often or the application is deployed frequently to a new server you can exclude this information. How is it deployed? How is the server or application accessed VPN connectivity?

## Telemetry and Alerting

What telemetry is collected and where is that telemetry found? What is collecting that telemetry? 

What are the thresholds for when an alert will be generated and where does that alert go when it is met? Who is alerted?

The following table summarizes what should be considered. Please try and fill this table out completely.

| Metric                              | Monitoring Mechanism | Alert Threshold | Alert Location |
|-------------------------------------|----------------------|-----------------|----------------|
| Disk Space                          |                      |                 |                |
| Disk Read/Write Speed               |                      |                 |                |
| Network Bytes in/out                |                      |                 |                |
| Memory                              |                      |                 |                |
| CPU Load                            |                      |                 |                |
| Ping                                |                      |                 |                |
| Monitoring Agent has not checked in |                      |                 |                |
| Backup Failed                       |                      |                 |                |

## Backup and Recovery

How is the workload backed up? At what frequency? Where are the backups kept?  Disaster Recovery Plans and procedure. If a service machine died how would you fail-over to the hot/cold spare? Have we practiced a recovery situation? Should we?

## Common Tasks

Any common troubleshooting tasks that this workload regularly experiences. This list should be targeted for future work on the application. Ideally all of these tasks are automated. Please include any patch schedule this workload follows!

## Ownership and SLAs

Who owns the application from both a development and support standpoint? What is the agreed upon time to acknowledge and start troubleshooting an error with the workload? What is the agreed upon time to solve the issue? The (social or real) contract made with customers. Typically things like Uptime Goal (how many 9s), RPO (Recovery Point Objective), RTO (Recovery Time Objective) and SLI (Service Level Indicator).

## Outages

Date and time of any recent outages. A brief description of the outage and a link to the postmortem.

| Date | Description | Postmortem Link | Notes |
|------|-------------|-----------------|-------|
|      |             |                 |       |

## Notes

Any other notes that you would like to include about the workload.

## Links

Any other links you think are relevant to the workload.
