---
author: DCtheGeek
ms.service: azure-policy
ms.topic: include
ms.date: 09/13/2021
ms.author: dacoulte
ms.custom: generated
---

|Name<br /><sub>(Azure portal)</sub> |Description |Effect(s) |Version<br /><sub>(GitHub)</sub> |
|---|---|---|---|
|[Endpoint protection health issues should be resolved on your machines](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2Fproviders%2FMicrosoft.Authorization%2FpolicyDefinitions%2F8e42c1f2-a2ab-49bc-994a-12bcd0dc4ac2) |Resolve endpoint protection health issues on your virtual machines to protect them from latest threats and vulnerabilities. Azure Security Center supported endpoint protection solutions are documented here - [https://docs.microsoft.com/azure/security-center/security-center-services?tabs=features-windows](../../../../../articles/security-center/security-center-services.md?tabs=features-windows). Endpoint protection assessment is documented here - [https://docs.microsoft.com/azure/security-center/security-center-endpoint-protection](../../../../../articles/security-center/security-center-endpoint-protection.md). |AuditIfNotExists, Disabled |[1.0.0](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policyDefinitions/Security%20Center/ASC_EndpointProtectionHealthIssuesShouldBeResolvedOnYourMachines_Audit.json) |
|[Endpoint protection should be installed on your machines](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2Fproviders%2FMicrosoft.Authorization%2FpolicyDefinitions%2F1f7c564c-0a90-4d44-b7e1-9d456cffaee8) |To protect your machines from threats and vulnerabilities, install a supported endpoint protection solution. |AuditIfNotExists, Disabled |[1.0.0](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policyDefinitions/Security%20Center/ASC_EndpointProtectionShouldBeInstalledOnYourMachines_Audit.json) |