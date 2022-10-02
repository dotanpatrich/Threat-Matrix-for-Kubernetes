---
hide:
  - toc
  - footer
---

# Compromised Image In Registry

!!! info inline end
    ID: ???<br>
    Tactic: [Initial Access](../InitialAccess/index.md) <br>
    MITRE technique: [T1195.002](https://attack.mitre.org/techniques/T1195/002/)

Running a compromised image in a cluster can compromise the cluster. Attackers who get access to a private registry can plant their own compromised images in the registry. The latter can then be pulled by a user. In addition, users often use untrusted images from public registries (such as Docker Hub) that may be malicious.

## Mitigations

|ID|Mitigation|Description|
|--|----------|-----------|