---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewAdministrativeUnit()
displayName := "Greater Seattle District Technical Schools"
requestBody.SetDisplayName(&displayName)
administrativeUnitId := "administrativeUnit-id"
graphClient.Directory().AdministrativeUnitsById(&administrativeUnitId).Patch(requestBody)


```