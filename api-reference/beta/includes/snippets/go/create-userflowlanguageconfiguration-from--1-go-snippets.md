---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
requestBody.SetAdditionalData(map[string]interface{}{
	"id": "es-ES",
	"isEnabled": true,
}
b2cIdentityUserFlowId := "b2cIdentityUserFlow-id"
userFlowLanguageConfigurationId := "userFlowLanguageConfiguration-id"
graphClient.Identity().B2cUserFlowsById(&b2cIdentityUserFlowId).LanguagesById(&userFlowLanguageConfigurationId).Put(requestBody)


```