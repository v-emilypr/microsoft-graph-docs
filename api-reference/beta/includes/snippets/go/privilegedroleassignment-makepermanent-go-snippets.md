---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
reason := "reason-value"
requestBody.SetReason(&reason)
ticketNumber := "ticketNumber-value"
requestBody.SetTicketNumber(&ticketNumber)
ticketSystem := "ticketSystem-value"
requestBody.SetTicketSystem(&ticketSystem)
privilegedRoleAssignmentId := "privilegedRoleAssignment-id"
result, err := graphClient.PrivilegedRoleAssignmentsById(&privilegedRoleAssignmentId).MakePermanent(privilegedRoleAssignment-id).Post(requestBody)


```