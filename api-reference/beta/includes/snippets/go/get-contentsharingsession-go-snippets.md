---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

callId := "call-id"
contentSharingSessionId := "contentSharingSession-id"
result, err := graphClient.Communications().CallsById(&callId).ContentSharingSessionsById(&contentSharingSessionId).Get()


```