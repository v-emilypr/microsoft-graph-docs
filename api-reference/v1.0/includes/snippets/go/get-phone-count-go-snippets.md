---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.ContactsRequestBuilderGetQueryParameters{
	Search: "%22displayName:wa%22",
	Count: true,
}
headers := map[string]string{
	"ConsistencyLevel": "eventual"
}
options := &msgraphsdk.ContactsRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
	Headers: headers,
}
result, err := graphClient.Contacts().GetWithRequestConfigurationAndResponseHandler(options, nil)


```