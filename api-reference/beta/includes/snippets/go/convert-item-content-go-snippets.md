---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.ContentRequestBuilderGetQueryParameters{
	Format: "%7Bformat%7D",
}
options := &msgraphsdk.ContentRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
driveItemId := "driveItem-id"
graphClient.Drive().ItemsById(&driveItemId).Content().GetWithRequestConfigurationAndResponseHandler(options, nil)


```