---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let sections = await client.api('/me/onenote/sections')
	.version('beta')
	.get();

```