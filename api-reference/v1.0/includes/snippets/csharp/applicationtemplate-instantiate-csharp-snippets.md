---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var displayName = "My custom name";

await graphClient.ApplicationTemplates["{applicationTemplate-id}"]
	.Instantiate(displayName)
	.Request()
	.PostAsync();

```