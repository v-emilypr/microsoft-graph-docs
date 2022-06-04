---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
requestBody.SetTargets( []InvitationParticipantInfo {
	msgraphsdk.NewInvitationParticipantInfo(),
	SetAdditionalData(map[string]interface{}{
		"@odata.type": "#microsoft.graph.invitationParticipantInfo",
	}
}
callbackUri := "https://bot.contoso.com/api/calls/24701998-1a73-4d42-8085-bf46ed0ae039"
requestBody.SetCallbackUri(&callbackUri)
callId := "call-id"
graphClient.Communications().CallsById(&callId).Redirect(call-id).Post(requestBody)


```