---
title: "IInterruptMonitor"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل معلومات حول الانقطاع."
type: docs
weight: 11
url: /ar/java/com.aspose.psd.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor
```

يمثل معلومات حول الانقطاع.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [interrupt()](#interrupt--) | يرسل طلبًا لإيقاف العمليات. |
| [isInterrupted()](#isInterrupted--) | يحصل على القيمة التي تشير إلى ما إذا كان يجب إيقاف العمليات. |
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


يرسل طلبًا لإيقاف العمليات.

### isInterrupted() {#isInterrupted--}
```
public abstract boolean isInterrupted()
```


يحصل على القيمة التي تشير إلى ما إذا كان يجب إيقاف العمليات.

**Returns:**
منطقية - القيمة التي تشير إلى ما إذا كان يجب إيقاف العمليات.
