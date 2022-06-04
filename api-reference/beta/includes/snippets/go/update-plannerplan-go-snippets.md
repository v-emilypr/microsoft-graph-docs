---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewPlannerPlan()
title := "title-value"
requestBody.SetTitle(&title)
headers := map[string]string{
	"Prefer": "return=representation"
	"If-Match": "W/"JzEtVGFzayAgQEBAQEBAQEBAQEBAQEBAWCc=""
}
options := &msgraphsdk.PlannerPlanRequestBuilderPatchRequestConfiguration{
	Headers: headers,
}
plannerPlanId := "plannerPlan-id"
graphClient.Planner().PlansById(&plannerPlanId).PatchWithRequestConfigurationAndResponseHandler(requestBody, options, nil)


```