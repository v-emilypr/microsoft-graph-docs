---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
id := "5793aa3b-cca9-4794-679a240f8b58"
requestBody.SetId(&id)
requestBody.SetCredentials( []Credential {
	msgraphsdk.NewCredential(),
	SetAdditionalData(map[string]interface{}{
		"fieldId": "param_username",
		"value": "myusername",
		"type": "username",
	}
	msgraphsdk.NewCredential(),
	SetAdditionalData(map[string]interface{}{
		"fieldId": "param_password",
		"value": "pa$$w0rd",
		"type": "password",
	}
}
servicePrincipalId := "servicePrincipal-id"
result, err := graphClient.ServicePrincipalsById(&servicePrincipalId).CreatePasswordSingleSignOnCredentials(servicePrincipal-id).Post(requestBody)


```