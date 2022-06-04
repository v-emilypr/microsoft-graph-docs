---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewMessage()
receivedDateTime, err := time.Parse(time.RFC3339, "datetime-value")
requestBody.SetReceivedDateTime(&receivedDateTime)
sentDateTime, err := time.Parse(time.RFC3339, "datetime-value")
requestBody.SetSentDateTime(&sentDateTime)
hasAttachments := true
requestBody.SetHasAttachments(&hasAttachments)
subject := "subject-value"
requestBody.SetSubject(&subject)
body := msgraphsdk.NewItemBody()
requestBody.SetBody(body)
contentType := ""
body.SetContentType(&contentType)
content := "content-value"
body.SetContent(&content)
bodyPreview := "bodyPreview-value"
requestBody.SetBodyPreview(&bodyPreview)
mailFolderId := "mailFolder-id"
result, err := graphClient.Me().MailFoldersById(&mailFolderId).Messages().Post(requestBody)


```