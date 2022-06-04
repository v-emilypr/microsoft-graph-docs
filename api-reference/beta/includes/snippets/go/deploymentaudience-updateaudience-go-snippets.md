---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
requestBody.SetAddMembers( []UpdatableAsset {
	msgraphsdk.NewUpdatableAsset(),
	SetAdditionalData(map[string]interface{}{
		"@odata.type": "#microsoft.graph.windowsUpdates.azureADDevice",
		"id": "String (identifier)",
	}
}
requestBody.SetRemoveMembers( []UpdatableAsset {
	msgraphsdk.NewUpdatableAsset(),
	SetAdditionalData(map[string]interface{}{
		"@odata.type": "#microsoft.graph.windowsUpdates.azureADDevice",
		"id": "String (identifier)",
	}
}
requestBody.SetAddExclusions( []UpdatableAsset {
	msgraphsdk.NewUpdatableAsset(),
	SetAdditionalData(map[string]interface{}{
		"@odata.type": "#microsoft.graph.windowsUpdates.azureADDevice",
		"id": "String (identifier)",
	}
}
requestBody.SetRemoveExclusions( []UpdatableAsset {
	msgraphsdk.NewUpdatableAsset(),
	SetAdditionalData(map[string]interface{}{
		"@odata.type": "#microsoft.graph.windowsUpdates.azureADDevice",
		"id": "String (identifier)",
	}
}
deploymentId := "deployment-id"
graphClient.Admin().Windows().Updates().DeploymentsById(&deploymentId).Audience().UpdateAudience(deployment-id).Post(requestBody)


```