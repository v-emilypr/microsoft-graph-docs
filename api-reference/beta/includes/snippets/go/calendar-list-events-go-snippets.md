---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.EventsRequestBuilderGetQueryParameters{
	Filter: "startsWith(subject,'All')",
}
options := &msgraphsdk.EventsRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
result, err := graphClient.Me().Calendar().Events().GetWithRequestConfigurationAndResponseHandler(options, nil)


```