---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

headers := map[string]string{
	"Authorization": "Bearer {Token}"
}
options := &msgraphsdk.SchemaRequestBuilderGetRequestConfiguration{
	Headers: headers,
}
servicePrincipalId := "servicePrincipal-id"
synchronizationJobId := "synchronizationJob-id"
result, err := graphClient.ServicePrincipalsById(&servicePrincipalId).Synchronization().JobsById(&synchronizationJobId).Schema().GetWithRequestConfigurationAndResponseHandler(options, nil)


```