---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

subjectRightsRequestId := "subjectRightsRequest-id"
graphClient.Privacy().SubjectRightsRequestsById(&subjectRightsRequestId).GetFinalAttachment()(subjectRightsRequest-id).Get()


```