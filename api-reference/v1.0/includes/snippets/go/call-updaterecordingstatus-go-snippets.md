---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
clientContext := "clientContext-value"
requestBody.SetClientContext(&clientContext)
status := "notRecording | recording | failed"
requestBody.SetStatus(&status)
callId := "call-id"
result, err := graphClient.Communications().CallsById(&callId).UpdateRecordingStatus(call-id).Post(requestBody)


```