---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new CloudPcOrganizationSettings()
requestBody.userAccountType = "standardUser";
requestBody.osVersion = "windows11";
requestBody.additionalData = {
		 "@odata.type" : "#microsoft.graph.cloudPcOrganizationSettings",
			 ["language" , "en-US"],
	 }
const result = async () => {
	await graphServiceClient.deviceManagement.virtualEndpoint.organizationSettings.patch(requestBody);
}


```