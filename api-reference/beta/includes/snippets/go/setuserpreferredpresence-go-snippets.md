---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
availability := "DoNotDisturb"
requestBody.SetAvailability(&availability)
activity := "DoNotDisturb"
requestBody.SetActivity(&activity)
expirationDuration := "PT8H"
requestBody.SetExpirationDuration(&expirationDuration)
userId := "user-id"
graphClient.UsersById(&userId).Presence().SetUserPreferredPresence(user-id).Post(requestBody)


```