---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewConversationThread()
requestBody.SetAdditionalData(map[string]interface{}{
	"originalStartTimeZone": "originalStartTimeZone-value",
	"originalEndTimeZone": "originalEndTimeZone-value",
	"uid": "iCalUId-value",
	"reminderMinutesBeforeStart": ,
	"isReminderOn": true,
}
groupId := "group-id"
conversationThreadId := "conversationThread-id"
graphClient.GroupsById(&groupId).ThreadsById(&conversationThreadId).Patch(requestBody)


```