---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.PrinterRequestBuilderGetQueryParameters{
	Select: "id,displayName,capabilities",
}
options := &msgraphsdk.PrinterRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
printerId := "printer-id"
result, err := graphClient.Print().PrintersById(&printerId).GetWithRequestConfigurationAndResponseHandler(options, nil)


```