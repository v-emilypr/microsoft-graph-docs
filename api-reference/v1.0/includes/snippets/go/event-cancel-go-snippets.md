---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewCommentRequestBody()
comment := "Cancelling for this week due to all hands"
requestBody.SetComment(&comment)
eventId := "event-id"
graphClient.Me().EventsById(&eventId).Cancel(event-id).Post(requestBody)


```