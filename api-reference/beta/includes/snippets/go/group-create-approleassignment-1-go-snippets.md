---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewAppRoleAssignment()
principalId := "7679d9a4-2323-44cd-b5c2-673ec88d8b12"
requestBody.SetPrincipalId(&principalId)
resourceId := "076e8b57-bac8-49d7-9396-e3449b685055"
requestBody.SetResourceId(&resourceId)
appRoleId := "00000000-0000-0000-0000-000000000000"
requestBody.SetAppRoleId(&appRoleId)
groupId := "group-id"
result, err := graphClient.GroupsById(&groupId).AppRoleAssignments().Post(requestBody)


```