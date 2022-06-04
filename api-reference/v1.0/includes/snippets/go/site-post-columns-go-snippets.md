---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewColumnDefinition()
description := "test"
requestBody.SetDescription(&description)
enforceUniqueValues := false
requestBody.SetEnforceUniqueValues(&enforceUniqueValues)
hidden := false
requestBody.SetHidden(&hidden)
indexed := false
requestBody.SetIndexed(&indexed)
name := "Title"
requestBody.SetName(&name)
text := msgraphsdk.NewTextColumn()
requestBody.SetText(text)
allowMultipleLines := false
text.SetAllowMultipleLines(&allowMultipleLines)
appendChangesToExistingText := false
text.SetAppendChangesToExistingText(&appendChangesToExistingText)
linesForEditing := int32(0)
text.SetLinesForEditing(&linesForEditing)
maxLength := int32(255)
text.SetMaxLength(&maxLength)
siteId := "site-id"
result, err := graphClient.SitesById(&siteId).Columns().Post(requestBody)


```