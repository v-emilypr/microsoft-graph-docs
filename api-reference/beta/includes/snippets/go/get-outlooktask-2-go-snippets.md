---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

headers := map[string]string{
	"Prefer": "outlook.timezone="Pacific Standard Time""
}
options := &msgraphsdk.OutlookTaskRequestBuilderGetRequestConfiguration{
	Headers: headers,
}
outlookTaskId := "outlookTask-id"
result, err := graphClient.Me().Outlook().TasksById(&outlookTaskId).GetWithRequestConfigurationAndResponseHandler(options, nil)


```