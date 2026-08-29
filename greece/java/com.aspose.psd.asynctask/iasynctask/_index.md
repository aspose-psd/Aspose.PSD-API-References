---
title: "IAsyncTask"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η ασύγχρονη εργασία."
type: docs
weight: 16
url: /el/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Η ασύγχρονη εργασία.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [abort()](#abort--) | Διακόπτει αυτήν την εργασία. |
| [cancel()](#cancel--) | Ακυρώνει αυτήν την εργασία. |
| [getError()](#getError--) | Λαμβάνει το σφάλμα της εργασίας που είναι διαθέσιμο μετά την ολοκλήρωση της εργασίας. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει τον διαχειριστή συμβάντος προόδου της ασύγχρονης εργασίας. |
| [getResult()](#getResult--) | Λαμβάνει το αποτέλεσμα αυτής της εργασίας. |
| [isBusy()](#isBusy--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία εκτελείται αυτή τη στιγμή. |
| [isCanceled()](#isCanceled--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία ακυρώθηκε. |
| [isFaulted()](#isFaulted--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία παρουσίασε σφάλμα. |
| [runAsync()](#runAsync--) | Εκτελεί αυτήν την εργασία. |
| [runAsync(int priority)](#runAsync-int-) | Εκτελεί αυτήν την εργασία. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Ορίζει το delegate της κλήσης επιστροφής ολοκλήρωσης. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ορίζει τον διαχειριστή συμβάντος προόδου της ασύγχρονης εργασίας. |
### abort() {#abort--}
```
public abstract void abort()
```


Διακόπτει αυτήν την εργασία. Η εργασία ολοκληρώνεται αμέσως, με κίνδυνο να μην ελευθερωθούν οι εσωτερικοί μη διαχειριζόμενοι πόροι.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Ακυρώνει αυτήν την εργασία. Η εργασία ολοκληρώνεται με ασφάλεια μέσω του ελεγχόμενου τερματισμού του αλγορίθμου.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Λαμβάνει το σφάλμα της εργασίας που είναι διαθέσιμο μετά την ολοκλήρωση της εργασίας.

Τιμή: Το σφάλμα της εργασίας.

**Returns:**
java.lang.Throwable - το σφάλμα της εργασίας που είναι διαθέσιμο μετά την ολοκλήρωση της εργασίας.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Λαμβάνει τον διαχειριστή συμβάντος προόδου της ασύγχρονης εργασίας.

Τιμή: Ο χειριστής συμβάντος προόδου της ασύγχρονης εργασίας.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Λαμβάνει το αποτέλεσμα αυτής της εργασίας.

Τιμή: Το αποτέλεσμα αυτής της εργασίας.

**Returns:**
java.lang.Object - το αποτέλεσμα αυτής της εργασίας.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία εκτελείται αυτή τη στιγμή.

Τιμή:  true  εάν αυτή η εργασία εκτελείται αυτή τη στιγμή· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν αυτή η εργασία εκτελείται αυτή τη στιγμή.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία ακυρώθηκε.

Τιμή:  true  εάν αυτή η εργασία ακυρώθηκε· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν αυτή η εργασία ακυρώθηκε.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία παρουσίασε σφάλμα.

Τιμή:  true  εάν αυτή η εργασία παρουσίασε σφάλμα· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν αυτή η εργασία παρουσίασε σφάλμα.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Εκτελεί αυτήν την εργασία.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Εκτελεί αυτήν την εργασία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| προτεραιότητα | int | Η προτεραιότητα του νήματος. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Ορίζει το delegate της κλήσης επιστροφής ολοκλήρωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | Η ολοκληρωμένη κλήση επιστροφής. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Ορίζει τον διαχειριστή συμβάντος προόδου της ασύγχρονης εργασίας.

Τιμή: Ο χειριστής συμβάντος προόδου της ασύγχρονης εργασίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | ο χειριστής συμβάντος προόδου της ασύγχρονης εργασίας. |

