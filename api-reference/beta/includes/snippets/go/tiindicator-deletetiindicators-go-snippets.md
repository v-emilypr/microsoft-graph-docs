---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewValueRequestBody()
requestBody.SetValue( []String {
	"id-value1",
	"id-value2",
}
result, err := graphClient.Security().TiIndicators().DeleteTiIndicators().Post(requestBody)


```