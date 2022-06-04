---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.ListRequestBuilderGetQueryParameters{
	Select: "id,name,lastModifiedDateTime",
	Expand: "columns(select=name,description),items)",
}
options := &msgraphsdk.ListRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
siteId := "site-id"
listId := "list-id"
result, err := graphClient.SitesById(&siteId).ListsById(&listId).GetWithRequestConfigurationAndResponseHandler(options, nil)


```