---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
reason := "busy"
requestBody.SetReason(&reason)
callId := "call-id"
graphClient.Communications().CallsById(&callId).Reject(call-id).Post(requestBody)


```