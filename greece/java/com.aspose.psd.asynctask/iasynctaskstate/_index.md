---
title: "IAsyncTaskState"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Παρέχει πρόσβαση στην κατάσταση της ασύγχρονης εργασίας."
type: docs
weight: 17
url: /el/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Παρέχει πρόσβαση στην κατάσταση της ασύγχρονης εργασίας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getProgress()](#getProgress--) | Λαμβάνει την πρόοδο της ασύγχρονης εργασίας. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Αυξάνει τη μέγιστη τιμή της προόδου. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Ορίζει την πρόοδο της ασύγχρονης εργασίας. |
| [isCanceled()](#isCanceled--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η ασύγχρονη εργασία έχει ακυρωθεί. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Λαμβάνει την πρόοδο της ασύγχρονης εργασίας.

Τιμή: Η πρόοδος της ασύγχρονης εργασίας.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Αυξάνει τη μέγιστη τιμή της προόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η τιμή αύξησης. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Ορίζει την πρόοδο της ασύγχρονης εργασίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Η κατάσταση προόδου. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η ασύγχρονη εργασία έχει ακυρωθεί.

Τιμή:  true  εάν η ασύγχρονη εργασία έχει ακυρωθεί· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν η ασύγχρονη εργασία έχει ακυρωθεί.
