---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new UserAccountInformation()
requestBody.allowedAudiences = "organization";
requestBody.countryCode = "NO";
const result = async () => {
	await graphServiceClient.me.profile.account.post(requestBody);
}


```