---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.AgentGroupsRequestBuilderGetQueryParameters{
	Expand: "agents,publishedResources",
}
options := &msgraphsdk.AgentGroupsRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
onPremisesPublishingProfileId := "onPremisesPublishingProfile-id"
result, err := graphClient.OnPremisesPublishingProfilesById(&onPremisesPublishingProfileId).AgentGroups().GetWithRequestConfigurationAndResponseHandler(options, nil)


```