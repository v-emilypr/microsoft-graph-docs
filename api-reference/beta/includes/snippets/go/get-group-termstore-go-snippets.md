---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.GroupRequestBuilderGetQueryParameters{
	Select: "*,parentSiteId",
}
options := &msgraphsdk.GroupRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
siteId := "site-id"
groupId := "group-id"
result, err := graphClient.SitesById(&siteId).TermStore().GroupsById(&groupId).GetWithRequestConfigurationAndResponseHandler(options, nil)


```