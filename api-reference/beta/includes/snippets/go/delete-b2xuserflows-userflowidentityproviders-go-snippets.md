---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

b2xIdentityUserFlowId := "b2xIdentityUserFlow-id"
identityProviderBaseId := "identityProviderBase-id"
graphClient.Identity().B2xUserFlowsById(&b2xIdentityUserFlowId).UserFlowIdentityProvidersById(&identityProviderBaseId).$ref().Delete()


```