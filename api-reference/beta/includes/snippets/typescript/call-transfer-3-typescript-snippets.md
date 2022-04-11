---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new ()
requestBody.transferTarget = new InvitationParticipantInfo();
requestBody.transferTarget.endpointType = "default";
requestBody.transferTarget.identity = new IdentitySet();
requestBody.transferTarget.identity.additionalData = {
					 ["@odata.type" , "#microsoft.graph.identity"],
					 ["id" , "+12345678901"],
			 }
requestBody.transferTarget.additionalData = {
			 "languageId" : "languageId-value",
			 "region" : "region-value"
		 }
async () => {
	await graphServiceClient.communications.callsById("call-id").transfer.post(requestBody);
}


```