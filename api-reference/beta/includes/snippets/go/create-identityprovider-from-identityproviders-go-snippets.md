---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewIdentityProvider()
name := "Login with Amazon"
requestBody.SetName(&name)
type := "Amazon"
requestBody.SetType(&type)
clientId := "56433757-cadd-4135-8431-2c9e3fd68ae8"
requestBody.SetClientId(&clientId)
clientSecret := "000000000000"
requestBody.SetClientSecret(&clientSecret)
requestBody.SetAdditionalData(map[string]interface{}{
	"@odata.type": "microsoft.graph.identityProvider",
}
result, err := graphClient.IdentityProviders().Post(requestBody)


```