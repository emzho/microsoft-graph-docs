---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const todoTaskList = {
  displayName: 'Travel items'
};

await client.api('/me/todo/lists')
	.version('beta')
	.post(todoTaskList);

```