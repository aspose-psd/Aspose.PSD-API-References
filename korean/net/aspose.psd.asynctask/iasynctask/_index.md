---
title: Interface IAsyncTask
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.AsyncTask.IAsyncTask 상호 작용. 비동기 작업입니다.
type: docs
weight: 80
url: /ko/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

비동기 작업입니다.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | 작업이 완료된 후 사용할 수 있는 작업 오류를 가져옵니다. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | 이 작업이 현재 실행 중인지 여부를 나타내는 값을 가져옵니다. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | 이 작업이 취소되었는지 여부를 나타내는 값을 가져옵니다. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | 이 작업에 오류가 발생했는지 여부를 나타내는 값을 가져옵니다. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | 비동기 작업의 진행 상황을 가져옵니다. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | 이 작업의 결과를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | 이 작업을 중단합니다. 작업이 즉시 완료되지만 관리되지 않는 내부 리소스가 해제되지 않을 위험이 있습니다. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | 이 작업을 취소합니다. 알고리즘의 제어 중지에 의해 작업이 안전하게 완료됩니다. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | 이 작업을 실행합니다. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | 이 작업을 실행합니다. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | 전체 콜백 대리자를 설정합니다. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | 진행률 콜백 대리자를 설정합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* 집회 [Aspose.PSD](../../)


