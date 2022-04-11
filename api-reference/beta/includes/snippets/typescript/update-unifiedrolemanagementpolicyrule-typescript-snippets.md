---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new UnifiedRoleManagementPolicyRule()
requestBody.target = new UnifiedRoleManagementPolicyRuleTarget();
requestBody.target.additionalData = {
			 "@odata.type" : "microsoft.graph.unifiedRoleManagementPolicyRuleTarget"
		 }
requestBody.additionalData = {
		 "@odata.type" : "#microsoft.graph.unifiedRoleManagementPolicyApprovalRule"
	 }
const result = async () => {
	await graphServiceClient.policies.roleManagementPoliciesById("unifiedRoleManagementPolicy-id").rulesById("unifiedRoleManagementPolicyRule-id").patch(requestBody);
}


```