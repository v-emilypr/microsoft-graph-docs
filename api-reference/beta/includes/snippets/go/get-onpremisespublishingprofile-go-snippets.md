---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.OnPremisesPublishingProfileRequestBuilderGetQueryParameters{
	Expand: "publishedResources,agents,agentGroups",
}
options := &msgraphsdk.OnPremisesPublishingProfileRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
onPremisesPublishingProfileId := "onPremisesPublishingProfile-id"
result, err := graphClient.OnPremisesPublishingProfilesById(&onPremisesPublishingProfileId).GetWithRequestConfigurationAndResponseHandler(options, nil)


```