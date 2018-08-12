---
title: Nodablock API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell
  - python

toc_footers:
  - <a href='https://nodablock.com'>Return to nodablock</a>
#  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

Welcome to the NodaBlock API! You can use our API to access NodaBlock API endpoints. The documentation is currently a Work In Progress.

# Authentication

> To authorize, use this code:

```python
import nodablock

api = nodablock.authorize('meowmeowmeow')
```

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```


> Make sure to replace `meowmeowmeow` with your API key.

Nodablock uses API keys to allow access to the API. You can register a new Nodablock API key at our [developer portal](#).

Nodablock expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

