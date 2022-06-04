---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.PrivilegedRoleAssignmentsRequestBuilderGetQueryParameters{
	Filter: "isElevated%20eq%20true%20and%20expirationDateTime%20ne%20null%20or%20isElevated%20eq%20false",
}
options := &msgraphsdk.PrivilegedRoleAssignmentsRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
result, err := graphClient.PrivilegedRoleAssignments().GetWithRequestConfigurationAndResponseHandler(options, nil)


```