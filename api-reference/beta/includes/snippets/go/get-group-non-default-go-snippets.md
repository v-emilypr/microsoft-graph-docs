---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.GroupRequestBuilderGetQueryParameters{
	Select: "allowExternalSenders,autoSubscribeNewMembers,isSubscribedByMail,unseenCount",
}
options := &msgraphsdk.GroupRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
groupId := "group-id"
result, err := graphClient.GroupsById(&groupId).GetWithRequestConfigurationAndResponseHandler(options, nil)


```