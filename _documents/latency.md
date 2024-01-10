---
title: latency
target: https://github.com/Blueprint-uServices/blueprint/tree/main/plugins/latency
date: 2024-01-10
description: Package latencyinjector provides a Blueprint modifier for the server side of service calls.The plugin configures the server side to inject a user\-defined amount of latency. Currently latency is injected for all requests and only a pre\-defined duration is supported with no variance/noise added. The plugin will generate a wrapper class that will sleep for a fixed amount of time \(the specified latency to be injected\) before invoking the handler for handling the request. Example Usage to add 100ms latency to each request-
---
