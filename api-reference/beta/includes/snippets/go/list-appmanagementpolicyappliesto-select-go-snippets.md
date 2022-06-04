---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.AppliesToRequestBuilderGetQueryParameters{
	Select: "id,appId,displayName,createdDateTime",
}
options := &msgraphsdk.AppliesToRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}
appManagementPolicyId := "appManagementPolicy-id"
result, err := graphClient.Policies().AppManagementPoliciesById(&appManagementPolicyId).AppliesTo().GetWithRequestConfigurationAndResponseHandler(options, nil)


```