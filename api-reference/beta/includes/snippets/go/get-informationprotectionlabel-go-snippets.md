---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

informationProtectionLabelId := "informationProtectionLabel-id"
result, err := graphClient.Me().InformationProtection().Policy().LabelsById(&informationProtectionLabelId).Get()


```