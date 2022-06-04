---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewIdentityProviderBase()
requestBody.SetAdditionalData(map[string]interface{}{
	"@odata.type": "#microsoft.graph.socialIdentityProvider",
	"responseType": "id_token",
}
identityProviderBaseId := "identityProviderBase-id"
graphClient.Identity().IdentityProvidersById(&identityProviderBaseId).Patch(requestBody)


```