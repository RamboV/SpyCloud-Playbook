This is SpyCloud Breach playbook. It execute when any incident of `SpyCloud Breach Data` type is created.

## Steps to be perform by user

- Provide the password length as playbook input.
#### Task-2 "Check if the user is currently an active employee"
- This is a skeleton task for user reference. Please implement your internal logic to check current employee in your network. 
#### Task-3 "Check if the exposed password is in use on the network"
- This is a skeleton task for user reference. Please implement your internal logic to check exposed password.
#### Task-4 "Perform a password reset and escalate"
- This is skeleton task for user reference. Please perform password reset logic here.

## Dependencies

This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks

This playbook does not use any sub-playbooks.

### Integrations

SpyCloud Enterprise.

### Scripts

* StringLength

### Commands

* setIncident

## Playbook Inputs
| **Name**               | **Description** | **Default Value** | **Required** |
|------------------------| --- |-------------------|-----------|
| Minimum Password Length | Minimum Password Length | 8 | Required. |

## Playbook Outputs

---
There are no outputs for this playbook.

## Playbook Image

---

![SpyCloud Breach](SpyCloud_Breach_Playbook.png)
