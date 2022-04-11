---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new ()
requestBody.outputName = "2020-12-06 Contoso investigation export";
requestBody.description = "Export for the Contoso investigation";
requestBody.exportOptions = "originalFiles,fileInfo,tags";
requestBody.exportStructure = "directory";
async () => {
	await graphServiceClient.compliance.ediscovery.casesById("case-id").reviewSetsById("reviewSet-id").export.post(requestBody);
}


```