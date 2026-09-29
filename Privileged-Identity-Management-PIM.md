## Implement and configure Privileged Identity Management (PIM)

### Basic terminology
|Item|Description|
|---|---|
|**P**rivileged role|  A set of permissions that allows for high levels of access (e.g. owner) to resources |
|**S**tanding privilege | A privileged role permanently assigned to a user or group |
|**B**last radius | Scope of systems, data and operations an attacker can reach with a compromised identity|
|**J**ust in time access | No access by default, elevation is always deliberate, access expires automatically |
|**E**ntra ID role | Global administrator, password administrator - uses the Graph API plane - no access to Azure resources by default |
|Azure **r**esource role | e.g. Owner, Contributor, Reader scoped to Subscription, resource group etc for Azure resources |
|**E**ligible assignment | Has the potential for elevation - the end user must request activation for the privileged role |
|**A**ctive assignment | Privileged role is assigned immediately for a specified time window |

### PIM assignment controls
|Item|Description|
|---|---|
|**M**FA|  additional MFA required to activated the role |
|**J**ustification | Written explanation of why activation is needed |
|**A**pproval | Additional human reassurance that the access is needed and the request for activation is valid |
|**D**uration | Activation time window after which the elevated access expires |
|**A**udit | Every activation generates an audit log stored against the role for 30 days |


