---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewGroupIdsRequestBody()
requestBody.SetGroupIds( []String {
	"fee2c45b-915a-4a64b130f4eb9e75525e",
	"4fe90ae065a-478b9400e0a0e1cbd540",
}
result, err := graphClient.Me().CheckMemberGroups().Post(requestBody)


```