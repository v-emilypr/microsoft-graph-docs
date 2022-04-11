---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new ()
requestBody.notes = new ItemBody();
requestBody.notes.contentType = "text";
requestBody.notes.content = "clock in notes";
requestBody.additionalData = {
		 "atAprovedLocation" : true
	 }
const result = async () => {
	await graphServiceClient.teamsById("team-id").schedule.timeCards.clockIn.post(requestBody);
}


```