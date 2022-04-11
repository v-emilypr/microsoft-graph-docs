---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new ()
requestBody.updateCategory = "String";
const updatableasset = new UpdatableAsset();
updatableasset.additionalData = {
					 "@odata.type" : "#microsoft.graph.windowsUpdates.azureADDevice",
					 "id" : "String (identifier)"
				 }
requestBody.assets = [
			updatableasset
		]
async () => {
	await graphServiceClient.admin.windows.updates.updatableAssets.unenrollAssets.post(requestBody);
}


```