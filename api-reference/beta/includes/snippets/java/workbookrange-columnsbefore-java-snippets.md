---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

WorkbookRange workbookRange = graphClient.drive().root().workbook().worksheets("{id}")
	.range()
	.columnsBefore(WorkbookRangeColumnsBeforeParameterSet
		.newBuilder()
		.withCount(2)
		.build())
	.buildRequest()
	.get();

```