---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.TabsRequestBuilderGetQueryParameters{
	Expand: "teamsApp",
}
options := &msgraphsdk.TabsRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
chatId := "chat-id"
result, err := graphClient.ChatsById(&chatId).Tabs().GetWithRequestConfigurationAndResponseHandler(options, nil)


```