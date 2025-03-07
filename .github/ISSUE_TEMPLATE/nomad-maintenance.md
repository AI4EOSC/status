---
name: Nomad maintenance event
about: Create a Nomad maintenance event that the users will see in the Dashboard.
title: "[nomad-maintenance] Downtime for Nomad maintenance"
labels: nomad-maintenance
assignees: ''

---

```yaml
title:  Scheduled Nomad maintenance
summary: There will be a downtime to update the Platform.  # additional info
datacenters:
    - "ifca-ai4eosc"
    - "ifca-imagine"
    - "iisas-ai4eosc"
    - "incd-imagine"
    - "tubitak-imagine"
vo:  # vo to show the popup to, comma-separated. eg: "vo.ai4eosc.eu, vo.imagine-ai.eu" - if empty show to everyone
downtimeStart: 2025-01-01T00:00:00.000Z  # start date when the maintenance will start
downtimeEnd: 2025-01-01T00:00:00.000Z  # end date when the maintenance will end
start: 2024-07-24T00:00:00.000Z  # start date when the notification will appear
end: 2024-08-24T00:00:00.000Z  # end date when the notification will disappear
```

_Put here additional information that won't be shown to users_
