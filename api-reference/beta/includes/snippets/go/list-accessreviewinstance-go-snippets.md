---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.InstancesRequestBuilderGetQueryParameters{
	Top: 100,
	Skip: 0,
}
options := &msgraphsdk.InstancesRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
accessReviewScheduleDefinitionId := "accessReviewScheduleDefinition-id"
result, err := graphClient.IdentityGovernance().AccessReviews().DefinitionsById(&accessReviewScheduleDefinitionId).Instances().GetWithRequestConfigurationAndResponseHandler(options, nil)


```