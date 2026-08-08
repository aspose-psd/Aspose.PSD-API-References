---
title: "IInterruptMonitor"
second_title: "Java용 Aspose.PSD API 참조"
description: "중단에 대한 정보를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor
```

중단에 대한 정보를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [interrupt()](#interrupt--) | 작업을 중단하도록 요청을 보냅니다. |
| [isInterrupted()](#isInterrupted--) | 작업을 중단해야 하는지 여부를 나타내는 값을 가져옵니다. |
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


작업을 중단하도록 요청을 보냅니다.

### isInterrupted() {#isInterrupted--}
```
public abstract boolean isInterrupted()
```


작업을 중단해야 하는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 작업을 중단해야 하는지 여부를 나타내는 값.
