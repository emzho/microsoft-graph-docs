---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

ScopedRoleMembership scopedRoleMembership = graphClient.directory().administrativeUnits("{id}").scopedRoleMembers("{id}")
	.buildRequest()
	.get();

```