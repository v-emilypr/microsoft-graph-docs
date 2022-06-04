---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
requestBody.SetParticipants( []InvitationParticipantInfo {
	msgraphsdk.NewInvitationParticipantInfo(),
	SetAdditionalData(map[string]interface{}{
		"@odata.type": "#microsoft.graph.invitationParticipantInfo",
		"replacesCallId": "a7ebfb2d-871e-419c-87af-27290b22e8db",
	}
	msgraphsdk.NewInvitationParticipantInfo(),
	SetAdditionalData(map[string]interface{}{
		"@odata.type": "#microsoft.graph.invitationParticipantInfo",
		"replacesCallId": "a7ebfb2d-871e-419c-87af-27290b22e8db",
	}
}
clientContext := "f2fa86af-3c51-4bc2-8fc0-475452d9764f"
requestBody.SetClientContext(&clientContext)
callId := "call-id"
result, err := graphClient.Communications().CallsById(&callId).Participants().Invite(call-id).Post(requestBody)


```