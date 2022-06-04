---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
requestBody.SetHubSiteUrls( []String {
	"https://graph.microsoft.com/v1.0/sites/{site-id}",
}
propagateToExistingLists := false
requestBody.SetPropagateToExistingLists(&propagateToExistingLists)
siteId := "site-id"
contentTypeId := "contentType-id"
graphClient.SitesById(&siteId).ContentTypesById(&contentTypeId).AssociateWithHubSites(site-id, contentType-id).Post(requestBody)


```