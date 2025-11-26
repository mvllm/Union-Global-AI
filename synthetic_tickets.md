# Synthetic Enterprise Ticket Dataset

This file contains 1,000 synthetic support tickets for testing and MCP querying.

```json
[
  {
    "id": "TCK-0001",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-06T04:18:20Z",
    "updated_at": "2025-09-11T10:18:20Z",
    "closed_at": "2025-09-11T10:18:20Z",
    "sla_due_at": "2025-09-06T11:18:20Z",
    "sla_breached": true,
    "requester": "user27@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0002",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-22T07:16:27Z",
    "updated_at": "2025-11-26T07:43:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-22T22:16:27Z",
    "sla_breached": true,
    "requester": "user184@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "sso",
      "problem",
      "change",
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0003",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-05T16:58:20Z",
    "updated_at": "2025-11-10T07:58:20Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T15:58:20Z",
    "sla_breached": true,
    "requester": "user24@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "change",
      "onboarding",
      "network"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0004",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-19T03:48:51Z",
    "updated_at": "2025-09-25T10:48:51Z",
    "closed_at": null,
    "sla_due_at": "2025-09-21T07:48:51Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0005",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-20T05:27:14Z",
    "updated_at": "2025-10-28T08:27:14Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T14:27:14Z",
    "sla_breached": true,
    "requester": "user94@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "vip",
      "sso",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0006",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-08-28T08:45:53Z",
    "updated_at": "2025-09-01T00:45:53Z",
    "closed_at": "2025-09-01T00:45:53Z",
    "sla_due_at": "2025-08-28T21:45:53Z",
    "sla_breached": true,
    "requester": "user42@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "onboarding",
      "bug",
      "request",
      "sso"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0007",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-19T00:01:11Z",
    "updated_at": "2025-11-26T08:04:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-19T08:01:11Z",
    "sla_breached": true,
    "requester": "user146@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "sso",
      "bug",
      "problem"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0008",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-04T15:39:10Z",
    "updated_at": "2025-09-09T22:39:10Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T13:39:10Z",
    "sla_breached": true,
    "requester": "user68@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "incident",
      "vip",
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0009",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-21T14:23:26Z",
    "updated_at": "2025-09-23T23:23:26Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T05:23:26Z",
    "sla_breached": true,
    "requester": "user175@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0010",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-10T15:19:04Z",
    "updated_at": "2025-09-22T11:19:04Z",
    "closed_at": null,
    "sla_due_at": "2025-09-13T14:19:04Z",
    "sla_breached": true,
    "requester": "user175@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "bug",
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0011",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-19T16:31:47Z",
    "updated_at": "2025-11-04T02:31:47Z",
    "closed_at": "2025-11-04T02:31:47Z",
    "sla_due_at": "2025-10-20T16:31:47Z",
    "sla_breached": true,
    "requester": "user129@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "request",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0012",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-05T13:52:32Z",
    "updated_at": "2025-09-09T00:52:32Z",
    "closed_at": null,
    "sla_due_at": "2025-09-06T18:52:32Z",
    "sla_breached": true,
    "requester": "user136@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem",
      "network",
      "security"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0013",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-17T23:38:27Z",
    "updated_at": "2025-10-30T02:38:27Z",
    "closed_at": null,
    "sla_due_at": "2025-10-18T10:38:27Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": null,
    "tags": [
      "access",
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0014",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-09-17T02:20:49Z",
    "updated_at": "2025-09-30T01:20:49Z",
    "closed_at": "2025-09-30T01:20:49Z",
    "sla_due_at": "2025-09-18T15:20:49Z",
    "sla_breached": true,
    "requester": "user139@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "db",
      "onboarding"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0015",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-01T08:41:52Z",
    "updated_at": "2025-09-12T09:41:52Z",
    "closed_at": "2025-09-12T09:41:52Z",
    "sla_due_at": "2025-09-03T11:41:52Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "network",
      "change",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0016",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-12T00:20:28Z",
    "updated_at": "2025-09-25T12:20:28Z",
    "closed_at": null,
    "sla_due_at": "2025-09-12T04:20:28Z",
    "sla_breached": true,
    "requester": "user9@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0017",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-21T14:41:08Z",
    "updated_at": "2025-11-06T01:41:08Z",
    "closed_at": "2025-11-06T01:41:08Z",
    "sla_due_at": "2025-10-22T21:41:08Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "analytics",
      "problem"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0018",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-02T04:55:29Z",
    "updated_at": "2025-11-09T18:55:29Z",
    "closed_at": "2025-11-09T18:55:29Z",
    "sla_due_at": "2025-11-02T20:55:29Z",
    "sla_breached": true,
    "requester": "user187@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "network"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0019",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-14T04:22:50Z",
    "updated_at": "2025-10-25T15:22:50Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T15:22:50Z",
    "sla_breached": true,
    "requester": "user47@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0020",
    "subject": "Email delivery delayed",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-14T06:31:02Z",
    "updated_at": "2025-11-19T08:31:02Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T11:31:02Z",
    "sla_breached": true,
    "requester": "user124@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "network",
      "access",
      "incident",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0021",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-23T15:47:34Z",
    "updated_at": "2025-11-08T06:47:34Z",
    "closed_at": "2025-11-08T06:47:34Z",
    "sla_due_at": "2025-10-25T07:47:34Z",
    "sla_breached": true,
    "requester": "user184@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "sso",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0022",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-18T11:16:18Z",
    "updated_at": "2025-11-19T17:16:18Z",
    "closed_at": "2025-11-19T17:16:18Z",
    "sla_due_at": "2025-11-18T22:16:18Z",
    "sla_breached": true,
    "requester": "user129@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "network",
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0023",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-03T05:51:51Z",
    "updated_at": "2025-11-08T06:51:51Z",
    "closed_at": "2025-11-08T06:51:51Z",
    "sla_due_at": "2025-11-03T17:51:51Z",
    "sla_breached": true,
    "requester": "user146@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0024",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-03T08:25:29Z",
    "updated_at": "2025-10-08T22:25:29Z",
    "closed_at": null,
    "sla_due_at": "2025-10-06T06:25:29Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "bug",
      "analytics"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0025",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-28T20:50:51Z",
    "updated_at": "2025-10-12T03:50:51Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T09:50:51Z",
    "sla_breached": true,
    "requester": "user19@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "access",
      "vip",
      "security"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0026",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-09T21:58:59Z",
    "updated_at": "2025-10-21T12:58:59Z",
    "closed_at": "2025-10-21T12:58:59Z",
    "sla_due_at": "2025-10-10T21:58:59Z",
    "sla_breached": true,
    "requester": "user168@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0027",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-19T04:35:15Z",
    "updated_at": "2025-10-21T11:35:15Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T01:35:15Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "sso",
      "bug",
      "db"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0028",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-22T14:34:20Z",
    "updated_at": "2025-09-23T17:34:20Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T02:34:20Z",
    "sla_breached": true,
    "requester": "user71@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0029",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-05T22:49:17Z",
    "updated_at": "2025-09-17T17:49:17Z",
    "closed_at": "2025-09-17T17:49:17Z",
    "sla_due_at": "2025-09-06T22:49:17Z",
    "sla_breached": true,
    "requester": "user3@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0030",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-18T07:02:50Z",
    "updated_at": "2025-09-21T11:02:50Z",
    "closed_at": "2025-09-21T11:02:50Z",
    "sla_due_at": "2025-09-20T10:02:50Z",
    "sla_breached": true,
    "requester": "user79@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0031",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "high",
    "created_at": "2025-08-30T23:16:26Z",
    "updated_at": "2025-09-11T22:16:26Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T16:16:26Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": null,
    "tags": [
      "access",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0032",
    "subject": "Upgrade request for enterprise license",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-23T01:49:43Z",
    "updated_at": "2025-11-26T07:30:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-24T23:49:43Z",
    "sla_breached": true,
    "requester": "user64@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "analytics",
      "db"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0033",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-09T06:56:57Z",
    "updated_at": "2025-10-19T02:56:57Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T22:56:57Z",
    "sla_breached": true,
    "requester": "user59@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "incident",
      "vip"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0034",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-17T22:11:47Z",
    "updated_at": "2025-11-26T07:38:32Z",
    "closed_at": "2025-11-26T07:38:32Z",
    "sla_due_at": "2025-11-19T22:11:47Z",
    "sla_breached": true,
    "requester": "user8@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "access",
      "change",
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0035",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-12T10:38:19Z",
    "updated_at": "2025-11-19T03:38:19Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T21:38:19Z",
    "sla_breached": true,
    "requester": "user131@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "onboarding",
      "network"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0036",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-25T13:25:46Z",
    "updated_at": "2025-11-26T07:34:32Z",
    "closed_at": "2025-11-26T07:34:32Z",
    "sla_due_at": "2025-11-28T13:25:46Z",
    "sla_breached": false,
    "requester": "user111@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "change",
      "vip",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0037",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-18T13:53:43Z",
    "updated_at": "2025-10-25T13:53:43Z",
    "closed_at": "2025-10-25T13:53:43Z",
    "sla_due_at": "2025-10-20T08:53:43Z",
    "sla_breached": true,
    "requester": "user142@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "incident",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0038",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-01T02:01:22Z",
    "updated_at": "2025-09-18T21:01:22Z",
    "closed_at": "2025-09-18T21:01:22Z",
    "sla_due_at": "2025-09-02T20:01:22Z",
    "sla_breached": true,
    "requester": "user54@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "problem",
      "analytics",
      "db"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0039",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-21T15:07:51Z",
    "updated_at": "2025-09-27T17:07:51Z",
    "closed_at": "2025-09-27T17:07:51Z",
    "sla_due_at": "2025-09-22T16:07:51Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0040",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-08-31T21:03:25Z",
    "updated_at": "2025-09-04T01:03:25Z",
    "closed_at": null,
    "sla_due_at": "2025-09-02T05:03:25Z",
    "sla_breached": true,
    "requester": "user122@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0041",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-06T11:23:58Z",
    "updated_at": "2025-09-14T16:23:58Z",
    "closed_at": "2025-09-14T16:23:58Z",
    "sla_due_at": "2025-09-07T15:23:58Z",
    "sla_breached": true,
    "requester": "user38@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0042",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-03T00:23:29Z",
    "updated_at": "2025-10-17T21:23:29Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T02:23:29Z",
    "sla_breached": true,
    "requester": "user143@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0043",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-27T13:01:16Z",
    "updated_at": "2025-10-07T00:01:16Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T09:01:16Z",
    "sla_breached": true,
    "requester": "user130@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "access",
      "db",
      "problem",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0044",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-25T09:08:33Z",
    "updated_at": "2025-11-05T12:08:33Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T00:08:33Z",
    "sla_breached": true,
    "requester": "user71@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0045",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-26T22:27:58Z",
    "updated_at": "2025-11-07T11:27:58Z",
    "closed_at": null,
    "sla_due_at": "2025-10-28T20:27:58Z",
    "sla_breached": true,
    "requester": "user60@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "security",
      "incident"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0046",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-14T12:36:11Z",
    "updated_at": "2025-10-18T22:36:11Z",
    "closed_at": "2025-10-18T22:36:11Z",
    "sla_due_at": "2025-10-17T03:36:11Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0047",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-26T08:08:40Z",
    "updated_at": "2025-10-04T16:08:40Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T09:08:40Z",
    "sla_breached": true,
    "requester": "user108@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "problem",
      "sso"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0048",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-01T14:40:38Z",
    "updated_at": "2025-10-15T21:40:38Z",
    "closed_at": null,
    "sla_due_at": "2025-10-01T21:40:38Z",
    "sla_breached": true,
    "requester": "user186@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "change",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0049",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-06T10:48:32Z",
    "updated_at": "2025-10-15T14:48:32Z",
    "closed_at": null,
    "sla_due_at": "2025-10-06T17:48:32Z",
    "sla_breached": true,
    "requester": "user47@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "sso",
      "problem",
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0050",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-08T22:13:41Z",
    "updated_at": "2025-10-10T16:13:41Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T07:13:41Z",
    "sla_breached": true,
    "requester": "user139@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "bug",
      "security"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0051",
    "subject": "Application performance degradation",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-22T23:21:21Z",
    "updated_at": "2025-11-26T08:12:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-24T04:21:21Z",
    "sla_breached": true,
    "requester": "user172@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "problem",
      "db"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0052",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-10T02:15:00Z",
    "updated_at": "2025-10-13T14:15:00Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T20:15:00Z",
    "sla_breached": true,
    "requester": "user7@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "incident",
      "db",
      "sso",
      "security"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0053",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-12T21:22:43Z",
    "updated_at": "2025-11-24T23:22:43Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T16:22:43Z",
    "sla_breached": true,
    "requester": "user137@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "security",
      "request",
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0054",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-24T17:03:55Z",
    "updated_at": "2025-11-26T07:41:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-27T11:03:55Z",
    "sla_breached": false,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "change",
      "request",
      "problem"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0055",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-01T10:47:16Z",
    "updated_at": "2025-10-06T16:47:16Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T00:47:16Z",
    "sla_breached": true,
    "requester": "user72@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "problem"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0056",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-14T07:18:51Z",
    "updated_at": "2025-10-18T05:18:51Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T02:18:51Z",
    "sla_breached": true,
    "requester": "user67@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "change",
      "db",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0057",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-24T13:32:57Z",
    "updated_at": "2025-11-26T07:50:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T17:32:57Z",
    "sla_breached": true,
    "requester": "user177@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "problem",
      "network",
      "security",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0058",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-05T23:30:02Z",
    "updated_at": "2025-10-13T20:30:02Z",
    "closed_at": "2025-10-13T20:30:02Z",
    "sla_due_at": "2025-10-07T18:30:02Z",
    "sla_breached": true,
    "requester": "user89@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "vip",
      "db",
      "problem"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0059",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-17T23:12:21Z",
    "updated_at": "2025-10-22T02:12:21Z",
    "closed_at": null,
    "sla_due_at": "2025-10-19T08:12:21Z",
    "sla_breached": true,
    "requester": "user138@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso",
      "analytics"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0060",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-21T10:53:34Z",
    "updated_at": "2025-10-23T14:53:34Z",
    "closed_at": "2025-10-23T14:53:34Z",
    "sla_due_at": "2025-10-24T09:53:34Z",
    "sla_breached": false,
    "requester": "user59@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "onboarding",
      "network"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0061",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-11-09T22:22:18Z",
    "updated_at": "2025-11-21T18:22:18Z",
    "closed_at": null,
    "sla_due_at": "2025-11-10T07:22:18Z",
    "sla_breached": true,
    "requester": "user33@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "security",
      "network",
      "change",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0062",
    "subject": "Password reset request",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-25T16:19:19Z",
    "updated_at": "2025-09-26T19:19:19Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T15:19:19Z",
    "sla_breached": true,
    "requester": "user123@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "problem",
      "security",
      "change",
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0063",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-06T11:52:00Z",
    "updated_at": "2025-11-11T19:52:00Z",
    "closed_at": null,
    "sla_due_at": "2025-11-08T05:52:00Z",
    "sla_breached": true,
    "requester": "user107@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "analytics",
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0064",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-29T16:14:24Z",
    "updated_at": "2025-10-08T20:14:24Z",
    "closed_at": null,
    "sla_due_at": "2025-10-01T10:14:24Z",
    "sla_breached": true,
    "requester": "user16@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0065",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-07T00:40:33Z",
    "updated_at": "2025-09-10T09:40:33Z",
    "closed_at": "2025-09-10T09:40:33Z",
    "sla_due_at": "2025-09-08T13:40:33Z",
    "sla_breached": true,
    "requester": "user20@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0066",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-08-29T10:44:20Z",
    "updated_at": "2025-09-03T09:44:20Z",
    "closed_at": null,
    "sla_due_at": "2025-09-01T02:44:20Z",
    "sla_breached": true,
    "requester": "user180@enterprise.example.com",
    "assignee": null,
    "tags": [
      "bug"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0067",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-23T09:36:05Z",
    "updated_at": "2025-11-04T00:36:05Z",
    "closed_at": "2025-11-04T00:36:05Z",
    "sla_due_at": "2025-10-24T14:36:05Z",
    "sla_breached": true,
    "requester": "user69@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0068",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-17T10:41:39Z",
    "updated_at": "2025-10-27T10:41:39Z",
    "closed_at": "2025-10-27T10:41:39Z",
    "sla_due_at": "2025-10-19T02:41:39Z",
    "sla_breached": true,
    "requester": "user104@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "problem",
      "security",
      "change",
      "network"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0069",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-15T10:22:43Z",
    "updated_at": "2025-10-20T08:22:43Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T22:22:43Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "change",
      "network",
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0070",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-20T08:38:18Z",
    "updated_at": "2025-09-24T05:38:18Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T20:38:18Z",
    "sla_breached": true,
    "requester": "user126@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "vip",
      "incident",
      "analytics",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0071",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-05T20:21:04Z",
    "updated_at": "2025-11-12T00:21:04Z",
    "closed_at": "2025-11-12T00:21:04Z",
    "sla_due_at": "2025-11-08T04:21:04Z",
    "sla_breached": true,
    "requester": "user195@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0072",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-16T23:10:10Z",
    "updated_at": "2025-10-25T14:10:10Z",
    "closed_at": null,
    "sla_due_at": "2025-10-18T20:10:10Z",
    "sla_breached": true,
    "requester": "user1@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "incident",
      "network",
      "sso",
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0073",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-07T14:12:34Z",
    "updated_at": "2025-09-11T23:12:34Z",
    "closed_at": null,
    "sla_due_at": "2025-09-10T02:12:34Z",
    "sla_breached": true,
    "requester": "user74@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "security",
      "network",
      "bug",
      "change"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0074",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-08-28T02:35:34Z",
    "updated_at": "2025-09-08T21:35:34Z",
    "closed_at": "2025-09-08T21:35:34Z",
    "sla_due_at": "2025-08-29T21:35:34Z",
    "sla_breached": true,
    "requester": "user30@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0075",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-23T21:43:58Z",
    "updated_at": "2025-10-02T18:43:58Z",
    "closed_at": "2025-10-02T18:43:58Z",
    "sla_due_at": "2025-09-26T18:43:58Z",
    "sla_breached": true,
    "requester": "user121@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "request",
      "access",
      "incident",
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0076",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-11-09T05:49:02Z",
    "updated_at": "2025-11-18T02:49:02Z",
    "closed_at": null,
    "sla_due_at": "2025-11-10T20:49:02Z",
    "sla_breached": true,
    "requester": "user130@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0077",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-11T11:14:41Z",
    "updated_at": "2025-09-21T00:14:41Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T05:14:41Z",
    "sla_breached": true,
    "requester": "user86@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "problem",
      "vip",
      "sso",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0078",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-27T17:24:11Z",
    "updated_at": "2025-11-06T20:24:11Z",
    "closed_at": null,
    "sla_due_at": "2025-10-28T02:24:11Z",
    "sla_breached": true,
    "requester": "user98@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "problem",
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0079",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-22T10:52:16Z",
    "updated_at": "2025-10-01T20:52:16Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T08:52:16Z",
    "sla_breached": true,
    "requester": "user117@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "incident",
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0080",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-16T15:15:55Z",
    "updated_at": "2025-11-26T07:56:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-18T04:15:55Z",
    "sla_breached": true,
    "requester": "user85@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "bug",
      "problem",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0081",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-09-08T05:52:04Z",
    "updated_at": "2025-09-27T21:52:04Z",
    "closed_at": "2025-09-27T21:52:04Z",
    "sla_due_at": "2025-09-09T15:52:04Z",
    "sla_breached": true,
    "requester": "user192@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "security",
      "bug",
      "analytics",
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0082",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-29T21:27:21Z",
    "updated_at": "2025-08-31T02:27:21Z",
    "closed_at": null,
    "sla_due_at": "2025-08-30T04:27:21Z",
    "sla_breached": true,
    "requester": "user111@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "change",
      "bug",
      "access",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0083",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-15T10:10:05Z",
    "updated_at": "2025-11-20T14:10:05Z",
    "closed_at": "2025-11-20T14:10:05Z",
    "sla_due_at": "2025-11-17T14:10:05Z",
    "sla_breached": true,
    "requester": "user37@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "bug",
      "onboarding",
      "problem",
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0084",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-27T21:53:12Z",
    "updated_at": "2025-10-05T06:53:12Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T21:53:12Z",
    "sla_breached": true,
    "requester": "user109@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "sso",
      "incident",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0085",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-26T18:28:26Z",
    "updated_at": "2025-11-10T17:28:26Z",
    "closed_at": "2025-11-10T17:28:26Z",
    "sla_due_at": "2025-10-28T19:28:26Z",
    "sla_breached": true,
    "requester": "user169@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "network",
      "change",
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0086",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-09T14:16:25Z",
    "updated_at": "2025-09-14T12:16:25Z",
    "closed_at": null,
    "sla_due_at": "2025-09-11T06:16:25Z",
    "sla_breached": true,
    "requester": "user57@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "change",
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0087",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-07T04:49:17Z",
    "updated_at": "2025-09-16T14:49:17Z",
    "closed_at": null,
    "sla_due_at": "2025-09-07T13:49:17Z",
    "sla_breached": true,
    "requester": "user188@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "db",
      "incident",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0088",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-09T12:43:11Z",
    "updated_at": "2025-11-26T08:04:32Z",
    "closed_at": "2025-11-26T08:04:32Z",
    "sla_due_at": "2025-11-11T14:43:11Z",
    "sla_breached": true,
    "requester": "user124@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "analytics",
      "security",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0089",
    "subject": "Multi-factor authentication not working",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-11-08T00:08:41Z",
    "updated_at": "2025-11-19T22:08:41Z",
    "closed_at": null,
    "sla_due_at": "2025-11-10T06:08:41Z",
    "sla_breached": true,
    "requester": "user102@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "request",
      "security",
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0090",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-08-31T22:48:50Z",
    "updated_at": "2025-09-08T21:48:50Z",
    "closed_at": null,
    "sla_due_at": "2025-09-03T02:48:50Z",
    "sla_breached": true,
    "requester": "user121@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "change",
      "sso",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0091",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-05T15:27:20Z",
    "updated_at": "2025-09-08T03:27:20Z",
    "closed_at": "2025-09-08T03:27:20Z",
    "sla_due_at": "2025-09-07T09:27:20Z",
    "sla_breached": true,
    "requester": "user10@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "security",
      "analytics",
      "sso",
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0092",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-10-07T15:50:33Z",
    "updated_at": "2025-10-23T12:50:33Z",
    "closed_at": "2025-10-23T12:50:33Z",
    "sla_due_at": "2025-10-09T18:50:33Z",
    "sla_breached": true,
    "requester": "user108@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "incident",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0093",
    "subject": "Login issues on corporate portal",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-24T09:56:38Z",
    "updated_at": "2025-09-30T09:56:38Z",
    "closed_at": null,
    "sla_due_at": "2025-09-26T17:56:38Z",
    "sla_breached": true,
    "requester": "user56@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "sso",
      "vip",
      "security",
      "db"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0094",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-04T19:18:00Z",
    "updated_at": "2025-09-08T21:18:00Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T06:18:00Z",
    "sla_breached": true,
    "requester": "user117@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0095",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-26T03:46:27Z",
    "updated_at": "2025-11-06T23:46:27Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T09:46:27Z",
    "sla_breached": true,
    "requester": "user60@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0096",
    "subject": "Upgrade request for enterprise license",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-09T12:41:25Z",
    "updated_at": "2025-11-11T21:41:25Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T00:41:25Z",
    "sla_breached": true,
    "requester": "user34@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "analytics",
      "sso",
      "change"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0097",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-24T02:00:54Z",
    "updated_at": "2025-11-26T07:48:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T15:00:54Z",
    "sla_breached": true,
    "requester": "user122@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0098",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-28T09:57:49Z",
    "updated_at": "2025-11-16T19:57:49Z",
    "closed_at": "2025-11-16T19:57:49Z",
    "sla_due_at": "2025-10-28T18:57:49Z",
    "sla_breached": true,
    "requester": "user78@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "network"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0099",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-05T16:50:20Z",
    "updated_at": "2025-10-25T02:50:20Z",
    "closed_at": "2025-10-25T02:50:20Z",
    "sla_due_at": "2025-10-06T09:50:20Z",
    "sla_breached": true,
    "requester": "user21@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "security",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0100",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-07T09:18:34Z",
    "updated_at": "2025-09-20T03:18:34Z",
    "closed_at": null,
    "sla_due_at": "2025-09-09T06:18:34Z",
    "sla_breached": true,
    "requester": "user130@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0101",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-29T16:42:02Z",
    "updated_at": "2025-11-07T12:42:02Z",
    "closed_at": null,
    "sla_due_at": "2025-11-01T05:42:02Z",
    "sla_breached": true,
    "requester": "user103@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0102",
    "subject": "Bug report for ticketing system",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-16T23:04:44Z",
    "updated_at": "2025-10-31T15:04:44Z",
    "closed_at": null,
    "sla_due_at": "2025-10-19T02:04:44Z",
    "sla_breached": true,
    "requester": "user24@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0103",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-10T03:37:18Z",
    "updated_at": "2025-10-22T03:37:18Z",
    "closed_at": "2025-10-22T03:37:18Z",
    "sla_due_at": "2025-10-10T14:37:18Z",
    "sla_breached": true,
    "requester": "user32@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "bug",
      "incident",
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0104",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-10T20:58:59Z",
    "updated_at": "2025-09-21T16:58:59Z",
    "closed_at": null,
    "sla_due_at": "2025-09-12T21:58:59Z",
    "sla_breached": true,
    "requester": "user124@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "request",
      "vip",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0105",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-14T00:07:29Z",
    "updated_at": "2025-09-27T07:07:29Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T10:07:29Z",
    "sla_breached": true,
    "requester": "user143@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "network",
      "access",
      "onboarding"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0106",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-13T19:34:43Z",
    "updated_at": "2025-10-16T21:34:43Z",
    "closed_at": null,
    "sla_due_at": "2025-10-13T23:34:43Z",
    "sla_breached": true,
    "requester": "user18@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0107",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-29T18:39:44Z",
    "updated_at": "2025-11-02T03:39:44Z",
    "closed_at": "2025-11-02T03:39:44Z",
    "sla_due_at": "2025-11-01T03:39:44Z",
    "sla_breached": true,
    "requester": "user84@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0108",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-05T09:51:51Z",
    "updated_at": "2025-11-11T05:51:51Z",
    "closed_at": "2025-11-11T05:51:51Z",
    "sla_due_at": "2025-11-05T19:51:51Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "incident",
      "onboarding",
      "sso",
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0109",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-12T16:42:23Z",
    "updated_at": "2025-10-27T04:42:23Z",
    "closed_at": null,
    "sla_due_at": "2025-10-13T10:42:23Z",
    "sla_breached": true,
    "requester": "user171@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "change",
      "network",
      "db",
      "sso"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0110",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-30T03:21:45Z",
    "updated_at": "2025-11-01T17:21:45Z",
    "closed_at": null,
    "sla_due_at": "2025-10-31T15:21:45Z",
    "sla_breached": true,
    "requester": "user111@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "request",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0111",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-16T17:54:08Z",
    "updated_at": "2025-11-26T07:23:32Z",
    "closed_at": "2025-11-26T07:23:32Z",
    "sla_due_at": "2025-11-17T02:54:08Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "db",
      "bug",
      "incident",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0112",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-06T07:35:59Z",
    "updated_at": "2025-10-19T12:35:59Z",
    "closed_at": null,
    "sla_due_at": "2025-10-08T04:35:59Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "incident",
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0113",
    "subject": "Application performance degradation",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-20T05:29:44Z",
    "updated_at": "2025-09-27T11:29:44Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T11:29:44Z",
    "sla_breached": true,
    "requester": "user44@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0114",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-01T19:38:19Z",
    "updated_at": "2025-11-19T07:38:19Z",
    "closed_at": "2025-11-19T07:38:19Z",
    "sla_due_at": "2025-11-03T19:38:19Z",
    "sla_breached": true,
    "requester": "user61@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "onboarding",
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0115",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-10T02:47:36Z",
    "updated_at": "2025-09-23T12:47:36Z",
    "closed_at": null,
    "sla_due_at": "2025-09-10T15:47:36Z",
    "sla_breached": true,
    "requester": "user145@enterprise.example.com",
    "assignee": null,
    "tags": [
      "bug",
      "change",
      "analytics",
      "db"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0116",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-06T20:50:56Z",
    "updated_at": "2025-09-16T21:50:56Z",
    "closed_at": "2025-09-16T21:50:56Z",
    "sla_due_at": "2025-09-07T19:50:56Z",
    "sla_breached": true,
    "requester": "user71@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0117",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-16T21:03:27Z",
    "updated_at": "2025-11-18T03:03:27Z",
    "closed_at": "2025-11-18T03:03:27Z",
    "sla_due_at": "2025-11-19T12:03:27Z",
    "sla_breached": false,
    "requester": "user20@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0118",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-07T15:30:44Z",
    "updated_at": "2025-10-24T22:30:44Z",
    "closed_at": "2025-10-24T22:30:44Z",
    "sla_due_at": "2025-10-08T00:30:44Z",
    "sla_breached": true,
    "requester": "user83@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "request",
      "access",
      "network",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0119",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-14T05:17:19Z",
    "updated_at": "2025-10-15T02:17:19Z",
    "closed_at": "2025-10-15T02:17:19Z",
    "sla_due_at": "2025-10-17T01:17:19Z",
    "sla_breached": false,
    "requester": "user113@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "vip",
      "analytics"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0120",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-07T17:28:34Z",
    "updated_at": "2025-10-08T20:28:34Z",
    "closed_at": "2025-10-08T20:28:34Z",
    "sla_due_at": "2025-10-09T16:28:34Z",
    "sla_breached": false,
    "requester": "user86@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "security",
      "request",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0121",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-20T23:11:03Z",
    "updated_at": "2025-11-02T10:11:03Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T22:11:03Z",
    "sla_breached": true,
    "requester": "user90@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "access",
      "change",
      "security",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0122",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-08T08:55:49Z",
    "updated_at": "2025-10-22T16:55:49Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T06:55:49Z",
    "sla_breached": true,
    "requester": "user190@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0123",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-21T19:11:07Z",
    "updated_at": "2025-09-25T16:11:07Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T01:11:07Z",
    "sla_breached": true,
    "requester": "user197@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "access",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0124",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-13T13:52:29Z",
    "updated_at": "2025-11-20T18:52:29Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T12:52:29Z",
    "sla_breached": true,
    "requester": "user34@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "access",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0125",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-01T06:46:06Z",
    "updated_at": "2025-10-06T08:46:06Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T14:46:06Z",
    "sla_breached": true,
    "requester": "user193@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso",
      "request",
      "analytics",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0126",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-01T18:57:59Z",
    "updated_at": "2025-11-07T19:57:59Z",
    "closed_at": "2025-11-07T19:57:59Z",
    "sla_due_at": "2025-11-04T06:57:59Z",
    "sla_breached": true,
    "requester": "user136@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "sso",
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0127",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-25T06:27:33Z",
    "updated_at": "2025-11-06T02:27:33Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T23:27:33Z",
    "sla_breached": true,
    "requester": "user133@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "security",
      "access",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0128",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-22T02:59:39Z",
    "updated_at": "2025-09-26T20:59:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T13:59:39Z",
    "sla_breached": true,
    "requester": "user90@enterprise.example.com",
    "assignee": null,
    "tags": [
      "network",
      "incident",
      "request",
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0129",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-08T05:23:16Z",
    "updated_at": "2025-10-15T01:23:16Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T08:23:16Z",
    "sla_breached": true,
    "requester": "user183@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "network",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0130",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-08-29T03:18:21Z",
    "updated_at": "2025-08-29T06:18:21Z",
    "closed_at": "2025-08-29T06:18:21Z",
    "sla_due_at": "2025-08-31T19:18:21Z",
    "sla_breached": false,
    "requester": "user66@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "request",
      "db"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0131",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-03T04:18:39Z",
    "updated_at": "2025-10-05T19:18:39Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T20:18:39Z",
    "sla_breached": true,
    "requester": "user164@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security",
      "analytics",
      "problem",
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0132",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-23T09:21:01Z",
    "updated_at": "2025-11-26T08:12:32Z",
    "closed_at": "2025-11-26T08:12:32Z",
    "sla_due_at": "2025-11-26T06:21:01Z",
    "sla_breached": true,
    "requester": "user158@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "change",
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0133",
    "subject": "Slow network in branch office",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-02T05:14:31Z",
    "updated_at": "2025-09-03T16:14:31Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T04:14:31Z",
    "sla_breached": true,
    "requester": "user130@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0134",
    "subject": "Security alert investigation",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-11-20T09:12:54Z",
    "updated_at": "2025-11-25T19:12:54Z",
    "closed_at": null,
    "sla_due_at": "2025-11-22T14:12:54Z",
    "sla_breached": true,
    "requester": "user18@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "db",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0135",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-12T20:15:09Z",
    "updated_at": "2025-09-24T12:15:09Z",
    "closed_at": null,
    "sla_due_at": "2025-09-13T17:15:09Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": null,
    "tags": [
      "db",
      "problem",
      "bug",
      "access"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0136",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-17T15:41:44Z",
    "updated_at": "2025-11-18T14:41:44Z",
    "closed_at": null,
    "sla_due_at": "2025-11-17T23:41:44Z",
    "sla_breached": true,
    "requester": "user11@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "request",
      "problem",
      "onboarding",
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0137",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-20T19:21:43Z",
    "updated_at": "2025-10-27T21:21:43Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T05:21:43Z",
    "sla_breached": true,
    "requester": "user95@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "db",
      "problem",
      "incident",
      "vip"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0138",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-23T14:14:41Z",
    "updated_at": "2025-10-04T16:14:41Z",
    "closed_at": null,
    "sla_due_at": "2025-09-25T17:14:41Z",
    "sla_breached": true,
    "requester": "user187@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0139",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-17T21:39:48Z",
    "updated_at": "2025-09-24T21:39:48Z",
    "closed_at": null,
    "sla_due_at": "2025-09-19T18:39:48Z",
    "sla_breached": true,
    "requester": "user115@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "db",
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0140",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-30T06:49:01Z",
    "updated_at": "2025-10-09T13:49:01Z",
    "closed_at": "2025-10-09T13:49:01Z",
    "sla_due_at": "2025-10-02T07:49:01Z",
    "sla_breached": true,
    "requester": "user15@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "vip",
      "request",
      "bug",
      "access"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0141",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-07T10:14:17Z",
    "updated_at": "2025-11-08T21:14:17Z",
    "closed_at": null,
    "sla_due_at": "2025-11-09T22:14:17Z",
    "sla_breached": true,
    "requester": "user94@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0142",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "low",
    "created_at": "2025-08-31T15:58:40Z",
    "updated_at": "2025-09-02T07:58:40Z",
    "closed_at": null,
    "sla_due_at": "2025-09-02T18:58:40Z",
    "sla_breached": true,
    "requester": "user94@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "sso",
      "security",
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0143",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-23T13:30:31Z",
    "updated_at": "2025-09-26T02:30:31Z",
    "closed_at": null,
    "sla_due_at": "2025-09-25T18:30:31Z",
    "sla_breached": true,
    "requester": "user181@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "change",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0144",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-01T03:53:38Z",
    "updated_at": "2025-11-10T19:53:38Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T00:53:38Z",
    "sla_breached": true,
    "requester": "user114@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "bug",
      "vip",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0145",
    "subject": "Upgrade request for enterprise license",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-17T21:47:14Z",
    "updated_at": "2025-10-02T20:47:14Z",
    "closed_at": null,
    "sla_due_at": "2025-09-19T15:47:14Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "security",
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0146",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-26T14:22:20Z",
    "updated_at": "2025-11-07T20:22:20Z",
    "closed_at": null,
    "sla_due_at": "2025-10-26T21:22:20Z",
    "sla_breached": true,
    "requester": "user142@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0147",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-25T13:13:09Z",
    "updated_at": "2025-10-07T20:13:09Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T21:13:09Z",
    "sla_breached": true,
    "requester": "user82@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0148",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-30T13:31:21Z",
    "updated_at": "2025-09-11T08:31:21Z",
    "closed_at": null,
    "sla_due_at": "2025-09-01T13:31:21Z",
    "sla_breached": true,
    "requester": "user197@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request",
      "network",
      "security",
      "analytics"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0149",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-19T02:21:51Z",
    "updated_at": "2025-10-23T22:21:51Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T02:21:51Z",
    "sla_breached": true,
    "requester": "user133@enterprise.example.com",
    "assignee": null,
    "tags": [
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0150",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-05T12:18:13Z",
    "updated_at": "2025-09-12T00:18:13Z",
    "closed_at": null,
    "sla_due_at": "2025-09-07T03:18:13Z",
    "sla_breached": true,
    "requester": "user129@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "access",
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0151",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-15T06:51:33Z",
    "updated_at": "2025-09-28T23:51:33Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T13:51:33Z",
    "sla_breached": true,
    "requester": "user167@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "change",
      "bug",
      "network",
      "problem"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0152",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-19T08:59:16Z",
    "updated_at": "2025-11-05T13:59:16Z",
    "closed_at": "2025-11-05T13:59:16Z",
    "sla_due_at": "2025-10-21T02:59:16Z",
    "sla_breached": true,
    "requester": "user77@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0153",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-05T16:21:13Z",
    "updated_at": "2025-11-10T01:21:13Z",
    "closed_at": "2025-11-10T01:21:13Z",
    "sla_due_at": "2025-11-08T01:21:13Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "db",
      "vip",
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0154",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-09T13:36:33Z",
    "updated_at": "2025-10-19T12:36:33Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T06:36:33Z",
    "sla_breached": true,
    "requester": "user64@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "incident",
      "change",
      "analytics"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0155",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-05T20:26:15Z",
    "updated_at": "2025-11-09T06:26:15Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T16:26:15Z",
    "sla_breached": true,
    "requester": "user120@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "network",
      "security",
      "incident",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0156",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-27T00:31:33Z",
    "updated_at": "2025-11-02T01:31:33Z",
    "closed_at": null,
    "sla_due_at": "2025-10-29T01:31:33Z",
    "sla_breached": true,
    "requester": "user168@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "security"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0157",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-08T22:43:48Z",
    "updated_at": "2025-11-16T18:43:48Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T00:43:48Z",
    "sla_breached": true,
    "requester": "user146@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "vip",
      "request"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0158",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-16T18:17:33Z",
    "updated_at": "2025-11-26T08:04:32Z",
    "closed_at": "2025-11-26T08:04:32Z",
    "sla_due_at": "2025-11-19T14:17:33Z",
    "sla_breached": true,
    "requester": "user175@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0159",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-06T18:46:17Z",
    "updated_at": "2025-10-14T14:46:17Z",
    "closed_at": "2025-10-14T14:46:17Z",
    "sla_due_at": "2025-10-08T17:46:17Z",
    "sla_breached": true,
    "requester": "user155@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "request",
      "network",
      "db",
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0160",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-14T15:06:38Z",
    "updated_at": "2025-10-27T14:06:38Z",
    "closed_at": "2025-10-27T14:06:38Z",
    "sla_due_at": "2025-10-17T13:06:38Z",
    "sla_breached": true,
    "requester": "user84@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "access",
      "incident",
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0161",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-11T20:06:43Z",
    "updated_at": "2025-09-23T05:06:43Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T16:06:43Z",
    "sla_breached": true,
    "requester": "user77@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0162",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-01T04:22:06Z",
    "updated_at": "2025-09-18T04:22:06Z",
    "closed_at": "2025-09-18T04:22:06Z",
    "sla_due_at": "2025-09-03T13:22:06Z",
    "sla_breached": true,
    "requester": "user177@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0163",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-23T08:29:23Z",
    "updated_at": "2025-11-04T19:29:23Z",
    "closed_at": "2025-11-04T19:29:23Z",
    "sla_due_at": "2025-10-24T17:29:23Z",
    "sla_breached": true,
    "requester": "user162@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "access",
      "bug",
      "sso",
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0164",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-02T07:40:10Z",
    "updated_at": "2025-11-05T13:40:10Z",
    "closed_at": null,
    "sla_due_at": "2025-11-04T19:40:10Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "db",
      "analytics",
      "network",
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0165",
    "subject": "Slow network in branch office",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-30T11:56:16Z",
    "updated_at": "2025-11-09T16:56:16Z",
    "closed_at": null,
    "sla_due_at": "2025-11-01T08:56:16Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "request",
      "vip",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0166",
    "subject": "Slow network in branch office",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-08T14:43:50Z",
    "updated_at": "2025-09-14T13:43:50Z",
    "closed_at": null,
    "sla_due_at": "2025-09-09T18:43:50Z",
    "sla_breached": true,
    "requester": "user77@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "db",
      "sso",
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0167",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-25T19:39:34Z",
    "updated_at": "2025-10-08T01:39:34Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T10:39:34Z",
    "sla_breached": true,
    "requester": "user102@enterprise.example.com",
    "assignee": null,
    "tags": [
      "onboarding",
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0168",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-15T19:44:54Z",
    "updated_at": "2025-11-26T07:51:32Z",
    "closed_at": "2025-11-26T07:51:32Z",
    "sla_due_at": "2025-11-18T07:44:54Z",
    "sla_breached": true,
    "requester": "user138@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "access",
      "security",
      "change"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0169",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-26T06:30:39Z",
    "updated_at": "2025-10-31T06:30:39Z",
    "closed_at": null,
    "sla_due_at": "2025-10-29T05:30:39Z",
    "sla_breached": true,
    "requester": "user85@enterprise.example.com",
    "assignee": null,
    "tags": [
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0170",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-25T12:19:17Z",
    "updated_at": "2025-11-26T07:25:32Z",
    "closed_at": "2025-11-26T07:25:32Z",
    "sla_due_at": "2025-11-26T12:19:17Z",
    "sla_breached": false,
    "requester": "user167@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "vip",
      "onboarding",
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0171",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-14T08:36:34Z",
    "updated_at": "2025-11-26T07:27:32Z",
    "closed_at": "2025-11-26T07:27:32Z",
    "sla_due_at": "2025-11-15T17:36:34Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "network",
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0172",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-02T21:49:11Z",
    "updated_at": "2025-11-15T00:49:11Z",
    "closed_at": null,
    "sla_due_at": "2025-11-03T05:49:11Z",
    "sla_breached": true,
    "requester": "user86@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "access",
      "request",
      "problem",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0173",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-11T20:19:09Z",
    "updated_at": "2025-11-25T16:19:09Z",
    "closed_at": "2025-11-25T16:19:09Z",
    "sla_due_at": "2025-11-12T20:19:09Z",
    "sla_breached": true,
    "requester": "user4@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "analytics",
      "onboarding",
      "change"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0174",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-03T10:06:53Z",
    "updated_at": "2025-11-14T10:06:53Z",
    "closed_at": null,
    "sla_due_at": "2025-11-05T17:06:53Z",
    "sla_breached": true,
    "requester": "user172@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "access",
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0175",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-26T08:06:37Z",
    "updated_at": "2025-11-04T21:06:37Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T21:06:37Z",
    "sla_breached": true,
    "requester": "user85@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0176",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-08-29T23:45:20Z",
    "updated_at": "2025-09-08T22:45:20Z",
    "closed_at": "2025-09-08T22:45:20Z",
    "sla_due_at": "2025-08-30T10:45:20Z",
    "sla_breached": true,
    "requester": "user176@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "db",
      "security",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0177",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-09T09:58:52Z",
    "updated_at": "2025-10-12T06:58:52Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T17:58:52Z",
    "sla_breached": true,
    "requester": "user192@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident",
      "db",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0178",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-19T00:24:25Z",
    "updated_at": "2025-10-01T18:24:25Z",
    "closed_at": "2025-10-01T18:24:25Z",
    "sla_due_at": "2025-09-20T11:24:25Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "security",
      "change",
      "analytics"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0179",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-16T13:57:17Z",
    "updated_at": "2025-09-19T18:57:17Z",
    "closed_at": "2025-09-19T18:57:17Z",
    "sla_due_at": "2025-09-17T18:57:17Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0180",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-12T14:33:41Z",
    "updated_at": "2025-09-22T03:33:41Z",
    "closed_at": null,
    "sla_due_at": "2025-09-13T05:33:41Z",
    "sla_breached": true,
    "requester": "user34@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "problem",
      "change",
      "network",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0181",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-31T21:08:20Z",
    "updated_at": "2025-08-31T23:08:20Z",
    "closed_at": null,
    "sla_due_at": "2025-09-01T03:08:20Z",
    "sla_breached": true,
    "requester": "user19@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0182",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-17T15:10:17Z",
    "updated_at": "2025-11-21T12:10:17Z",
    "closed_at": null,
    "sla_due_at": "2025-11-17T23:10:17Z",
    "sla_breached": true,
    "requester": "user165@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "incident",
      "problem",
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0183",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-15T12:43:25Z",
    "updated_at": "2025-11-22T23:43:25Z",
    "closed_at": "2025-11-22T23:43:25Z",
    "sla_due_at": "2025-11-16T09:43:25Z",
    "sla_breached": true,
    "requester": "user138@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "db",
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0184",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-23T21:29:45Z",
    "updated_at": "2025-11-26T07:54:32Z",
    "closed_at": "2025-11-26T07:54:32Z",
    "sla_due_at": "2025-11-26T12:29:45Z",
    "sla_breached": false,
    "requester": "user59@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "vip",
      "access",
      "onboarding",
      "sso"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0185",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-21T17:05:42Z",
    "updated_at": "2025-11-23T04:05:42Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T23:05:42Z",
    "sla_breached": true,
    "requester": "user115@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0186",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-05T16:22:37Z",
    "updated_at": "2025-10-21T19:22:37Z",
    "closed_at": "2025-10-21T19:22:37Z",
    "sla_due_at": "2025-10-07T01:22:37Z",
    "sla_breached": true,
    "requester": "user36@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "sso",
      "db",
      "change"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0187",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-13T10:35:22Z",
    "updated_at": "2025-09-16T12:35:22Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T07:35:22Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "bug",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0188",
    "subject": "Upgrade request for enterprise license",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-15T14:18:50Z",
    "updated_at": "2025-09-29T08:18:50Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T00:18:50Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "incident",
      "access",
      "onboarding",
      "analytics"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0189",
    "subject": "SSO configuration change",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-18T15:07:07Z",
    "updated_at": "2025-09-25T01:07:07Z",
    "closed_at": null,
    "sla_due_at": "2025-09-20T01:07:07Z",
    "sla_breached": true,
    "requester": "user119@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "incident",
      "request",
      "db",
      "access"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0190",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-25T23:04:30Z",
    "updated_at": "2025-10-27T16:04:30Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T05:04:30Z",
    "sla_breached": true,
    "requester": "user95@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "network",
      "onboarding"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0191",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-08-31T10:19:58Z",
    "updated_at": "2025-09-04T11:19:58Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T19:19:58Z",
    "sla_breached": true,
    "requester": "user186@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "problem",
      "sso"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0192",
    "subject": "Security alert investigation",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-10-19T07:48:03Z",
    "updated_at": "2025-10-21T20:48:03Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T14:48:03Z",
    "sla_breached": true,
    "requester": "user123@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "incident",
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0193",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-15T22:03:11Z",
    "updated_at": "2025-10-29T19:03:11Z",
    "closed_at": "2025-10-29T19:03:11Z",
    "sla_due_at": "2025-10-18T02:03:11Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "problem",
      "security",
      "analytics",
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0194",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-09T20:57:57Z",
    "updated_at": "2025-10-14T14:57:57Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T04:57:57Z",
    "sla_breached": true,
    "requester": "user67@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "onboarding",
      "access",
      "sso",
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0195",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-08T11:36:49Z",
    "updated_at": "2025-10-22T11:36:49Z",
    "closed_at": "2025-10-22T11:36:49Z",
    "sla_due_at": "2025-10-09T22:36:49Z",
    "sla_breached": true,
    "requester": "user196@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "problem",
      "access",
      "vip",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0196",
    "subject": "Upgrade request for enterprise license",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-09-17T14:34:48Z",
    "updated_at": "2025-09-29T04:34:48Z",
    "closed_at": null,
    "sla_due_at": "2025-09-18T17:34:48Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0197",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-25T17:20:39Z",
    "updated_at": "2025-11-26T08:17:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-26T14:20:39Z",
    "sla_breached": false,
    "requester": "user56@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "vip",
      "network",
      "change",
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0198",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-02T14:35:48Z",
    "updated_at": "2025-09-14T09:35:48Z",
    "closed_at": null,
    "sla_due_at": "2025-09-02T20:35:48Z",
    "sla_breached": true,
    "requester": "user136@enterprise.example.com",
    "assignee": null,
    "tags": [
      "network",
      "request",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0199",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-04T04:27:46Z",
    "updated_at": "2025-11-09T08:27:46Z",
    "closed_at": "2025-11-09T08:27:46Z",
    "sla_due_at": "2025-11-04T20:27:46Z",
    "sla_breached": true,
    "requester": "user65@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "analytics",
      "incident",
      "security"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0200",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-05T15:38:51Z",
    "updated_at": "2025-10-10T11:38:51Z",
    "closed_at": null,
    "sla_due_at": "2025-10-07T02:38:51Z",
    "sla_breached": true,
    "requester": "user21@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "security"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0201",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-08T18:37:36Z",
    "updated_at": "2025-10-08T23:37:36Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T10:37:36Z",
    "sla_breached": true,
    "requester": "user128@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "security",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0202",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-28T00:39:42Z",
    "updated_at": "2025-10-29T15:39:42Z",
    "closed_at": null,
    "sla_due_at": "2025-10-30T16:39:42Z",
    "sla_breached": true,
    "requester": "user140@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "vip",
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0203",
    "subject": "Email delivery delayed",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-12T03:06:33Z",
    "updated_at": "2025-09-18T13:06:33Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T09:06:33Z",
    "sla_breached": true,
    "requester": "user146@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "incident",
      "db",
      "access"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0204",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-22T19:46:00Z",
    "updated_at": "2025-09-27T18:46:00Z",
    "closed_at": null,
    "sla_due_at": "2025-09-23T05:46:00Z",
    "sla_breached": true,
    "requester": "user155@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "vip",
      "network",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0205",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-25T00:03:10Z",
    "updated_at": "2025-10-03T01:03:10Z",
    "closed_at": "2025-10-03T01:03:10Z",
    "sla_due_at": "2025-09-27T01:03:10Z",
    "sla_breached": true,
    "requester": "user150@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "security",
      "change",
      "onboarding",
      "sso"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0206",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-15T22:36:09Z",
    "updated_at": "2025-11-26T08:12:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T21:36:09Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "problem",
      "vip",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0207",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-10T05:10:50Z",
    "updated_at": "2025-11-22T03:10:50Z",
    "closed_at": "2025-11-22T03:10:50Z",
    "sla_due_at": "2025-11-11T08:10:50Z",
    "sla_breached": true,
    "requester": "user27@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0208",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-14T10:37:32Z",
    "updated_at": "2025-11-14T17:37:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T07:37:32Z",
    "sla_breached": true,
    "requester": "user200@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "change",
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0209",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-30T18:29:49Z",
    "updated_at": "2025-09-06T05:29:49Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T19:29:49Z",
    "sla_breached": true,
    "requester": "user17@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "onboarding",
      "problem",
      "security",
      "vip"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0210",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-25T09:36:08Z",
    "updated_at": "2025-10-29T14:36:08Z",
    "closed_at": "2025-10-29T14:36:08Z",
    "sla_due_at": "2025-10-28T04:36:08Z",
    "sla_breached": true,
    "requester": "user78@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "vip",
      "change",
      "incident",
      "analytics"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0211",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-14T16:40:51Z",
    "updated_at": "2025-10-27T13:40:51Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T13:40:51Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "onboarding",
      "db",
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0212",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-13T23:31:57Z",
    "updated_at": "2025-09-22T09:31:57Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T20:31:57Z",
    "sla_breached": true,
    "requester": "user145@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "bug",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0213",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-28T00:43:33Z",
    "updated_at": "2025-10-12T19:43:33Z",
    "closed_at": null,
    "sla_due_at": "2025-09-30T12:43:33Z",
    "sla_breached": true,
    "requester": "user105@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "access",
      "bug",
      "onboarding",
      "sso"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0214",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-09-03T02:44:49Z",
    "updated_at": "2025-09-04T16:44:49Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T12:44:49Z",
    "sla_breached": true,
    "requester": "user123@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "request",
      "analytics",
      "incident",
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0215",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-10T12:48:39Z",
    "updated_at": "2025-10-15T20:48:39Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T02:48:39Z",
    "sla_breached": true,
    "requester": "user43@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "analytics",
      "vip",
      "incident",
      "security"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0216",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-13T22:56:19Z",
    "updated_at": "2025-11-25T00:56:19Z",
    "closed_at": "2025-11-25T00:56:19Z",
    "sla_due_at": "2025-11-15T06:56:19Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "vip",
      "incident",
      "problem",
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0217",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-06T19:47:57Z",
    "updated_at": "2025-11-13T03:47:57Z",
    "closed_at": "2025-11-13T03:47:57Z",
    "sla_due_at": "2025-11-07T02:47:57Z",
    "sla_breached": true,
    "requester": "user22@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "vip",
      "onboarding"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0218",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-29T00:49:38Z",
    "updated_at": "2025-10-09T04:49:38Z",
    "closed_at": "2025-10-09T04:49:38Z",
    "sla_due_at": "2025-10-01T22:49:38Z",
    "sla_breached": true,
    "requester": "user179@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "security",
      "onboarding",
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0219",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-23T19:52:05Z",
    "updated_at": "2025-11-26T07:22:32Z",
    "closed_at": "2025-11-26T07:22:32Z",
    "sla_due_at": "2025-11-24T12:52:05Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "vip",
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0220",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-27T23:55:03Z",
    "updated_at": "2025-10-01T23:55:03Z",
    "closed_at": "2025-10-01T23:55:03Z",
    "sla_due_at": "2025-09-30T06:55:03Z",
    "sla_breached": true,
    "requester": "user102@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "problem",
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0221",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-08T08:11:49Z",
    "updated_at": "2025-10-09T17:11:49Z",
    "closed_at": null,
    "sla_due_at": "2025-10-09T15:11:49Z",
    "sla_breached": true,
    "requester": "user138@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "problem",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0222",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-01T14:32:15Z",
    "updated_at": "2025-09-08T07:32:15Z",
    "closed_at": null,
    "sla_due_at": "2025-09-04T13:32:15Z",
    "sla_breached": true,
    "requester": "user101@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0223",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-28T09:52:54Z",
    "updated_at": "2025-10-04T18:52:54Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T11:52:54Z",
    "sla_breached": true,
    "requester": "user22@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "vip",
      "security"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0224",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-18T04:06:04Z",
    "updated_at": "2025-10-21T05:06:04Z",
    "closed_at": null,
    "sla_due_at": "2025-10-19T07:06:04Z",
    "sla_breached": true,
    "requester": "user153@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "access",
      "problem",
      "bug",
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0225",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-16T02:17:01Z",
    "updated_at": "2025-09-20T02:17:01Z",
    "closed_at": null,
    "sla_due_at": "2025-09-18T20:17:01Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0226",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-01T18:22:48Z",
    "updated_at": "2025-11-10T12:22:48Z",
    "closed_at": "2025-11-10T12:22:48Z",
    "sla_due_at": "2025-11-04T14:22:48Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "access",
      "security",
      "change",
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0227",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-20T07:10:07Z",
    "updated_at": "2025-10-26T11:10:07Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T22:10:07Z",
    "sla_breached": true,
    "requester": "user145@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request",
      "analytics",
      "security",
      "change"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0228",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-22T12:35:06Z",
    "updated_at": "2025-11-07T16:35:06Z",
    "closed_at": "2025-11-07T16:35:06Z",
    "sla_due_at": "2025-10-24T14:35:06Z",
    "sla_breached": true,
    "requester": "user113@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "incident",
      "security"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0229",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-19T07:11:08Z",
    "updated_at": "2025-10-21T04:11:08Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T20:11:08Z",
    "sla_breached": true,
    "requester": "user31@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso",
      "db"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0230",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-27T10:08:24Z",
    "updated_at": "2025-08-30T10:08:24Z",
    "closed_at": null,
    "sla_due_at": "2025-08-29T20:08:24Z",
    "sla_breached": true,
    "requester": "user53@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request",
      "onboarding",
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0231",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-04T20:34:31Z",
    "updated_at": "2025-11-10T13:34:31Z",
    "closed_at": null,
    "sla_due_at": "2025-11-06T13:34:31Z",
    "sla_breached": true,
    "requester": "user174@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "incident"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0232",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-21T08:28:43Z",
    "updated_at": "2025-10-24T04:28:43Z",
    "closed_at": "2025-10-24T04:28:43Z",
    "sla_due_at": "2025-10-22T04:28:43Z",
    "sla_breached": true,
    "requester": "user83@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "problem",
      "access",
      "change",
      "onboarding"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0233",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-08T15:54:09Z",
    "updated_at": "2025-10-27T10:54:09Z",
    "closed_at": "2025-10-27T10:54:09Z",
    "sla_due_at": "2025-10-09T04:54:09Z",
    "sla_breached": true,
    "requester": "user132@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "db",
      "vip",
      "problem"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0234",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-10-15T11:10:14Z",
    "updated_at": "2025-10-17T11:10:14Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T15:10:14Z",
    "sla_breached": true,
    "requester": "user163@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "security",
      "request",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0235",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-03T00:38:45Z",
    "updated_at": "2025-10-09T02:38:45Z",
    "closed_at": null,
    "sla_due_at": "2025-10-05T19:38:45Z",
    "sla_breached": true,
    "requester": "user34@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "bug",
      "network",
      "db"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0236",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-06T15:37:34Z",
    "updated_at": "2025-09-10T00:37:34Z",
    "closed_at": null,
    "sla_due_at": "2025-09-06T21:37:34Z",
    "sla_breached": true,
    "requester": "user110@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "bug",
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0237",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-22T04:57:38Z",
    "updated_at": "2025-10-30T03:57:38Z",
    "closed_at": null,
    "sla_due_at": "2025-10-24T06:57:38Z",
    "sla_breached": true,
    "requester": "user43@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "db",
      "analytics",
      "sso"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0238",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-04T05:02:19Z",
    "updated_at": "2025-09-14T10:02:19Z",
    "closed_at": null,
    "sla_due_at": "2025-09-04T21:02:19Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0239",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-10T16:58:59Z",
    "updated_at": "2025-11-15T14:58:59Z",
    "closed_at": "2025-11-15T14:58:59Z",
    "sla_due_at": "2025-11-11T12:58:59Z",
    "sla_breached": true,
    "requester": "user27@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "vip",
      "onboarding",
      "access"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0240",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-08T09:00:00Z",
    "updated_at": "2025-11-20T10:00:00Z",
    "closed_at": null,
    "sla_due_at": "2025-11-09T07:00:00Z",
    "sla_breached": true,
    "requester": "user43@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "bug",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0241",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-04T09:55:42Z",
    "updated_at": "2025-10-06T06:55:42Z",
    "closed_at": null,
    "sla_due_at": "2025-10-06T21:55:42Z",
    "sla_breached": true,
    "requester": "user193@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "vip",
      "incident",
      "analytics",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0242",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-21T08:53:21Z",
    "updated_at": "2025-11-03T04:53:21Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T22:53:21Z",
    "sla_breached": true,
    "requester": "user73@enterprise.example.com",
    "assignee": null,
    "tags": [
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0243",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-30T13:30:30Z",
    "updated_at": "2025-11-07T22:30:30Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T10:30:30Z",
    "sla_breached": true,
    "requester": "user62@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "problem",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0244",
    "subject": "New user onboarding request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-20T07:55:11Z",
    "updated_at": "2025-09-23T03:55:11Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T09:55:11Z",
    "sla_breached": true,
    "requester": "user146@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "request",
      "bug",
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0245",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-17T07:45:05Z",
    "updated_at": "2025-11-21T22:45:05Z",
    "closed_at": null,
    "sla_due_at": "2025-11-17T19:45:05Z",
    "sla_breached": true,
    "requester": "user102@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "incident",
      "db",
      "analytics",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0246",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-18T09:55:46Z",
    "updated_at": "2025-09-25T00:55:46Z",
    "closed_at": null,
    "sla_due_at": "2025-09-19T08:55:46Z",
    "sla_breached": true,
    "requester": "user53@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request",
      "vip"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0247",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-11T09:15:54Z",
    "updated_at": "2025-09-20T17:15:54Z",
    "closed_at": null,
    "sla_due_at": "2025-09-11T21:15:54Z",
    "sla_breached": true,
    "requester": "user62@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "security",
      "problem",
      "change",
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0248",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-17T08:24:00Z",
    "updated_at": "2025-10-20T07:24:00Z",
    "closed_at": null,
    "sla_due_at": "2025-10-18T10:24:00Z",
    "sla_breached": true,
    "requester": "user128@enterprise.example.com",
    "assignee": null,
    "tags": [
      "access",
      "vip",
      "analytics"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0249",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-11T07:17:25Z",
    "updated_at": "2025-11-17T03:17:25Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T05:17:25Z",
    "sla_breached": true,
    "requester": "user183@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0250",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-21T19:14:50Z",
    "updated_at": "2025-10-03T22:14:50Z",
    "closed_at": "2025-10-03T22:14:50Z",
    "sla_due_at": "2025-09-22T06:14:50Z",
    "sla_breached": true,
    "requester": "user66@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0251",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-27T13:50:00Z",
    "updated_at": "2025-10-27T20:50:00Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T17:50:00Z",
    "sla_breached": true,
    "requester": "user94@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "network",
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0252",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-28T20:38:33Z",
    "updated_at": "2025-11-13T05:38:33Z",
    "closed_at": "2025-11-13T05:38:33Z",
    "sla_due_at": "2025-10-30T07:38:33Z",
    "sla_breached": true,
    "requester": "user20@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "security",
      "request",
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0253",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-11-04T00:13:59Z",
    "updated_at": "2025-11-12T14:13:59Z",
    "closed_at": null,
    "sla_due_at": "2025-11-06T22:13:59Z",
    "sla_breached": true,
    "requester": "user73@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "vip",
      "security",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0254",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-24T18:55:38Z",
    "updated_at": "2025-11-26T07:34:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T23:55:38Z",
    "sla_breached": true,
    "requester": "user95@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "db",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0255",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-07T08:07:37Z",
    "updated_at": "2025-11-18T22:07:37Z",
    "closed_at": null,
    "sla_due_at": "2025-11-09T16:07:37Z",
    "sla_breached": true,
    "requester": "user178@enterprise.example.com",
    "assignee": null,
    "tags": [
      "network",
      "bug",
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0256",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-11-13T00:53:17Z",
    "updated_at": "2025-11-21T23:53:17Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T23:53:17Z",
    "sla_breached": true,
    "requester": "user37@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "security",
      "network",
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0257",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-10-04T18:47:49Z",
    "updated_at": "2025-10-06T14:47:49Z",
    "closed_at": null,
    "sla_due_at": "2025-10-07T08:47:49Z",
    "sla_breached": true,
    "requester": "user35@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "security",
      "change",
      "db",
      "network"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0258",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-03T03:36:00Z",
    "updated_at": "2025-09-09T21:36:00Z",
    "closed_at": null,
    "sla_due_at": "2025-09-04T13:36:00Z",
    "sla_breached": true,
    "requester": "user180@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "problem",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0259",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-17T00:58:43Z",
    "updated_at": "2025-11-26T08:15:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-17T21:58:43Z",
    "sla_breached": true,
    "requester": "user116@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "incident",
      "security",
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0260",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-30T15:54:19Z",
    "updated_at": "2025-11-17T20:54:19Z",
    "closed_at": "2025-11-17T20:54:19Z",
    "sla_due_at": "2025-11-01T10:54:19Z",
    "sla_breached": true,
    "requester": "user176@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0261",
    "subject": "Slow network in branch office",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-11-08T05:02:17Z",
    "updated_at": "2025-11-16T16:02:17Z",
    "closed_at": null,
    "sla_due_at": "2025-11-09T16:02:17Z",
    "sla_breached": true,
    "requester": "user77@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "network",
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0262",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-15T12:19:47Z",
    "updated_at": "2025-09-17T17:19:47Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T23:19:47Z",
    "sla_breached": true,
    "requester": "user32@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "access",
      "sso"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0263",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-09T09:24:38Z",
    "updated_at": "2025-10-14T22:24:38Z",
    "closed_at": "2025-10-14T22:24:38Z",
    "sla_due_at": "2025-10-09T23:24:38Z",
    "sla_breached": true,
    "requester": "user6@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "bug",
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0264",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-14T20:17:16Z",
    "updated_at": "2025-11-24T17:17:16Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T15:17:16Z",
    "sla_breached": true,
    "requester": "user147@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "problem",
      "network",
      "incident",
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0265",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-12T00:32:29Z",
    "updated_at": "2025-10-21T13:32:29Z",
    "closed_at": null,
    "sla_due_at": "2025-10-13T03:32:29Z",
    "sla_breached": true,
    "requester": "user158@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "problem",
      "incident",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0266",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-19T05:09:55Z",
    "updated_at": "2025-11-26T08:09:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T20:09:55Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0267",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-25T12:32:01Z",
    "updated_at": "2025-10-07T14:32:01Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T06:32:01Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "network",
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0268",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-26T13:04:59Z",
    "updated_at": "2025-10-01T13:04:59Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T14:04:59Z",
    "sla_breached": true,
    "requester": "user169@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "request",
      "db",
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0269",
    "subject": "Email delivery delayed",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-13T18:13:01Z",
    "updated_at": "2025-09-17T11:13:01Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T19:13:01Z",
    "sla_breached": true,
    "requester": "user82@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "change",
      "network",
      "vip"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0270",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-15T01:30:20Z",
    "updated_at": "2025-09-18T19:30:20Z",
    "closed_at": "2025-09-18T19:30:20Z",
    "sla_due_at": "2025-09-17T20:30:20Z",
    "sla_breached": true,
    "requester": "user15@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "network",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0271",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-11-25T20:16:51Z",
    "updated_at": "2025-11-26T07:36:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-27T01:16:51Z",
    "sla_breached": false,
    "requester": "user83@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0272",
    "subject": "Security alert investigation",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-11-11T13:11:50Z",
    "updated_at": "2025-11-19T13:11:50Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T15:11:50Z",
    "sla_breached": true,
    "requester": "user102@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0273",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-16T03:23:28Z",
    "updated_at": "2025-10-25T11:23:28Z",
    "closed_at": "2025-10-25T11:23:28Z",
    "sla_due_at": "2025-10-17T03:23:28Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "access",
      "db",
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0274",
    "subject": "Password reset request",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-28T10:54:58Z",
    "updated_at": "2025-11-12T03:54:58Z",
    "closed_at": null,
    "sla_due_at": "2025-10-29T12:54:58Z",
    "sla_breached": true,
    "requester": "user187@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "analytics",
      "change",
      "network",
      "access"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0275",
    "subject": "Multi-factor authentication not working",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-09T00:18:59Z",
    "updated_at": "2025-09-12T01:18:59Z",
    "closed_at": null,
    "sla_due_at": "2025-09-09T17:18:59Z",
    "sla_breached": true,
    "requester": "user61@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "access",
      "bug",
      "security"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0276",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-30T07:56:39Z",
    "updated_at": "2025-10-15T02:56:39Z",
    "closed_at": null,
    "sla_due_at": "2025-10-01T20:56:39Z",
    "sla_breached": true,
    "requester": "user28@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0277",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-04T02:18:10Z",
    "updated_at": "2025-10-12T04:18:10Z",
    "closed_at": "2025-10-12T04:18:10Z",
    "sla_due_at": "2025-10-06T10:18:10Z",
    "sla_breached": true,
    "requester": "user26@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "access",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0278",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-21T21:37:18Z",
    "updated_at": "2025-11-24T03:37:18Z",
    "closed_at": null,
    "sla_due_at": "2025-11-22T03:37:18Z",
    "sla_breached": true,
    "requester": "user97@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0279",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-08-28T07:13:50Z",
    "updated_at": "2025-08-31T20:13:50Z",
    "closed_at": null,
    "sla_due_at": "2025-08-30T18:13:50Z",
    "sla_breached": true,
    "requester": "user41@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0280",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-01T17:27:27Z",
    "updated_at": "2025-11-08T02:27:27Z",
    "closed_at": "2025-11-08T02:27:27Z",
    "sla_due_at": "2025-11-03T06:27:27Z",
    "sla_breached": true,
    "requester": "user101@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "access",
      "network",
      "vip",
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0281",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-14T21:38:05Z",
    "updated_at": "2025-11-15T11:38:05Z",
    "closed_at": null,
    "sla_due_at": "2025-11-17T14:38:05Z",
    "sla_breached": true,
    "requester": "user75@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security",
      "onboarding",
      "incident",
      "problem"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0282",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-02T22:42:38Z",
    "updated_at": "2025-09-11T05:42:38Z",
    "closed_at": "2025-09-11T05:42:38Z",
    "sla_due_at": "2025-09-03T13:42:38Z",
    "sla_breached": true,
    "requester": "user98@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "problem",
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0283",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-30T15:25:36Z",
    "updated_at": "2025-10-06T09:25:36Z",
    "closed_at": null,
    "sla_due_at": "2025-10-02T04:25:36Z",
    "sla_breached": true,
    "requester": "user193@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0284",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-17T17:17:10Z",
    "updated_at": "2025-10-05T16:17:10Z",
    "closed_at": "2025-10-05T16:17:10Z",
    "sla_due_at": "2025-09-19T02:17:10Z",
    "sla_breached": true,
    "requester": "user108@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "change",
      "sso",
      "problem",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0285",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-07T07:05:41Z",
    "updated_at": "2025-10-18T08:05:41Z",
    "closed_at": "2025-10-18T08:05:41Z",
    "sla_due_at": "2025-10-10T03:05:41Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0286",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-04T02:16:22Z",
    "updated_at": "2025-11-06T19:16:22Z",
    "closed_at": null,
    "sla_due_at": "2025-11-05T09:16:22Z",
    "sla_breached": true,
    "requester": "user175@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "bug",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0287",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-17T05:55:09Z",
    "updated_at": "2025-10-25T17:55:09Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T20:55:09Z",
    "sla_breached": true,
    "requester": "user71@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "security",
      "incident",
      "access",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0288",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-12T11:52:20Z",
    "updated_at": "2025-11-23T22:52:20Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T03:52:20Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "bug",
      "problem",
      "change",
      "analytics"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0289",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-22T02:05:22Z",
    "updated_at": "2025-11-26T07:43:32Z",
    "closed_at": "2025-11-26T07:43:32Z",
    "sla_due_at": "2025-11-23T17:05:22Z",
    "sla_breached": true,
    "requester": "user10@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "db",
      "sso",
      "network"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0290",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-22T18:47:56Z",
    "updated_at": "2025-10-29T06:47:56Z",
    "closed_at": null,
    "sla_due_at": "2025-10-23T00:47:56Z",
    "sla_breached": true,
    "requester": "user126@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0291",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-18T16:13:33Z",
    "updated_at": "2025-10-27T14:13:33Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T13:13:33Z",
    "sla_breached": true,
    "requester": "user49@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "analytics",
      "request",
      "vip",
      "network"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0292",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-06T05:58:12Z",
    "updated_at": "2025-11-14T20:58:12Z",
    "closed_at": "2025-11-14T20:58:12Z",
    "sla_due_at": "2025-11-08T00:58:12Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0293",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-01T06:15:39Z",
    "updated_at": "2025-11-02T08:15:39Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T17:15:39Z",
    "sla_breached": true,
    "requester": "user51@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "bug",
      "security",
      "analytics",
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0294",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-09T14:33:46Z",
    "updated_at": "2025-10-19T17:33:46Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T03:33:46Z",
    "sla_breached": true,
    "requester": "user89@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0295",
    "subject": "SSO configuration change",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-08T06:33:05Z",
    "updated_at": "2025-10-12T20:33:05Z",
    "closed_at": null,
    "sla_due_at": "2025-10-09T06:33:05Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "onboarding",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0296",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-22T07:37:44Z",
    "updated_at": "2025-09-25T03:37:44Z",
    "closed_at": "2025-09-25T03:37:44Z",
    "sla_due_at": "2025-09-22T12:37:44Z",
    "sla_breached": true,
    "requester": "user3@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "change",
      "onboarding",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0297",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-02T18:39:07Z",
    "updated_at": "2025-10-07T10:39:07Z",
    "closed_at": "2025-10-07T10:39:07Z",
    "sla_due_at": "2025-10-04T18:39:07Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "change",
      "security",
      "network",
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0298",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-15T08:47:24Z",
    "updated_at": "2025-09-17T16:47:24Z",
    "closed_at": null,
    "sla_due_at": "2025-09-17T00:47:24Z",
    "sla_breached": true,
    "requester": "user71@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "bug",
      "db",
      "analytics"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0299",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-02T02:54:01Z",
    "updated_at": "2025-11-03T08:54:01Z",
    "closed_at": null,
    "sla_due_at": "2025-11-05T00:54:01Z",
    "sla_breached": true,
    "requester": "user154@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "bug",
      "access",
      "network"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0300",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-19T22:54:49Z",
    "updated_at": "2025-11-04T16:54:49Z",
    "closed_at": "2025-11-04T16:54:49Z",
    "sla_due_at": "2025-10-22T07:54:49Z",
    "sla_breached": true,
    "requester": "user147@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "db",
      "analytics",
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0301",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-05T15:02:17Z",
    "updated_at": "2025-09-23T16:02:17Z",
    "closed_at": "2025-09-23T16:02:17Z",
    "sla_due_at": "2025-09-07T16:02:17Z",
    "sla_breached": true,
    "requester": "user143@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "security",
      "problem",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0302",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-16T01:41:37Z",
    "updated_at": "2025-09-20T19:41:37Z",
    "closed_at": "2025-09-20T19:41:37Z",
    "sla_due_at": "2025-09-17T23:41:37Z",
    "sla_breached": true,
    "requester": "user79@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "vip",
      "onboarding",
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0303",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-28T04:04:15Z",
    "updated_at": "2025-10-11T17:04:15Z",
    "closed_at": null,
    "sla_due_at": "2025-09-30T20:04:15Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0304",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-19T21:29:46Z",
    "updated_at": "2025-09-23T03:29:46Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T05:29:46Z",
    "sla_breached": true,
    "requester": "user88@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "access",
      "vip",
      "analytics",
      "security"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0305",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-14T09:23:02Z",
    "updated_at": "2025-10-15T15:23:02Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T11:23:02Z",
    "sla_breached": true,
    "requester": "user54@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0306",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-15T03:38:51Z",
    "updated_at": "2025-11-23T18:38:51Z",
    "closed_at": "2025-11-23T18:38:51Z",
    "sla_due_at": "2025-11-17T14:38:51Z",
    "sla_breached": true,
    "requester": "user99@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0307",
    "subject": "Application performance degradation",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-10T07:50:47Z",
    "updated_at": "2025-10-21T15:50:47Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T04:50:47Z",
    "sla_breached": true,
    "requester": "user2@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "sso",
      "db"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0308",
    "subject": "Password reset request",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-18T03:39:53Z",
    "updated_at": "2025-10-30T17:39:53Z",
    "closed_at": null,
    "sla_due_at": "2025-10-18T20:39:53Z",
    "sla_breached": true,
    "requester": "user12@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "db",
      "request",
      "change",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0309",
    "subject": "Multi-factor authentication not working",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-02T03:29:16Z",
    "updated_at": "2025-10-12T14:29:16Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T02:29:16Z",
    "sla_breached": true,
    "requester": "user43@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0310",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-10T00:40:11Z",
    "updated_at": "2025-11-13T15:40:11Z",
    "closed_at": "2025-11-13T15:40:11Z",
    "sla_due_at": "2025-11-10T06:40:11Z",
    "sla_breached": true,
    "requester": "user167@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "bug",
      "onboarding",
      "request",
      "change"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0311",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-11T06:36:46Z",
    "updated_at": "2025-09-11T17:36:46Z",
    "closed_at": "2025-09-11T17:36:46Z",
    "sla_due_at": "2025-09-11T23:36:46Z",
    "sla_breached": false,
    "requester": "user107@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "security",
      "request",
      "onboarding",
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0312",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-30T09:24:36Z",
    "updated_at": "2025-11-13T12:24:36Z",
    "closed_at": null,
    "sla_due_at": "2025-10-30T14:24:36Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "incident",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0313",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-08T04:04:21Z",
    "updated_at": "2025-09-10T11:04:21Z",
    "closed_at": null,
    "sla_due_at": "2025-09-09T20:04:21Z",
    "sla_breached": true,
    "requester": "user52@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0314",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-20T02:31:12Z",
    "updated_at": "2025-11-08T13:31:12Z",
    "closed_at": "2025-11-08T13:31:12Z",
    "sla_due_at": "2025-10-20T11:31:12Z",
    "sla_breached": true,
    "requester": "user124@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "network",
      "analytics"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0315",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-11T11:27:17Z",
    "updated_at": "2025-11-13T10:27:17Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T06:27:17Z",
    "sla_breached": true,
    "requester": "user186@enterprise.example.com",
    "assignee": null,
    "tags": [
      "bug",
      "sso",
      "problem"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0316",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-23T15:27:19Z",
    "updated_at": "2025-10-27T09:27:19Z",
    "closed_at": null,
    "sla_due_at": "2025-10-24T01:27:19Z",
    "sla_breached": true,
    "requester": "user75@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "incident",
      "db",
      "security"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0317",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-21T08:00:25Z",
    "updated_at": "2025-11-25T00:00:25Z",
    "closed_at": "2025-11-25T00:00:25Z",
    "sla_due_at": "2025-11-22T05:00:25Z",
    "sla_breached": true,
    "requester": "user113@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "db",
      "security",
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0318",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-03T04:12:52Z",
    "updated_at": "2025-11-12T22:12:52Z",
    "closed_at": "2025-11-12T22:12:52Z",
    "sla_due_at": "2025-11-05T11:12:52Z",
    "sla_breached": true,
    "requester": "user177@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "bug",
      "access",
      "security",
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0319",
    "subject": "Data export failing in analytics app",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-06T04:34:59Z",
    "updated_at": "2025-11-16T12:34:59Z",
    "closed_at": null,
    "sla_due_at": "2025-11-08T13:34:59Z",
    "sla_breached": true,
    "requester": "user113@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "analytics",
      "vip",
      "change",
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0320",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-25T14:35:13Z",
    "updated_at": "2025-10-05T00:35:13Z",
    "closed_at": null,
    "sla_due_at": "2025-09-26T08:35:13Z",
    "sla_breached": true,
    "requester": "user168@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0321",
    "subject": "SSO configuration change",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-13T11:47:15Z",
    "updated_at": "2025-09-27T18:47:15Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T19:47:15Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0322",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-25T19:46:14Z",
    "updated_at": "2025-10-07T17:46:14Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T00:46:14Z",
    "sla_breached": true,
    "requester": "user14@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "problem",
      "access",
      "security",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0323",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-26T20:18:41Z",
    "updated_at": "2025-10-31T15:18:41Z",
    "closed_at": null,
    "sla_due_at": "2025-10-28T11:18:41Z",
    "sla_breached": true,
    "requester": "user104@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0324",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-13T16:02:39Z",
    "updated_at": "2025-09-23T05:02:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T07:02:39Z",
    "sla_breached": true,
    "requester": "user128@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "security"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0325",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-05T07:03:16Z",
    "updated_at": "2025-10-18T05:03:16Z",
    "closed_at": null,
    "sla_due_at": "2025-10-05T11:03:16Z",
    "sla_breached": true,
    "requester": "user131@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "bug",
      "analytics"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0326",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-13T19:07:48Z",
    "updated_at": "2025-10-23T12:07:48Z",
    "closed_at": null,
    "sla_due_at": "2025-10-14T05:07:48Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "db",
      "bug",
      "vip",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0327",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-13T08:22:08Z",
    "updated_at": "2025-11-20T22:22:08Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T16:22:08Z",
    "sla_breached": true,
    "requester": "user75@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0328",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-24T03:14:44Z",
    "updated_at": "2025-10-07T04:14:44Z",
    "closed_at": null,
    "sla_due_at": "2025-09-26T11:14:44Z",
    "sla_breached": true,
    "requester": "user101@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "security",
      "incident",
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0329",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-29T15:42:22Z",
    "updated_at": "2025-10-10T07:42:22Z",
    "closed_at": null,
    "sla_due_at": "2025-10-02T11:42:22Z",
    "sla_breached": true,
    "requester": "user13@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "request",
      "access",
      "change",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0330",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-12T18:15:14Z",
    "updated_at": "2025-11-20T23:15:14Z",
    "closed_at": "2025-11-20T23:15:14Z",
    "sla_due_at": "2025-11-14T15:15:14Z",
    "sla_breached": true,
    "requester": "user178@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "onboarding",
      "incident"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0331",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-19T15:52:17Z",
    "updated_at": "2025-11-01T12:52:17Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T12:52:17Z",
    "sla_breached": true,
    "requester": "user132@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "db",
      "analytics",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0332",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-01T00:43:25Z",
    "updated_at": "2025-11-20T16:43:25Z",
    "closed_at": "2025-11-20T16:43:25Z",
    "sla_due_at": "2025-11-02T17:43:25Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "request",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0333",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-08-28T04:09:26Z",
    "updated_at": "2025-09-09T15:09:26Z",
    "closed_at": "2025-09-09T15:09:26Z",
    "sla_due_at": "2025-08-30T05:09:26Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "incident",
      "network",
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0334",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-22T18:29:31Z",
    "updated_at": "2025-11-23T23:29:31Z",
    "closed_at": null,
    "sla_due_at": "2025-11-23T16:29:31Z",
    "sla_breached": true,
    "requester": "user42@enterprise.example.com",
    "assignee": null,
    "tags": [
      "access",
      "network",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0335",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-18T07:10:58Z",
    "updated_at": "2025-09-20T12:10:58Z",
    "closed_at": null,
    "sla_due_at": "2025-09-20T08:10:58Z",
    "sla_breached": true,
    "requester": "user190@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "db",
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0336",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-07T23:42:30Z",
    "updated_at": "2025-10-22T20:42:30Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T20:42:30Z",
    "sla_breached": true,
    "requester": "user13@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "incident",
      "bug",
      "vip",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0337",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-24T23:12:29Z",
    "updated_at": "2025-11-26T07:26:32Z",
    "closed_at": "2025-11-26T07:26:32Z",
    "sla_due_at": "2025-11-26T04:12:29Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "analytics",
      "change",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0338",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-01T21:38:54Z",
    "updated_at": "2025-11-16T11:38:54Z",
    "closed_at": null,
    "sla_due_at": "2025-11-04T10:38:54Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0339",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-02T22:11:49Z",
    "updated_at": "2025-10-15T10:11:49Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T11:11:49Z",
    "sla_breached": true,
    "requester": "user85@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0340",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-11T06:30:27Z",
    "updated_at": "2025-09-23T12:30:27Z",
    "closed_at": "2025-09-23T12:30:27Z",
    "sla_due_at": "2025-09-13T00:30:27Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "access",
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0341",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-23T02:33:23Z",
    "updated_at": "2025-10-01T17:33:23Z",
    "closed_at": "2025-10-01T17:33:23Z",
    "sla_due_at": "2025-09-25T11:33:23Z",
    "sla_breached": true,
    "requester": "user55@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "vip",
      "analytics",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0342",
    "subject": "Login issues on corporate portal",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-09-07T13:02:39Z",
    "updated_at": "2025-09-21T10:02:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-10T05:02:39Z",
    "sla_breached": true,
    "requester": "user89@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "bug",
      "change"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0343",
    "subject": "New user onboarding request",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-20T20:40:27Z",
    "updated_at": "2025-11-23T07:40:27Z",
    "closed_at": null,
    "sla_due_at": "2025-11-23T00:40:27Z",
    "sla_breached": true,
    "requester": "user186@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0344",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-21T13:50:12Z",
    "updated_at": "2025-09-27T21:50:12Z",
    "closed_at": "2025-09-27T21:50:12Z",
    "sla_due_at": "2025-09-24T02:50:12Z",
    "sla_breached": true,
    "requester": "user83@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "security"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0345",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-18T12:56:44Z",
    "updated_at": "2025-09-23T00:56:44Z",
    "closed_at": "2025-09-23T00:56:44Z",
    "sla_due_at": "2025-09-18T16:56:44Z",
    "sla_breached": true,
    "requester": "user55@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "security",
      "sso",
      "request",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0346",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-08-31T02:45:40Z",
    "updated_at": "2025-09-07T04:45:40Z",
    "closed_at": "2025-09-07T04:45:40Z",
    "sla_due_at": "2025-08-31T09:45:40Z",
    "sla_breached": true,
    "requester": "user14@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "request",
      "security",
      "change"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0347",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-23T17:31:03Z",
    "updated_at": "2025-11-01T09:31:03Z",
    "closed_at": "2025-11-01T09:31:03Z",
    "sla_due_at": "2025-10-25T22:31:03Z",
    "sla_breached": true,
    "requester": "user100@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0348",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-04T09:50:44Z",
    "updated_at": "2025-09-16T21:50:44Z",
    "closed_at": null,
    "sla_due_at": "2025-09-04T21:50:44Z",
    "sla_breached": true,
    "requester": "user19@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0349",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-10T05:12:34Z",
    "updated_at": "2025-09-19T14:12:34Z",
    "closed_at": null,
    "sla_due_at": "2025-09-11T21:12:34Z",
    "sla_breached": true,
    "requester": "user170@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "access",
      "request",
      "sso",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0350",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-17T21:37:09Z",
    "updated_at": "2025-10-01T17:37:09Z",
    "closed_at": null,
    "sla_due_at": "2025-09-18T19:37:09Z",
    "sla_breached": true,
    "requester": "user3@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "security",
      "network"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0351",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-13T10:38:08Z",
    "updated_at": "2025-09-15T06:38:08Z",
    "closed_at": "2025-09-15T06:38:08Z",
    "sla_due_at": "2025-09-15T16:38:08Z",
    "sla_breached": false,
    "requester": "user190@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "sso",
      "incident",
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0352",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-08T02:29:56Z",
    "updated_at": "2025-11-13T12:29:56Z",
    "closed_at": null,
    "sla_due_at": "2025-11-09T05:29:56Z",
    "sla_breached": true,
    "requester": "user172@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0353",
    "subject": "Password reset request",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-27T08:53:14Z",
    "updated_at": "2025-09-28T19:53:14Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T21:53:14Z",
    "sla_breached": true,
    "requester": "user186@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "access",
      "bug",
      "db"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0354",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-13T21:58:39Z",
    "updated_at": "2025-11-20T16:58:39Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T09:58:39Z",
    "sla_breached": true,
    "requester": "user158@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "db",
      "change",
      "access"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0355",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-16T16:45:53Z",
    "updated_at": "2025-10-21T23:45:53Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T17:45:53Z",
    "sla_breached": true,
    "requester": "user190@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "access",
      "bug",
      "vip"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0356",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-27T16:08:39Z",
    "updated_at": "2025-10-08T02:08:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T17:08:39Z",
    "sla_breached": true,
    "requester": "user166@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0357",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-19T01:12:26Z",
    "updated_at": "2025-10-02T10:12:26Z",
    "closed_at": "2025-10-02T10:12:26Z",
    "sla_due_at": "2025-09-20T14:12:26Z",
    "sla_breached": true,
    "requester": "user5@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0358",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-09-12T00:36:46Z",
    "updated_at": "2025-09-23T15:36:46Z",
    "closed_at": "2025-09-23T15:36:46Z",
    "sla_due_at": "2025-09-12T08:36:46Z",
    "sla_breached": true,
    "requester": "user121@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "vip",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0359",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-11T21:45:51Z",
    "updated_at": "2025-09-22T19:45:51Z",
    "closed_at": "2025-09-22T19:45:51Z",
    "sla_due_at": "2025-09-12T18:45:51Z",
    "sla_breached": true,
    "requester": "user129@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "analytics",
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0360",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-22T03:14:54Z",
    "updated_at": "2025-10-04T05:14:54Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T16:14:54Z",
    "sla_breached": true,
    "requester": "user38@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "network",
      "sso",
      "problem"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0361",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-17T22:44:03Z",
    "updated_at": "2025-11-26T08:08:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T01:44:03Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0362",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-12T13:22:35Z",
    "updated_at": "2025-11-18T04:22:35Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T04:22:35Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "vip",
      "change",
      "bug",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0363",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-24T18:39:26Z",
    "updated_at": "2025-11-01T07:39:26Z",
    "closed_at": "2025-11-01T07:39:26Z",
    "sla_due_at": "2025-10-26T02:39:26Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0364",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-01T02:19:46Z",
    "updated_at": "2025-10-14T20:19:46Z",
    "closed_at": null,
    "sla_due_at": "2025-10-02T11:19:46Z",
    "sla_breached": true,
    "requester": "user48@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0365",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-03T20:20:09Z",
    "updated_at": "2025-10-14T02:20:09Z",
    "closed_at": "2025-10-14T02:20:09Z",
    "sla_due_at": "2025-10-04T14:20:09Z",
    "sla_breached": true,
    "requester": "user42@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "network",
      "sso",
      "analytics",
      "access"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0366",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-08T09:26:17Z",
    "updated_at": "2025-11-20T15:26:17Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T06:26:17Z",
    "sla_breached": true,
    "requester": "user67@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "analytics",
      "bug",
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0367",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-16T00:28:23Z",
    "updated_at": "2025-11-26T02:28:23Z",
    "closed_at": "2025-11-26T02:28:23Z",
    "sla_due_at": "2025-11-18T13:28:23Z",
    "sla_breached": true,
    "requester": "user57@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "analytics",
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0368",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-07T13:45:40Z",
    "updated_at": "2025-09-22T05:45:40Z",
    "closed_at": null,
    "sla_due_at": "2025-09-09T02:45:40Z",
    "sla_breached": true,
    "requester": "user153@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "incident",
      "access",
      "security",
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0369",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-20T13:59:45Z",
    "updated_at": "2025-10-03T12:59:45Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T22:59:45Z",
    "sla_breached": true,
    "requester": "user158@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0370",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-23T04:04:49Z",
    "updated_at": "2025-09-25T23:04:49Z",
    "closed_at": "2025-09-25T23:04:49Z",
    "sla_due_at": "2025-09-23T19:04:49Z",
    "sla_breached": true,
    "requester": "user1@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "request",
      "incident",
      "vip",
      "network"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0371",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-03T00:00:13Z",
    "updated_at": "2025-10-11T04:00:13Z",
    "closed_at": null,
    "sla_due_at": "2025-10-05T17:00:13Z",
    "sla_breached": true,
    "requester": "user190@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0372",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-24T14:59:13Z",
    "updated_at": "2025-10-26T09:59:13Z",
    "closed_at": null,
    "sla_due_at": "2025-10-25T23:59:13Z",
    "sla_breached": true,
    "requester": "user140@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "sso",
      "network",
      "db"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0373",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-10T13:26:06Z",
    "updated_at": "2025-11-14T23:26:06Z",
    "closed_at": null,
    "sla_due_at": "2025-11-10T17:26:06Z",
    "sla_breached": true,
    "requester": "user105@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "bug",
      "change",
      "onboarding",
      "analytics"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0374",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-02T11:48:00Z",
    "updated_at": "2025-10-17T00:48:00Z",
    "closed_at": "2025-10-17T00:48:00Z",
    "sla_due_at": "2025-10-04T13:48:00Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "access",
      "vip",
      "request",
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0375",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-24T21:11:39Z",
    "updated_at": "2025-11-02T09:11:39Z",
    "closed_at": null,
    "sla_due_at": "2025-10-26T21:11:39Z",
    "sla_breached": true,
    "requester": "user169@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "problem",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0376",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-14T00:33:03Z",
    "updated_at": "2025-11-21T06:33:03Z",
    "closed_at": "2025-11-21T06:33:03Z",
    "sla_due_at": "2025-11-16T21:33:03Z",
    "sla_breached": true,
    "requester": "user179@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "access"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0377",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-06T08:09:59Z",
    "updated_at": "2025-09-16T10:09:59Z",
    "closed_at": null,
    "sla_due_at": "2025-09-06T23:09:59Z",
    "sla_breached": true,
    "requester": "user23@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "sso",
      "vip",
      "security"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0378",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-07T17:46:19Z",
    "updated_at": "2025-10-20T11:46:19Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T15:46:19Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0379",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-21T01:16:07Z",
    "updated_at": "2025-10-31T23:16:07Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T09:16:07Z",
    "sla_breached": true,
    "requester": "user158@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0380",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-04T08:20:55Z",
    "updated_at": "2025-09-10T06:20:55Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T08:20:55Z",
    "sla_breached": true,
    "requester": "user172@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "request",
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0381",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-14T12:20:56Z",
    "updated_at": "2025-11-26T07:23:32Z",
    "closed_at": "2025-11-26T07:23:32Z",
    "sla_due_at": "2025-11-16T04:20:56Z",
    "sla_breached": true,
    "requester": "user71@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "problem",
      "incident"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0382",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-24T01:59:10Z",
    "updated_at": "2025-11-05T00:59:10Z",
    "closed_at": "2025-11-05T00:59:10Z",
    "sla_due_at": "2025-10-26T09:59:10Z",
    "sla_breached": true,
    "requester": "user88@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "request",
      "change",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0383",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-08T11:51:17Z",
    "updated_at": "2025-10-15T17:51:17Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T04:51:17Z",
    "sla_breached": true,
    "requester": "user118@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0384",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-24T05:53:58Z",
    "updated_at": "2025-10-28T22:53:58Z",
    "closed_at": "2025-10-28T22:53:58Z",
    "sla_due_at": "2025-10-26T09:53:58Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "request",
      "analytics",
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0385",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-25T21:53:57Z",
    "updated_at": "2025-11-02T05:53:57Z",
    "closed_at": null,
    "sla_due_at": "2025-10-26T12:53:57Z",
    "sla_breached": true,
    "requester": "user46@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "change",
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0386",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-08-31T01:26:07Z",
    "updated_at": "2025-09-05T02:26:07Z",
    "closed_at": "2025-09-05T02:26:07Z",
    "sla_due_at": "2025-09-02T20:26:07Z",
    "sla_breached": true,
    "requester": "user68@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "sso",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0387",
    "subject": "Upgrade request for enterprise license",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-07T04:28:29Z",
    "updated_at": "2025-11-21T15:28:29Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T23:28:29Z",
    "sla_breached": true,
    "requester": "user2@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0388",
    "subject": "SSO configuration change",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-07T20:52:30Z",
    "updated_at": "2025-09-20T03:52:30Z",
    "closed_at": null,
    "sla_due_at": "2025-09-10T15:52:30Z",
    "sla_breached": true,
    "requester": "user47@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "incident",
      "sso",
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0389",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-19T13:13:03Z",
    "updated_at": "2025-11-26T08:19:32Z",
    "closed_at": "2025-11-26T08:19:32Z",
    "sla_due_at": "2025-11-21T23:13:03Z",
    "sla_breached": true,
    "requester": "user176@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "problem",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0390",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-28T20:51:59Z",
    "updated_at": "2025-10-03T08:51:59Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T01:51:59Z",
    "sla_breached": true,
    "requester": "user84@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "request",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0391",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-22T15:11:52Z",
    "updated_at": "2025-11-02T07:11:52Z",
    "closed_at": null,
    "sla_due_at": "2025-10-24T14:11:52Z",
    "sla_breached": true,
    "requester": "user180@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident",
      "onboarding",
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0392",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-14T03:35:04Z",
    "updated_at": "2025-09-19T22:35:04Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T12:35:04Z",
    "sla_breached": true,
    "requester": "user111@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "access",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0393",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-27T08:00:16Z",
    "updated_at": "2025-09-30T05:00:16Z",
    "closed_at": "2025-09-30T05:00:16Z",
    "sla_due_at": "2025-09-28T10:00:16Z",
    "sla_breached": true,
    "requester": "user133@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "analytics",
      "problem",
      "onboarding"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0394",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-15T11:41:05Z",
    "updated_at": "2025-09-30T05:41:05Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T21:41:05Z",
    "sla_breached": true,
    "requester": "user66@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0395",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-23T19:13:00Z",
    "updated_at": "2025-11-12T17:13:00Z",
    "closed_at": "2025-11-12T17:13:00Z",
    "sla_due_at": "2025-10-25T21:13:00Z",
    "sla_breached": true,
    "requester": "user6@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0396",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-13T11:23:29Z",
    "updated_at": "2025-09-19T13:23:29Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T11:23:29Z",
    "sla_breached": true,
    "requester": "user131@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "security",
      "incident",
      "change",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0397",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-07T03:05:07Z",
    "updated_at": "2025-09-26T23:05:07Z",
    "closed_at": "2025-09-26T23:05:07Z",
    "sla_due_at": "2025-09-08T04:05:07Z",
    "sla_breached": true,
    "requester": "user157@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "security",
      "analytics",
      "access",
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0398",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-16T20:49:19Z",
    "updated_at": "2025-10-29T18:49:19Z",
    "closed_at": "2025-10-29T18:49:19Z",
    "sla_due_at": "2025-10-18T13:49:19Z",
    "sla_breached": true,
    "requester": "user114@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "db",
      "change",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0399",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-05T02:16:02Z",
    "updated_at": "2025-10-07T19:16:02Z",
    "closed_at": null,
    "sla_due_at": "2025-10-06T05:16:02Z",
    "sla_breached": true,
    "requester": "user65@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0400",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-07T04:36:31Z",
    "updated_at": "2025-10-17T07:36:31Z",
    "closed_at": null,
    "sla_due_at": "2025-10-07T20:36:31Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0401",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-08T02:42:20Z",
    "updated_at": "2025-09-27T00:42:20Z",
    "closed_at": "2025-09-27T00:42:20Z",
    "sla_due_at": "2025-09-08T16:42:20Z",
    "sla_breached": true,
    "requester": "user64@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "problem",
      "bug",
      "access"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0402",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-20T02:08:51Z",
    "updated_at": "2025-09-27T17:08:51Z",
    "closed_at": null,
    "sla_due_at": "2025-09-20T09:08:51Z",
    "sla_breached": true,
    "requester": "user122@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "request",
      "problem",
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0403",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-03T10:50:51Z",
    "updated_at": "2025-11-17T00:50:51Z",
    "closed_at": "2025-11-17T00:50:51Z",
    "sla_due_at": "2025-11-06T00:50:51Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "vip",
      "problem",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0404",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-14T16:16:17Z",
    "updated_at": "2025-11-20T06:16:17Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T11:16:17Z",
    "sla_breached": true,
    "requester": "user1@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "vip",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0405",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-09-19T08:03:22Z",
    "updated_at": "2025-09-29T13:03:22Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T02:03:22Z",
    "sla_breached": true,
    "requester": "user111@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "analytics",
      "network"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0406",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-10T01:29:36Z",
    "updated_at": "2025-10-19T09:29:36Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T09:29:36Z",
    "sla_breached": true,
    "requester": "user184@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "incident",
      "sso",
      "onboarding",
      "security"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0407",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-06T23:38:13Z",
    "updated_at": "2025-09-20T01:38:13Z",
    "closed_at": null,
    "sla_due_at": "2025-09-09T21:38:13Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "incident",
      "sso",
      "security"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0408",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-08T21:48:55Z",
    "updated_at": "2025-11-22T02:48:55Z",
    "closed_at": "2025-11-22T02:48:55Z",
    "sla_due_at": "2025-11-09T15:48:55Z",
    "sla_breached": true,
    "requester": "user160@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "vip",
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0409",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-19T12:52:53Z",
    "updated_at": "2025-11-21T17:52:53Z",
    "closed_at": null,
    "sla_due_at": "2025-11-19T18:52:53Z",
    "sla_breached": true,
    "requester": "user184@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "security",
      "access"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0410",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-24T00:27:05Z",
    "updated_at": "2025-10-10T19:27:05Z",
    "closed_at": "2025-10-10T19:27:05Z",
    "sla_due_at": "2025-09-25T23:27:05Z",
    "sla_breached": true,
    "requester": "user96@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0411",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-08T06:19:07Z",
    "updated_at": "2025-11-09T19:19:07Z",
    "closed_at": null,
    "sla_due_at": "2025-11-09T20:19:07Z",
    "sla_breached": true,
    "requester": "user50@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "network",
      "security",
      "sso",
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0412",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-26T07:08:20Z",
    "updated_at": "2025-11-11T18:08:20Z",
    "closed_at": "2025-11-11T18:08:20Z",
    "sla_due_at": "2025-10-27T12:08:20Z",
    "sla_breached": true,
    "requester": "user54@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "bug",
      "onboarding",
      "vip",
      "access"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0413",
    "subject": "Password reset request",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-16T13:23:34Z",
    "updated_at": "2025-09-30T04:23:34Z",
    "closed_at": null,
    "sla_due_at": "2025-09-17T08:23:34Z",
    "sla_breached": true,
    "requester": "user14@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security",
      "sso"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0414",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-16T07:48:38Z",
    "updated_at": "2025-10-28T19:48:38Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T08:48:38Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0415",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-08-29T10:39:06Z",
    "updated_at": "2025-08-31T08:39:06Z",
    "closed_at": null,
    "sla_due_at": "2025-08-30T09:39:06Z",
    "sla_breached": true,
    "requester": "user24@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0416",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-05T02:45:18Z",
    "updated_at": "2025-09-07T19:45:18Z",
    "closed_at": null,
    "sla_due_at": "2025-09-08T02:45:18Z",
    "sla_breached": true,
    "requester": "user143@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "analytics",
      "problem",
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0417",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-08-29T18:36:18Z",
    "updated_at": "2025-09-04T03:36:18Z",
    "closed_at": "2025-09-04T03:36:18Z",
    "sla_due_at": "2025-08-31T19:36:18Z",
    "sla_breached": true,
    "requester": "user181@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "request",
      "db",
      "problem"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0418",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-15T01:33:51Z",
    "updated_at": "2025-09-25T01:33:51Z",
    "closed_at": null,
    "sla_due_at": "2025-09-17T01:33:51Z",
    "sla_breached": true,
    "requester": "user154@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security",
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0419",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-29T21:35:38Z",
    "updated_at": "2025-10-09T14:35:38Z",
    "closed_at": "2025-10-09T14:35:38Z",
    "sla_due_at": "2025-10-01T10:35:38Z",
    "sla_breached": true,
    "requester": "user130@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "network",
      "change"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0420",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-07T23:39:54Z",
    "updated_at": "2025-09-22T01:39:54Z",
    "closed_at": "2025-09-22T01:39:54Z",
    "sla_due_at": "2025-09-09T20:39:54Z",
    "sla_breached": true,
    "requester": "user49@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "analytics",
      "request",
      "access",
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0421",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-15T17:26:19Z",
    "updated_at": "2025-10-26T21:26:19Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T14:26:19Z",
    "sla_breached": true,
    "requester": "user34@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "security",
      "problem"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0422",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-14T07:12:02Z",
    "updated_at": "2025-11-25T13:12:02Z",
    "closed_at": "2025-11-25T13:12:02Z",
    "sla_due_at": "2025-11-16T12:12:02Z",
    "sla_breached": true,
    "requester": "user66@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "sso",
      "change",
      "security"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0423",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-30T08:29:02Z",
    "updated_at": "2025-11-01T01:29:02Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T02:29:02Z",
    "sla_breached": true,
    "requester": "user16@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "vip",
      "db",
      "network",
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0424",
    "subject": "Application performance degradation",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-09-20T06:52:44Z",
    "updated_at": "2025-09-21T22:52:44Z",
    "closed_at": null,
    "sla_due_at": "2025-09-20T19:52:44Z",
    "sla_breached": true,
    "requester": "user25@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "request",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0425",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-01T13:12:03Z",
    "updated_at": "2025-11-05T09:12:03Z",
    "closed_at": "2025-11-05T09:12:03Z",
    "sla_due_at": "2025-11-03T00:12:03Z",
    "sla_breached": true,
    "requester": "user107@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0426",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-08-31T15:39:27Z",
    "updated_at": "2025-09-04T05:39:27Z",
    "closed_at": null,
    "sla_due_at": "2025-09-03T01:39:27Z",
    "sla_breached": true,
    "requester": "user103@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "bug",
      "access",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0427",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-11T20:53:05Z",
    "updated_at": "2025-10-20T16:53:05Z",
    "closed_at": null,
    "sla_due_at": "2025-10-13T17:53:05Z",
    "sla_breached": true,
    "requester": "user186@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "change",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0428",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-08T12:19:32Z",
    "updated_at": "2025-10-18T04:19:32Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T00:19:32Z",
    "sla_breached": true,
    "requester": "user1@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "network",
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0429",
    "subject": "SSO configuration change",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-19T08:07:12Z",
    "updated_at": "2025-10-23T22:07:12Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T02:07:12Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "request",
      "analytics",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0430",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-14T06:59:06Z",
    "updated_at": "2025-11-17T05:59:06Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T20:59:06Z",
    "sla_breached": true,
    "requester": "user150@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "security",
      "change",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0431",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-16T20:32:14Z",
    "updated_at": "2025-11-26T07:37:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-19T13:32:14Z",
    "sla_breached": true,
    "requester": "user25@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0432",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-16T06:19:23Z",
    "updated_at": "2025-11-25T13:19:23Z",
    "closed_at": null,
    "sla_due_at": "2025-11-18T04:19:23Z",
    "sla_breached": true,
    "requester": "user31@enterprise.example.com",
    "assignee": null,
    "tags": [
      "db",
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0433",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-05T09:20:30Z",
    "updated_at": "2025-09-16T14:20:30Z",
    "closed_at": null,
    "sla_due_at": "2025-09-07T13:20:30Z",
    "sla_breached": true,
    "requester": "user145@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "access",
      "network"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0434",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-29T10:41:27Z",
    "updated_at": "2025-10-08T16:41:27Z",
    "closed_at": null,
    "sla_due_at": "2025-10-02T06:41:27Z",
    "sla_breached": true,
    "requester": "user38@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "change",
      "db",
      "network",
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0435",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-24T05:15:41Z",
    "updated_at": "2025-11-09T18:15:41Z",
    "closed_at": "2025-11-09T18:15:41Z",
    "sla_due_at": "2025-10-26T12:15:41Z",
    "sla_breached": true,
    "requester": "user35@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "problem",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0436",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-15T09:55:53Z",
    "updated_at": "2025-09-16T22:55:53Z",
    "closed_at": null,
    "sla_due_at": "2025-09-18T08:55:53Z",
    "sla_breached": true,
    "requester": "user83@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "security"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0437",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-02T19:03:36Z",
    "updated_at": "2025-10-10T04:03:36Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T19:03:36Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "change",
      "access",
      "problem",
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0438",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-31T18:44:55Z",
    "updated_at": "2025-11-02T14:44:55Z",
    "closed_at": null,
    "sla_due_at": "2025-11-01T17:44:55Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "onboarding",
      "network"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0439",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-08-30T04:18:27Z",
    "updated_at": "2025-08-30T16:18:27Z",
    "closed_at": "2025-08-30T16:18:27Z",
    "sla_due_at": "2025-08-31T23:18:27Z",
    "sla_breached": false,
    "requester": "user138@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "request",
      "analytics"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0440",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-16T14:46:21Z",
    "updated_at": "2025-09-30T21:46:21Z",
    "closed_at": "2025-09-30T21:46:21Z",
    "sla_due_at": "2025-09-17T12:46:21Z",
    "sla_breached": true,
    "requester": "user170@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0441",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-18T22:01:06Z",
    "updated_at": "2025-11-26T08:04:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T03:01:06Z",
    "sla_breached": true,
    "requester": "user3@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "bug",
      "onboarding",
      "analytics",
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0442",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-23T21:42:35Z",
    "updated_at": "2025-11-26T07:49:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-26T02:42:35Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0443",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-22T15:41:03Z",
    "updated_at": "2025-10-03T23:41:03Z",
    "closed_at": null,
    "sla_due_at": "2025-09-22T21:41:03Z",
    "sla_breached": true,
    "requester": "user101@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0444",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-11T09:35:42Z",
    "updated_at": "2025-10-22T02:35:42Z",
    "closed_at": null,
    "sla_due_at": "2025-10-13T03:35:42Z",
    "sla_breached": true,
    "requester": "user161@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0445",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-29T02:50:08Z",
    "updated_at": "2025-11-12T03:50:08Z",
    "closed_at": null,
    "sla_due_at": "2025-10-31T01:50:08Z",
    "sla_breached": true,
    "requester": "user98@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "incident",
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0446",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-02T20:59:08Z",
    "updated_at": "2025-10-05T16:59:08Z",
    "closed_at": "2025-10-05T16:59:08Z",
    "sla_due_at": "2025-10-04T18:59:08Z",
    "sla_breached": true,
    "requester": "user149@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "access",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0447",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-08T16:42:03Z",
    "updated_at": "2025-11-20T18:42:03Z",
    "closed_at": "2025-11-20T18:42:03Z",
    "sla_due_at": "2025-11-09T14:42:03Z",
    "sla_breached": true,
    "requester": "user18@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0448",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-08T07:17:08Z",
    "updated_at": "2025-11-17T03:17:08Z",
    "closed_at": null,
    "sla_due_at": "2025-11-10T03:17:08Z",
    "sla_breached": true,
    "requester": "user191@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "access",
      "sso",
      "security"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0449",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-03T07:24:19Z",
    "updated_at": "2025-11-16T09:24:19Z",
    "closed_at": "2025-11-16T09:24:19Z",
    "sla_due_at": "2025-11-04T21:24:19Z",
    "sla_breached": true,
    "requester": "user60@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0450",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-08-29T15:00:23Z",
    "updated_at": "2025-09-11T13:00:23Z",
    "closed_at": "2025-09-11T13:00:23Z",
    "sla_due_at": "2025-08-30T12:00:23Z",
    "sla_breached": true,
    "requester": "user96@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "problem",
      "analytics",
      "access",
      "bug"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0451",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-29T07:11:08Z",
    "updated_at": "2025-10-29T15:11:08Z",
    "closed_at": null,
    "sla_due_at": "2025-10-31T15:11:08Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "analytics",
      "sso"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0452",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-03T16:21:55Z",
    "updated_at": "2025-11-22T04:21:55Z",
    "closed_at": "2025-11-22T04:21:55Z",
    "sla_due_at": "2025-11-06T10:21:55Z",
    "sla_breached": true,
    "requester": "user110@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0453",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-16T18:00:30Z",
    "updated_at": "2025-11-04T11:00:30Z",
    "closed_at": "2025-11-04T11:00:30Z",
    "sla_due_at": "2025-10-19T18:00:30Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "problem",
      "network",
      "sso",
      "request"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0454",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-07T06:55:48Z",
    "updated_at": "2025-10-20T17:55:48Z",
    "closed_at": "2025-10-20T17:55:48Z",
    "sla_due_at": "2025-10-09T11:55:48Z",
    "sla_breached": true,
    "requester": "user113@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "analytics",
      "onboarding",
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0455",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-02T21:38:22Z",
    "updated_at": "2025-10-22T04:38:22Z",
    "closed_at": "2025-10-22T04:38:22Z",
    "sla_due_at": "2025-10-03T07:38:22Z",
    "sla_breached": true,
    "requester": "user166@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0456",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-12T01:48:50Z",
    "updated_at": "2025-11-18T23:48:50Z",
    "closed_at": null,
    "sla_due_at": "2025-11-12T22:48:50Z",
    "sla_breached": true,
    "requester": "user117@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "problem",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0457",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-15T08:44:42Z",
    "updated_at": "2025-10-18T00:44:42Z",
    "closed_at": "2025-10-18T00:44:42Z",
    "sla_due_at": "2025-10-16T08:44:42Z",
    "sla_breached": true,
    "requester": "user116@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "security",
      "request",
      "incident"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0458",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-09T02:32:14Z",
    "updated_at": "2025-09-10T01:32:14Z",
    "closed_at": "2025-09-10T01:32:14Z",
    "sla_due_at": "2025-09-11T06:32:14Z",
    "sla_breached": false,
    "requester": "user86@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "access",
      "analytics"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0459",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-19T17:04:57Z",
    "updated_at": "2025-11-26T08:03:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T12:04:57Z",
    "sla_breached": true,
    "requester": "user34@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0460",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-24T15:39:37Z",
    "updated_at": "2025-11-26T07:30:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-27T10:39:37Z",
    "sla_breached": false,
    "requester": "user127@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "change",
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0461",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-28T17:25:33Z",
    "updated_at": "2025-10-11T13:25:33Z",
    "closed_at": null,
    "sla_due_at": "2025-10-01T05:25:33Z",
    "sla_breached": true,
    "requester": "user141@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "network",
      "access"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0462",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-18T08:34:26Z",
    "updated_at": "2025-11-19T01:34:26Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T08:34:26Z",
    "sla_breached": true,
    "requester": "user155@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "security"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0463",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-04T02:29:06Z",
    "updated_at": "2025-11-18T21:29:06Z",
    "closed_at": "2025-11-18T21:29:06Z",
    "sla_due_at": "2025-11-05T18:29:06Z",
    "sla_breached": true,
    "requester": "user144@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "db",
      "change",
      "vip",
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0464",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-18T20:36:20Z",
    "updated_at": "2025-10-20T07:36:20Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T23:36:20Z",
    "sla_breached": true,
    "requester": "user141@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "problem",
      "access",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0465",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-14T13:10:11Z",
    "updated_at": "2025-10-29T10:10:11Z",
    "closed_at": "2025-10-29T10:10:11Z",
    "sla_due_at": "2025-10-16T21:10:11Z",
    "sla_breached": true,
    "requester": "user28@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0466",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-02T10:11:30Z",
    "updated_at": "2025-10-14T17:11:30Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T06:11:30Z",
    "sla_breached": true,
    "requester": "user34@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "problem",
      "access",
      "change",
      "sso"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0467",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-02T08:18:05Z",
    "updated_at": "2025-11-15T17:18:05Z",
    "closed_at": null,
    "sla_due_at": "2025-11-03T03:18:05Z",
    "sla_breached": true,
    "requester": "user54@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident",
      "network",
      "vip",
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0468",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-06T00:37:41Z",
    "updated_at": "2025-09-20T18:37:41Z",
    "closed_at": "2025-09-20T18:37:41Z",
    "sla_due_at": "2025-09-06T05:37:41Z",
    "sla_breached": true,
    "requester": "user18@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "request",
      "analytics",
      "vip"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0469",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-11T20:13:28Z",
    "updated_at": "2025-11-24T00:13:28Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T19:13:28Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "problem",
      "network",
      "bug",
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0470",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-06T09:31:24Z",
    "updated_at": "2025-11-17T20:31:24Z",
    "closed_at": null,
    "sla_due_at": "2025-11-08T23:31:24Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0471",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-14T20:52:19Z",
    "updated_at": "2025-09-27T04:52:19Z",
    "closed_at": null,
    "sla_due_at": "2025-09-17T20:52:19Z",
    "sla_breached": true,
    "requester": "user91@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "network",
      "vip",
      "incident"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0472",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-04T11:34:13Z",
    "updated_at": "2025-11-06T23:34:13Z",
    "closed_at": null,
    "sla_due_at": "2025-11-06T16:34:13Z",
    "sla_breached": true,
    "requester": "user79@enterprise.example.com",
    "assignee": null,
    "tags": [
      "db",
      "network",
      "onboarding"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0473",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-14T14:15:43Z",
    "updated_at": "2025-11-21T01:15:43Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T00:15:43Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "security",
      "problem"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0474",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-22T14:47:09Z",
    "updated_at": "2025-11-26T07:22:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T10:47:09Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "analytics",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0475",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-01T03:31:37Z",
    "updated_at": "2025-09-10T23:31:37Z",
    "closed_at": "2025-09-10T23:31:37Z",
    "sla_due_at": "2025-09-02T09:31:37Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0476",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-30T10:43:18Z",
    "updated_at": "2025-08-31T10:43:18Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T01:43:18Z",
    "sla_breached": true,
    "requester": "user169@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0477",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-06T00:43:08Z",
    "updated_at": "2025-09-12T03:43:08Z",
    "closed_at": null,
    "sla_due_at": "2025-09-07T21:43:08Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "access",
      "analytics",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0478",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-24T09:40:42Z",
    "updated_at": "2025-11-26T07:59:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-27T06:40:42Z",
    "sla_breached": false,
    "requester": "user37@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "sso",
      "access"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0479",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-17T10:01:51Z",
    "updated_at": "2025-10-18T12:01:51Z",
    "closed_at": "2025-10-18T12:01:51Z",
    "sla_due_at": "2025-10-19T09:01:51Z",
    "sla_breached": false,
    "requester": "user173@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0480",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-14T16:49:55Z",
    "updated_at": "2025-11-26T07:24:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T22:49:55Z",
    "sla_breached": true,
    "requester": "user177@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "onboarding",
      "vip",
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0481",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-15T15:24:13Z",
    "updated_at": "2025-11-26T07:52:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T11:24:13Z",
    "sla_breached": true,
    "requester": "user176@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "problem",
      "sso",
      "db",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0482",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-10T18:05:02Z",
    "updated_at": "2025-10-24T23:05:02Z",
    "closed_at": "2025-10-24T23:05:02Z",
    "sla_due_at": "2025-10-11T21:05:02Z",
    "sla_breached": true,
    "requester": "user84@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "network",
      "security",
      "problem",
      "db"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0483",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-25T15:33:57Z",
    "updated_at": "2025-10-03T02:33:57Z",
    "closed_at": null,
    "sla_due_at": "2025-09-26T16:33:57Z",
    "sla_breached": true,
    "requester": "user131@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0484",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-04T05:46:36Z",
    "updated_at": "2025-09-12T19:46:36Z",
    "closed_at": "2025-09-12T19:46:36Z",
    "sla_due_at": "2025-09-05T23:46:36Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "problem",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0485",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-14T00:46:38Z",
    "updated_at": "2025-10-23T07:46:38Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T11:46:38Z",
    "sla_breached": true,
    "requester": "user140@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "access",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0486",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-13T14:38:29Z",
    "updated_at": "2025-09-23T12:38:29Z",
    "closed_at": "2025-09-23T12:38:29Z",
    "sla_due_at": "2025-09-14T08:38:29Z",
    "sla_breached": true,
    "requester": "user114@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "incident",
      "security",
      "change"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0487",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "low",
    "created_at": "2025-08-30T10:38:40Z",
    "updated_at": "2025-09-13T05:38:40Z",
    "closed_at": null,
    "sla_due_at": "2025-09-01T14:38:40Z",
    "sla_breached": true,
    "requester": "user56@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0488",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-03T02:55:34Z",
    "updated_at": "2025-09-11T10:55:34Z",
    "closed_at": "2025-09-11T10:55:34Z",
    "sla_due_at": "2025-09-05T15:55:34Z",
    "sla_breached": true,
    "requester": "user51@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "onboarding",
      "change",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0489",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-01T19:49:29Z",
    "updated_at": "2025-10-14T21:49:29Z",
    "closed_at": "2025-10-14T21:49:29Z",
    "sla_due_at": "2025-10-02T10:49:29Z",
    "sla_breached": true,
    "requester": "user33@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0490",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-20T08:19:42Z",
    "updated_at": "2025-11-26T07:26:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-22T09:19:42Z",
    "sla_breached": true,
    "requester": "user180@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "db",
      "incident",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0491",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-01T12:30:43Z",
    "updated_at": "2025-10-11T16:30:43Z",
    "closed_at": "2025-10-11T16:30:43Z",
    "sla_due_at": "2025-10-02T19:30:43Z",
    "sla_breached": true,
    "requester": "user99@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "access",
      "onboarding",
      "bug",
      "analytics"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0492",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-25T05:44:49Z",
    "updated_at": "2025-11-26T07:39:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T11:44:49Z",
    "sla_breached": true,
    "requester": "user35@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "problem",
      "db",
      "change",
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0493",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-28T13:48:42Z",
    "updated_at": "2025-10-08T04:48:42Z",
    "closed_at": "2025-10-08T04:48:42Z",
    "sla_due_at": "2025-09-30T23:48:42Z",
    "sla_breached": true,
    "requester": "user48@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0494",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-26T14:05:30Z",
    "updated_at": "2025-11-07T06:05:30Z",
    "closed_at": "2025-11-07T06:05:30Z",
    "sla_due_at": "2025-10-28T04:05:30Z",
    "sla_breached": true,
    "requester": "user10@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "db",
      "vip",
      "security",
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0495",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-08-30T05:26:38Z",
    "updated_at": "2025-09-10T11:26:38Z",
    "closed_at": "2025-09-10T11:26:38Z",
    "sla_due_at": "2025-08-31T03:26:38Z",
    "sla_breached": true,
    "requester": "user200@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "request",
      "security",
      "analytics",
      "change"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0496",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-25T15:09:27Z",
    "updated_at": "2025-11-06T04:09:27Z",
    "closed_at": "2025-11-06T04:09:27Z",
    "sla_due_at": "2025-10-26T04:09:27Z",
    "sla_breached": true,
    "requester": "user157@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "request",
      "network",
      "problem"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0497",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-21T15:16:29Z",
    "updated_at": "2025-10-08T16:16:29Z",
    "closed_at": "2025-10-08T16:16:29Z",
    "sla_due_at": "2025-09-23T13:16:29Z",
    "sla_breached": true,
    "requester": "user10@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "db",
      "change",
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0498",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-06T15:07:54Z",
    "updated_at": "2025-09-20T16:07:54Z",
    "closed_at": "2025-09-20T16:07:54Z",
    "sla_due_at": "2025-09-07T16:07:54Z",
    "sla_breached": true,
    "requester": "user160@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "problem",
      "security",
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0499",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-16T22:14:34Z",
    "updated_at": "2025-11-22T22:14:34Z",
    "closed_at": null,
    "sla_due_at": "2025-11-18T10:14:34Z",
    "sla_breached": true,
    "requester": "user4@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0500",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-02T16:05:49Z",
    "updated_at": "2025-09-08T06:05:49Z",
    "closed_at": null,
    "sla_due_at": "2025-09-04T19:05:49Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0501",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-07T10:40:33Z",
    "updated_at": "2025-11-16T06:40:33Z",
    "closed_at": null,
    "sla_due_at": "2025-11-08T09:40:33Z",
    "sla_breached": true,
    "requester": "user170@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "sso",
      "change"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0502",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-19T08:58:30Z",
    "updated_at": "2025-11-21T20:58:30Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T21:58:30Z",
    "sla_breached": true,
    "requester": "user103@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "problem",
      "db",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0503",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-08T18:09:25Z",
    "updated_at": "2025-10-20T02:09:25Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T10:09:25Z",
    "sla_breached": true,
    "requester": "user74@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident",
      "bug",
      "vip",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0504",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-11-13T13:00:55Z",
    "updated_at": "2025-11-22T19:00:55Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T14:00:55Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "onboarding",
      "security",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0505",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-09-27T23:33:20Z",
    "updated_at": "2025-10-12T10:33:20Z",
    "closed_at": "2025-10-12T10:33:20Z",
    "sla_due_at": "2025-09-29T03:33:20Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0506",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-18T07:55:25Z",
    "updated_at": "2025-11-20T13:55:25Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T15:55:25Z",
    "sla_breached": true,
    "requester": "user57@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso",
      "network",
      "db"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0507",
    "subject": "Security alert investigation",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-11-18T10:43:38Z",
    "updated_at": "2025-11-26T08:14:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-19T17:43:38Z",
    "sla_breached": true,
    "requester": "user23@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "incident",
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0508",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-12T01:39:01Z",
    "updated_at": "2025-11-26T04:39:01Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T13:39:01Z",
    "sla_breached": true,
    "requester": "user117@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "incident",
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0509",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-25T02:27:43Z",
    "updated_at": "2025-10-26T10:27:43Z",
    "closed_at": null,
    "sla_due_at": "2025-10-25T15:27:43Z",
    "sla_breached": true,
    "requester": "user16@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "problem",
      "security"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0510",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-31T10:08:19Z",
    "updated_at": "2025-11-10T22:08:19Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T16:08:19Z",
    "sla_breached": true,
    "requester": "user197@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0511",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-13T07:05:23Z",
    "updated_at": "2025-11-18T16:05:23Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T20:05:23Z",
    "sla_breached": true,
    "requester": "user128@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "network"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0512",
    "subject": "Login issues on corporate portal",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-23T02:50:21Z",
    "updated_at": "2025-11-04T09:50:21Z",
    "closed_at": null,
    "sla_due_at": "2025-10-25T00:50:21Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "incident",
      "analytics",
      "security",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0513",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-25T18:21:45Z",
    "updated_at": "2025-11-26T07:22:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-28T11:21:45Z",
    "sla_breached": false,
    "requester": "user78@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0514",
    "subject": "Upgrade request for enterprise license",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-14T05:25:47Z",
    "updated_at": "2025-10-20T10:25:47Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T19:25:47Z",
    "sla_breached": true,
    "requester": "user142@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "bug",
      "sso",
      "onboarding",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0515",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-06T19:16:43Z",
    "updated_at": "2025-09-20T07:16:43Z",
    "closed_at": null,
    "sla_due_at": "2025-09-09T13:16:43Z",
    "sla_breached": true,
    "requester": "user36@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "problem",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0516",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-17T08:56:00Z",
    "updated_at": "2025-10-05T04:56:00Z",
    "closed_at": "2025-10-05T04:56:00Z",
    "sla_due_at": "2025-09-19T03:56:00Z",
    "sla_breached": true,
    "requester": "user5@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "network",
      "vip",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0517",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-11T00:39:07Z",
    "updated_at": "2025-11-25T12:39:07Z",
    "closed_at": "2025-11-25T12:39:07Z",
    "sla_due_at": "2025-11-13T22:39:07Z",
    "sla_breached": true,
    "requester": "user39@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "security",
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0518",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-24T08:33:13Z",
    "updated_at": "2025-10-13T23:33:13Z",
    "closed_at": "2025-10-13T23:33:13Z",
    "sla_due_at": "2025-09-24T14:33:13Z",
    "sla_breached": true,
    "requester": "user180@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "network",
      "access"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0519",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-18T04:49:00Z",
    "updated_at": "2025-11-05T00:49:00Z",
    "closed_at": "2025-11-05T00:49:00Z",
    "sla_due_at": "2025-10-20T18:49:00Z",
    "sla_breached": true,
    "requester": "user28@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "change",
      "analytics",
      "sso",
      "security"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0520",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-02T20:04:36Z",
    "updated_at": "2025-10-17T11:04:36Z",
    "closed_at": null,
    "sla_due_at": "2025-10-05T03:04:36Z",
    "sla_breached": true,
    "requester": "user83@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0521",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-15T06:03:26Z",
    "updated_at": "2025-10-24T03:03:26Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T01:03:26Z",
    "sla_breached": true,
    "requester": "user142@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0522",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-06T10:03:39Z",
    "updated_at": "2025-09-06T19:03:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-08T14:03:39Z",
    "sla_breached": true,
    "requester": "user2@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "security",
      "db"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0523",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-03T15:01:41Z",
    "updated_at": "2025-10-17T07:01:41Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T11:01:41Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0524",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-23T10:04:30Z",
    "updated_at": "2025-10-10T03:04:30Z",
    "closed_at": "2025-10-10T03:04:30Z",
    "sla_due_at": "2025-09-24T01:04:30Z",
    "sla_breached": true,
    "requester": "user2@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "sso",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0525",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-13T09:49:29Z",
    "updated_at": "2025-11-24T22:49:29Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T11:49:29Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "onboarding",
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0526",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-12T02:55:34Z",
    "updated_at": "2025-11-15T12:55:34Z",
    "closed_at": "2025-11-15T12:55:34Z",
    "sla_due_at": "2025-11-14T18:55:34Z",
    "sla_breached": true,
    "requester": "user14@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "onboarding",
      "sso",
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0527",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-14T09:54:05Z",
    "updated_at": "2025-10-15T12:54:05Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T23:54:05Z",
    "sla_breached": true,
    "requester": "user41@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request",
      "security",
      "db",
      "sso"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0528",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-11T11:15:02Z",
    "updated_at": "2025-09-27T10:15:02Z",
    "closed_at": "2025-09-27T10:15:02Z",
    "sla_due_at": "2025-09-13T08:15:02Z",
    "sla_breached": true,
    "requester": "user59@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0529",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-13T23:43:33Z",
    "updated_at": "2025-11-22T00:43:33Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T07:43:33Z",
    "sla_breached": true,
    "requester": "user121@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "network",
      "incident",
      "access",
      "sso"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0530",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-03T18:15:24Z",
    "updated_at": "2025-11-07T22:15:24Z",
    "closed_at": null,
    "sla_due_at": "2025-11-05T21:15:24Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0531",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-22T03:23:21Z",
    "updated_at": "2025-10-31T22:23:21Z",
    "closed_at": null,
    "sla_due_at": "2025-10-22T21:23:21Z",
    "sla_breached": true,
    "requester": "user88@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "change",
      "access",
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0532",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-13T12:14:02Z",
    "updated_at": "2025-09-24T16:14:02Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T21:14:02Z",
    "sla_breached": true,
    "requester": "user56@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "network",
      "db",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0533",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-25T20:26:33Z",
    "updated_at": "2025-11-13T21:26:33Z",
    "closed_at": "2025-11-13T21:26:33Z",
    "sla_due_at": "2025-10-28T07:26:33Z",
    "sla_breached": true,
    "requester": "user39@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0534",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-20T15:13:23Z",
    "updated_at": "2025-11-26T07:56:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-23T11:13:23Z",
    "sla_breached": true,
    "requester": "user179@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem",
      "sso",
      "security",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0535",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-08-29T17:33:16Z",
    "updated_at": "2025-09-05T01:33:16Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T00:33:16Z",
    "sla_breached": true,
    "requester": "user24@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "access",
      "db",
      "problem"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0536",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-28T15:28:26Z",
    "updated_at": "2025-10-07T07:28:26Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T12:28:26Z",
    "sla_breached": true,
    "requester": "user95@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "db",
      "bug",
      "network",
      "security"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0537",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-29T20:14:18Z",
    "updated_at": "2025-09-07T23:14:18Z",
    "closed_at": null,
    "sla_due_at": "2025-09-01T19:14:18Z",
    "sla_breached": true,
    "requester": "user157@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0538",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-18T13:37:05Z",
    "updated_at": "2025-11-20T22:37:05Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T15:37:05Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "vip",
      "access",
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0539",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-28T05:55:10Z",
    "updated_at": "2025-09-04T09:55:10Z",
    "closed_at": null,
    "sla_due_at": "2025-08-29T11:55:10Z",
    "sla_breached": true,
    "requester": "user167@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "analytics",
      "db"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0540",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-15T19:31:02Z",
    "updated_at": "2025-10-24T20:31:02Z",
    "closed_at": "2025-10-24T20:31:02Z",
    "sla_due_at": "2025-10-17T09:31:02Z",
    "sla_breached": true,
    "requester": "user96@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "problem",
      "request",
      "db",
      "security"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0541",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-08-27T12:59:35Z",
    "updated_at": "2025-09-06T04:59:35Z",
    "closed_at": null,
    "sla_due_at": "2025-08-30T12:59:35Z",
    "sla_breached": true,
    "requester": "user173@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0542",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-15T05:26:24Z",
    "updated_at": "2025-11-21T09:26:24Z",
    "closed_at": null,
    "sla_due_at": "2025-11-17T11:26:24Z",
    "sla_breached": true,
    "requester": "user71@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "problem",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0543",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-20T09:31:14Z",
    "updated_at": "2025-10-04T23:31:14Z",
    "closed_at": null,
    "sla_due_at": "2025-09-20T15:31:14Z",
    "sla_breached": true,
    "requester": "user122@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0544",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-18T07:33:24Z",
    "updated_at": "2025-11-26T07:40:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-19T16:33:24Z",
    "sla_breached": true,
    "requester": "user88@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "problem",
      "change",
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0545",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-16T16:08:52Z",
    "updated_at": "2025-09-19T12:08:52Z",
    "closed_at": null,
    "sla_due_at": "2025-09-19T06:08:52Z",
    "sla_breached": true,
    "requester": "user44@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem",
      "vip"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0546",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-20T02:57:29Z",
    "updated_at": "2025-11-23T16:57:29Z",
    "closed_at": null,
    "sla_due_at": "2025-11-22T03:57:29Z",
    "sla_breached": true,
    "requester": "user183@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "db",
      "analytics"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0547",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-05T23:41:50Z",
    "updated_at": "2025-11-12T18:41:50Z",
    "closed_at": null,
    "sla_due_at": "2025-11-06T17:41:50Z",
    "sla_breached": true,
    "requester": "user67@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0548",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-13T02:58:21Z",
    "updated_at": "2025-10-16T14:58:21Z",
    "closed_at": "2025-10-16T14:58:21Z",
    "sla_due_at": "2025-10-15T05:58:21Z",
    "sla_breached": true,
    "requester": "user7@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "analytics",
      "access",
      "problem",
      "vip"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0549",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-25T12:28:28Z",
    "updated_at": "2025-11-26T07:51:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-28T08:28:28Z",
    "sla_breached": false,
    "requester": "user194@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0550",
    "subject": "Upgrade request for enterprise license",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-14T04:16:11Z",
    "updated_at": "2025-10-17T04:16:11Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T21:16:11Z",
    "sla_breached": true,
    "requester": "user79@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "change",
      "sso",
      "problem",
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0551",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-10-16T06:21:19Z",
    "updated_at": "2025-10-21T00:21:19Z",
    "closed_at": "2025-10-21T00:21:19Z",
    "sla_due_at": "2025-10-17T10:21:19Z",
    "sla_breached": true,
    "requester": "user72@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0552",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-30T05:10:40Z",
    "updated_at": "2025-10-10T17:10:40Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T02:10:40Z",
    "sla_breached": true,
    "requester": "user131@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident",
      "access",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0553",
    "subject": "Password reset request",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-07T18:47:05Z",
    "updated_at": "2025-10-15T06:47:05Z",
    "closed_at": null,
    "sla_due_at": "2025-10-07T23:47:05Z",
    "sla_breached": true,
    "requester": "user144@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "db",
      "incident",
      "problem",
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0554",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-02T17:16:43Z",
    "updated_at": "2025-10-15T12:16:43Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T14:16:43Z",
    "sla_breached": true,
    "requester": "user78@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "security",
      "change",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0555",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-25T17:27:04Z",
    "updated_at": "2025-11-26T07:52:32Z",
    "closed_at": "2025-11-26T07:52:32Z",
    "sla_due_at": "2025-11-27T07:27:04Z",
    "sla_breached": false,
    "requester": "user36@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "incident",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0556",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-25T06:49:17Z",
    "updated_at": "2025-10-01T18:49:17Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T00:49:17Z",
    "sla_breached": true,
    "requester": "user119@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0557",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-11-06T22:47:43Z",
    "updated_at": "2025-11-20T12:47:43Z",
    "closed_at": null,
    "sla_due_at": "2025-11-08T16:47:43Z",
    "sla_breached": true,
    "requester": "user171@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "access",
      "problem",
      "bug",
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0558",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-11-10T22:15:57Z",
    "updated_at": "2025-11-12T09:15:57Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T17:15:57Z",
    "sla_breached": true,
    "requester": "user149@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "onboarding",
      "bug",
      "db",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0559",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-09T13:41:55Z",
    "updated_at": "2025-10-13T01:41:55Z",
    "closed_at": null,
    "sla_due_at": "2025-10-09T19:41:55Z",
    "sla_breached": true,
    "requester": "user82@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "vip",
      "access"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0560",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-22T19:12:34Z",
    "updated_at": "2025-10-30T10:12:34Z",
    "closed_at": "2025-10-30T10:12:34Z",
    "sla_due_at": "2025-10-25T04:12:34Z",
    "sla_breached": true,
    "requester": "user136@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0561",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-07T01:41:14Z",
    "updated_at": "2025-09-10T15:41:14Z",
    "closed_at": "2025-09-10T15:41:14Z",
    "sla_due_at": "2025-09-07T17:41:14Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "onboarding",
      "bug",
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0562",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-18T11:14:25Z",
    "updated_at": "2025-09-18T18:14:25Z",
    "closed_at": null,
    "sla_due_at": "2025-09-20T12:14:25Z",
    "sla_breached": true,
    "requester": "user96@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "incident",
      "vip",
      "access",
      "security"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0563",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-06T14:01:53Z",
    "updated_at": "2025-11-18T13:01:53Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T22:01:53Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0564",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-11-17T04:06:54Z",
    "updated_at": "2025-11-26T07:59:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-18T00:06:54Z",
    "sla_breached": true,
    "requester": "user36@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "access",
      "db",
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0565",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-11T00:15:48Z",
    "updated_at": "2025-11-14T01:15:48Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T20:15:48Z",
    "sla_breached": true,
    "requester": "user33@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "security",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0566",
    "subject": "Application performance degradation",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-17T07:40:28Z",
    "updated_at": "2025-11-18T05:40:28Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T00:40:28Z",
    "sla_breached": true,
    "requester": "user169@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0567",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-25T06:47:00Z",
    "updated_at": "2025-10-25T12:47:00Z",
    "closed_at": null,
    "sla_due_at": "2025-10-25T18:47:00Z",
    "sla_breached": true,
    "requester": "user32@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0568",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-01T19:33:36Z",
    "updated_at": "2025-09-07T18:33:36Z",
    "closed_at": null,
    "sla_due_at": "2025-09-02T02:33:36Z",
    "sla_breached": true,
    "requester": "user42@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request",
      "change"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0569",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-13T11:18:35Z",
    "updated_at": "2025-11-26T08:09:32Z",
    "closed_at": "2025-11-26T08:09:32Z",
    "sla_due_at": "2025-11-13T16:18:35Z",
    "sla_breached": true,
    "requester": "user194@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0570",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-29T14:00:07Z",
    "updated_at": "2025-11-11T04:00:07Z",
    "closed_at": null,
    "sla_due_at": "2025-11-01T06:00:07Z",
    "sla_breached": true,
    "requester": "user28@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "incident",
      "sso",
      "request",
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0571",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-11T20:54:59Z",
    "updated_at": "2025-11-22T23:54:59Z",
    "closed_at": "2025-11-22T23:54:59Z",
    "sla_due_at": "2025-11-12T15:54:59Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "request",
      "db",
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0572",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-15T14:23:01Z",
    "updated_at": "2025-10-25T08:23:01Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T08:23:01Z",
    "sla_breached": true,
    "requester": "user176@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso",
      "request",
      "incident",
      "onboarding"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0573",
    "subject": "Email delivery delayed",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-11-02T05:49:29Z",
    "updated_at": "2025-11-10T02:49:29Z",
    "closed_at": null,
    "sla_due_at": "2025-11-04T21:49:29Z",
    "sla_breached": true,
    "requester": "user173@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0574",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-20T08:22:55Z",
    "updated_at": "2025-09-28T19:22:55Z",
    "closed_at": null,
    "sla_due_at": "2025-09-20T22:22:55Z",
    "sla_breached": true,
    "requester": "user27@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security",
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0575",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-14T01:04:04Z",
    "updated_at": "2025-10-23T03:04:04Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T08:04:04Z",
    "sla_breached": true,
    "requester": "user196@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "bug",
      "incident"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0576",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-09-26T10:23:54Z",
    "updated_at": "2025-10-07T08:23:54Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T17:23:54Z",
    "sla_breached": true,
    "requester": "user117@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0577",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-23T23:57:18Z",
    "updated_at": "2025-09-25T03:57:18Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T20:57:18Z",
    "sla_breached": true,
    "requester": "user174@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "change",
      "bug",
      "vip",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0578",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-07T09:40:04Z",
    "updated_at": "2025-09-21T12:40:04Z",
    "closed_at": null,
    "sla_due_at": "2025-09-08T01:40:04Z",
    "sla_breached": true,
    "requester": "user127@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "onboarding",
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0579",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-24T13:58:48Z",
    "updated_at": "2025-10-11T20:58:48Z",
    "closed_at": "2025-10-11T20:58:48Z",
    "sla_due_at": "2025-09-26T02:58:48Z",
    "sla_breached": true,
    "requester": "user5@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0580",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-07T15:58:15Z",
    "updated_at": "2025-10-17T02:58:15Z",
    "closed_at": null,
    "sla_due_at": "2025-10-09T11:58:15Z",
    "sla_breached": true,
    "requester": "user46@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "db",
      "access",
      "problem"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0581",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-08T20:58:58Z",
    "updated_at": "2025-11-11T05:58:58Z",
    "closed_at": "2025-11-11T05:58:58Z",
    "sla_due_at": "2025-11-11T01:58:58Z",
    "sla_breached": true,
    "requester": "user169@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "problem",
      "request",
      "access",
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0582",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-06T22:46:09Z",
    "updated_at": "2025-10-15T00:46:09Z",
    "closed_at": "2025-10-15T00:46:09Z",
    "sla_due_at": "2025-10-09T17:46:09Z",
    "sla_breached": true,
    "requester": "user197@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "network",
      "analytics",
      "change"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0583",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-09T19:01:06Z",
    "updated_at": "2025-11-22T06:01:06Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T19:01:06Z",
    "sla_breached": true,
    "requester": "user161@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "security",
      "incident",
      "vip",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0584",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-13T06:18:14Z",
    "updated_at": "2025-10-27T02:18:14Z",
    "closed_at": null,
    "sla_due_at": "2025-10-14T17:18:14Z",
    "sla_breached": true,
    "requester": "user177@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0585",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-23T12:45:21Z",
    "updated_at": "2025-11-26T07:26:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T09:45:21Z",
    "sla_breached": true,
    "requester": "user108@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "change",
      "network",
      "vip",
      "incident"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0586",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-15T11:30:49Z",
    "updated_at": "2025-10-17T15:30:49Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T03:30:49Z",
    "sla_breached": true,
    "requester": "user87@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "access",
      "change",
      "onboarding"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0587",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-02T01:00:48Z",
    "updated_at": "2025-10-18T21:00:48Z",
    "closed_at": "2025-10-18T21:00:48Z",
    "sla_due_at": "2025-10-04T20:00:48Z",
    "sla_breached": true,
    "requester": "user138@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "onboarding",
      "network",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0588",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-28T09:37:09Z",
    "updated_at": "2025-11-09T18:37:09Z",
    "closed_at": "2025-11-09T18:37:09Z",
    "sla_due_at": "2025-10-29T00:37:09Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "incident",
      "sso",
      "vip",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0589",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-22T21:26:23Z",
    "updated_at": "2025-09-29T14:26:23Z",
    "closed_at": "2025-09-29T14:26:23Z",
    "sla_due_at": "2025-09-25T08:26:23Z",
    "sla_breached": true,
    "requester": "user65@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "bug",
      "request",
      "access",
      "network"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0590",
    "subject": "Password reset request",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-02T11:21:24Z",
    "updated_at": "2025-11-12T11:21:24Z",
    "closed_at": null,
    "sla_due_at": "2025-11-05T06:21:24Z",
    "sla_breached": true,
    "requester": "user137@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "db",
      "bug",
      "network"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0591",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-31T19:05:46Z",
    "updated_at": "2025-11-04T01:05:46Z",
    "closed_at": null,
    "sla_due_at": "2025-11-03T10:05:46Z",
    "sla_breached": true,
    "requester": "user77@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "security",
      "bug",
      "sso"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0592",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-22T21:54:29Z",
    "updated_at": "2025-11-04T17:54:29Z",
    "closed_at": null,
    "sla_due_at": "2025-10-23T21:54:29Z",
    "sla_breached": true,
    "requester": "user30@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "analytics",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0593",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-24T11:58:35Z",
    "updated_at": "2025-10-13T19:58:35Z",
    "closed_at": "2025-10-13T19:58:35Z",
    "sla_due_at": "2025-09-26T22:58:35Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0594",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-02T12:18:30Z",
    "updated_at": "2025-09-03T10:18:30Z",
    "closed_at": "2025-09-03T10:18:30Z",
    "sla_due_at": "2025-09-03T14:18:30Z",
    "sla_breached": false,
    "requester": "user6@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0595",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-17T17:32:25Z",
    "updated_at": "2025-11-26T08:16:32Z",
    "closed_at": "2025-11-26T08:16:32Z",
    "sla_due_at": "2025-11-19T19:32:25Z",
    "sla_breached": true,
    "requester": "user186@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "security",
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0596",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-10T13:21:18Z",
    "updated_at": "2025-11-12T12:21:18Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T12:21:18Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "db",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0597",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-03T00:25:18Z",
    "updated_at": "2025-10-07T14:25:18Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T22:25:18Z",
    "sla_breached": true,
    "requester": "user66@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0598",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-10T04:14:46Z",
    "updated_at": "2025-10-20T08:14:46Z",
    "closed_at": "2025-10-20T08:14:46Z",
    "sla_due_at": "2025-10-12T00:14:46Z",
    "sla_breached": true,
    "requester": "user72@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "problem",
      "db",
      "vip"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0599",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-23T08:51:39Z",
    "updated_at": "2025-11-26T07:30:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-23T16:51:39Z",
    "sla_breached": true,
    "requester": "user172@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "request",
      "incident",
      "onboarding"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0600",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-08-31T03:54:55Z",
    "updated_at": "2025-09-09T14:54:55Z",
    "closed_at": null,
    "sla_due_at": "2025-09-03T03:54:55Z",
    "sla_breached": true,
    "requester": "user101@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "security",
      "sso",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0601",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-05T16:22:52Z",
    "updated_at": "2025-11-19T10:22:52Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T12:22:52Z",
    "sla_breached": true,
    "requester": "user71@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "problem",
      "db",
      "incident",
      "vip"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0602",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-14T02:31:16Z",
    "updated_at": "2025-11-21T15:31:16Z",
    "closed_at": "2025-11-21T15:31:16Z",
    "sla_due_at": "2025-11-15T15:31:16Z",
    "sla_breached": true,
    "requester": "user141@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "problem",
      "db",
      "network"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0603",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-04T08:59:58Z",
    "updated_at": "2025-09-21T06:59:58Z",
    "closed_at": "2025-09-21T06:59:58Z",
    "sla_due_at": "2025-09-05T11:59:58Z",
    "sla_breached": true,
    "requester": "user103@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "vip",
      "change",
      "security"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0604",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-05T23:16:16Z",
    "updated_at": "2025-11-22T09:16:16Z",
    "closed_at": "2025-11-22T09:16:16Z",
    "sla_due_at": "2025-11-08T21:16:16Z",
    "sla_breached": true,
    "requester": "user34@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "analytics",
      "vip",
      "problem",
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0605",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-24T02:02:34Z",
    "updated_at": "2025-10-28T08:02:34Z",
    "closed_at": null,
    "sla_due_at": "2025-10-25T23:02:34Z",
    "sla_breached": true,
    "requester": "user47@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "change",
      "sso",
      "network",
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0606",
    "subject": "Application performance degradation",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-04T10:04:36Z",
    "updated_at": "2025-09-14T07:04:36Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T19:04:36Z",
    "sla_breached": true,
    "requester": "user44@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "change",
      "incident",
      "analytics",
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0607",
    "subject": "Login issues on corporate portal",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-11-14T18:57:48Z",
    "updated_at": "2025-11-17T07:57:48Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T19:57:48Z",
    "sla_breached": true,
    "requester": "user112@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "bug",
      "problem",
      "security",
      "sso"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0608",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-01T22:40:01Z",
    "updated_at": "2025-11-10T02:40:01Z",
    "closed_at": "2025-11-10T02:40:01Z",
    "sla_due_at": "2025-11-03T14:40:01Z",
    "sla_breached": true,
    "requester": "user53@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "onboarding",
      "db"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0609",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-10-04T01:47:31Z",
    "updated_at": "2025-10-04T16:47:31Z",
    "closed_at": null,
    "sla_due_at": "2025-10-06T09:47:31Z",
    "sla_breached": true,
    "requester": "user61@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "sso",
      "vip",
      "change",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0610",
    "subject": "Upgrade request for enterprise license",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-24T15:17:15Z",
    "updated_at": "2025-11-26T07:56:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T12:17:15Z",
    "sla_breached": true,
    "requester": "user99@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "db",
      "change",
      "onboarding",
      "security"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0611",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-16T06:13:12Z",
    "updated_at": "2025-09-21T07:13:12Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T16:13:12Z",
    "sla_breached": true,
    "requester": "user156@enterprise.example.com",
    "assignee": null,
    "tags": [
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0612",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-22T09:47:53Z",
    "updated_at": "2025-09-30T20:47:53Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T13:47:53Z",
    "sla_breached": true,
    "requester": "user144@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "access",
      "request",
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0613",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-28T03:33:22Z",
    "updated_at": "2025-10-09T11:33:22Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T18:33:22Z",
    "sla_breached": true,
    "requester": "user30@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "onboarding",
      "db",
      "vip",
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0614",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-23T10:02:34Z",
    "updated_at": "2025-11-01T18:02:34Z",
    "closed_at": "2025-11-01T18:02:34Z",
    "sla_due_at": "2025-10-24T23:02:34Z",
    "sla_breached": true,
    "requester": "user189@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "request",
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0615",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-20T01:28:50Z",
    "updated_at": "2025-11-23T23:28:50Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T00:28:50Z",
    "sla_breached": true,
    "requester": "user42@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security",
      "problem",
      "network",
      "db"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0616",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-08-27T11:56:20Z",
    "updated_at": "2025-08-29T21:56:20Z",
    "closed_at": "2025-08-29T21:56:20Z",
    "sla_due_at": "2025-08-30T05:56:20Z",
    "sla_breached": false,
    "requester": "user38@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "security",
      "sso",
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0617",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-04T13:50:11Z",
    "updated_at": "2025-11-18T17:50:11Z",
    "closed_at": "2025-11-18T17:50:11Z",
    "sla_due_at": "2025-11-06T03:50:11Z",
    "sla_breached": true,
    "requester": "user2@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "incident",
      "security"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0618",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-24T04:55:32Z",
    "updated_at": "2025-10-08T17:55:32Z",
    "closed_at": null,
    "sla_due_at": "2025-09-26T02:55:32Z",
    "sla_breached": true,
    "requester": "user96@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "access",
      "network",
      "security"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0619",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-08-27T14:53:17Z",
    "updated_at": "2025-09-02T08:53:17Z",
    "closed_at": "2025-09-02T08:53:17Z",
    "sla_due_at": "2025-08-30T04:53:17Z",
    "sla_breached": true,
    "requester": "user85@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "vip",
      "db",
      "change",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0620",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-19T08:55:29Z",
    "updated_at": "2025-11-20T13:55:29Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T00:55:29Z",
    "sla_breached": true,
    "requester": "user155@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "access",
      "sso",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0621",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-24T00:46:40Z",
    "updated_at": "2025-11-26T08:03:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T00:46:40Z",
    "sla_breached": true,
    "requester": "user168@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "analytics",
      "incident",
      "onboarding",
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0622",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-12T04:51:35Z",
    "updated_at": "2025-10-22T15:51:35Z",
    "closed_at": "2025-10-22T15:51:35Z",
    "sla_due_at": "2025-10-14T07:51:35Z",
    "sla_breached": true,
    "requester": "user122@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "security",
      "incident",
      "vip",
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0623",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-01T09:23:47Z",
    "updated_at": "2025-10-12T08:23:47Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T19:23:47Z",
    "sla_breached": true,
    "requester": "user174@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "problem",
      "request"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0624",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-15T21:46:29Z",
    "updated_at": "2025-11-26T07:30:32Z",
    "closed_at": "2025-11-26T07:30:32Z",
    "sla_due_at": "2025-11-18T12:46:29Z",
    "sla_breached": true,
    "requester": "user33@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "sso",
      "request",
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0625",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-15T06:37:17Z",
    "updated_at": "2025-09-26T05:37:17Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T19:37:17Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "bug",
      "db",
      "change",
      "onboarding"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0626",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-24T11:02:21Z",
    "updated_at": "2025-10-24T20:02:21Z",
    "closed_at": null,
    "sla_due_at": "2025-10-25T01:02:21Z",
    "sla_breached": true,
    "requester": "user119@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "incident",
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0627",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-03T21:31:19Z",
    "updated_at": "2025-10-13T14:31:19Z",
    "closed_at": "2025-10-13T14:31:19Z",
    "sla_due_at": "2025-10-05T17:31:19Z",
    "sla_breached": true,
    "requester": "user160@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "analytics",
      "access",
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0628",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-15T10:21:58Z",
    "updated_at": "2025-11-17T17:21:58Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T23:21:58Z",
    "sla_breached": true,
    "requester": "user2@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0629",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-09-03T14:59:15Z",
    "updated_at": "2025-09-22T03:59:15Z",
    "closed_at": "2025-09-22T03:59:15Z",
    "sla_due_at": "2025-09-06T04:59:15Z",
    "sla_breached": true,
    "requester": "user155@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "onboarding",
      "change",
      "db",
      "vip"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0630",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-19T05:10:06Z",
    "updated_at": "2025-10-23T07:10:06Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T01:10:06Z",
    "sla_breached": true,
    "requester": "user179@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0631",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-04T03:04:27Z",
    "updated_at": "2025-09-17T12:04:27Z",
    "closed_at": "2025-09-17T12:04:27Z",
    "sla_due_at": "2025-09-05T13:04:27Z",
    "sla_breached": true,
    "requester": "user49@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "analytics",
      "problem",
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0632",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-03T07:33:53Z",
    "updated_at": "2025-10-06T14:33:53Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T01:33:53Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "sso",
      "onboarding"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0633",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-19T20:12:14Z",
    "updated_at": "2025-11-26T07:55:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T01:12:14Z",
    "sla_breached": true,
    "requester": "user149@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "network",
      "problem",
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0634",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-21T10:50:24Z",
    "updated_at": "2025-09-22T18:50:24Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T04:50:24Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "bug",
      "incident",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0635",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-23T09:41:14Z",
    "updated_at": "2025-10-02T17:41:14Z",
    "closed_at": "2025-10-02T17:41:14Z",
    "sla_due_at": "2025-09-25T09:41:14Z",
    "sla_breached": true,
    "requester": "user186@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "vip",
      "problem",
      "sso",
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0636",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-11T20:00:39Z",
    "updated_at": "2025-09-18T03:00:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T11:00:39Z",
    "sla_breached": true,
    "requester": "user107@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "problem",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0637",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-21T05:13:15Z",
    "updated_at": "2025-10-25T12:13:15Z",
    "closed_at": null,
    "sla_due_at": "2025-10-23T22:13:15Z",
    "sla_breached": true,
    "requester": "user26@enterprise.example.com",
    "assignee": null,
    "tags": [
      "onboarding",
      "sso",
      "db",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0638",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-23T19:17:46Z",
    "updated_at": "2025-11-26T08:10:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T08:17:46Z",
    "sla_breached": true,
    "requester": "user129@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "incident",
      "security",
      "change"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0639",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-10T11:53:52Z",
    "updated_at": "2025-11-17T18:53:52Z",
    "closed_at": "2025-11-17T18:53:52Z",
    "sla_due_at": "2025-11-11T19:53:52Z",
    "sla_breached": true,
    "requester": "user12@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "access",
      "db",
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0640",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-08-28T06:31:24Z",
    "updated_at": "2025-08-30T15:31:24Z",
    "closed_at": null,
    "sla_due_at": "2025-08-30T18:31:24Z",
    "sla_breached": true,
    "requester": "user157@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0641",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-04T09:25:27Z",
    "updated_at": "2025-11-12T03:25:27Z",
    "closed_at": null,
    "sla_due_at": "2025-11-05T04:25:27Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "db",
      "security",
      "access",
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0642",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-09T03:52:53Z",
    "updated_at": "2025-11-18T00:52:53Z",
    "closed_at": "2025-11-18T00:52:53Z",
    "sla_due_at": "2025-11-10T08:52:53Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "onboarding",
      "request",
      "access"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0643",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-22T18:47:57Z",
    "updated_at": "2025-11-05T23:47:57Z",
    "closed_at": null,
    "sla_due_at": "2025-10-25T03:47:57Z",
    "sla_breached": true,
    "requester": "user193@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "analytics",
      "incident"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0644",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-04T15:39:23Z",
    "updated_at": "2025-10-12T09:39:23Z",
    "closed_at": null,
    "sla_due_at": "2025-10-07T13:39:23Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "security"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0645",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-16T17:44:07Z",
    "updated_at": "2025-10-25T03:44:07Z",
    "closed_at": "2025-10-25T03:44:07Z",
    "sla_due_at": "2025-10-17T18:44:07Z",
    "sla_breached": true,
    "requester": "user165@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0646",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-19T17:05:33Z",
    "updated_at": "2025-11-03T16:05:33Z",
    "closed_at": null,
    "sla_due_at": "2025-10-22T00:05:33Z",
    "sla_breached": true,
    "requester": "user185@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "vip",
      "network",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0647",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-09T03:00:43Z",
    "updated_at": "2025-09-13T13:00:43Z",
    "closed_at": "2025-09-13T13:00:43Z",
    "sla_due_at": "2025-09-11T10:00:43Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "db",
      "vip",
      "bug",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0648",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-19T05:17:26Z",
    "updated_at": "2025-10-27T13:17:26Z",
    "closed_at": "2025-10-27T13:17:26Z",
    "sla_due_at": "2025-10-19T13:17:26Z",
    "sla_breached": true,
    "requester": "user33@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "sso",
      "security",
      "request"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0649",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-17T13:22:40Z",
    "updated_at": "2025-10-20T23:22:40Z",
    "closed_at": null,
    "sla_due_at": "2025-10-19T12:22:40Z",
    "sla_breached": true,
    "requester": "user139@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "sso",
      "onboarding",
      "incident"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0650",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-12T06:10:35Z",
    "updated_at": "2025-11-23T02:10:35Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T09:10:35Z",
    "sla_breached": true,
    "requester": "user194@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "onboarding",
      "change",
      "network",
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0651",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-26T11:11:02Z",
    "updated_at": "2025-10-31T11:11:02Z",
    "closed_at": null,
    "sla_due_at": "2025-10-29T11:11:02Z",
    "sla_breached": true,
    "requester": "user171@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "db",
      "incident"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0652",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-26T04:31:40Z",
    "updated_at": "2025-10-30T07:31:40Z",
    "closed_at": "2025-10-30T07:31:40Z",
    "sla_due_at": "2025-10-28T01:31:40Z",
    "sla_breached": true,
    "requester": "user117@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "db",
      "incident"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0653",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-16T05:00:01Z",
    "updated_at": "2025-11-19T00:00:01Z",
    "closed_at": "2025-11-19T00:00:01Z",
    "sla_due_at": "2025-11-16T16:00:01Z",
    "sla_breached": true,
    "requester": "user20@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "change",
      "request",
      "db",
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0654",
    "subject": "Bug report for ticketing system",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-09-12T14:11:50Z",
    "updated_at": "2025-09-27T07:11:50Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T00:11:50Z",
    "sla_breached": true,
    "requester": "user188@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "access",
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0655",
    "subject": "SSO configuration change",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-24T15:41:39Z",
    "updated_at": "2025-10-05T14:41:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-25T11:41:39Z",
    "sla_breached": true,
    "requester": "user178@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "problem",
      "network",
      "access",
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0656",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-10T10:27:20Z",
    "updated_at": "2025-11-18T08:27:20Z",
    "closed_at": null,
    "sla_due_at": "2025-11-12T18:27:20Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "vip",
      "onboarding",
      "db"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0657",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-23T03:09:26Z",
    "updated_at": "2025-11-26T08:18:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-24T01:09:26Z",
    "sla_breached": true,
    "requester": "user73@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "db",
      "problem"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0658",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-10T12:25:26Z",
    "updated_at": "2025-11-11T11:25:26Z",
    "closed_at": null,
    "sla_due_at": "2025-11-12T12:25:26Z",
    "sla_breached": true,
    "requester": "user80@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "problem",
      "db",
      "change",
      "access"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0659",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-22T09:11:10Z",
    "updated_at": "2025-10-06T15:11:10Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T23:11:10Z",
    "sla_breached": true,
    "requester": "user187@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0660",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-07T23:52:56Z",
    "updated_at": "2025-10-08T23:52:56Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T05:52:56Z",
    "sla_breached": true,
    "requester": "user189@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "db",
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0661",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-09-15T08:52:10Z",
    "updated_at": "2025-09-17T04:52:10Z",
    "closed_at": "2025-09-17T04:52:10Z",
    "sla_due_at": "2025-09-16T03:52:10Z",
    "sla_breached": true,
    "requester": "user139@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0662",
    "subject": "Upgrade request for enterprise license",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-11-01T15:02:04Z",
    "updated_at": "2025-11-04T05:02:04Z",
    "closed_at": null,
    "sla_due_at": "2025-11-04T11:02:04Z",
    "sla_breached": true,
    "requester": "user47@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "analytics",
      "sso",
      "db"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0663",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-15T12:56:00Z",
    "updated_at": "2025-11-16T12:56:00Z",
    "closed_at": "2025-11-16T12:56:00Z",
    "sla_due_at": "2025-11-17T09:56:00Z",
    "sla_breached": false,
    "requester": "user6@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "access",
      "incident",
      "network",
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0664",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-08T22:59:44Z",
    "updated_at": "2025-10-11T01:59:44Z",
    "closed_at": null,
    "sla_due_at": "2025-10-09T13:59:44Z",
    "sla_breached": true,
    "requester": "user37@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0665",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-05T02:11:56Z",
    "updated_at": "2025-10-12T01:11:56Z",
    "closed_at": "2025-10-12T01:11:56Z",
    "sla_due_at": "2025-10-05T13:11:56Z",
    "sla_breached": true,
    "requester": "user15@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "security",
      "vip",
      "access",
      "incident"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0666",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-23T18:41:13Z",
    "updated_at": "2025-10-28T21:41:13Z",
    "closed_at": null,
    "sla_due_at": "2025-10-24T13:41:13Z",
    "sla_breached": true,
    "requester": "user61@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "security",
      "onboarding",
      "network",
      "vip"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0667",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-16T17:32:16Z",
    "updated_at": "2025-09-25T10:32:16Z",
    "closed_at": "2025-09-25T10:32:16Z",
    "sla_due_at": "2025-09-17T05:32:16Z",
    "sla_breached": true,
    "requester": "user5@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0668",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-04T03:47:14Z",
    "updated_at": "2025-09-13T16:47:14Z",
    "closed_at": "2025-09-13T16:47:14Z",
    "sla_due_at": "2025-09-05T21:47:14Z",
    "sla_breached": true,
    "requester": "user129@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "vip",
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0669",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-10-25T12:47:17Z",
    "updated_at": "2025-11-06T09:47:17Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T22:47:17Z",
    "sla_breached": true,
    "requester": "user119@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "bug",
      "access",
      "network"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0670",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-25T22:24:30Z",
    "updated_at": "2025-10-04T01:24:30Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T10:24:30Z",
    "sla_breached": true,
    "requester": "user55@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "network",
      "access",
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0671",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-19T05:05:33Z",
    "updated_at": "2025-11-05T23:05:33Z",
    "closed_at": "2025-11-05T23:05:33Z",
    "sla_due_at": "2025-10-21T11:05:33Z",
    "sla_breached": true,
    "requester": "user72@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "change",
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0672",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-08-30T19:53:03Z",
    "updated_at": "2025-09-09T11:53:03Z",
    "closed_at": null,
    "sla_due_at": "2025-09-01T08:53:03Z",
    "sla_breached": true,
    "requester": "user83@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "problem",
      "change"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0673",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-24T03:29:25Z",
    "updated_at": "2025-11-24T06:29:25Z",
    "closed_at": "2025-11-24T06:29:25Z",
    "sla_due_at": "2025-11-24T07:29:25Z",
    "sla_breached": false,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "analytics",
      "incident",
      "request",
      "security"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0674",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-19T07:13:56Z",
    "updated_at": "2025-09-26T20:13:56Z",
    "closed_at": "2025-09-26T20:13:56Z",
    "sla_due_at": "2025-09-21T19:13:56Z",
    "sla_breached": true,
    "requester": "user154@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "access",
      "db",
      "network",
      "security"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0675",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-10T01:19:57Z",
    "updated_at": "2025-10-10T12:19:57Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T13:19:57Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "analytics",
      "db",
      "sso"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0676",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-23T19:08:33Z",
    "updated_at": "2025-10-06T18:08:33Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T03:08:33Z",
    "sla_breached": true,
    "requester": "user164@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "access",
      "request",
      "sso",
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0677",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-17T10:56:41Z",
    "updated_at": "2025-11-20T04:56:41Z",
    "closed_at": "2025-11-20T04:56:41Z",
    "sla_due_at": "2025-11-18T06:56:41Z",
    "sla_breached": true,
    "requester": "user59@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "sso",
      "bug",
      "network"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0678",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-08T23:09:02Z",
    "updated_at": "2025-09-18T02:09:02Z",
    "closed_at": null,
    "sla_due_at": "2025-09-11T13:09:02Z",
    "sla_breached": true,
    "requester": "user167@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "incident",
      "onboarding",
      "security",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0679",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-23T19:11:54Z",
    "updated_at": "2025-09-28T14:11:54Z",
    "closed_at": null,
    "sla_due_at": "2025-09-26T17:11:54Z",
    "sla_breached": true,
    "requester": "user108@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "vip",
      "network",
      "incident",
      "sso"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0680",
    "subject": "Security alert investigation",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-15T11:32:23Z",
    "updated_at": "2025-11-20T07:32:23Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T18:32:23Z",
    "sla_breached": true,
    "requester": "user20@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "access",
      "vip"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0681",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-17T09:34:02Z",
    "updated_at": "2025-11-26T07:30:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-18T01:34:02Z",
    "sla_breached": true,
    "requester": "user161@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso",
      "security",
      "problem"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0682",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-14T06:22:38Z",
    "updated_at": "2025-10-19T08:22:38Z",
    "closed_at": "2025-10-19T08:22:38Z",
    "sla_due_at": "2025-10-16T04:22:38Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0683",
    "subject": "New user onboarding request",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-13T03:48:51Z",
    "updated_at": "2025-09-13T21:48:51Z",
    "closed_at": null,
    "sla_due_at": "2025-09-13T17:48:51Z",
    "sla_breached": true,
    "requester": "user178@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "network",
      "problem"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0684",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-18T10:07:22Z",
    "updated_at": "2025-11-01T21:07:22Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T21:07:22Z",
    "sla_breached": true,
    "requester": "user76@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security",
      "change",
      "incident",
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0685",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-28T18:22:51Z",
    "updated_at": "2025-10-12T00:22:51Z",
    "closed_at": null,
    "sla_due_at": "2025-10-01T09:22:51Z",
    "sla_breached": true,
    "requester": "user167@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0686",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-14T10:57:27Z",
    "updated_at": "2025-10-14T17:57:27Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T14:57:27Z",
    "sla_breached": true,
    "requester": "user152@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0687",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-24T19:25:11Z",
    "updated_at": "2025-11-07T01:25:11Z",
    "closed_at": "2025-11-07T01:25:11Z",
    "sla_due_at": "2025-10-27T04:25:11Z",
    "sla_breached": true,
    "requester": "user36@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0688",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-12T16:29:25Z",
    "updated_at": "2025-09-20T08:29:25Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T13:29:25Z",
    "sla_breached": true,
    "requester": "user139@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "access",
      "problem"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0689",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-09T19:52:28Z",
    "updated_at": "2025-09-10T00:52:28Z",
    "closed_at": null,
    "sla_due_at": "2025-09-11T12:52:28Z",
    "sla_breached": true,
    "requester": "user174@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0690",
    "subject": "Application performance degradation",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-01T01:03:49Z",
    "updated_at": "2025-11-08T08:03:49Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T06:03:49Z",
    "sla_breached": true,
    "requester": "user178@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "change",
      "db",
      "vip",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0691",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-08T21:26:59Z",
    "updated_at": "2025-09-11T03:26:59Z",
    "closed_at": null,
    "sla_due_at": "2025-09-11T06:26:59Z",
    "sla_breached": true,
    "requester": "user11@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "db",
      "sso"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0692",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-08T00:35:56Z",
    "updated_at": "2025-09-24T10:35:56Z",
    "closed_at": "2025-09-24T10:35:56Z",
    "sla_due_at": "2025-09-09T10:35:56Z",
    "sla_breached": true,
    "requester": "user190@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "incident",
      "access"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0693",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-11T07:59:56Z",
    "updated_at": "2025-10-23T04:59:56Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T20:59:56Z",
    "sla_breached": true,
    "requester": "user113@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "network",
      "analytics",
      "sso"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0694",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-21T02:01:07Z",
    "updated_at": "2025-10-24T20:01:07Z",
    "closed_at": null,
    "sla_due_at": "2025-10-22T10:01:07Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "network",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0695",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-14T07:35:41Z",
    "updated_at": "2025-11-16T16:35:41Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T04:35:41Z",
    "sla_breached": true,
    "requester": "user79@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "bug",
      "access",
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0696",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-18T04:02:41Z",
    "updated_at": "2025-11-20T23:02:41Z",
    "closed_at": null,
    "sla_due_at": "2025-11-19T02:02:41Z",
    "sla_breached": true,
    "requester": "user137@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "vip",
      "change",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0697",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-20T09:55:48Z",
    "updated_at": "2025-11-26T07:31:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T13:55:48Z",
    "sla_breached": true,
    "requester": "user14@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "access",
      "request",
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0698",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-31T05:23:42Z",
    "updated_at": "2025-11-13T08:23:42Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T21:23:42Z",
    "sla_breached": true,
    "requester": "user100@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "problem",
      "request",
      "analytics"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0699",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-15T18:44:47Z",
    "updated_at": "2025-10-31T01:44:47Z",
    "closed_at": "2025-10-31T01:44:47Z",
    "sla_due_at": "2025-10-18T17:44:47Z",
    "sla_breached": true,
    "requester": "user149@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0700",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-31T15:53:57Z",
    "updated_at": "2025-11-07T04:53:57Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T01:53:57Z",
    "sla_breached": true,
    "requester": "user147@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "request",
      "security",
      "access"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0701",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-19T16:10:30Z",
    "updated_at": "2025-11-01T03:10:30Z",
    "closed_at": null,
    "sla_due_at": "2025-10-22T14:10:30Z",
    "sla_breached": true,
    "requester": "user160@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "incident",
      "analytics",
      "vip",
      "problem"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0702",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-22T18:26:14Z",
    "updated_at": "2025-10-27T18:26:14Z",
    "closed_at": null,
    "sla_due_at": "2025-10-23T01:26:14Z",
    "sla_breached": true,
    "requester": "user92@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request",
      "analytics",
      "db"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0703",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-22T00:04:02Z",
    "updated_at": "2025-10-29T17:04:02Z",
    "closed_at": null,
    "sla_due_at": "2025-10-22T16:04:02Z",
    "sla_breached": true,
    "requester": "user86@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "onboarding",
      "db",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0704",
    "subject": "Bug report for ticketing system",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-01T10:22:01Z",
    "updated_at": "2025-11-13T01:22:01Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T07:22:01Z",
    "sla_breached": true,
    "requester": "user198@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "vip",
      "incident",
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0705",
    "subject": "SSO configuration change",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-26T08:32:39Z",
    "updated_at": "2025-09-29T13:32:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T05:32:39Z",
    "sla_breached": true,
    "requester": "user59@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "problem",
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0706",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-11T12:14:20Z",
    "updated_at": "2025-09-21T09:14:20Z",
    "closed_at": "2025-09-21T09:14:20Z",
    "sla_due_at": "2025-09-14T03:14:20Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "analytics",
      "db",
      "incident",
      "sso"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0707",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-29T12:01:36Z",
    "updated_at": "2025-10-11T20:01:36Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T19:01:36Z",
    "sla_breached": true,
    "requester": "user189@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "vip",
      "sso",
      "incident"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0708",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-08-30T17:40:22Z",
    "updated_at": "2025-09-12T06:40:22Z",
    "closed_at": null,
    "sla_due_at": "2025-09-02T17:40:22Z",
    "sla_breached": true,
    "requester": "user9@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0709",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-09T00:55:27Z",
    "updated_at": "2025-10-17T06:55:27Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T06:55:27Z",
    "sla_breached": true,
    "requester": "user85@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "security",
      "access",
      "analytics"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0710",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-04T07:11:30Z",
    "updated_at": "2025-11-08T13:11:30Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T01:11:30Z",
    "sla_breached": true,
    "requester": "user99@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "bug",
      "request",
      "security"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0711",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-18T18:56:13Z",
    "updated_at": "2025-11-25T18:56:13Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T16:56:13Z",
    "sla_breached": true,
    "requester": "user101@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "request",
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0712",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-17T18:11:46Z",
    "updated_at": "2025-11-22T04:11:46Z",
    "closed_at": null,
    "sla_due_at": "2025-11-19T00:11:46Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "change",
      "sso",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0713",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-22T01:00:55Z",
    "updated_at": "2025-10-31T14:00:55Z",
    "closed_at": null,
    "sla_due_at": "2025-10-22T05:00:55Z",
    "sla_breached": true,
    "requester": "user155@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "change",
      "problem",
      "db"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0714",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-14T06:56:10Z",
    "updated_at": "2025-09-24T00:56:10Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T21:56:10Z",
    "sla_breached": true,
    "requester": "user183@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "access",
      "incident",
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0715",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-07T16:37:39Z",
    "updated_at": "2025-09-21T18:37:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-10T06:37:39Z",
    "sla_breached": true,
    "requester": "user25@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "access",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0716",
    "subject": "Data export failing in analytics app",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-20T05:55:44Z",
    "updated_at": "2025-10-29T00:55:44Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T12:55:44Z",
    "sla_breached": true,
    "requester": "user95@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0717",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-04T15:56:27Z",
    "updated_at": "2025-10-15T11:56:27Z",
    "closed_at": null,
    "sla_due_at": "2025-10-05T16:56:27Z",
    "sla_breached": true,
    "requester": "user19@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "incident",
      "vip",
      "analytics",
      "sso"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0718",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-22T07:58:05Z",
    "updated_at": "2025-11-25T05:58:05Z",
    "closed_at": null,
    "sla_due_at": "2025-11-23T19:58:05Z",
    "sla_breached": true,
    "requester": "user119@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0719",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-01T03:15:09Z",
    "updated_at": "2025-10-04T14:15:09Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T19:15:09Z",
    "sla_breached": true,
    "requester": "user156@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "onboarding",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0720",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-07T02:13:33Z",
    "updated_at": "2025-10-07T08:13:33Z",
    "closed_at": "2025-10-07T08:13:33Z",
    "sla_due_at": "2025-10-07T15:13:33Z",
    "sla_breached": false,
    "requester": "user113@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "sso",
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0721",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-08-31T12:58:43Z",
    "updated_at": "2025-09-01T13:58:43Z",
    "closed_at": "2025-09-01T13:58:43Z",
    "sla_due_at": "2025-09-01T19:58:43Z",
    "sla_breached": false,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0722",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-01T06:27:02Z",
    "updated_at": "2025-10-09T08:27:02Z",
    "closed_at": null,
    "sla_due_at": "2025-10-01T10:27:02Z",
    "sla_breached": true,
    "requester": "user64@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "security",
      "network"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0723",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-23T07:49:44Z",
    "updated_at": "2025-11-26T07:39:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T06:49:44Z",
    "sla_breached": true,
    "requester": "user25@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "db",
      "access"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0724",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-03T13:41:58Z",
    "updated_at": "2025-10-10T11:41:58Z",
    "closed_at": null,
    "sla_due_at": "2025-10-04T06:41:58Z",
    "sla_breached": true,
    "requester": "user160@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "incident",
      "security",
      "sso",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0725",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-11T20:35:08Z",
    "updated_at": "2025-10-25T19:35:08Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T22:35:08Z",
    "sla_breached": true,
    "requester": "user55@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "bug",
      "change",
      "vip"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0726",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-18T00:24:05Z",
    "updated_at": "2025-11-26T07:50:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-20T08:24:05Z",
    "sla_breached": true,
    "requester": "user146@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "bug",
      "db",
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0727",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-10-15T01:58:32Z",
    "updated_at": "2025-10-29T07:58:32Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T21:58:32Z",
    "sla_breached": true,
    "requester": "user5@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "incident",
      "request",
      "bug",
      "sso"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0728",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-12T07:52:30Z",
    "updated_at": "2025-09-14T23:52:30Z",
    "closed_at": null,
    "sla_due_at": "2025-09-13T16:52:30Z",
    "sla_breached": true,
    "requester": "user110@enterprise.example.com",
    "assignee": null,
    "tags": [
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0729",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-09T14:12:03Z",
    "updated_at": "2025-10-17T15:12:03Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T07:12:03Z",
    "sla_breached": true,
    "requester": "user61@enterprise.example.com",
    "assignee": null,
    "tags": [
      "db",
      "vip",
      "access",
      "onboarding"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0730",
    "subject": "Upgrade request for enterprise license",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-05T06:55:01Z",
    "updated_at": "2025-09-14T03:55:01Z",
    "closed_at": null,
    "sla_due_at": "2025-09-08T04:55:01Z",
    "sla_breached": true,
    "requester": "user193@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "db",
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0731",
    "subject": "Application performance degradation",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-26T00:51:56Z",
    "updated_at": "2025-11-09T05:51:56Z",
    "closed_at": null,
    "sla_due_at": "2025-10-26T10:51:56Z",
    "sla_breached": true,
    "requester": "user179@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "change",
      "incident"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0732",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-16T01:40:35Z",
    "updated_at": "2025-10-17T11:40:35Z",
    "closed_at": "2025-10-17T11:40:35Z",
    "sla_due_at": "2025-10-18T13:40:35Z",
    "sla_breached": false,
    "requester": "user50@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "sso",
      "access"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0733",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-03T10:46:55Z",
    "updated_at": "2025-11-05T03:46:55Z",
    "closed_at": null,
    "sla_due_at": "2025-11-04T16:46:55Z",
    "sla_breached": true,
    "requester": "user80@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "incident",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0734",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-18T21:58:11Z",
    "updated_at": "2025-10-23T05:58:11Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T10:58:11Z",
    "sla_breached": true,
    "requester": "user124@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "incident",
      "analytics",
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0735",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-30T16:58:09Z",
    "updated_at": "2025-10-09T22:58:09Z",
    "closed_at": "2025-10-09T22:58:09Z",
    "sla_due_at": "2025-10-03T12:58:09Z",
    "sla_breached": true,
    "requester": "user124@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "incident",
      "security",
      "onboarding",
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0736",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-06T12:13:49Z",
    "updated_at": "2025-11-16T10:13:49Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T14:13:49Z",
    "sla_breached": true,
    "requester": "user97@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0737",
    "subject": "Login issues on corporate portal",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-27T01:14:00Z",
    "updated_at": "2025-09-27T04:14:00Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T00:14:00Z",
    "sla_breached": true,
    "requester": "user187@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "problem",
      "incident",
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0738",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-09T18:22:36Z",
    "updated_at": "2025-10-22T08:22:36Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T12:22:36Z",
    "sla_breached": true,
    "requester": "user10@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0739",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-01T16:28:26Z",
    "updated_at": "2025-11-09T03:28:26Z",
    "closed_at": null,
    "sla_due_at": "2025-11-03T04:28:26Z",
    "sla_breached": true,
    "requester": "user163@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "db",
      "network",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0740",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-02T23:22:25Z",
    "updated_at": "2025-10-22T15:22:25Z",
    "closed_at": "2025-10-22T15:22:25Z",
    "sla_due_at": "2025-10-04T10:22:25Z",
    "sla_breached": true,
    "requester": "user181@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0741",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-23T10:18:57Z",
    "updated_at": "2025-10-26T14:18:57Z",
    "closed_at": null,
    "sla_due_at": "2025-10-26T00:18:57Z",
    "sla_breached": true,
    "requester": "user149@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "network",
      "security"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0742",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-04T18:21:55Z",
    "updated_at": "2025-09-24T00:21:55Z",
    "closed_at": "2025-09-24T00:21:55Z",
    "sla_due_at": "2025-09-07T00:21:55Z",
    "sla_breached": true,
    "requester": "user49@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "incident",
      "onboarding"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0743",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-22T12:56:45Z",
    "updated_at": "2025-10-08T04:56:45Z",
    "closed_at": "2025-10-08T04:56:45Z",
    "sla_due_at": "2025-09-24T16:56:45Z",
    "sla_breached": true,
    "requester": "user187@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0744",
    "subject": "Security alert investigation",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-07T22:33:51Z",
    "updated_at": "2025-11-16T10:33:51Z",
    "closed_at": null,
    "sla_due_at": "2025-11-09T04:33:51Z",
    "sla_breached": true,
    "requester": "user44@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "security"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0745",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-08-28T17:08:45Z",
    "updated_at": "2025-09-03T21:08:45Z",
    "closed_at": "2025-09-03T21:08:45Z",
    "sla_due_at": "2025-08-31T16:08:45Z",
    "sla_breached": true,
    "requester": "user46@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "db",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0746",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-25T01:43:59Z",
    "updated_at": "2025-10-04T16:43:59Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T21:43:59Z",
    "sla_breached": true,
    "requester": "user48@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0747",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-01T22:54:59Z",
    "updated_at": "2025-11-21T10:54:59Z",
    "closed_at": "2025-11-21T10:54:59Z",
    "sla_due_at": "2025-11-04T06:54:59Z",
    "sla_breached": true,
    "requester": "user163@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0748",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-09T03:49:10Z",
    "updated_at": "2025-10-09T19:49:10Z",
    "closed_at": null,
    "sla_due_at": "2025-10-10T18:49:10Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0749",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-25T11:09:10Z",
    "updated_at": "2025-11-26T07:31:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T20:09:10Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem",
      "analytics",
      "vip"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0750",
    "subject": "Multi-factor authentication not working",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-13T18:51:33Z",
    "updated_at": "2025-10-18T21:51:33Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T17:51:33Z",
    "sla_breached": true,
    "requester": "user97@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0751",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-14T08:14:48Z",
    "updated_at": "2025-11-22T22:14:48Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T22:14:48Z",
    "sla_breached": true,
    "requester": "user36@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0752",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-08-28T23:18:36Z",
    "updated_at": "2025-09-12T15:18:36Z",
    "closed_at": "2025-09-12T15:18:36Z",
    "sla_due_at": "2025-08-31T02:18:36Z",
    "sla_breached": true,
    "requester": "user132@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "network",
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0753",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-23T09:17:02Z",
    "updated_at": "2025-11-26T07:38:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T11:17:02Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0754",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-26T08:23:23Z",
    "updated_at": "2025-10-02T15:23:23Z",
    "closed_at": "2025-10-02T15:23:23Z",
    "sla_due_at": "2025-09-27T00:23:23Z",
    "sla_breached": true,
    "requester": "user37@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0755",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-14T21:23:14Z",
    "updated_at": "2025-11-24T10:23:14Z",
    "closed_at": null,
    "sla_due_at": "2025-11-17T12:23:14Z",
    "sla_breached": true,
    "requester": "user139@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "analytics",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0756",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-12T16:31:30Z",
    "updated_at": "2025-11-19T16:31:30Z",
    "closed_at": null,
    "sla_due_at": "2025-11-12T23:31:30Z",
    "sla_breached": true,
    "requester": "user72@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "bug",
      "security",
      "analytics",
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0757",
    "subject": "SSO configuration change",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-05T14:26:50Z",
    "updated_at": "2025-09-12T17:26:50Z",
    "closed_at": null,
    "sla_due_at": "2025-09-06T05:26:50Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0758",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-08T18:27:49Z",
    "updated_at": "2025-10-13T13:27:49Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T05:27:49Z",
    "sla_breached": true,
    "requester": "user23@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0759",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-11T11:30:09Z",
    "updated_at": "2025-11-18T04:30:09Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T14:30:09Z",
    "sla_breached": true,
    "requester": "user1@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "incident",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0760",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-11T03:45:37Z",
    "updated_at": "2025-10-23T18:45:37Z",
    "closed_at": "2025-10-23T18:45:37Z",
    "sla_due_at": "2025-10-14T01:45:37Z",
    "sla_breached": true,
    "requester": "user3@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "vip",
      "access",
      "onboarding",
      "sso"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0761",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-08-30T15:45:52Z",
    "updated_at": "2025-09-02T18:45:52Z",
    "closed_at": "2025-09-02T18:45:52Z",
    "sla_due_at": "2025-08-31T13:45:52Z",
    "sla_breached": true,
    "requester": "user180@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "onboarding",
      "request",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0762",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-08-27T11:27:41Z",
    "updated_at": "2025-09-01T02:27:41Z",
    "closed_at": "2025-09-01T02:27:41Z",
    "sla_due_at": "2025-08-30T04:27:41Z",
    "sla_breached": true,
    "requester": "user97@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "access",
      "db",
      "sso"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0763",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-08-29T06:26:43Z",
    "updated_at": "2025-09-06T15:26:43Z",
    "closed_at": null,
    "sla_due_at": "2025-08-30T08:26:43Z",
    "sla_breached": true,
    "requester": "user169@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0764",
    "subject": "New user onboarding request",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-10-13T16:58:43Z",
    "updated_at": "2025-10-22T01:58:43Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T08:58:43Z",
    "sla_breached": true,
    "requester": "user187@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "db",
      "sso",
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0765",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-14T03:35:35Z",
    "updated_at": "2025-11-26T07:26:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T00:35:35Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "bug",
      "access",
      "change",
      "db"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0766",
    "subject": "Application performance degradation",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-08-28T14:47:38Z",
    "updated_at": "2025-09-02T02:47:38Z",
    "closed_at": null,
    "sla_due_at": "2025-08-30T07:47:38Z",
    "sla_breached": true,
    "requester": "user51@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0767",
    "subject": "Upgrade request for enterprise license",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-01T02:59:06Z",
    "updated_at": "2025-09-10T05:59:06Z",
    "closed_at": null,
    "sla_due_at": "2025-09-03T06:59:06Z",
    "sla_breached": true,
    "requester": "user15@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "problem",
      "access",
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0768",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-21T08:41:23Z",
    "updated_at": "2025-09-24T13:41:23Z",
    "closed_at": "2025-09-24T13:41:23Z",
    "sla_due_at": "2025-09-23T07:41:23Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0769",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-24T21:20:18Z",
    "updated_at": "2025-10-02T22:20:18Z",
    "closed_at": "2025-10-02T22:20:18Z",
    "sla_due_at": "2025-09-25T23:20:18Z",
    "sla_breached": true,
    "requester": "user172@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0770",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-03T18:26:50Z",
    "updated_at": "2025-09-13T06:26:50Z",
    "closed_at": "2025-09-13T06:26:50Z",
    "sla_due_at": "2025-09-05T09:26:50Z",
    "sla_breached": true,
    "requester": "user30@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0771",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-29T07:31:14Z",
    "updated_at": "2025-10-31T08:31:14Z",
    "closed_at": null,
    "sla_due_at": "2025-11-01T00:31:14Z",
    "sla_breached": true,
    "requester": "user99@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "onboarding",
      "change",
      "access",
      "security"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0772",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-17T12:47:20Z",
    "updated_at": "2025-11-26T08:20:32Z",
    "closed_at": "2025-11-26T08:20:32Z",
    "sla_due_at": "2025-11-18T15:47:20Z",
    "sla_breached": true,
    "requester": "user138@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "security",
      "request",
      "change",
      "db"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0773",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-30T08:22:51Z",
    "updated_at": "2025-11-12T03:22:51Z",
    "closed_at": null,
    "sla_due_at": "2025-10-31T03:22:51Z",
    "sla_breached": true,
    "requester": "user143@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0774",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-14T00:51:02Z",
    "updated_at": "2025-09-19T12:51:02Z",
    "closed_at": null,
    "sla_due_at": "2025-09-15T00:51:02Z",
    "sla_breached": true,
    "requester": "user22@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "request",
      "access"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0775",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-03T08:21:21Z",
    "updated_at": "2025-09-14T10:21:21Z",
    "closed_at": null,
    "sla_due_at": "2025-09-04T19:21:21Z",
    "sla_breached": true,
    "requester": "user169@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "db",
      "vip",
      "request",
      "analytics"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0776",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-22T00:43:08Z",
    "updated_at": "2025-09-22T23:43:08Z",
    "closed_at": "2025-09-22T23:43:08Z",
    "sla_due_at": "2025-09-22T16:43:08Z",
    "sla_breached": true,
    "requester": "user37@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "access",
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0777",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-29T10:48:46Z",
    "updated_at": "2025-11-11T17:48:46Z",
    "closed_at": null,
    "sla_due_at": "2025-10-31T11:48:46Z",
    "sla_breached": true,
    "requester": "user66@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "incident",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0778",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-24T16:52:22Z",
    "updated_at": "2025-10-26T05:52:22Z",
    "closed_at": "2025-10-26T05:52:22Z",
    "sla_due_at": "2025-10-25T14:52:22Z",
    "sla_breached": true,
    "requester": "user163@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "db",
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0779",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-10T02:23:11Z",
    "updated_at": "2025-09-16T20:23:11Z",
    "closed_at": null,
    "sla_due_at": "2025-09-12T11:23:11Z",
    "sla_breached": true,
    "requester": "user7@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "security",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0780",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-19T04:21:16Z",
    "updated_at": "2025-10-02T20:21:16Z",
    "closed_at": null,
    "sla_due_at": "2025-09-21T12:21:16Z",
    "sla_breached": true,
    "requester": "user86@enterprise.example.com",
    "assignee": null,
    "tags": [
      "analytics",
      "sso"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0781",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-11-25T04:47:34Z",
    "updated_at": "2025-11-26T07:57:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-27T08:47:34Z",
    "sla_breached": false,
    "requester": "user32@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "change",
      "problem",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0782",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-12T11:31:39Z",
    "updated_at": "2025-10-25T11:31:39Z",
    "closed_at": "2025-10-25T11:31:39Z",
    "sla_due_at": "2025-10-14T03:31:39Z",
    "sla_breached": true,
    "requester": "user44@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "access",
      "vip",
      "bug",
      "request"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0783",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-10T17:41:56Z",
    "updated_at": "2025-09-16T06:41:56Z",
    "closed_at": "2025-09-16T06:41:56Z",
    "sla_due_at": "2025-09-13T10:41:56Z",
    "sla_breached": true,
    "requester": "user183@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "access",
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0784",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-19T09:05:12Z",
    "updated_at": "2025-11-24T17:05:12Z",
    "closed_at": "2025-11-24T17:05:12Z",
    "sla_due_at": "2025-11-21T12:05:12Z",
    "sla_breached": true,
    "requester": "user181@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "problem",
      "vip"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0785",
    "subject": "Security alert investigation",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-22T21:54:58Z",
    "updated_at": "2025-10-04T00:54:58Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T12:54:58Z",
    "sla_breached": true,
    "requester": "user59@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0786",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-17T05:04:38Z",
    "updated_at": "2025-10-22T08:04:38Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T19:04:38Z",
    "sla_breached": true,
    "requester": "user15@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "analytics",
      "network",
      "incident",
      "request"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0787",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-25T14:14:04Z",
    "updated_at": "2025-10-10T01:14:04Z",
    "closed_at": "2025-10-10T01:14:04Z",
    "sla_due_at": "2025-09-28T11:14:04Z",
    "sla_breached": true,
    "requester": "user32@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0788",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-25T16:53:10Z",
    "updated_at": "2025-11-26T07:34:32Z",
    "closed_at": "2025-11-26T07:34:32Z",
    "sla_due_at": "2025-11-28T16:53:10Z",
    "sla_breached": false,
    "requester": "user136@enterprise.example.com",
    "assignee": "agent44@support.example.com",
    "tags": [
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0789",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-04T13:17:54Z",
    "updated_at": "2025-11-12T09:17:54Z",
    "closed_at": null,
    "sla_due_at": "2025-11-05T21:17:54Z",
    "sla_breached": true,
    "requester": "user91@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem",
      "incident",
      "access",
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0790",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-13T23:15:55Z",
    "updated_at": "2025-10-24T07:15:55Z",
    "closed_at": null,
    "sla_due_at": "2025-10-14T18:15:55Z",
    "sla_breached": true,
    "requester": "user1@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso",
      "onboarding",
      "bug",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0791",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-27T09:52:03Z",
    "updated_at": "2025-09-27T13:52:03Z",
    "closed_at": null,
    "sla_due_at": "2025-09-30T03:52:03Z",
    "sla_breached": true,
    "requester": "user77@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "db",
      "access",
      "incident"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0792",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-25T04:40:10Z",
    "updated_at": "2025-11-26T07:48:32Z",
    "closed_at": "2025-11-26T07:48:32Z",
    "sla_due_at": "2025-11-27T15:40:10Z",
    "sla_breached": false,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "network",
      "access",
      "bug",
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0793",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-26T17:57:52Z",
    "updated_at": "2025-10-05T21:57:52Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T20:57:52Z",
    "sla_breached": true,
    "requester": "user69@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "access",
      "analytics",
      "vip",
      "incident"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0794",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-12T01:07:59Z",
    "updated_at": "2025-10-12T22:07:59Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T19:07:59Z",
    "sla_breached": true,
    "requester": "user191@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "bug",
      "sso"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0795",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-01T22:40:54Z",
    "updated_at": "2025-09-13T16:40:54Z",
    "closed_at": "2025-09-13T16:40:54Z",
    "sla_due_at": "2025-09-02T17:40:54Z",
    "sla_breached": true,
    "requester": "user183@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "analytics",
      "incident",
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0796",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-10T04:21:50Z",
    "updated_at": "2025-11-12T21:21:50Z",
    "closed_at": null,
    "sla_due_at": "2025-11-10T21:21:50Z",
    "sla_breached": true,
    "requester": "user4@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "network",
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0797",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-02T10:37:11Z",
    "updated_at": "2025-10-08T15:37:11Z",
    "closed_at": "2025-10-08T15:37:11Z",
    "sla_due_at": "2025-10-02T15:37:11Z",
    "sla_breached": true,
    "requester": "user195@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "change",
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0798",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-02T23:16:34Z",
    "updated_at": "2025-11-08T14:16:34Z",
    "closed_at": null,
    "sla_due_at": "2025-11-04T14:16:34Z",
    "sla_breached": true,
    "requester": "user110@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "db",
      "security",
      "request",
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0799",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-01T10:50:03Z",
    "updated_at": "2025-11-04T06:50:03Z",
    "closed_at": null,
    "sla_due_at": "2025-11-02T09:50:03Z",
    "sla_breached": true,
    "requester": "user50@enterprise.example.com",
    "assignee": null,
    "tags": [
      "network",
      "change",
      "sso",
      "security"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0800",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-08T17:31:47Z",
    "updated_at": "2025-10-22T06:31:47Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T16:31:47Z",
    "sla_breached": true,
    "requester": "user110@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "bug",
      "network",
      "onboarding",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0801",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-10T22:08:39Z",
    "updated_at": "2025-10-16T05:08:39Z",
    "closed_at": "2025-10-16T05:08:39Z",
    "sla_due_at": "2025-10-12T22:08:39Z",
    "sla_breached": true,
    "requester": "user47@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0802",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-29T21:58:15Z",
    "updated_at": "2025-11-11T20:58:15Z",
    "closed_at": null,
    "sla_due_at": "2025-11-01T13:58:15Z",
    "sla_breached": true,
    "requester": "user65@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "onboarding",
      "security"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0803",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-02T07:51:42Z",
    "updated_at": "2025-09-10T01:51:42Z",
    "closed_at": null,
    "sla_due_at": "2025-09-03T03:51:42Z",
    "sla_breached": true,
    "requester": "user136@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "sso",
      "change",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0804",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-13T03:36:30Z",
    "updated_at": "2025-11-26T07:29:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-13T22:36:30Z",
    "sla_breached": true,
    "requester": "user115@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0805",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-18T15:05:38Z",
    "updated_at": "2025-10-21T22:05:38Z",
    "closed_at": "2025-10-21T22:05:38Z",
    "sla_due_at": "2025-10-19T20:05:38Z",
    "sla_breached": true,
    "requester": "user108@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "analytics",
      "request",
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0806",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-29T09:25:35Z",
    "updated_at": "2025-09-30T20:25:35Z",
    "closed_at": null,
    "sla_due_at": "2025-09-30T04:25:35Z",
    "sla_breached": true,
    "requester": "user129@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "change",
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0807",
    "subject": "Application performance degradation",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-20T06:42:16Z",
    "updated_at": "2025-11-04T02:42:16Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T17:42:16Z",
    "sla_breached": true,
    "requester": "user102@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0808",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-21T18:22:21Z",
    "updated_at": "2025-09-27T14:22:21Z",
    "closed_at": "2025-09-27T14:22:21Z",
    "sla_due_at": "2025-09-23T23:22:21Z",
    "sla_breached": true,
    "requester": "user41@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "change",
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0809",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-21T15:46:37Z",
    "updated_at": "2025-10-02T20:46:37Z",
    "closed_at": "2025-10-02T20:46:37Z",
    "sla_due_at": "2025-09-24T11:46:37Z",
    "sla_breached": true,
    "requester": "user57@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "request",
      "security",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0810",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-20T12:55:57Z",
    "updated_at": "2025-11-26T08:12:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T22:55:57Z",
    "sla_breached": true,
    "requester": "user35@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "sso",
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0811",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-11-25T08:44:33Z",
    "updated_at": "2025-11-26T08:01:32Z",
    "closed_at": "2025-11-26T08:01:32Z",
    "sla_due_at": "2025-11-27T08:44:33Z",
    "sla_breached": false,
    "requester": "user141@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "incident",
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0812",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-10-16T06:16:27Z",
    "updated_at": "2025-10-20T23:16:27Z",
    "closed_at": null,
    "sla_due_at": "2025-10-16T11:16:27Z",
    "sla_breached": true,
    "requester": "user46@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0813",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-08-29T18:27:05Z",
    "updated_at": "2025-09-12T07:27:05Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T06:27:05Z",
    "sla_breached": true,
    "requester": "user114@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "onboarding",
      "sso",
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0814",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-06T16:07:07Z",
    "updated_at": "2025-11-15T23:07:07Z",
    "closed_at": "2025-11-15T23:07:07Z",
    "sla_due_at": "2025-11-08T01:07:07Z",
    "sla_breached": true,
    "requester": "user123@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "access",
      "problem",
      "analytics",
      "bug"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0815",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-14T14:29:59Z",
    "updated_at": "2025-09-15T01:29:59Z",
    "closed_at": "2025-09-15T01:29:59Z",
    "sla_due_at": "2025-09-15T17:29:59Z",
    "sla_breached": false,
    "requester": "user46@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "security",
      "access"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0816",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-02T23:25:47Z",
    "updated_at": "2025-10-11T14:25:47Z",
    "closed_at": null,
    "sla_due_at": "2025-10-05T13:25:47Z",
    "sla_breached": true,
    "requester": "user36@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0817",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-08T18:22:42Z",
    "updated_at": "2025-10-09T01:22:42Z",
    "closed_at": null,
    "sla_due_at": "2025-10-09T00:22:42Z",
    "sla_breached": true,
    "requester": "user12@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0818",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-06T10:31:37Z",
    "updated_at": "2025-09-06T15:31:37Z",
    "closed_at": null,
    "sla_due_at": "2025-09-06T15:31:37Z",
    "sla_breached": true,
    "requester": "user189@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0819",
    "subject": "Multi-factor authentication not working",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-25T11:51:58Z",
    "updated_at": "2025-10-02T01:51:58Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T23:51:58Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "bug",
      "request",
      "security"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0820",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-21T04:36:56Z",
    "updated_at": "2025-11-26T08:12:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-22T21:36:56Z",
    "sla_breached": true,
    "requester": "user7@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "vip",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0821",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-28T18:21:03Z",
    "updated_at": "2025-10-31T03:21:03Z",
    "closed_at": "2025-10-31T03:21:03Z",
    "sla_due_at": "2025-10-29T12:21:03Z",
    "sla_breached": true,
    "requester": "user73@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0822",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-10T19:14:02Z",
    "updated_at": "2025-11-23T17:14:02Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T09:14:02Z",
    "sla_breached": true,
    "requester": "user136@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "bug",
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0823",
    "subject": "Password reset request",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-01T21:22:46Z",
    "updated_at": "2025-09-04T03:22:46Z",
    "closed_at": null,
    "sla_due_at": "2025-09-03T13:22:46Z",
    "sla_breached": true,
    "requester": "user170@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0824",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-06T08:28:48Z",
    "updated_at": "2025-11-14T16:28:48Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T06:28:48Z",
    "sla_breached": true,
    "requester": "user123@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0825",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-22T03:05:31Z",
    "updated_at": "2025-10-24T21:05:31Z",
    "closed_at": null,
    "sla_due_at": "2025-10-22T18:05:31Z",
    "sla_breached": true,
    "requester": "user91@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "db",
      "incident",
      "change",
      "vip"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0826",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-03T23:24:21Z",
    "updated_at": "2025-09-14T14:24:21Z",
    "closed_at": "2025-09-14T14:24:21Z",
    "sla_due_at": "2025-09-06T04:24:21Z",
    "sla_breached": true,
    "requester": "user137@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "incident",
      "security"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0827",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-19T11:19:09Z",
    "updated_at": "2025-09-24T12:19:09Z",
    "closed_at": "2025-09-24T12:19:09Z",
    "sla_due_at": "2025-09-20T19:19:09Z",
    "sla_breached": true,
    "requester": "user5@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "access",
      "security",
      "network",
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0828",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-08T21:37:46Z",
    "updated_at": "2025-11-20T16:37:46Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T11:37:46Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0829",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-11T03:08:59Z",
    "updated_at": "2025-11-26T00:08:59Z",
    "closed_at": "2025-11-26T00:08:59Z",
    "sla_due_at": "2025-11-13T07:08:59Z",
    "sla_breached": true,
    "requester": "user180@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0830",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-23T03:00:40Z",
    "updated_at": "2025-11-26T08:17:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-25T05:00:40Z",
    "sla_breached": true,
    "requester": "user107@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "db",
      "access",
      "request",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0831",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-04T20:04:37Z",
    "updated_at": "2025-10-19T16:04:37Z",
    "closed_at": null,
    "sla_due_at": "2025-10-07T08:04:37Z",
    "sla_breached": true,
    "requester": "user40@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0832",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-23T02:31:15Z",
    "updated_at": "2025-10-02T03:31:15Z",
    "closed_at": null,
    "sla_due_at": "2025-09-23T07:31:15Z",
    "sla_breached": true,
    "requester": "user117@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "db",
      "sso",
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0833",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-23T05:00:42Z",
    "updated_at": "2025-10-25T22:00:42Z",
    "closed_at": null,
    "sla_due_at": "2025-10-26T03:00:42Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "db",
      "request"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0834",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-08-29T15:18:14Z",
    "updated_at": "2025-09-12T08:18:14Z",
    "closed_at": null,
    "sla_due_at": "2025-09-01T08:18:14Z",
    "sla_breached": true,
    "requester": "user43@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "sso",
      "onboarding",
      "security",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0835",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-10T10:23:51Z",
    "updated_at": "2025-10-16T11:23:51Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T08:23:51Z",
    "sla_breached": true,
    "requester": "user17@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "sso",
      "request",
      "analytics"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0836",
    "subject": "Login issues on corporate portal",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-26T22:33:32Z",
    "updated_at": "2025-11-08T00:33:32Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T12:33:32Z",
    "sla_breached": true,
    "requester": "user124@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0837",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-18T08:03:01Z",
    "updated_at": "2025-10-26T20:03:01Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T09:03:01Z",
    "sla_breached": true,
    "requester": "user193@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "access",
      "db",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0838",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-14T17:31:49Z",
    "updated_at": "2025-10-17T22:31:49Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T13:31:49Z",
    "sla_breached": true,
    "requester": "user98@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "access",
      "analytics",
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0839",
    "subject": "Bug report for ticketing system",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-15T09:34:08Z",
    "updated_at": "2025-11-20T08:34:08Z",
    "closed_at": null,
    "sla_due_at": "2025-11-16T00:34:08Z",
    "sla_breached": true,
    "requester": "user175@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "analytics",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0840",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-22T13:33:40Z",
    "updated_at": "2025-09-29T20:33:40Z",
    "closed_at": null,
    "sla_due_at": "2025-09-25T11:33:40Z",
    "sla_breached": true,
    "requester": "user87@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "change",
      "incident",
      "network"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0841",
    "subject": "Upgrade request for enterprise license",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-10-27T00:45:22Z",
    "updated_at": "2025-11-08T03:45:22Z",
    "closed_at": null,
    "sla_due_at": "2025-10-27T13:45:22Z",
    "sla_breached": true,
    "requester": "user25@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "analytics",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0842",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-14T14:11:39Z",
    "updated_at": "2025-11-18T05:11:39Z",
    "closed_at": "2025-11-18T05:11:39Z",
    "sla_due_at": "2025-11-15T06:11:39Z",
    "sla_breached": true,
    "requester": "user18@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "vip",
      "security",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0843",
    "subject": "Data export failing in analytics app",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-08-27T15:35:02Z",
    "updated_at": "2025-09-02T03:35:02Z",
    "closed_at": null,
    "sla_due_at": "2025-08-29T04:35:02Z",
    "sla_breached": true,
    "requester": "user167@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0844",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-20T19:07:31Z",
    "updated_at": "2025-11-26T07:42:32Z",
    "closed_at": "2025-11-26T07:42:32Z",
    "sla_due_at": "2025-11-22T11:07:31Z",
    "sla_breached": true,
    "requester": "user113@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "vip",
      "security",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0845",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-22T15:58:18Z",
    "updated_at": "2025-10-07T05:58:18Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T04:58:18Z",
    "sla_breached": true,
    "requester": "user165@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "db",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0846",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-07T04:31:31Z",
    "updated_at": "2025-11-19T08:31:31Z",
    "closed_at": null,
    "sla_due_at": "2025-11-08T21:31:31Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0847",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-09-27T08:58:01Z",
    "updated_at": "2025-10-07T07:58:01Z",
    "closed_at": null,
    "sla_due_at": "2025-09-30T08:58:01Z",
    "sla_breached": true,
    "requester": "user188@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "analytics",
      "incident",
      "sso",
      "db"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0848",
    "subject": "Security alert investigation",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-11-17T20:48:25Z",
    "updated_at": "2025-11-26T08:08:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-19T19:48:25Z",
    "sla_breached": true,
    "requester": "user30@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "network",
      "request",
      "access",
      "problem"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0849",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-06T00:35:13Z",
    "updated_at": "2025-09-18T20:35:13Z",
    "closed_at": "2025-09-18T20:35:13Z",
    "sla_due_at": "2025-09-07T20:35:13Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "sso",
      "network",
      "analytics",
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0850",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-22T23:10:53Z",
    "updated_at": "2025-10-24T11:10:53Z",
    "closed_at": null,
    "sla_due_at": "2025-10-24T01:10:53Z",
    "sla_breached": true,
    "requester": "user77@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident",
      "request",
      "sso",
      "onboarding"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0851",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-20T04:59:36Z",
    "updated_at": "2025-11-26T08:11:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-22T14:59:36Z",
    "sla_breached": true,
    "requester": "user108@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "db",
      "incident"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0852",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-08-29T11:35:40Z",
    "updated_at": "2025-09-10T11:35:40Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T16:35:40Z",
    "sla_breached": true,
    "requester": "user51@enterprise.example.com",
    "assignee": "agent5@support.example.com",
    "tags": [
      "vip",
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0853",
    "subject": "Multi-factor authentication not working",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-11-25T02:52:45Z",
    "updated_at": "2025-11-26T07:26:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-27T16:52:45Z",
    "sla_breached": false,
    "requester": "user173@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "request",
      "db",
      "network"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0854",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-09T09:15:54Z",
    "updated_at": "2025-11-21T18:15:54Z",
    "closed_at": "2025-11-21T18:15:54Z",
    "sla_due_at": "2025-11-11T22:15:54Z",
    "sla_breached": true,
    "requester": "user191@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "db",
      "request",
      "access",
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0855",
    "subject": "Access request to internal repository",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-10-29T19:41:08Z",
    "updated_at": "2025-11-13T07:41:08Z",
    "closed_at": null,
    "sla_due_at": "2025-10-31T01:41:08Z",
    "sla_breached": true,
    "requester": "user95@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "onboarding"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0856",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-23T03:49:02Z",
    "updated_at": "2025-10-02T21:49:02Z",
    "closed_at": "2025-10-02T21:49:02Z",
    "sla_due_at": "2025-09-25T22:49:02Z",
    "sla_breached": true,
    "requester": "user91@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "request",
      "vip",
      "security",
      "access"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0857",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-02T18:46:27Z",
    "updated_at": "2025-10-06T06:46:27Z",
    "closed_at": "2025-10-06T06:46:27Z",
    "sla_due_at": "2025-10-03T20:46:27Z",
    "sla_breached": true,
    "requester": "user73@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "bug",
      "onboarding",
      "change",
      "security"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0858",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-13T05:05:43Z",
    "updated_at": "2025-11-22T00:05:43Z",
    "closed_at": "2025-11-22T00:05:43Z",
    "sla_due_at": "2025-11-13T11:05:43Z",
    "sla_breached": true,
    "requester": "user193@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0859",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-22T11:11:49Z",
    "updated_at": "2025-10-10T16:11:49Z",
    "closed_at": "2025-10-10T16:11:49Z",
    "sla_due_at": "2025-09-22T19:11:49Z",
    "sla_breached": true,
    "requester": "user199@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "security",
      "sso",
      "problem",
      "analytics"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0860",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-27T17:19:28Z",
    "updated_at": "2025-10-05T17:19:28Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T23:19:28Z",
    "sla_breached": true,
    "requester": "user73@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "onboarding",
      "incident",
      "bug"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0861",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-25T17:15:56Z",
    "updated_at": "2025-11-26T07:31:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-26T01:15:56Z",
    "sla_breached": true,
    "requester": "user133@enterprise.example.com",
    "assignee": null,
    "tags": [
      "vip",
      "access",
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0862",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-26T12:07:31Z",
    "updated_at": "2025-11-09T06:07:31Z",
    "closed_at": null,
    "sla_due_at": "2025-10-28T18:07:31Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "db",
      "access",
      "incident",
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0863",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-05T16:26:01Z",
    "updated_at": "2025-11-08T09:26:01Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T01:26:01Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": null,
    "tags": [
      "request",
      "access",
      "vip"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0864",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-15T04:57:48Z",
    "updated_at": "2025-11-26T07:32:32Z",
    "closed_at": "2025-11-26T07:32:32Z",
    "sla_due_at": "2025-11-15T11:57:48Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0865",
    "subject": "Email delivery delayed",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-23T03:36:21Z",
    "updated_at": "2025-11-26T07:59:32Z",
    "closed_at": "2025-11-26T07:59:32Z",
    "sla_due_at": "2025-11-25T17:36:21Z",
    "sla_breached": true,
    "requester": "user57@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "request",
      "sso"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0866",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-24T06:28:30Z",
    "updated_at": "2025-10-27T08:28:30Z",
    "closed_at": null,
    "sla_due_at": "2025-10-25T21:28:30Z",
    "sla_breached": true,
    "requester": "user149@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0867",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-13T03:11:42Z",
    "updated_at": "2025-11-17T00:11:42Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T19:11:42Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident",
      "security"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0868",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-23T17:17:42Z",
    "updated_at": "2025-11-26T08:17:32Z",
    "closed_at": "2025-11-26T08:17:32Z",
    "sla_due_at": "2025-11-24T06:17:42Z",
    "sla_breached": true,
    "requester": "user97@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "analytics",
      "access",
      "db",
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0869",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-03T11:42:16Z",
    "updated_at": "2025-11-10T19:42:16Z",
    "closed_at": null,
    "sla_due_at": "2025-11-03T19:42:16Z",
    "sla_breached": true,
    "requester": "user158@enterprise.example.com",
    "assignee": "agent1@support.example.com",
    "tags": [
      "request",
      "db"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0870",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-11T01:20:16Z",
    "updated_at": "2025-11-22T03:20:16Z",
    "closed_at": "2025-11-22T03:20:16Z",
    "sla_due_at": "2025-11-11T08:20:16Z",
    "sla_breached": true,
    "requester": "user56@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0871",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-16T03:18:51Z",
    "updated_at": "2025-10-30T22:18:51Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T11:18:51Z",
    "sla_breached": true,
    "requester": "user124@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "db",
      "request",
      "bug"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0872",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-27T14:18:27Z",
    "updated_at": "2025-10-06T03:18:27Z",
    "closed_at": "2025-10-06T03:18:27Z",
    "sla_due_at": "2025-09-30T01:18:27Z",
    "sla_breached": true,
    "requester": "user45@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "incident",
      "security",
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0873",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-05T00:51:54Z",
    "updated_at": "2025-11-14T13:51:54Z",
    "closed_at": "2025-11-14T13:51:54Z",
    "sla_due_at": "2025-11-07T18:51:54Z",
    "sla_breached": true,
    "requester": "user70@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "change"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0874",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-03T01:05:15Z",
    "updated_at": "2025-10-16T13:05:15Z",
    "closed_at": null,
    "sla_due_at": "2025-10-05T02:05:15Z",
    "sla_breached": true,
    "requester": "user43@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "incident",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0875",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-11T17:51:26Z",
    "updated_at": "2025-10-18T15:51:26Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T00:51:26Z",
    "sla_breached": true,
    "requester": "user92@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "vip",
      "access",
      "analytics"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0876",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-24T20:45:34Z",
    "updated_at": "2025-11-26T07:52:32Z",
    "closed_at": "2025-11-26T07:52:32Z",
    "sla_due_at": "2025-11-25T01:45:34Z",
    "sla_breached": true,
    "requester": "user60@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0877",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-10T00:38:02Z",
    "updated_at": "2025-09-22T00:38:02Z",
    "closed_at": null,
    "sla_due_at": "2025-09-12T23:38:02Z",
    "sla_breached": true,
    "requester": "user172@enterprise.example.com",
    "assignee": "agent42@support.example.com",
    "tags": [
      "bug",
      "incident",
      "vip",
      "analytics"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0878",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-01T06:33:03Z",
    "updated_at": "2025-11-07T03:33:03Z",
    "closed_at": "2025-11-07T03:33:03Z",
    "sla_due_at": "2025-11-04T01:33:03Z",
    "sla_breached": true,
    "requester": "user116@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "change",
      "incident",
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0879",
    "subject": "Email delivery delayed",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-21T07:42:35Z",
    "updated_at": "2025-10-27T09:42:35Z",
    "closed_at": null,
    "sla_due_at": "2025-10-21T11:42:35Z",
    "sla_breached": true,
    "requester": "user104@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0880",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-17T15:15:03Z",
    "updated_at": "2025-11-26T07:35:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-18T07:15:03Z",
    "sla_breached": true,
    "requester": "user193@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "security",
      "request",
      "vip",
      "problem"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0881",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-06T21:29:35Z",
    "updated_at": "2025-10-20T14:29:35Z",
    "closed_at": "2025-10-20T14:29:35Z",
    "sla_due_at": "2025-10-09T11:29:35Z",
    "sla_breached": true,
    "requester": "user96@enterprise.example.com",
    "assignee": "agent40@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0882",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-20T07:58:50Z",
    "updated_at": "2025-11-26T07:26:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T04:58:50Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "request",
      "network",
      "db"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0883",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-21T04:19:29Z",
    "updated_at": "2025-11-22T19:19:29Z",
    "closed_at": null,
    "sla_due_at": "2025-11-21T14:19:29Z",
    "sla_breached": true,
    "requester": "user157@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "db",
      "access",
      "analytics"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0884",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-11T03:45:40Z",
    "updated_at": "2025-11-23T15:45:40Z",
    "closed_at": null,
    "sla_due_at": "2025-11-12T23:45:40Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "bug",
      "security",
      "request",
      "analytics"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0885",
    "subject": "Data export failing in analytics app",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-13T14:57:30Z",
    "updated_at": "2025-09-20T11:57:30Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T08:57:30Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "analytics",
      "onboarding",
      "security"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0886",
    "subject": "Database connection timeout",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-15T23:32:04Z",
    "updated_at": "2025-09-17T14:32:04Z",
    "closed_at": "2025-09-17T14:32:04Z",
    "sla_due_at": "2025-09-17T05:32:04Z",
    "sla_breached": true,
    "requester": "user4@enterprise.example.com",
    "assignee": "agent43@support.example.com",
    "tags": [
      "problem",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0887",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-25T04:33:11Z",
    "updated_at": "2025-10-07T19:33:11Z",
    "closed_at": null,
    "sla_due_at": "2025-09-27T03:33:11Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": null,
    "tags": [
      "db",
      "problem",
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0888",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-23T04:30:43Z",
    "updated_at": "2025-09-30T23:30:43Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T00:30:43Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "sso",
      "security",
      "onboarding",
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0889",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-08-30T21:10:34Z",
    "updated_at": "2025-09-02T04:10:34Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T14:10:34Z",
    "sla_breached": true,
    "requester": "user5@enterprise.example.com",
    "assignee": null,
    "tags": [
      "onboarding",
      "network"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0890",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-02T13:01:48Z",
    "updated_at": "2025-09-05T02:01:48Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T02:01:48Z",
    "sla_breached": true,
    "requester": "user91@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "request",
      "incident",
      "analytics",
      "vip"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0891",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-30T22:26:04Z",
    "updated_at": "2025-10-14T19:26:04Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T01:26:04Z",
    "sla_breached": true,
    "requester": "user109@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "access",
      "change",
      "onboarding",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0892",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "critical",
    "created_at": "2025-09-20T16:34:24Z",
    "updated_at": "2025-10-04T11:34:24Z",
    "closed_at": "2025-10-04T11:34:24Z",
    "sla_due_at": "2025-09-21T09:34:24Z",
    "sla_breached": true,
    "requester": "user57@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0893",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-27T05:57:42Z",
    "updated_at": "2025-11-01T01:57:42Z",
    "closed_at": null,
    "sla_due_at": "2025-10-30T05:57:42Z",
    "sla_breached": true,
    "requester": "user184@enterprise.example.com",
    "assignee": "agent26@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0894",
    "subject": "Upgrade request for enterprise license",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-24T00:52:10Z",
    "updated_at": "2025-10-01T10:52:10Z",
    "closed_at": null,
    "sla_due_at": "2025-09-25T01:52:10Z",
    "sla_breached": true,
    "requester": "user153@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "security"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0895",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-22T09:42:30Z",
    "updated_at": "2025-10-10T14:42:30Z",
    "closed_at": "2025-10-10T14:42:30Z",
    "sla_due_at": "2025-09-25T02:42:30Z",
    "sla_breached": true,
    "requester": "user44@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0896",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-14T15:47:06Z",
    "updated_at": "2025-10-28T21:47:06Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T13:47:06Z",
    "sla_breached": true,
    "requester": "user6@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "security",
      "access",
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0897",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-10T19:32:16Z",
    "updated_at": "2025-09-21T06:32:16Z",
    "closed_at": "2025-09-21T06:32:16Z",
    "sla_due_at": "2025-09-13T11:32:16Z",
    "sla_breached": true,
    "requester": "user29@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0898",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-27T13:14:04Z",
    "updated_at": "2025-10-30T17:14:04Z",
    "closed_at": null,
    "sla_due_at": "2025-10-30T09:14:04Z",
    "sla_breached": true,
    "requester": "user78@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem",
      "analytics",
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0899",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-24T14:38:47Z",
    "updated_at": "2025-10-24T21:38:47Z",
    "closed_at": null,
    "sla_due_at": "2025-10-26T02:38:47Z",
    "sla_breached": true,
    "requester": "user182@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "security",
      "onboarding",
      "bug",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0900",
    "subject": "Multi-factor authentication not working",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-07T17:25:11Z",
    "updated_at": "2025-11-10T18:25:11Z",
    "closed_at": "2025-11-10T18:25:11Z",
    "sla_due_at": "2025-11-09T01:25:11Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "vip",
      "sso",
      "security",
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0901",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-06T04:25:46Z",
    "updated_at": "2025-09-20T16:25:46Z",
    "closed_at": null,
    "sla_due_at": "2025-09-07T19:25:46Z",
    "sla_breached": true,
    "requester": "user116@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "onboarding",
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0902",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-10-14T18:07:20Z",
    "updated_at": "2025-10-20T16:07:20Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T03:07:20Z",
    "sla_breached": true,
    "requester": "user149@enterprise.example.com",
    "assignee": "agent34@support.example.com",
    "tags": [
      "change",
      "security",
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0903",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-09-14T19:43:31Z",
    "updated_at": "2025-09-15T00:43:31Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T11:43:31Z",
    "sla_breached": true,
    "requester": "user38@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "change",
      "request",
      "bug"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0904",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-18T14:38:03Z",
    "updated_at": "2025-10-24T21:38:03Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T06:38:03Z",
    "sla_breached": true,
    "requester": "user56@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "network"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0905",
    "subject": "Login issues on corporate portal",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-18T08:10:25Z",
    "updated_at": "2025-10-18T09:10:25Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T19:10:25Z",
    "sla_breached": true,
    "requester": "user90@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security",
      "db"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0906",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-08T01:11:47Z",
    "updated_at": "2025-11-09T19:11:47Z",
    "closed_at": "2025-11-09T19:11:47Z",
    "sla_due_at": "2025-11-10T12:11:47Z",
    "sla_breached": false,
    "requester": "user122@enterprise.example.com",
    "assignee": "agent23@support.example.com",
    "tags": [
      "analytics",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0907",
    "subject": "Access request to internal repository",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-10-02T17:49:40Z",
    "updated_at": "2025-10-09T04:49:40Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T09:49:40Z",
    "sla_breached": true,
    "requester": "user145@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "analytics",
      "change",
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0908",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-25T03:25:07Z",
    "updated_at": "2025-10-31T14:25:07Z",
    "closed_at": "2025-10-31T14:25:07Z",
    "sla_due_at": "2025-10-27T12:25:07Z",
    "sla_breached": true,
    "requester": "user146@enterprise.example.com",
    "assignee": "agent41@support.example.com",
    "tags": [
      "request",
      "access",
      "incident",
      "bug"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0909",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-08T13:11:14Z",
    "updated_at": "2025-11-19T07:11:14Z",
    "closed_at": "2025-11-19T07:11:14Z",
    "sla_due_at": "2025-11-11T01:11:14Z",
    "sla_breached": true,
    "requester": "user92@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "incident",
      "problem",
      "analytics"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0910",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-28T07:21:05Z",
    "updated_at": "2025-10-07T07:21:05Z",
    "closed_at": null,
    "sla_due_at": "2025-09-28T14:21:05Z",
    "sla_breached": true,
    "requester": "user158@enterprise.example.com",
    "assignee": "agent20@support.example.com",
    "tags": [
      "change",
      "request"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0911",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-09T09:45:11Z",
    "updated_at": "2025-11-17T19:45:11Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T02:45:11Z",
    "sla_breached": true,
    "requester": "user2@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "network",
      "security",
      "analytics",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0912",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-14T10:43:11Z",
    "updated_at": "2025-10-26T12:43:11Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T02:43:11Z",
    "sla_breached": true,
    "requester": "user16@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "db"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0913",
    "subject": "Upgrade request for enterprise license",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-21T03:06:38Z",
    "updated_at": "2025-10-05T13:06:38Z",
    "closed_at": null,
    "sla_due_at": "2025-09-23T22:06:38Z",
    "sla_breached": true,
    "requester": "user78@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0914",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-08T01:03:06Z",
    "updated_at": "2025-09-11T08:03:06Z",
    "closed_at": null,
    "sla_due_at": "2025-09-08T19:03:06Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "problem"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0915",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-22T16:12:01Z",
    "updated_at": "2025-09-25T07:12:01Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T22:12:01Z",
    "sla_breached": true,
    "requester": "user48@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "bug",
      "problem"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0916",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-02T03:02:04Z",
    "updated_at": "2025-10-16T04:02:04Z",
    "closed_at": null,
    "sla_due_at": "2025-10-02T09:02:04Z",
    "sla_breached": true,
    "requester": "user190@enterprise.example.com",
    "assignee": "agent13@support.example.com",
    "tags": [
      "problem",
      "onboarding",
      "db",
      "security"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0917",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-09T22:20:24Z",
    "updated_at": "2025-10-12T05:20:24Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T04:20:24Z",
    "sla_breached": true,
    "requester": "user109@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "security",
      "change",
      "incident",
      "network"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0918",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "high",
    "created_at": "2025-11-21T08:52:17Z",
    "updated_at": "2025-11-26T08:13:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-23T20:52:17Z",
    "sla_breached": true,
    "requester": "user118@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "request",
      "analytics",
      "sso"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0919",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-08-27T13:14:32Z",
    "updated_at": "2025-08-31T07:14:32Z",
    "closed_at": "2025-08-31T07:14:32Z",
    "sla_due_at": "2025-08-29T18:14:32Z",
    "sla_breached": true,
    "requester": "user168@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "problem",
      "db",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0920",
    "subject": "Database connection timeout",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-02T21:19:47Z",
    "updated_at": "2025-09-16T16:19:47Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T03:19:47Z",
    "sla_breached": true,
    "requester": "user121@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "access",
      "db",
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0921",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-12T09:52:39Z",
    "updated_at": "2025-09-13T01:52:39Z",
    "closed_at": null,
    "sla_due_at": "2025-09-14T16:52:39Z",
    "sla_breached": true,
    "requester": "user60@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "bug",
      "problem",
      "vip",
      "sso"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0922",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-11-13T02:01:26Z",
    "updated_at": "2025-11-22T02:01:26Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T07:01:26Z",
    "sla_breached": true,
    "requester": "user157@enterprise.example.com",
    "assignee": "agent17@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0923",
    "subject": "Unable to access VPN",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-09-30T18:43:49Z",
    "updated_at": "2025-10-07T15:43:49Z",
    "closed_at": null,
    "sla_due_at": "2025-10-01T01:43:49Z",
    "sla_breached": true,
    "requester": "user97@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "sso",
      "onboarding"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0924",
    "subject": "New user onboarding request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-30T21:56:34Z",
    "updated_at": "2025-10-04T08:56:34Z",
    "closed_at": null,
    "sla_due_at": "2025-10-02T05:56:34Z",
    "sla_breached": true,
    "requester": "user50@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0925",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-09T08:10:06Z",
    "updated_at": "2025-11-21T11:10:06Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T10:10:06Z",
    "sla_breached": true,
    "requester": "user88@enterprise.example.com",
    "assignee": "agent12@support.example.com",
    "tags": [
      "sso",
      "analytics",
      "change",
      "problem"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0926",
    "subject": "New user onboarding request",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-11T19:22:47Z",
    "updated_at": "2025-10-21T04:22:47Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T16:22:47Z",
    "sla_breached": true,
    "requester": "user19@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0927",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-19T04:41:06Z",
    "updated_at": "2025-10-20T07:41:06Z",
    "closed_at": "2025-10-20T07:41:06Z",
    "sla_due_at": "2025-10-19T23:41:06Z",
    "sla_breached": true,
    "requester": "user6@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "onboarding",
      "incident",
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0928",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-05T21:52:15Z",
    "updated_at": "2025-11-11T01:52:15Z",
    "closed_at": "2025-11-11T01:52:15Z",
    "sla_due_at": "2025-11-06T10:52:15Z",
    "sla_breached": true,
    "requester": "user157@enterprise.example.com",
    "assignee": "agent33@support.example.com",
    "tags": [
      "incident",
      "change",
      "network"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0929",
    "subject": "Upgrade request for enterprise license",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-08-29T04:19:20Z",
    "updated_at": "2025-09-03T19:19:20Z",
    "closed_at": null,
    "sla_due_at": "2025-08-31T20:19:20Z",
    "sla_breached": true,
    "requester": "user87@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "sso",
      "vip",
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0930",
    "subject": "Bug report for ticketing system",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-30T12:26:25Z",
    "updated_at": "2025-11-13T16:26:25Z",
    "closed_at": null,
    "sla_due_at": "2025-11-01T10:26:25Z",
    "sla_breached": true,
    "requester": "user61@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "analytics"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0931",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-13T05:46:57Z",
    "updated_at": "2025-10-26T07:46:57Z",
    "closed_at": "2025-10-26T07:46:57Z",
    "sla_due_at": "2025-10-15T14:46:57Z",
    "sla_breached": true,
    "requester": "user142@enterprise.example.com",
    "assignee": "agent31@support.example.com",
    "tags": [
      "onboarding",
      "db"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0932",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-13T07:03:46Z",
    "updated_at": "2025-11-26T07:59:32Z",
    "closed_at": "2025-11-26T07:59:32Z",
    "sla_due_at": "2025-11-16T02:03:46Z",
    "sla_breached": true,
    "requester": "user59@enterprise.example.com",
    "assignee": "agent2@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0933",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-18T10:13:03Z",
    "updated_at": "2025-10-04T04:13:03Z",
    "closed_at": "2025-10-04T04:13:03Z",
    "sla_due_at": "2025-09-20T14:13:03Z",
    "sla_breached": true,
    "requester": "user14@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "db",
      "access",
      "incident",
      "bug"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0934",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-09T04:09:03Z",
    "updated_at": "2025-11-22T08:09:03Z",
    "closed_at": null,
    "sla_due_at": "2025-11-11T16:09:03Z",
    "sla_breached": true,
    "requester": "user50@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "sso",
      "security"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0935",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-10-27T17:19:11Z",
    "updated_at": "2025-11-13T20:19:11Z",
    "closed_at": "2025-11-13T20:19:11Z",
    "sla_due_at": "2025-10-30T17:19:11Z",
    "sla_breached": true,
    "requester": "user64@enterprise.example.com",
    "assignee": "agent4@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0936",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-01T01:47:02Z",
    "updated_at": "2025-10-08T13:47:02Z",
    "closed_at": null,
    "sla_due_at": "2025-10-02T17:47:02Z",
    "sla_breached": true,
    "requester": "user63@enterprise.example.com",
    "assignee": null,
    "tags": [
      "change",
      "incident"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0937",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-03T03:54:12Z",
    "updated_at": "2025-09-14T18:54:12Z",
    "closed_at": null,
    "sla_due_at": "2025-09-03T16:54:12Z",
    "sla_breached": true,
    "requester": "user189@enterprise.example.com",
    "assignee": null,
    "tags": [
      "problem",
      "db"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0938",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-10T12:16:59Z",
    "updated_at": "2025-10-15T18:16:59Z",
    "closed_at": null,
    "sla_due_at": "2025-10-12T05:16:59Z",
    "sla_breached": true,
    "requester": "user82@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "network"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0939",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-04T09:43:03Z",
    "updated_at": "2025-10-08T18:43:03Z",
    "closed_at": null,
    "sla_due_at": "2025-10-07T03:43:03Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent48@support.example.com",
    "tags": [
      "security",
      "vip"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0940",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-21T23:47:57Z",
    "updated_at": "2025-11-26T07:21:32Z",
    "closed_at": "2025-11-26T07:21:32Z",
    "sla_due_at": "2025-11-24T11:47:57Z",
    "sla_breached": true,
    "requester": "user9@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "change",
      "incident",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0941",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-18T22:11:51Z",
    "updated_at": "2025-11-26T07:57:32Z",
    "closed_at": "2025-11-26T07:57:32Z",
    "sla_due_at": "2025-11-21T03:11:51Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "access",
      "bug",
      "incident",
      "request"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0942",
    "subject": "Bug report for ticketing system",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-02T21:14:56Z",
    "updated_at": "2025-09-10T08:14:56Z",
    "closed_at": "2025-09-10T08:14:56Z",
    "sla_due_at": "2025-09-03T05:14:56Z",
    "sla_breached": true,
    "requester": "user156@enterprise.example.com",
    "assignee": "agent49@support.example.com",
    "tags": [
      "onboarding",
      "change",
      "sso"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0943",
    "subject": "Data export failing in analytics app",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-10-13T09:43:47Z",
    "updated_at": "2025-10-14T15:43:47Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T20:43:47Z",
    "sla_breached": true,
    "requester": "user100@enterprise.example.com",
    "assignee": "agent47@support.example.com",
    "tags": [
      "request",
      "problem",
      "incident"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0944",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-24T02:26:27Z",
    "updated_at": "2025-11-12T20:26:27Z",
    "closed_at": "2025-11-12T20:26:27Z",
    "sla_due_at": "2025-10-26T06:26:27Z",
    "sla_breached": true,
    "requester": "user4@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "security",
      "sso",
      "request"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0945",
    "subject": "Multi-factor authentication not working",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-13T11:34:00Z",
    "updated_at": "2025-10-19T08:34:00Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T17:34:00Z",
    "sla_breached": true,
    "requester": "user65@enterprise.example.com",
    "assignee": null,
    "tags": [
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0946",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-14T20:40:20Z",
    "updated_at": "2025-09-24T08:40:20Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T09:40:20Z",
    "sla_breached": true,
    "requester": "user3@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0947",
    "subject": "Unable to access VPN",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-05T12:05:37Z",
    "updated_at": "2025-09-17T21:05:37Z",
    "closed_at": "2025-09-17T21:05:37Z",
    "sla_due_at": "2025-09-06T19:05:37Z",
    "sla_breached": true,
    "requester": "user157@enterprise.example.com",
    "assignee": "agent36@support.example.com",
    "tags": [
      "security",
      "problem",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0948",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "low",
    "created_at": "2025-10-21T22:54:34Z",
    "updated_at": "2025-11-04T09:54:34Z",
    "closed_at": null,
    "sla_due_at": "2025-10-24T17:54:34Z",
    "sla_breached": true,
    "requester": "user159@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "bug"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0949",
    "subject": "Slow network in branch office",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-02T13:54:36Z",
    "updated_at": "2025-11-03T11:54:36Z",
    "closed_at": "2025-11-03T11:54:36Z",
    "sla_due_at": "2025-11-05T01:54:36Z",
    "sla_breached": false,
    "requester": "user16@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "onboarding",
      "network",
      "bug"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0950",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-18T06:43:49Z",
    "updated_at": "2025-09-19T22:43:49Z",
    "closed_at": null,
    "sla_due_at": "2025-09-19T16:43:49Z",
    "sla_breached": true,
    "requester": "user131@enterprise.example.com",
    "assignee": "agent14@support.example.com",
    "tags": [
      "change",
      "vip",
      "bug"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0951",
    "subject": "Login issues on corporate portal",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-16T08:59:19Z",
    "updated_at": "2025-11-19T10:59:19Z",
    "closed_at": null,
    "sla_due_at": "2025-11-18T18:59:19Z",
    "sla_breached": true,
    "requester": "user93@enterprise.example.com",
    "assignee": "agent22@support.example.com",
    "tags": [
      "bug",
      "vip",
      "problem",
      "onboarding"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0952",
    "subject": "Bug report for ticketing system",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-05T18:56:58Z",
    "updated_at": "2025-11-08T23:56:58Z",
    "closed_at": null,
    "sla_due_at": "2025-11-06T03:56:58Z",
    "sla_breached": true,
    "requester": "user28@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "sso",
      "incident",
      "change"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0953",
    "subject": "Unable to access VPN",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-09-03T02:53:42Z",
    "updated_at": "2025-09-16T23:53:42Z",
    "closed_at": null,
    "sla_due_at": "2025-09-05T06:53:42Z",
    "sla_breached": true,
    "requester": "user58@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "request",
      "db",
      "security",
      "analytics"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0954",
    "subject": "Password reset request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-09T15:09:43Z",
    "updated_at": "2025-09-16T10:09:43Z",
    "closed_at": "2025-09-16T10:09:43Z",
    "sla_due_at": "2025-09-12T14:09:43Z",
    "sla_breached": true,
    "requester": "user148@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "vip",
      "sso"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0955",
    "subject": "Security alert investigation",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-27T15:45:47Z",
    "updated_at": "2025-10-30T03:45:47Z",
    "closed_at": "2025-10-30T03:45:47Z",
    "sla_due_at": "2025-10-29T11:45:47Z",
    "sla_breached": true,
    "requester": "user188@enterprise.example.com",
    "assignee": "agent27@support.example.com",
    "tags": [
      "security",
      "vip",
      "request"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0956",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-11-16T19:10:06Z",
    "updated_at": "2025-11-26T07:31:32Z",
    "closed_at": "2025-11-26T07:31:32Z",
    "sla_due_at": "2025-11-19T12:10:06Z",
    "sla_breached": true,
    "requester": "user33@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "analytics",
      "incident"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0957",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-09T22:52:57Z",
    "updated_at": "2025-09-12T11:52:57Z",
    "closed_at": null,
    "sla_due_at": "2025-09-11T14:52:57Z",
    "sla_breached": true,
    "requester": "user130@enterprise.example.com",
    "assignee": null,
    "tags": [
      "bug",
      "sso",
      "access",
      "problem"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0958",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-11-05T03:57:40Z",
    "updated_at": "2025-11-16T23:57:40Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T12:57:40Z",
    "sla_breached": true,
    "requester": "user191@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "network",
      "db",
      "access",
      "security"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0959",
    "subject": "Email delivery delayed",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-09-21T13:05:15Z",
    "updated_at": "2025-09-29T03:05:15Z",
    "closed_at": null,
    "sla_due_at": "2025-09-23T18:05:15Z",
    "sla_breached": true,
    "requester": "user143@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "security",
      "vip",
      "db"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0960",
    "subject": "Database connection timeout",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-11-21T05:40:26Z",
    "updated_at": "2025-11-26T07:41:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-23T06:40:26Z",
    "sla_breached": true,
    "requester": "user112@enterprise.example.com",
    "assignee": "agent19@support.example.com",
    "tags": [
      "db",
      "access",
      "analytics",
      "change"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0961",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-16T02:48:56Z",
    "updated_at": "2025-11-24T00:48:56Z",
    "closed_at": "2025-11-24T00:48:56Z",
    "sla_due_at": "2025-11-16T06:48:56Z",
    "sla_breached": true,
    "requester": "user98@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "access",
      "request",
      "change",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0962",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-27T21:31:58Z",
    "updated_at": "2025-11-08T22:31:58Z",
    "closed_at": null,
    "sla_due_at": "2025-10-30T16:31:58Z",
    "sla_breached": true,
    "requester": "user149@enterprise.example.com",
    "assignee": "agent28@support.example.com",
    "tags": [
      "vip",
      "incident",
      "analytics"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0963",
    "subject": "Access request to internal repository",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-08T06:49:56Z",
    "updated_at": "2025-11-14T05:49:56Z",
    "closed_at": "2025-11-14T05:49:56Z",
    "sla_due_at": "2025-11-09T12:49:56Z",
    "sla_breached": true,
    "requester": "user81@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "onboarding",
      "access",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0964",
    "subject": "Password reset request",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-21T14:38:28Z",
    "updated_at": "2025-10-25T05:38:28Z",
    "closed_at": null,
    "sla_due_at": "2025-10-24T02:38:28Z",
    "sla_breached": true,
    "requester": "user67@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0965",
    "subject": "Data export failing in analytics app",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-08T04:51:53Z",
    "updated_at": "2025-11-19T01:51:53Z",
    "closed_at": "2025-11-19T01:51:53Z",
    "sla_due_at": "2025-11-09T10:51:53Z",
    "sla_breached": true,
    "requester": "user154@enterprise.example.com",
    "assignee": "agent3@support.example.com",
    "tags": [
      "network",
      "problem"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0966",
    "subject": "New user onboarding request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-10T00:57:46Z",
    "updated_at": "2025-10-22T05:57:46Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T16:57:46Z",
    "sla_breached": true,
    "requester": "user134@enterprise.example.com",
    "assignee": "agent9@support.example.com",
    "tags": [
      "onboarding",
      "security",
      "db",
      "problem"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0967",
    "subject": "Security alert investigation",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-09-23T22:46:53Z",
    "updated_at": "2025-09-29T21:46:53Z",
    "closed_at": null,
    "sla_due_at": "2025-09-24T13:46:53Z",
    "sla_breached": true,
    "requester": "user91@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "db",
      "security"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0968",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-11-05T13:53:51Z",
    "updated_at": "2025-11-19T00:53:51Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T11:53:51Z",
    "sla_breached": true,
    "requester": "user199@enterprise.example.com",
    "assignee": "agent45@support.example.com",
    "tags": [
      "network",
      "incident",
      "security"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0969",
    "subject": "Login issues on corporate portal",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-10-17T01:25:37Z",
    "updated_at": "2025-10-30T11:25:37Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T09:25:37Z",
    "sla_breached": true,
    "requester": "user151@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "bug",
      "sso"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0970",
    "subject": "Password reset request",
    "status": "pending",
    "priority": "low",
    "created_at": "2025-09-27T02:50:44Z",
    "updated_at": "2025-10-07T17:50:44Z",
    "closed_at": null,
    "sla_due_at": "2025-09-29T20:50:44Z",
    "sla_breached": true,
    "requester": "user163@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "network",
      "incident"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0971",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-09-24T12:03:09Z",
    "updated_at": "2025-09-25T08:03:09Z",
    "closed_at": "2025-09-25T08:03:09Z",
    "sla_due_at": "2025-09-25T18:03:09Z",
    "sla_breached": false,
    "requester": "user158@enterprise.example.com",
    "assignee": "agent25@support.example.com",
    "tags": [
      "bug",
      "vip"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0972",
    "subject": "Bug report for ticketing system",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-09-19T08:26:26Z",
    "updated_at": "2025-09-24T07:26:26Z",
    "closed_at": null,
    "sla_due_at": "2025-09-20T11:26:26Z",
    "sla_breached": true,
    "requester": "user125@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "change",
      "vip",
      "request",
      "problem"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0973",
    "subject": "New user onboarding request",
    "status": "on_hold",
    "priority": "critical",
    "created_at": "2025-11-14T00:23:17Z",
    "updated_at": "2025-11-20T04:23:17Z",
    "closed_at": null,
    "sla_due_at": "2025-11-14T18:23:17Z",
    "sla_breached": true,
    "requester": "user84@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "security",
      "access",
      "problem",
      "vip"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0974",
    "subject": "SSO configuration change",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-12T17:51:54Z",
    "updated_at": "2025-10-23T01:51:54Z",
    "closed_at": null,
    "sla_due_at": "2025-10-13T13:51:54Z",
    "sla_breached": true,
    "requester": "user126@enterprise.example.com",
    "assignee": "agent39@support.example.com",
    "tags": [
      "bug",
      "sso",
      "network",
      "onboarding"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0975",
    "subject": "Password reset request",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-23T00:31:38Z",
    "updated_at": "2025-09-29T22:31:38Z",
    "closed_at": null,
    "sla_due_at": "2025-09-25T08:31:38Z",
    "sla_breached": true,
    "requester": "user106@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "incident",
      "onboarding",
      "network",
      "db"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0976",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-28T19:59:09Z",
    "updated_at": "2025-11-06T13:59:09Z",
    "closed_at": null,
    "sla_due_at": "2025-10-29T04:59:09Z",
    "sla_breached": true,
    "requester": "user43@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "change"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0977",
    "subject": "Data export failing in analytics app",
    "status": "on_hold",
    "priority": "medium",
    "created_at": "2025-11-09T10:19:59Z",
    "updated_at": "2025-11-09T21:19:59Z",
    "closed_at": null,
    "sla_due_at": "2025-11-09T16:19:59Z",
    "sla_breached": true,
    "requester": "user200@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "vip",
      "request",
      "security"
    ],
    "description": "User reports intermittent issues impacting productivity. Needs urgent investigation and resolution."
  },
  {
    "id": "TCK-0978",
    "subject": "SSO configuration change",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-21T00:41:47Z",
    "updated_at": "2025-09-24T09:41:47Z",
    "closed_at": "2025-09-24T09:41:47Z",
    "sla_due_at": "2025-09-23T02:41:47Z",
    "sla_breached": true,
    "requester": "user184@enterprise.example.com",
    "assignee": "agent15@support.example.com",
    "tags": [
      "analytics",
      "access",
      "vip"
    ],
    "description": "Multiple users are affected and have raised similar complaints through different channels."
  },
  {
    "id": "TCK-0979",
    "subject": "SSO configuration change",
    "status": "on_hold",
    "priority": "low",
    "created_at": "2025-10-05T00:30:31Z",
    "updated_at": "2025-10-05T19:30:31Z",
    "closed_at": null,
    "sla_due_at": "2025-10-06T11:30:31Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent7@support.example.com",
    "tags": [
      "analytics",
      "problem",
      "network",
      "access"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0980",
    "subject": "Application performance degradation",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-10-19T07:28:35Z",
    "updated_at": "2025-11-03T00:28:35Z",
    "closed_at": "2025-11-03T00:28:35Z",
    "sla_due_at": "2025-10-20T16:28:35Z",
    "sla_breached": true,
    "requester": "user192@enterprise.example.com",
    "assignee": "agent8@support.example.com",
    "tags": [
      "bug",
      "incident",
      "access",
      "onboarding"
    ],
    "description": "Problem occurs during peak hours and appears related to load. Logs attached for review."
  },
  {
    "id": "TCK-0981",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-11-17T05:40:08Z",
    "updated_at": "2025-11-26T07:35:32Z",
    "closed_at": "2025-11-26T07:35:32Z",
    "sla_due_at": "2025-11-20T01:40:08Z",
    "sla_breached": true,
    "requester": "user191@enterprise.example.com",
    "assignee": "agent35@support.example.com",
    "tags": [
      "security",
      "db"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0982",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-11-01T10:18:23Z",
    "updated_at": "2025-11-10T12:18:23Z",
    "closed_at": null,
    "sla_due_at": "2025-11-03T05:18:23Z",
    "sla_breached": true,
    "requester": "user78@enterprise.example.com",
    "assignee": "agent18@support.example.com",
    "tags": [
      "sso",
      "security",
      "onboarding",
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0983",
    "subject": "Slow network in branch office",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-10-08T21:45:19Z",
    "updated_at": "2025-10-17T14:45:19Z",
    "closed_at": null,
    "sla_due_at": "2025-10-11T07:45:19Z",
    "sla_breached": true,
    "requester": "user73@enterprise.example.com",
    "assignee": null,
    "tags": [
      "incident",
      "network"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0984",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-10-06T18:47:17Z",
    "updated_at": "2025-10-19T02:47:17Z",
    "closed_at": "2025-10-19T02:47:17Z",
    "sla_due_at": "2025-10-07T11:47:17Z",
    "sla_breached": true,
    "requester": "user60@enterprise.example.com",
    "assignee": "agent29@support.example.com",
    "tags": [
      "problem",
      "change",
      "security"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0985",
    "subject": "Application performance degradation",
    "status": "open",
    "priority": "high",
    "created_at": "2025-10-15T03:07:28Z",
    "updated_at": "2025-10-18T18:07:28Z",
    "closed_at": null,
    "sla_due_at": "2025-10-15T17:07:28Z",
    "sla_breached": true,
    "requester": "user126@enterprise.example.com",
    "assignee": "agent6@support.example.com",
    "tags": [
      "incident",
      "change"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-0986",
    "subject": "Password reset request",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-20T11:43:42Z",
    "updated_at": "2025-10-01T00:43:42Z",
    "closed_at": null,
    "sla_due_at": "2025-09-21T20:43:42Z",
    "sla_breached": true,
    "requester": "user190@enterprise.example.com",
    "assignee": "agent10@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0987",
    "subject": "Database connection timeout",
    "status": "pending",
    "priority": "medium",
    "created_at": "2025-11-25T22:35:46Z",
    "updated_at": "2025-11-26T07:47:32Z",
    "closed_at": null,
    "sla_due_at": "2025-11-27T04:35:46Z",
    "sla_breached": false,
    "requester": "user167@enterprise.example.com",
    "assignee": "agent16@support.example.com",
    "tags": [
      "problem",
      "db",
      "analytics"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0988",
    "subject": "New user onboarding request",
    "status": "closed",
    "priority": "low",
    "created_at": "2025-09-16T05:23:39Z",
    "updated_at": "2025-09-17T21:23:39Z",
    "closed_at": "2025-09-17T21:23:39Z",
    "sla_due_at": "2025-09-16T22:23:39Z",
    "sla_breached": true,
    "requester": "user4@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0989",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-01T04:13:14Z",
    "updated_at": "2025-10-11T18:13:14Z",
    "closed_at": null,
    "sla_due_at": "2025-10-01T12:13:14Z",
    "sla_breached": true,
    "requester": "user135@enterprise.example.com",
    "assignee": "agent32@support.example.com",
    "tags": [
      "db",
      "request"
    ],
    "description": "This ticket is linked to a previous incident and may represent a regression."
  },
  {
    "id": "TCK-0990",
    "subject": "Security alert investigation",
    "status": "open",
    "priority": "critical",
    "created_at": "2025-10-06T08:01:19Z",
    "updated_at": "2025-10-12T15:01:19Z",
    "closed_at": null,
    "sla_due_at": "2025-10-08T01:01:19Z",
    "sla_breached": true,
    "requester": "user174@enterprise.example.com",
    "assignee": "agent21@support.example.com",
    "tags": [
      "change",
      "bug",
      "access"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0991",
    "subject": "Slow network in branch office",
    "status": "pending",
    "priority": "high",
    "created_at": "2025-10-19T13:18:29Z",
    "updated_at": "2025-10-27T12:18:29Z",
    "closed_at": null,
    "sla_due_at": "2025-10-20T19:18:29Z",
    "sla_breached": true,
    "requester": "user121@enterprise.example.com",
    "assignee": "agent30@support.example.com",
    "tags": [
      "vip",
      "db"
    ],
    "description": "Customer encountered an unexpected error while using the service. Screenshot and steps to reproduce provided."
  },
  {
    "id": "TCK-0992",
    "subject": "Email delivery delayed",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-04T13:16:01Z",
    "updated_at": "2025-11-13T11:16:01Z",
    "closed_at": null,
    "sla_due_at": "2025-11-07T05:16:01Z",
    "sla_breached": true,
    "requester": "user18@enterprise.example.com",
    "assignee": null,
    "tags": [
      "onboarding"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0993",
    "subject": "Login issues on corporate portal",
    "status": "closed",
    "priority": "high",
    "created_at": "2025-11-01T04:56:32Z",
    "updated_at": "2025-11-03T05:56:32Z",
    "closed_at": "2025-11-03T05:56:32Z",
    "sla_due_at": "2025-11-04T04:56:32Z",
    "sla_breached": false,
    "requester": "user153@enterprise.example.com",
    "assignee": "agent11@support.example.com",
    "tags": [
      "vip"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0994",
    "subject": "Password reset request",
    "status": "on_hold",
    "priority": "high",
    "created_at": "2025-10-28T19:47:58Z",
    "updated_at": "2025-11-03T16:47:58Z",
    "closed_at": null,
    "sla_due_at": "2025-10-29T00:47:58Z",
    "sla_breached": true,
    "requester": "user110@enterprise.example.com",
    "assignee": "agent38@support.example.com",
    "tags": [
      "vip",
      "change",
      "incident"
    ],
    "description": "Issue has been escalated by support. Root cause analysis may be required for audit purposes."
  },
  {
    "id": "TCK-0995",
    "subject": "Unable to access VPN",
    "status": "open",
    "priority": "high",
    "created_at": "2025-09-15T12:39:40Z",
    "updated_at": "2025-09-18T19:39:40Z",
    "closed_at": null,
    "sla_due_at": "2025-09-16T17:39:40Z",
    "sla_breached": true,
    "requester": "user72@enterprise.example.com",
    "assignee": "agent37@support.example.com",
    "tags": [
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0996",
    "subject": "Access request to internal repository",
    "status": "open",
    "priority": "medium",
    "created_at": "2025-09-11T08:52:53Z",
    "updated_at": "2025-09-24T00:52:53Z",
    "closed_at": null,
    "sla_due_at": "2025-09-13T13:52:53Z",
    "sla_breached": true,
    "requester": "user189@enterprise.example.com",
    "assignee": null,
    "tags": [
      "sso",
      "access",
      "network",
      "analytics"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  },
  {
    "id": "TCK-0997",
    "subject": "SSO configuration change",
    "status": "open",
    "priority": "low",
    "created_at": "2025-11-14T09:58:13Z",
    "updated_at": "2025-11-24T13:58:13Z",
    "closed_at": null,
    "sla_due_at": "2025-11-15T07:58:13Z",
    "sla_breached": true,
    "requester": "user20@enterprise.example.com",
    "assignee": null,
    "tags": [
      "access"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0998",
    "subject": "Data export failing in analytics app",
    "status": "open",
    "priority": "low",
    "created_at": "2025-09-30T16:52:14Z",
    "updated_at": "2025-10-11T09:52:14Z",
    "closed_at": null,
    "sla_due_at": "2025-10-03T08:52:14Z",
    "sla_breached": true,
    "requester": "user144@enterprise.example.com",
    "assignee": "agent50@support.example.com",
    "tags": [
      "db",
      "problem",
      "vip",
      "onboarding"
    ],
    "description": "Initial troubleshooting did not resolve the issue. Additional diagnostics are required."
  },
  {
    "id": "TCK-0999",
    "subject": "Email delivery delayed",
    "status": "pending",
    "priority": "critical",
    "created_at": "2025-10-16T13:02:14Z",
    "updated_at": "2025-10-21T03:02:14Z",
    "closed_at": null,
    "sla_due_at": "2025-10-17T03:02:14Z",
    "sla_breached": true,
    "requester": "user72@enterprise.example.com",
    "assignee": "agent46@support.example.com",
    "tags": [
      "incident",
      "request"
    ],
    "description": "The requester is from a VIP account; high priority and strict SLA timelines apply."
  },
  {
    "id": "TCK-1000",
    "subject": "Upgrade request for enterprise license",
    "status": "closed",
    "priority": "medium",
    "created_at": "2025-09-24T23:14:14Z",
    "updated_at": "2025-10-04T06:14:14Z",
    "closed_at": "2025-10-04T06:14:14Z",
    "sla_due_at": "2025-09-25T18:14:14Z",
    "sla_breached": true,
    "requester": "user7@enterprise.example.com",
    "assignee": "agent24@support.example.com",
    "tags": [
      "analytics",
      "bug",
      "vip",
      "incident"
    ],
    "description": "Request is part of a planned rollout for a new department. SLA applies as per enterprise contract."
  }
]
```
