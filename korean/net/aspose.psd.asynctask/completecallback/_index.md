---
title: "델리게이트 CompleteCallback"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "작업 완료 이벤트를 수신하는 콜백 함수"
type: docs
weight: 70
url: /ko/net/aspose.psd.asynctask/completecallback/
---
{{< psd/tize >}}
## CompleteCallback delegate

작업 완료 이벤트를 수신하기 위한 콜백 함수.

```csharp
public delegate void CompleteCallback(IAsyncTask task, bool wasCancelled, Exception error);
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| task | IAsyncTask | 비동기 작업. |
| wasCancelled | Boolean | `true` 로 설정된 경우 [was cancelled]. |
| error | Exception | 오류. |

### 또 보기

* interface [IAsyncTask](../iasynctask/)
* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


