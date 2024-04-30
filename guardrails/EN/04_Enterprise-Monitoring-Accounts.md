
# Enterprise Monitoring Accounts

([Back](../../GUARDRAILS.md))

## Objective

Create role-based account to enable enterprise monitoring and visibility.  
This section contains the Guardrails that address controls in the following contexts:

- Access Control (AC)
- Audit and Accountability (AU)
- Identification and Authentication (IA)


## Mandatory Requirements

| Activity  | Validation |
| --- | --- |
| Create role-based accounts to enable enterprise monitoring and visibility for cloud environments that are procured via the GC Cloud Broker or are included in the scope of centralized guardrails validation. | <ul><li>Verify that roles required to enable visibility in the GC have been provisioned or assigned.</li></ul> |
| Maintain healthy management of associated rols. | <ul><li>Verify the implementation of controls listed under [Manage Role Access](./02_Manage-Role-Access.md)</li></ul> |
| Have a plan in place for responding to security incidents detected through monitoring, including roles and responsibilities, communication plans, and recovery procedures. | <ul><li>Provide evidence that a plan is in place for responding to security incidents detected through monitoring, including roles and responsibilities, communication plans, and recovery procedures.</li></ul> |

## Conditional Requirements

| Activity  | Validation |
| --- | --- |
|  Integrate the SCM with a Security Information and Event Management (SIEM) system if available to centralize log analysis and alerting.| <ul><li>Provide evidence that the SCM is integrated with a SIEM system to centralize log analysis and alerting.</li></ul> |


## References

- [Direction on the Secure Use of Commercial Cloud Services: Security Policy Implementation Notice](https://www.canada.ca/en/treasury-board-secretariat/services/access-information-privacy/security-identity-management/direction-secure-use-commercial-cloud-services-spin.html) (SPIN) 2017-01, subsection 6.2.3
- Cyber Centre’s top 10 IT security actions, number 2
- [IT Security Risk Management: A Lifecycle Approach (ITSG-33), Annex 3A: Security Control Catalogue](https://cyber.gc.ca/en/guidance/it-security-risk-management-lifecycle-approach-itsg-33), AC-3(7)

## Related security controls from ITSG-33

AC-2, AC-3(7), AC-6(5), AU-2, AU-6, IA-2(1)