---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.DeviceRequestBuilderGetQueryParameters{
	Select: "id,extensionAttributes",
}
options := &msgraphsdk.DeviceRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
deviceId := "device-id"
result, err := graphClient.DevicesById(&deviceId).GetWithRequestConfigurationAndResponseHandler(options, nil)


```