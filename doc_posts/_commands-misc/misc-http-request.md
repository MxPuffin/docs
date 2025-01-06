---
title: HTTP Request
num: 9
redirect_from:
  - commands/169
---

This command lets you send a web request, i.e. call an API and receive its response.

{% include async.html %}

| Box Name | Type | Description | 
|-------|--------|--------
|URL|String|The web request URL, must start with `http` or `https`
|Method|Dropdown|Method to use. Select from dropdown menu or manually input
|Header Object Name (optional)|Object |Name of the object containing any required headers
|Body Object JSON (optional)|JSON|Body JSON string to send
|Save Variable As (optional)|String|Variable name to save the result into
{:class='table table-primary'}

{% include example_public.html src="/docs/assets/images/commands-misc/httpReq_Ex.png" size="100" title="Using HTTP Request to get dad jokes" pastebin="Sk1qXeV8" %}  







