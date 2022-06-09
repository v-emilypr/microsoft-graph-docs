---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewBookingBusiness()
displayName := "Fourth Coffee"
requestBody.SetDisplayName(&displayName)
address := msgraphsdk.NewPhysicalAddress()
requestBody.SetAddress(address)
postOfficeBox := "P.O. Box 123"
address.SetPostOfficeBox(&postOfficeBox)
street := "4567 Main Street"
address.SetStreet(&street)
city := "Buffalo"
address.SetCity(&city)
state := "NY"
address.SetState(&state)
countryOrRegion := "USA"
address.SetCountryOrRegion(&countryOrRegion)
postalCode := "98052"
address.SetPostalCode(&postalCode)
phone := "206-555-0100"
requestBody.SetPhone(&phone)
email := "manager@fourthcoffee.com"
requestBody.SetEmail(&email)
webSiteUrl := "https://www.fourthcoffee.com"
requestBody.SetWebSiteUrl(&webSiteUrl)
defaultCurrencyIso := "USD"
requestBody.SetDefaultCurrencyIso(&defaultCurrencyIso)
result, err := graphClient.BookingBusinesses().Post(requestBody)


```