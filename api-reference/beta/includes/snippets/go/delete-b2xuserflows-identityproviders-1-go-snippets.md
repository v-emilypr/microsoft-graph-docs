---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

b2cIdentityUserFlowId := "b2cIdentityUserFlow-id"
identityProviderId := "identityProvider-id"
graphClient.Identity().B2cUserFlowsById(&b2cIdentityUserFlowId).IdentityProvidersById(&identityProviderId).$ref().Delete()


```