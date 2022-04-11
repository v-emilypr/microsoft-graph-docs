---
description: "Automatically generated file. DO NOT MODIFY"
---

```typescript

//THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
const graphServiceClient = GraphServiceClient.init({authProvider});

const requestBody = new EducationAssignment()
requestBody.displayName = "Reading and review test 09.03 #5";
requestBody.instructions = new EducationItemBody();
requestBody.instructions.contentType = "text";
requestBody.instructions.content = "Read chapter 5 and write your review";
requestBody.dueDateTime =  new Date("2021-09-10T00:00:00Z");
requestBody.addedStudentAction = "none";
const result = async () => {
	await graphServiceClient.education.classesById("educationClass-id").assignmentsById("educationAssignment-id").patch(requestBody);
}


```