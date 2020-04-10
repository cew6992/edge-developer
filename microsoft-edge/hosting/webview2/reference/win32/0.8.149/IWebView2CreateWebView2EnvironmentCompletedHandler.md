---
description: Host web content in your Win32 app with the Microsoft Edge WebView2 control
title: Microsoft Edge WebView2 for Win32 apps
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 12/09/2019
ms.topic: reference
ms.prod: microsoft-edge
ms.technology: webview
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge
---

# interface IWebView2CreateWebView2EnvironmentCompletedHandler 

> [!NOTE]
> This interface may be altered or unavailable for releases after SDK version 0.8.355. Please refer to [WebView2 API browser](../../../reference-webview2.md) for the latest API reference.

```
interface IWebView2CreateWebView2EnvironmentCompletedHandler
  : public IUnknown
```

The caller implements this interface to receive the WebView2Environment created via CreateWebView2Environment.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[Invoke](#invoke) | Called to provide the implementer with the completion status and result of the corresponding asynchronous method call.

## Members

#### Invoke 

Called to provide the implementer with the completion status and result of the corresponding asynchronous method call.

> public HRESULT [Invoke](#invoke)(HRESULT result,[IWebView2Environment](IWebView2Environment.md) * webViewEnvironment)
