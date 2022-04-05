---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

AccessPackageAssignmentPolicy accessPackageAssignmentPolicy = new AccessPackageAssignmentPolicy();
accessPackageAssignmentPolicy.id = "87e1c7f7-c7f7-87e1-f7c7-e187f7c7e187";
accessPackageAssignmentPolicy.displayName = "All Users";
accessPackageAssignmentPolicy.description = "All users can request for access to the directory.";
AccessPackage accessPackage = new AccessPackage();
accessPackage.id = "49d2c59b-0a81-463d-a8ec-ddad3935d8a0";
accessPackageAssignmentPolicy.accessPackage = accessPackage;

graphClient.identityGovernance().entitlementManagement().assignmentPolicies("87e1c7f7-c7f7-87e1-f7c7-e187f7c7e187")
	.buildRequest()
	.put(accessPackageAssignmentPolicy);

```