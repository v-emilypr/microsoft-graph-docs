---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewPermission()
requestBody.SetRoles( []String {
	"read",
}
siteId := "site-id"
permissionId := "permission-id"
graphClient.SitesById(&siteId).PermissionsById(&permissionId).Patch(requestBody)


```