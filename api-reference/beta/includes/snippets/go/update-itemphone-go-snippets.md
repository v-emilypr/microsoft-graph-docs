---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewItemPhone()
type := "other"
requestBody.SetType(&type)
userId := "user-id"
itemPhoneId := "itemPhone-id"
graphClient.UsersById(&userId).Profile().PhonesById(&itemPhoneId).Patch(requestBody)


```