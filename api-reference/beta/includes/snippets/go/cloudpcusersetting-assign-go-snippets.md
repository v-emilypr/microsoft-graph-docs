---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewAssignmentsRequestBody()
requestBody.SetAssignments( []CloudPcUserSettingAssignment {
	msgraphsdk.NewCloudPcUserSettingAssignment(),
	SetAdditionalData(map[string]interface{}{
		"id": "b0c2d35f-3385-46c8-a6f5-6c3dfad7708b_64ff06de-9c00-4a5a-98b5-7f5abe26ffff",
	}
}
cloudPcUserSettingId := "cloudPcUserSetting-id"
graphClient.DeviceManagement().VirtualEndpoint().UserSettingsById(&cloudPcUserSettingId).Assign(cloudPcUserSetting-id).Post(requestBody)


```