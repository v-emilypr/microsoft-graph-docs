---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewDestinationIdRequestBody()
destinationId := "deleteditems"
requestBody.SetDestinationId(&destinationId)
messageId := "message-id"
result, err := graphClient.Me().MessagesById(&messageId).Move(message-id).Post(requestBody)


```