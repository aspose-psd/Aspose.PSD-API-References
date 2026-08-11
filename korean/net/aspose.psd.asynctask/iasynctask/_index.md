---
title: "인터페이스 IAsyncTask"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.AsyncTask.IAsyncTask 인터페이스. 비동기 작업"
type: docs
weight: 80
url: /ko/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

비동기 작업.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | 작업이 완료된 후 사용할 수 있는 작업 오류를 가져옵니다. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | 이 작업이 현재 실행 중인지 여부를 나타내는 값을 가져옵니다. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | 이 작업이 취소되었는지 여부를 나타내는 값을 가져옵니다. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | 이 작업이 오류가 발생했는지 여부를 나타내는 값을 가져옵니다. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | 비동기 작업의 진행률을 가져옵니다. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | 이 작업의 결과를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | 이 작업을 중단합니다. 작업이 즉시 완료되며, 내부 관리되지 않는 리소스가 해제되지 않을 위험이 있습니다. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | 이 작업을 취소합니다. 알고리즘을 제어된 방식으로 중지하여 작업이 안전하게 완료됩니다. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | 이 작업을 실행합니다. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | 이 작업을 실행합니다. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | 완료 콜백 대리자를 설정합니다. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | 진행 상황 콜백 대리자를 설정합니다. |

### 또 보기

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


