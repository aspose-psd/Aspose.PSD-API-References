---
title: "InterruptMonitor"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "割り込みに関する情報を表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

割り込みに関する情報を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | InterruptMonitor クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | 各スレッドごとに一意の IInterruptMonitor インスタンスを取得します。 |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | 操作を中断するリクエストを送信します。 |
| [isInterrupted()](#isInterrupted--) | 操作を中断すべきかを示す値を取得します。 |
| [isThreadInterrupted()](#isThreadInterrupted--) | 現在のスレッドの割り込みモニターが存在し、割り込まれていた場合は true を返し、そうでない場合は false を返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | 各スレッドごとに一意の IInterruptMonitor インスタンスを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


InterruptMonitor クラスの新しいインスタンスを初期化します。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


各スレッドごとに一意の IInterruptMonitor インスタンスを取得します。

**Returns:**
[IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### interrupt() {#interrupt--}
```
public void interrupt()
```


操作を中断するリクエストを送信します。

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


操作を中断すべきかを示す値を取得します。

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


現在のスレッドの割り込みモニターが存在し、割り込まれていた場合は true を返し、そうでない場合は false を返します。

**Returns:**
boolean - 現在のスレッドの割り込みモニターが存在し、割り込まれていた場合は true、そうでない場合は false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


各スレッドごとに一意の IInterruptMonitor インスタンスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

