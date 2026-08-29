---
title: "InterruptMonitor"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει πληροφορίες σχετικά με τη διακοπή."
type: docs
weight: 10
url: /el/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Αντιπροσωπεύει πληροφορίες σχετικά με τη διακοπή.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Αρχικοποιεί μια νέα παρουσία της  InterruptMonitor  κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Λαμβάνει την παρουσία IInterruptMonitor η οποία είναι μοναδική για κάθε νήμα. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | Στέλνει ένα αίτημα για διακοπή των λειτουργιών. |
| [isInterrupted()](#isInterrupted--) | Λαμβάνει την τιμή που υποδεικνύει εάν πρέπει να διακοπούν οι λειτουργίες. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Επιστρέφει  true  εάν υπάρχει ο παρακολουθητής διακοπής για το τρέχον νήμα και έχει διακοπεί, διαφορετικά  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | Ορίζει την παρουσία IInterruptMonitor η οποία είναι μοναδική για κάθε νήμα. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Αρχικοποιεί μια νέα παρουσία της  InterruptMonitor  κλάσης.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Λαμβάνει την παρουσία IInterruptMonitor η οποία είναι μοναδική για κάθε νήμα.

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


Στέλνει ένα αίτημα για διακοπή των λειτουργιών.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Λαμβάνει την τιμή που υποδεικνύει εάν πρέπει να διακοπούν οι λειτουργίες.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Επιστρέφει  true  εάν υπάρχει ο παρακολουθητής διακοπής για το τρέχον νήμα και έχει διακοπεί, διαφορετικά  false .

**Returns:**
boolean -  true  εάν υπάρχει ο παρακολουθητής διακοπής για το τρέχον νήμα και έχει διακοπεί, διαφορετικά  false .
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


Ορίζει την παρουσία IInterruptMonitor η οποία είναι μοναδική για κάθε νήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

