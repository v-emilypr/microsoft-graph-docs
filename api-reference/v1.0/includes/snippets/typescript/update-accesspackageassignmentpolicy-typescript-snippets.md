---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new ()
requestBody.additionalData = {
		 "id" : "87e1c7f7-c7f7-87e1-f7c7-e187f7c7e187",
		 "displayName" : "All Users",
		 "description" : "All users can request for access to the directory.",
			 ["id" , "49d2c59b-0a81-463d-a8ec-ddad3935d8a0"],
	 }
async () => {
	await graphServiceClient.identityGovernance.entitlementManagement.assignmentPoliciesById("accessPackageAssignmentPolicy-id").put(requestBody);
}


```