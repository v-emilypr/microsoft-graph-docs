---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

caseId := "case-id"
noncustodialDataSourceId := "noncustodialDataSource-id"
graphClient.Compliance().Ediscovery().CasesById(&caseId).NoncustodialDataSourcesById(&noncustodialDataSourceId).Release(case-id, noncustodialDataSource-id).Post()


```