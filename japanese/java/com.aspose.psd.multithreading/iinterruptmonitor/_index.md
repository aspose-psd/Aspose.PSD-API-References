---
title: "IInterruptMonitor"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "割り込みに関する情報を表します。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor
```

割り込みに関する情報を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [interrupt()](#interrupt--) | 操作を中断するリクエストを送信します。 |
| [isInterrupted()](#isInterrupted--) | 操作を中断すべきかを示す値を取得します。 |
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


操作を中断するリクエストを送信します。

### isInterrupted() {#isInterrupted--}
```
public abstract boolean isInterrupted()
```


操作を中断すべきかを示す値を取得します。

**Returns:**
boolean - 操作を中断すべきかを示す値。
