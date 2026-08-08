---
title: "CompleteCallback"
second_title: "Java용 Aspose.PSD API 참조"
description: "작업 완료 이벤트를 받기 위한 콜백 함수."
type: docs
weight: 15
url: /ko/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

작업 완료 이벤트를 받기 위한 콜백 함수.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | 작업 완료 이벤트를 받기 위한 콜백 함수. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


작업 완료 이벤트를 받기 위한 콜백 함수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | 비동기 작업. |
| wasCancelled | boolean | true 로 설정된 경우 [was cancelled]. |
| 오류 | java.lang.Throwable | 오류. |

