---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
comment := "comment-value"
requestBody.SetComment(&comment)
sendResponse := true
requestBody.SetSendResponse(&sendResponse)
eventId := "event-id"
graphClient.Me().EventsById(&eventId).Accept(event-id).Post(requestBody)


```