---
name: Nomad maintenance event
about: Create a nomad maintenance event that the users will see in the Dashboard.
title: "[nomad-maintenance] ***"
labels: nomad-maintenance
assignees: ''

---

```yaml
title:  Scheduled Nomad maintenance
datacenters:
    - "ifca-ai4eosc"
    - "ifca-imagine"
    - "iisas-ai4eosc"
    - "incd-imagine"
    - "tubitak-imagine"
vo:  # vo to show the popup to, comma-separated. eg: "vo.ai4eosc.eu, vo.imagine-ai.eu" - if empty show to everyone
notify: 2025-01-01T00:00:00.000Z  # date when users should start being notified
start: 2025-01-01T00:00:00.000Z  # start date when the maintenance will start
end: 2025-01-01T00:00:00.000Z  # end date when the maintenance will end
```

_Put here additional information that won't be shown to users_
