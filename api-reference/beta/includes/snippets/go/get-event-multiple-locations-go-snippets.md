---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.EventRequestBuilderGetQueryParameters{
	Select: "subject,body,bodyPreview,organizer,attendees,start,end,location,locations",
}
options := &msgraphsdk.EventRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
eventId := "event-id"
result, err := graphClient.Me().EventsById(&eventId).GetWithRequestConfigurationAndResponseHandler(options, nil)


```