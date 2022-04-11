---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new ()
requestBody.displayName = "My custom name";
const result = async () => {
	await graphServiceClient.applicationTemplatesById("applicationTemplate-id").instantiate.post(requestBody);
}


```