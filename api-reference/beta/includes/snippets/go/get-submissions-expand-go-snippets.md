---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.SubmissionsRequestBuilderGetQueryParameters{
	Expand: "outcomes",
}
options := &msgraphsdk.SubmissionsRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
educationClassId := "educationClass-id"
educationAssignmentId := "educationAssignment-id"
result, err := graphClient.Education().ClassesById(&educationClassId).AssignmentsById(&educationAssignmentId).Submissions().GetWithRequestConfigurationAndResponseHandler(options, nil)


```